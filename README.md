# assignment-1
 code to get the sum of even ,odd numbers and  numbers dividable by 7 from 0 to 100 
public class Main {
    public static void main(String[] args) {
        System.out.println("Even using for " + Even_for());
        System.out.println("Even using while " + Even_while());
        System.out.println("Even using do while " + Even_do_while());
        System.out.println("Odd using for " + odd_for());
        System.out.println("Odd using while " + odd_while());
        System.out.println("Odd using do while " + odd_do_while());
        System.out.println("Mod 7 using for " + Divisible_for());
        System.out.println("Mod 7 using while " + Divisible_while());
        System.out.println("Mod using do while "  + Divisible_do_while());
    }
    public static int Even_for (){
        int sum = 0;
        for (int i = 0; i <= 100; i+=2) {
            sum += i;
        }
        return sum;
    }
    public static int Even_while (){
        int sum = 0;
        int a = 0;
        while (a <= 100){
            if (a % 2 == 0)
                sum += a;
            a++;
        }
        return sum;
    }
    public static int Even_do_while () {
        int sum = 0;
        int a = 0;
        do {
            if (a % 2 == 0)
                sum += a;
            a++;
        } while (a <= 100);
        return sum;
    }
    public static int odd_for (){
        int sum = 0;
        for (int i = 1; i <= 100; i+=2) {
            sum += i;
        }
        return sum;
    }
    public static int odd_while (){
        int sum = 0;
        int a = 0;
        while (a <= 100){
            if (a % 2 == 1)
                sum += a;
            a++;
        }
        return sum;
    }
    public static int odd_do_while () {
        int sum = 0;
        int a = 0;
        do {
            if (a % 2 == 1)
                sum += a;
            a++;
        } while (a <= 100);
        return sum;
    }
    public static int Divisible_for (){
        int sum = 0;
        for (int i = 0; i <= 100; i+=7) {
            sum += i;
        }
        return sum;
    }
    public static int Divisible_while (){
        int sum = 0;
        int a = 0;
        while (a <= 100){
            if (a % 7 == 0)
                sum += a;
            a++;
        }
        return sum;
    }
    public static int Divisible_do_while () {
        int sum = 0;
        int a = 0;
        do {
            if (a % 7 == 0)
                sum += a;
            a++;
        } while (a <= 100);
        return sum;
    }
}
