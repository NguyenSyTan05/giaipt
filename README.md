[Uploading 
package giaiphuongtrinhbacnhat;

import java.util.Scanner;

public class GiaiPhuongTrinhBacNhat {
    public static String giaiPhuongTrinh(double a, double b) {
        if (a == 0) {
            if (b == 0) {
                return "phuong trinh vo nghiem.";
            } else {
                return "Phuong trinh vo nghiem.";
            }
        } else {
            double x = -b / a;
            return "Phuong trinh co nghiem x = " + x;
        }
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Nhap a: ");
        double a = scanner.nextDouble();
        
        System.out.print("Nhap b: ");
        double b = scanner.nextDouble();
        
        String ketQua = giaiPhuongTrinh(a, b);
        System.out.println(ketQua);
        
        scanner.close();
    }
}
GiaiPhuongTrinhBacNhat.java…]()
