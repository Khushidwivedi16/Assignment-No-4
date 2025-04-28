# Assignment-No-4
Assignment no 4



assignment no. 4 //////////////

// Calculator.java
public class Calculator {
    // Method to add two numbers
    public int add(int a, int b) {
        return a + b;
    }
}

// TestCalculator.java
import org.junit.Test;
import static org.junit.Assert.assertEquals;

public class TestCalculator {
    @Test
    public void testAdd() {
        Calculator calc = new Calculator(); // Create a Calculator
        int result = calc.add(2, 3);         // Add 2 and 3
        assertEquals(5, result);             // Check if result is 5
    }
}
