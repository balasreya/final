# final
class sample
{
    final int a=10;
    void run()
    {
        a=20;
        System.out.println("the value of a");
    }
class base extends sample
    {
        final void run()
        {
        System.out.println("running");
        }
    }
}
class Main
{
    public static void main(String[] args)
    {
        sample s=new sample();
        s.run();
        base o=new base();
        o.run();
    }
}
