# Largest-Of-Three-User
program that finds the largest from the numbers entered by the user



import javax.swing.JOptionPane;


public class LargestOfThree
{
    public static void main(String[] args) {

        //variables
        double num1, num2, num3;
        double largestNum;
        int reps = 1;
        String input;

        //input
        //ask the user for three numbers
        //num1
        input = JOptionPane.showInputDialog("Enter three numbers and " +
                "this program will display \n the largest of the three " +
                "ten times. " + " \n Enter the First number:");
        num1 = Double.parseDouble(input);

        //num2
        input = JOptionPane.showInputDialog("Enter the second number: ");
        num2 = Double.parseDouble(input);

        //num3
        input = JOptionPane.showInputDialog("Enter the Third number: ");
        num3 = Double.parseDouble(input);

        //process identification of largest number
        if (num1 >= num2)
            largestNum = num1;
        else if (num1 >= num2)
            largestNum = num1;
        else if (num2 >= num3)
            largestNum = num2;
        else
            largestNum = num3;




        //out put
        // declare the three numbers
        //and the largest number ten times in a loop
        JOptionPane.showMessageDialog(null, "The largest number from " +
                num1  +", " + num2 + " and " + num3 +
                " is " + largestNum + ". ");
        while (reps <= 10)
        {
            JOptionPane.showMessageDialog(null,largestNum );
            reps++;

        }
    }




}
