# Stack
import java.util.Stack;
class Scratch {
    public static void main(String[] args) {
        //stack
       // Stack<Integer> stack = getIntegers();
        Stack<Integer> stack = getIntegers();
       stack.push(1);
        stack.push(2);
        stack.push(3);
        System.out.println(stack.peek());
        System.out.println(stack.size());
        System.out.println(stack.pop());
        System.out.println(stack.size());
        System.out.println(stack.empty());
    }