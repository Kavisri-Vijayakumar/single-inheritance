class Animal {
    void sound() {
        System.out.println("Animals make sounds");
    }
}
class Dog extends Animal {  
    void sound() {
        System.out.println("Dog barks");
    }
}
public class Main {
    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.sound(); 
        Animal animal = new Animal();
        animal.sound(); 
    }
}
output
Dog barks
Animals make sounds
