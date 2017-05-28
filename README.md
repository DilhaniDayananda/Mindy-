# Mindy-
Small quiz application

-----------------------Interface-1---------------------
activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/holo_purple"
    tools:context="com.example.swan.mindyrush2.MainActivity">


    <TextView
        android:id="@+id/score"
        android:layout_width="138dp"
        android:layout_height="48dp"
        android:layout_marginEnd="3dp"
        android:layout_marginLeft="8dp"
        android:layout_marginStart="8dp"
        android:background="@android:color/transparent"
        android:foreground="@android:color/transparent"
        android:foregroundTint="@android:color/transparent"
        android:text="Score :   "
        android:textColor="@color/colorAccent"
        android:textSize="30sp"
        android:textStyle="bold"
        app:layout_constraintLeft_toLeftOf="parent"
        android:layout_marginRight="3dp"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.863"
        android:layout_marginBottom="8dp"
        app:layout_constraintTop_toTopOf="parent"
        android:layout_marginTop="8dp"
        app:layout_constraintVertical_bias="0.062" />


    <LinearLayout
        android:layout_width="322dp"
        android:layout_height="67dp"
        android:layout_marginBottom="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginTop="8dp"
        android:orientation="horizontal"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.716"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.655"
        android:id="@+id/linearLayout2">

        <Button
            android:id="@+id/button1"
            android:layout_width="10dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:foreground="@android:color/transparent"
            android:foregroundTint="@android:color/transparent"
            android:text="4"
            android:textAlignment="center"
            android:textColor="@color/colorPrimary"
            android:textSize="30sp" />

        <Button
            android:id="@+id/button2"
            android:layout_width="10dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:foreground="@android:color/transparent"
            android:text="5"
            android:textAlignment="center"
            android:textColor="@color/colorPrimaryDark"
            android:textColorLink="@android:color/transparent"
            android:textSize="30sp" />

        <Button
            android:id="@+id/button3"
            android:layout_width="10dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:foreground="@android:color/transparent"
            android:text="6"
            android:textAlignment="center"
            android:textColor="@color/colorPrimaryDark"
            android:textSize="30sp" />
    </LinearLayout>

    <LinearLayout
        android:id="@+id/linearLayout"
        android:layout_width="312dp"
        android:layout_height="58dp"
        android:layout_gravity="center_vertical"
        android:layout_marginBottom="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginStart="8dp"
        android:layout_marginTop="8dp"
        android:gravity="center_vertical"
        android:orientation="horizontal"
        android:textAlignment="center"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.416">

        <TextView
            android:id="@+id/num"
            android:layout_width="59dp"
            android:layout_height="48dp"
            android:text=" "
            android:textAlignment="center"
            android:textColor="@color/colorPrimaryDark"
            android:textSize="30sp" />

        <TextView
            android:id="@+id/question"
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:text=" "
            android:textAlignment="center"
            android:textColor="@color/colorPrimaryDark"
            android:textIsSelectable="false"
            android:textSize="30sp"
            tools:layout_editor_absoluteX="8dp"
            tools:layout_editor_absoluteY="-607dp" />

    </LinearLayout>
    
    </android.support.constraint.ConstraintLayout>

----------------------------------InterfaceHome-------------------------------

Activity_home.xml

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/holo_purple"
    tools:context="com.example.swan.mindyrush2.Home">


    <ImageButton
        android:id="@+id/ImageButton"
        android:layout_width="78dp"
        android:layout_height="97dp"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_marginBottom="8dp"
        android:layout_marginRight="171dp"
        android:layout_marginTop="8dp"
        android:layout_weight="1.68"
        android:src="@mipmap/start"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.366" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="295dp"
        android:layout_height="57dp"
        android:layout_below="@+id/ImageButton"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginTop="8dp"
        android:text="Press the image to start your quiz"
        android:textAppearance="?android:attr/textAppearanceSmall"
        android:textColorLink="@color/colorAccent"
        android:textSize="18sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.506"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.598" />


</android.support.constraint.ConstraintLayout>

-------------------MainActivity.java-------------
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

-------------------------------Question.java---------------
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
------------------------------Home.java--------------------------------------
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










