

public class ExampleProgram {
    // Non-static method
    public void nonStaticMethod() {
        System.out.println("This is a non-static method.");
    }
    
    // Static methods
    public static void staticMethod1() {
        System.out.println("This is static method 1.");
    }
    
    public static void staticMethod2() {
        System.out.println("This is static method 2.");
    }
    
    // Constructor
    public ExampleProgram() {
        System.out.println("This is the constructor.");
    }
    
    // Main method
    public static void main(String args) {
        // Creating an instance of the class
        ExampleProgram example = new ExampleProgram();
        
        // Calling the non-static method
        example.nonStaticMethod();
        
        // Calling the static methods
        staticMethod1();
        staticMethod2();
    }
}
