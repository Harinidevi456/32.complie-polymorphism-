# 32.complie-polymorphism-
public class Main {
 public int addition(int x,int y){
    return x+y;
}
public int addition(int x,int y,int z){
    return x+y+z;
}
public double addition(double  x,double y){
    return x+y;
}
       public static void main(String[] args) {
            Main number = new Main();
    int res1=number.addition(55, 100);
        System.out.println("Addition of two integers:" +res1);
        int res2=number.addition(45, 50, 60);
        System.out.println("Addition of three integers:" +res2);
        double res3=number.addition(11.1, 22.2);
        System.out.println("Addition of two doubles:" +res3);
    }
    
}
output
Addition of two integers:155
Addition of three integers:155
Addition of two doubles:33.3
