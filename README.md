//      Lab 2
//     Activity 1

//class Rectangle{
//    public int length, width;
//    public int Calculatedarea(){
//        return(length* width);
//    }
//}
//public class runner{
//    public static void main(String[] args){
//        Rectangle rect= new Rectangle();
//        rect.length=10;
//        rect.width=5;
//        System.out.println(rect.Calculatedarea());
//    }
//}


//     Activity 2

//class Rectangle{
//    public int length, width;
//    public Rectangle(){
//        length= 5;
//        width=2;
//    }
//    public Rectangle(int 1 ,int w){
//        length=1;
//        width=w;
//    }
//    public int Calculatedarea(){
//        return (length*width);
//    }
//}
//public class runner{
//    public static void main(String[] args){
//        Rectangle rect =new Rectangle();
//        System.out.println(rect.Calculatedarea());
//        Rectangle rect1 = new Rectangle(10,20);
//        System.out.println(rect1.Calculatedarea());
//    }
//}

//      Activity 3


//class Point {
//    private int x;
//    private int y;
//
//    public Point() {
//        x = 1;
//        y = 2;
//    }
//
//    public Point(int a, int b) {
//        x = a;
//        y = b;
//    }
//
//    public void setX(int a) {
//        x = a;
//        System.out.println(x);
//    }
//
//    public void setY(int b) {
//        y = b;
//        System.out.println(y);
//    }
//
//    public void display() {
//        System.out.println("x coordinate=" + x + "y coordinate =" + y);
//    }
//
//    public void movePoint(int a, int b) {
//        x = x + a;
//        y = y + b;
//        System.out.println("x coordinate after moving=" + x + "y coordinate after moving=" + y);
//    }
//}
//
//public class runner {
//    public static void main(String[] args) {
//        Point p1 = new Point();
//        p1.movePoint(2, 3);
//        p1.display();
//
//        Point p2 = new Point();
//        p2.movePoint(5, 9);
//        p2.display();
//        p1.setX(5);
//        p1.setY(10);
//    }
//}


//      Graded Lab Test

//      Lab Task 1

//class Circle{
//    double radius;
//    Circle(){
//        radius = 1.0;
//    }
//    Circle (double r,double x){
//        radius=r;
//    }
//    double circumference(){
//        return 2* Math.PI*radius;
//    }
//}
//public class main {
//    public static void main(String[] args){
//        Circle c1= new Circle();
//        System.out.println("Circumference of c1;"+c1.circumference());
//        Circle c2=new Circle(5,10);
//        System.out.println("circumference of c2:"+c2.circumference());
//    }
//}

//         Lab Task 2


//class Account {
//    int balance;
//
//        Account() {
//        balance = 0;
//    }
//
//        Account(int b, int x) {
//        balance = b;
//    }
//
//
//    void deposit(int amount) {
//        balance = balance + amount;
//        System.out.println("Balance after deposit = " + balance);
//    }
//    void withdraw(int amount) {
//        balance = balance - amount;
//        System.out.println("Balance after withdraw = " + balance);
//    }
//
//    public static void main(String[] args) {
//
//        Account a1 = new Account();
//        a1.deposit(5000);
//        a1.withdraw(1000);
//
//        Account a2 = new Account(10000, 20);
//        a2.deposit(2000);
//        a2.withdraw(3000);
//    }
//}


//    Lab Test 3


//class Distance {
//    int feet;
//    int inches;
//
//
//    Distance() {
//        feet = 0;
//        inches = 0;
//    }
//
//
//    Distance(int f, int i) {
//        feet = f;
//        inches = i;
//    }
//
//
//    void display() {
//        System.out.println("Feet = " + feet);
//        System.out.println("Inches = " + inches);
//    }
//}
//
//public class Main {
//    public static void main(String[] args) {
//
//        Distance d1 = new Distance();
//        d1.display();
//
//        Distance d2 = new Distance(5, 8);
//        d2.display();
//    }
//}

//         Lab Task 4


//class Marks {
//    int mark1;
//    int mark2;
//    int mark3;
//
//    Marks() {
//        mark1 = 0;
//        mark2 = 0;
//        mark3 = 0;
//    }
//    Marks(int m1, int m2, int m3) {
//        mark1 = m1;
//        mark2 = m2;
//        mark3 = m3;
//    }
//    int sum() {
//        return mark1 + mark2 + mark3;
//    }
//}
//
//public class Main {
//    public static void main(String[] args) {
//
//        Marks m = new Marks(80, 75, 90);
//
//        System.out.println("Sum = " + m.sum());
//    }
//}


//           Lab Task 5


//class Time {
//    int hr;
//    int min;
//    int seconds;
//    Time() {
//        hr = 0;
//        min = 0;
//        seconds = 0;
//    }
//
//        Time(int h, int m, int s) {
//        if (h >= 0 && h < 24)
//            hr = h;
//        else
//            hr = 0;
//
//        if (m >= 0 && m < 60)
//            min = m;
//        else
//            min = 0;
//
//        if (s >= 0 && s < 60)
//            seconds = s;
//        else
//            seconds = 0;
//    }
//
//        void display() {
//        System.out.println("Hour = " + hr);
//        System.out.println("Minute = " + min);
//        System.out.println("Seconds = " + seconds);
//    }
//}
//
//public class Main {
//    public static void main(String[] args) {
//
//        Time t = new Time(12, 30, 45);
//
//        t.display();
//    }
//}
