# maincode
funn
#threads examples
#public string getname()
#public void setname(String name)
#public string getid()

public class threadclass extends Thread{
public void run(){
System.out.println("runnning");
}
public class vijayexample{
public static void main(String[] args){
threadclass t1=new threadclass();
threadclass t2=new threadclass();
System.out.println(t1.getname());
System.out.println(t2.getname());
t1.start();
t2.start();
t1.setname("vijay");
System.out.println(+t1.getname());
}
}
