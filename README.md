//
// Source code recreated from a .class file by IntelliJ IDEA
// (powered by FernFlower decompiler)
//

import java.util.Scanner;

public class mess_calculator {
    public mess_calculator() {
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("enter your toṭal mess amount = ");
        float total = (float)scanner.nextInt();
        System.out.print("total members =");
        float m = (float)scanner.nextInt();
        float ph = total / m;

        int p;
        for(p = 0; (float)p < m; ++p) {
            System.out.println("" + p + " .person =" + ph);
        }

        System.out.println("not available days in this months=");
        p = scanner.nextInt();
        float na = ph / 30.0F;
        float pd = na * (float)p;
        float pdm = ph - pd;
        System.out.println("this person due ammount =" + pdm);
        System.out.println("rest amount divided persons=");
        float b = (float)scanner.nextInt();
        float a = pd / b;
        float z = a + ph;

        for(int j = 0; (float)j < m - 1.0F; ++j) {
            System.out.println("" + j + " .person =" + z);
        }

    }
}


# mess_calculator
this calculator are solve the mess over fight then  exact report  overall all spend of a months. 
