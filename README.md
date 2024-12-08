# Recursion-of-Natural-no.
Recursion of Natural numbers using java
import java.util.Scanner;

public class recurrsionNaturalno02 {
    public recurrsionNaturalno02() {
    }

    public class Main {
        public Main(recurrsionNaturalno02 this$0) {
        }

        static void func(int N) {
            if (N >= 1) {
                func(N - 1);
                System.out.println("" + N + "  ");
            }

        }

        public static void main(String[] args) {
            System.out.println("Enter a number: ");
            Scanner sc = new Scanner(System.in);
            int N = sc.nextInt();
            func(N);
        }
    }
}
