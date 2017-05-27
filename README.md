# Mindy-
Small quiz application

-------MainActivity.java------------
package com.example.swan.mindyrush2;

import android.app.Activity;
import android.content.DialogInterface;
import android.content.Intent;
import android.support.v7.app.AlertDialog;
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;

import java.util.Random;

public class MainActivity extends Activity {
    Button answer1,answer2,answer3;
    TextView score,question,num;
    private Question mQuestion = new Question();
    private int mnum = 1;
    private String mAnswer;
    private int mScore = 0;
    private int mQuestionLength = mQuestion.mQuestion.length;

    Random r;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        r = new Random();

        answer1= (Button) findViewById(R.id.button1);
        answer2= (Button) findViewById(R.id.button2);
        answer3= (Button) findViewById(R.id.button3);
        num = (TextView) findViewById(R.id.num);



        score= (TextView) findViewById(R.id.score);
        question= (TextView) findViewById(R.id.question);


        score.setText("Score:    "+ mScore);
        num.setText("("+mnum+")");

        updateQuestion(r.nextInt(mQuestionLength));

        answer1.setOnClickListener(new View.OnClickListener(){
            @Override
            public void onClick(View view){
                if(answer1.getText() == mAnswer){
                    mScore++;
                    score.setText("Score: "+ mScore);
                    updateQuestion(r.nextInt(mQuestionLength));


                }else {
                    gameOver();
                }
                mnum++;
                num.setText(""+mnum);

            }
        });
        answer2.setOnClickListener(new View.OnClickListener(){
            @Override
            public void onClick(View view){
                if(answer2.getText() == mAnswer){
                    mScore++;
                    score.setText("Score: "+ mScore);
                    updateQuestion(r.nextInt(mQuestionLength));
                }else {
                    gameOver();
                }
                mnum++;
                num.setText(""+mnum);
            }
        });
        answer3.setOnClickListener(new View.OnClickListener(){
            @Override
            public void onClick(View view){
                if(answer3.getText() == mAnswer){
                    mScore++;
                    score.setText("Score: "+ mScore);
                    updateQuestion(r.nextInt(mQuestionLength));
                }else {
                    gameOver();
                }
                mnum++;
                num.setText(""+mnum);
            }
        });

    }
    private void updateQuestion(int num){
        question.setText(mQuestion.getQuestion(num));
        answer1.setText(mQuestion.getChoice1(num));
        answer2.setText(mQuestion.getChoice2(num));
        answer3.setText(mQuestion.getChoice3(num));

        mAnswer = mQuestion.getCorrectAnswer(num);
        if (mnum == 10)
        {
            gameOver();
        }


    }
    private void gameOver(){
        AlertDialog.Builder alertDialogBuilder = new AlertDialog.Builder(MainActivity.this);
        if(mnum != 10) {
            alertDialogBuilder
                    .setMessage("Oopz!!! You are Lost!!! Your score is " + mScore + " points.")
                    .setCancelable(false)
                    .setPositiveButton("New Game",
                            new DialogInterface.OnClickListener() {
                                @Override
                                public void onClick(DialogInterface dialogInterface, int i) {
                                    startActivity(new Intent(getApplicationContext(), MainActivity.class));
                                    finish();
                                }
                            })
                    .setNegativeButton("EXIT",
                            new DialogInterface.OnClickListener() {
                                @Override
                                public void onClick(DialogInterface dialogInterface, int i) {
                                    finish();
                                }
                            });
            AlertDialog alertDialog = alertDialogBuilder.create();
            alertDialog.show();
        }
        else {
            alertDialogBuilder
                    .setMessage("Congratulations!!! You won!!! Your score is " + mScore + "points.")
                    .setCancelable(false)
                    .setPositiveButton("New Game",
                            new DialogInterface.OnClickListener() {
                                @Override
                                public void onClick(DialogInterface dialogInterface, int i) {
                                    startActivity(new Intent(getApplicationContext(), MainActivity.class));
                                    finish();
                                }
                            })
                    .setNegativeButton("EXIT",
                            new DialogInterface.OnClickListener() {
                                @Override
                                public void onClick(DialogInterface dialogInterface, int i) {
                                    finish();
                                }
                            });
            AlertDialog alertDialog = alertDialogBuilder.create();
            alertDialog.show();

        }


    }
}


--------------------Home.java-----------------------------
package com.example.swan.mindyrush2;

import android.content.Intent;
import android.support.v7.app.ActionBar;
import android.support.v7.app.ActionBarActivity;
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.MenuInflater;
import android.view.View;
import android.widget.ImageButton;

public class Home extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_home);

        ImageButton imageButton=(ImageButton) findViewById(R.id.ImageButton);
        imageButton.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                Intent intent=new Intent(getApplicationContext(),MainActivity.class);
                startActivity(intent);

            }
        });

    }
}

--------------------------Question.java----------------------
package com.example.swan.mindyrush2;

/**
 * Created by dil on 26/05/2017.
 */

public class Question {

        public String mQuestion[] = {
                "3 + 1 = ?",
                "10 / 2 = ? ",
                "10 * 3 = ?",
                "25 - 7 = ?",
                "48 + 23 = ?",
                "56 / 8 - 7 = ?",
                "7 * 7 + 23 = ?",
                "23 - 11 + 7 = ?",
                "64 / 4 + 32 = ?",
                "49 + 78 * 4 = ?"

        };

        private String mchoices[][] = {
                {"4","5","6"},
                {"7","4","5"},
                {"13","3","30"},
                {"18","23","14"},
                {"69","71","72"},
                {"55","0","41"},
                {"72","210","37"},
                {"34","17","19"},
                {"2","48","16"},
                {"361","264","261"},

        };

        private String mCorrectAnswer[] = { "4", "5", "30","18","71","0","72","19","48","361"};

        public String getQuestion(int a){
            String question =mQuestion[a];

                return question;

        }

        public String getChoice1(int a){
            String choise = mchoices[a][0];
            return choise;
        }

        public String getChoice2(int a){
            String choise = mchoices[a][1];
            return choise;
        }

        public String getChoice3(int a){
            String choise = mchoices[a][2];
            return choise;
        }

        public String getCorrectAnswer(int a){
            String answer = mCorrectAnswer[a];
            return answer;
        }

}




