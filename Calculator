import java.util.Scanner;
class Calculator{
double number1;
double number2;
double result;
char operator;
public Calculator(double number1, double number2, char operator){
    this.number1 = number1;
    this.number2 = number2;
    this.operator = operator;
    }

    public void calculate(){
        if(operator == '+'){
            result = number1 + number2;
            System.out.println("the result is=" + result);
        }
        else if(operator == '-'){
            result = number1 - number2;
            System.out.println("the result is=" + result);
        }
        else if(operator == '*'){
            result = number1 * number2;
            System.out.println("the result is=" + result);
        }
        else if (operator == '/') {
        if (number2 != 0) {
            result = number1 / number2;
            System.out.println("The result is = " + result);
        } else {
            System.out.println("Error: Division by zero is not allowed.");
        }
    } else {
        System.out.println("Error: Invalid operator.");
    }
    }
}
    public class Main{
        public static void main(String[]args){
        Scanner L = new Scanner(System.in);
        System.out.print("Enter the first number");
        double number1 = L.nextDouble();
        System.out.print("Enter the second number");
        double number2 = L.nextDouble();
        System.out.print("Enter the operator(+, -, *, /)");
        char operator = L.next().charAt(0);
        Calculator calculator = new Calculator(number1, number2, operator);
        calculator.calculate();
        L.close();
    }
}
