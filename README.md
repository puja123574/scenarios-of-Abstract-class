# scenarios-of-Abstract-class
non-abstract method), data member, constructor, and even main() method.

Have a look at the below example.


abstract class Pc{ 
        Pc(){System.out.println("PC repaired successfully");
        } 
        abstract void performance(); 
        void changeOS(){
     System.out.println("Win 10 installation is successful");
       } 
      } 
     //Creating a Child class which inherits Abstract class 
      class Hp extends Pc{ 
      void performance(){System.out.println("performance is Superb..");} 
      } 
     //Creating a Test class which calls abstract and non-abstract methods 
      class TestAbstraction1{ 
      public static void main(String args[]){ 
       Pc obj = new Hp(); 
       obj.performance(); 
       obj.changeOS(); 
      } 
     }

 
abstract class Pc{ 
        Pc(){System.out.println("PC repaired successfully");
        } 
        abstract void performance(); 
        void changeOS(){
     System.out.println("Win 10 installation is successful");
       } 
      } 
     //Creating a Child class which inherits Abstract class 
      class Hp extends Pc{ 
      void performance(){System.out.println("performance is Superb..");} 
      } 
     //Creating a Test class which calls abstract and non-abstract methods 
      class TestAbstraction1{ 
      public static void main(String args[]){ 
       Pc obj = new Hp(); 
       obj.performance(); 
       obj.changeOS(); 
      } 
     }
