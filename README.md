public class PersonalizedOutput {
    public static void main(String[] args) {
        // Declare variables
        String name = "Gian";
        int age = 17;
        double heightInMeters = 1.65;
        boolean isStudent = true;

        // Display the personalized output
        System.out.println("Hello! My name is " + name + ".");
        System.out.println("I am " + age + " years old.");
        System.out.println("My height is " + heightInMeters + " meters.");
        if (isStudent) {
            System.out.println("I am currently a student.");
        } else {
            System.out.println("I am not a student.");
            System.out.println("Hi, my name is " + name + ". I am " + age + " years old, " + heightInMeters + " meters tall, and it is " + isStudent + " that I am a student.");
        }
    }
}
