import java.util.Scanner;
import java.util.Random;
class Rand
{
   public static void main(String args[])
   {
        Scanner read=new Scanner(System.in);
        String play="yes";
        //while loop if we are going to play the game again!
        while(play.equals("yes"))
        {
           Random rand=new Random();
           int randnumber=rand.nextInt(100);
           int guess=-1;
           int tries=0;
           //while loop to check if the game is over
           while(guess!=randnumber)
           { 
               System.out.print("guess a number between 1 to 100");
               guess=read.nextInt();
               tries++;
               if(guess==randnumber)
               {
                      System.out.println("you guessed the correct number");
                      System.out.println("the total tries you took "+ tries );
                      System.out.println("would you like to play the again yes or no");
                      play=read.next().toLowerCase();
                }
                else if(guess>randnumber)
                {
                    System.out.println("you guessed very high number.try again!");
                }
                 else
                {
                      System.out.println("you guessed very low number.try again!");
                }
            }
        }
         read.close();
   }
}
