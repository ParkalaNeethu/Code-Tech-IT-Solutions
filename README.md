# Code-Tech-IT-Solutions
import java.util.Scanner;

public class simpleCalculator {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        //declare my variables
        int firstNum;
        int secondNum;
        int division = 0, addition = 0, subtraction = 0, multiplication = 0;
        String userChoice = "add";
        String choices[] = {"add","multiply","divide","subtract"};

        //ask for user input
        System.out.print("Please enter first number: ");
        firstNum = input.nextInt();
        System.out.print("Please enter second number: ");
        secondNum = input.nextInt();
        System.out.println("What type of operation would you like to perform on these numbers?");
        System.out.println("add " +"multiply " +"subtract " + "divide ");
        userChoice = input.nextLine();

        if (userChoice == "add"){
                    System.out.print("Answer = " + addition);
        }


        //calculator formulas
        addition = firstNum + secondNum;
        multiplication = firstNum * secondNum;
        subtraction = firstNum - secondNum;
        division = firstNum / secondNum;
    }
    
}
