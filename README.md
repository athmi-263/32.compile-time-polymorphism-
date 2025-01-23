public class Main {
public int addition(int x,int y){
    return x+y;
}
public int addition (int x ,int y ,int z ){
    return x + y + z;
}
public double addition(double x, double y){
    return x+y;
}
   
    public static void main(String[] args) {
        
        Main number = new Main();
        int res1 = number.addition(444,555);
        System.out.println("addition of two integers:"+res1);
        int res2 = number.addition(333,444,555);
        System.out.println("addition of three integes:"+res2);
        double res3 = number.addition(10.15,20.22);
        System.out.println("additin of two doubles:"+res3);
    }
    
}

OUTPUT
addition of two integers:999
addition of three integes:1332
additin of two doubles:30.369999999999997
# 32.compile-time-polymorphism-
