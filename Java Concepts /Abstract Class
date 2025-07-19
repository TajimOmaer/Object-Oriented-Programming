package lab7;

abstract class shape{
    protected double area;
    protected int no_of_edge;
}

class triangle extends shape {
    private double base, height ;
    triangle(int edge, double b, double h){
        no_of_edge = edge;
        base = b;
        height = h;
    }
    void area(){
        area = 0.5*base*height;
    }
    void show(){
        System.out.println("Number of edge:" +no_of_edge);
        area();
        System.out.println("Area: "+area);
    }
}

class square extends shape {
    private double side;
    square(int edge, double s){
        no_of_edge = edge;
        side = s;
    }
    void area(){
        area = side*side;
    }
    void show(){
        System.out.println("Number of edge: "+ no_of_edge);
        area();
        System.out.println("Area: "+area);
    }
}
public class Lab7 {

    public static void main(String[] args) {
        triangle t1 = new triangle(3, 20, 10);
        t1.show();
        
        square s1 = new square(4,5);
        s1.show();
    }
    
}
