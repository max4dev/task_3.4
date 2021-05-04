# task_3.4

public class Main {

    public static void main(String[] args) {
        int a = 2;
        int b = 9;
        System.out.println("Сумма " + a + " + " + b + " > 10 - " + min(a, b));
    }

    static boolean min (int a, int b) {
        if (a + b > 10) return true;
        else return false;
    }
}
