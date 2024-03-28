# GradeCalculator
Grade
I am excited to complete this internship of java programming import java.
import java.util.Scanner;

public class GreadeCalculator1 {
   
	public static void main(String[] args) {
       
		Scanner scanner = new Scanner(System.in);
        
      
        // Get input from user
       
        
        System.out.println("Enter the student's name:");
       
        
        String name = scanner.nextLine();
        
        System.out.println("Enter the student's score for Test 1 (out of 100):");
      
        double test1 = scanner.nextDouble();
        
        System.out.println("Enter the student's score for Test 2 (out of 100):");
      
        double test2 = scanner.nextDouble();
        
        System.out.println("Enter the student's score for Test 3 (out of 100):");
        
        
           double test3 = scanner.nextDouble();
        
        
           // Calculate average score
          
           double average = (test1 + test2 + test3) / 3;
        
        // Determine grade based on average score
      
           char grade;
     
           if (average >= 90) {
     
        	   grade = 'A';
     
           } else if (average >= 80) {
    
        	   grade = 'B';
    
           } else if (average >= 70) {
       
        	   grade = 'C';
       
           } else if (average >= 60) {
       
        	   grade = 'D';
        } else {
            grade = 'F';
        }
        
        // Output the result
       
           System.out.println("Student Name: " + name);
      
           System.out.println("Average Score: " + average);
      
           System.out.println("Grade: " + grade);
        
        scanner.close();
    }

}



