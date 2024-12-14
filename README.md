import java.util.Stack;

class Scratch {
    public static void main(String[] args) {
        // Create a Stack of integers
        Stack<Integer> stack = new Stack<>();

        // Push elements onto the stack
        stack.push(1);
        stack.push(2);
        stack.push(3);

        // Display the top element of the stack
        System.out.println("Top element (peek): " + stack.peek());

        // Display the size of the stack
        System.out.println("Stack size: " + stack.size());

        // Pop the top element and display it
        System.out.println("Popped element: " + stack.pop());

  
