import java.util.Scanner;

public class InputCalculator {
    public static void main(String[] args) {
        inputThenPrintSumAndAverage();
    }

    public static void inputThenPrintSumAndAverage(){
        Scanner scanner = new Scanner(System.in);

        int sum = 0, count = 0;
        double avg;

        while (true){
            boolean isInt = scanner.hasNextInt();
            if(isInt){
                int number = scanner.nextInt();
                count++;
                sum += number;
            } else {
                break;
            }
        }

        if(count == 0){
            System.out.println("SUM = 0 AVG = 0");
        } else {

            avg = Math.round((double)sum / (double) count);
            System.out.println("SUM = " + sum + " AVG = " + (int) avg);
        }
        scanner.close();
    }
}
