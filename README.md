# LoopsJava

public class Main {
    int f = 25;
    static int h= 556;


    public static void main(String[] args)
    {
        Main f1 = new Main();
        System.out.println(f1.f);
        int s = 35;
        System.out.println(s);
        System.out.println(h);
        }


//* First "Constructor" programme getting wrote off..

    public class Main {
    Main()
    {
        System.out.println("Sayan");
    }

     public static void main (String[] args) {

        Main c1 = new Main();
    }
    }


//* Called double method & integer with the help of "test" method

public class Main{

    int i = 20;
    static int k = 35;
    int f = 550:


    public void main(String[] args) {
        Main c1 = new Main();
        System.out.println(c1.i);
        System.out.println(k);

       c1.test();
    }
    public void test() {
        System.out.println(f);

    }

//*Called double method & integer with the help of "test" method another

public class Main{
    int i = 20;
    static int k = 35;

    public void main(String[] args) {
        Main c1 = new Main();
        c1.test();
    }
    public void test (){
        System.out.println(i);
        Main c2 = new Main();
        c2.test1();

    }
   public void test1 (){
        System.out.println("Lomen is used");

   }
}

//* Called double method & integer with the help of "this" command and we don't need to create "Objects" in second method
//*    And "this" command dont run in the "Static method" itself remember.

public class Main{
    int i = 20;
    static int k = 35;

    public void main(String[] args) {
        Main c1 = new Main();
        c1.test();
    }
    public void test (){
        System.out.println(i);
        this.test1();

    }
    public void test1 (){
        System.out.println(k);

    }
}

