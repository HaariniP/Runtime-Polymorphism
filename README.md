# Runtime-Polymorphism
class Shape {
    void draw() {
        System.out.println("Drawing a shape");
    }
}
class Circle extends Shape {
    void draw() {
        System.out.println("Drawing a circle");
    }
}
class Rectangle extends Shape {
    void draw() {
        System.out.println("Drawing a rectangle");
    }
}
public class RuntimePolymorphism {
    public static void main(String[] args) {
        // TODO code application logic here
          Shape shape;  
        shape = new Circle();
        shape.draw();  
        shape = new Rectangle();
        shape.draw();  
    }
    
}
output:
Drawing a circle
Drawing a rectangle
