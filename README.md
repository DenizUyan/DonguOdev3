import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Sayi Giriniz: ");
        int sayi = input.nextInt();

        for(int i=0; i<=sayi; i++){
            for(int j=1; j<=i; j++){
                System.out.print(" ");
            }
            for(int j=1; j<=(2*sayi-(2*i+1)); j++){
                System.out.print("*");
            }
            System.out.println();
        }

    }
}
