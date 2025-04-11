# calculate-the-garde-for-studend-by-java-language.
import java.util.Scanner;

public class Addition {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter the grade:");
        int grade = input.nextInt();
        String result;

        if (grade >= 97 && grade <= 100) {
            result = "A+";
        } else if (grade >= 93) {
            result = "A";
        } else if (grade >= 90) {
            result = "A-";
        } else if (grade >= 87) {
            result = "B+";
        } else if (grade >= 83) {
            result = "B";
        } else if (grade >= 80) {
            result = "B-";
        } else if (grade >= 77) {
            result = "C+";
        } else if (grade >= 73) {
            result = "C";
        } else if (grade >= 70) {
            result = "C-";
        } else if (grade >= 60) {
            result = "D";
        } else {
            result = "F";
        }

        System.out.println("your result is:" + result);
        input.close();
    }
}


