# Advance-Programming-Assignment-No-5
Assignment no 5

java code

public class MultilevelInheritanceExample {
    public static void main(String[] args) {
        Child c = new Child();
        c.showGrandparent();
        c.showParent();
        c.showChild();
    }
}

class Grandparent {
    void showGrandparent() {
        System.out.println("GrandParent");
    }
}

class Parent extends Grandparent {
    void showParent() {
        System.out.println("Parent");
    }
}

class Child extends Parent {
    void showChild() {
        System.out.println("Child");
    }
}

