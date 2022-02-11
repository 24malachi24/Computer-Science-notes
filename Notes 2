More Notes.

ChoiceQuestion(String questiontext){
super(questionText);

A subclass has no access to the private instance variables of the superclass.

Beginner's error : "solve" this problem by adding another instance variable.

If you are not satisifued with the behavior of an inherited method, you overide it by specifying a new implementation in the sublcass.

An overriding method can extend or replace the functionality of the superclass method.
The display method of the ChoiceQuestionclass needs to dsiplay the question text and display the answerchoices.

ChoiceQuestion's displaymethod can't access the textvariable of the super class directly because it is private.

It can call the displaymethod of the superclass, by using the reserved word super.

public void display()
{
//Display the question text.
super.display(): // OK
// Display the answer choices 

public class QuestionDemo2
{
    public static void main(String[] args)
      {
      ChoiceQuestion first = new ChoiceQuestion();
      first.settext("What was the orginal name of the Java Language?");
      
      first.addChoice("*7" , false);
      first.addChoice("Duke" , false);
      first.addChoice("Oak" , true);
      first.addChoice("Gosling" , false);
       
      
      ChoiceQuestion second = new ChoiceQuestion();
      
      second.setText(" In which country was thhe inventor of Java born?");
      second.addChoice("Australia" , false);
      second.addChoice("Canada" , true );
      second.addChoice("Denmark" , false);
      second.addChoice("United States" , false);
      
      presentQuestion(first);
      presentQuestion(second);
      
      }
      // Presents a question to the user and checks the response.
      
      public static void presentQuestion(ChoiceQuestion q)
      {
      q.display();
      System.out.print("Your Answer:   ");
      
     ChoiceQuestion.java /////////////////////////////// 
      
      import java.util.ArrayList;
      //A question with multiple choices.
      public class ChoiceQuestion extends Question
      {
      
      private ArrayList<String> choices;
      // Constructs a choice question with no choices.
      public ChoiceQuestion()
      {
          choices = new ArrayList<String>();
         
     }
      
      
  public void addChoice(String  choice , boolean correct )
  {
        choices.add(choice);
        if(correct)
  }
  Sav
  
  
  
