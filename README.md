# java-bootcamp
import java.util.*;
class Main{
    public static void main(String[] args){
        int a;
        Scanner b=new Scanner(System.in);
        System.out.println("enter a num");
        a=b.nextInt();
        if(a>=0){
            System.out.println("num is positive");
        }
        else {
            System.out.println("num is negative");
        }
    }
}
