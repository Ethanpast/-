# *Java要点*

### 1

1. 如果一个类命名为MyClazz，它的源文件名是？**答案：C**
   A MyClazz.src
   B MyClazz
   C MyClazz.java
   D myclazz.java

2. Java语言与其他主要语言相比较，独有的特点有？**答案：C**
   A 面向对象
   B 多线程
   C 平台无关性
   D 可扩展性

3. 编译Java程序filename.java后，生成的程序是？**答案：C**
   A filename.html
   B filename.java
   C filename.class
   D filename.jar

4. 已知JavaDemo.class是一个独立应用程序相应的class文件，下面执行语句中正确的语句是？**答案：B**
   A java JavaDemo.class
   B java JavaDemo
   C javac JavaDemo
   D appletviewer javaDemo

答案：CCCB



### 2

1. 数据类型能存储值1.75？**答案：D**
   A int
   B Boolean
   C char
   D float
2. 如果定义有变量double d1,d2=4.0，则下列说法正确的是？**答案：B**
   A 变量d1、d2均初始化为4.0
   B 变量d1没有初始化，d2初始化为4.0
   C 变量d1、d2均未初始化
   D 变量d2没有初始化，d1初始化为4.0

3. 下列哪个是合法的标识符？**答案：B**
   A a=b
   B _Hello
   C 2nd
   D Chong qing

4. 指出正确的表达式  **答案：C**

​       A、 byte=128;

​       B、Boolean=null;

​       C、 long l=0xfffL; 

​       D、double=0.9239d;

5. 下列代码的执行结果是  **答案：D**
   
   ```java
   public class Test{
   public static void main(String[] args){
   System.out.println(5/2);
   }
   }
   ```
   
   A 2.5
   B 2.0
   C 2.50
   D 2
   
6. 下列标识符中合法的是  **答案：A**
   A _book
   B 5files
   C +static
   D -3.14159

7. 下列语句中，语句会发生编译错误或警告。 **答案：A**

   A.char d=”d”; 

   B.int i=34;
   C.boolean isPresent=true; 

   D.System.out.print(10);

8. Java语言中下面哪个可以用作正确的变量名称  **答案：B**

   A. 3D

   B. name

   C. extends

   D. *number

9. 下面程序输出的j值为  **答案：C**  （0xFFFFFFF1是十六进制，二进制转化为反码算十进制的值）

   ```java
   public class Test{
   
   int i=0xFFFFFFF1;
   
   int j=~i;
   
   System.out.println("j="+j);
   
   }
   ```

   A. 0
   B. 1
   C. 14
   D.-15

10. 代码"Green eggs"+"Ham"的结果是  **答案：C**

    A."Green eggs + Ham"

    B."Green eggs Ham"

    C."Green eggsHam"

    D.Error

11. 下列选项中， 是正确的Java字符串  **答案：A**

    A."\"\""

    B.'\'\"

    C."\t\t\r\n'

    D.'boolean'

12. 下列逻辑运算表达式中，其值正确的是  **答案：D** 

    A.（true）&&(3>4)

    B.!(x>0)&&(x>0)

    C.(x>0)||(x<0)

    D.(x!=0)||(x==0)

13. 表达式(int)9.9的值是  **答案：A**

    A.9

    B.10

    C.true

    D.0

14. 对象类型转换分为( )、( )  **答案：自动类型转换,强制类型转换**

答案：DBBCD AABCC ADA
自动类型转换 强制类型转换



### 3

1. switch语句用什么表示块结束？ **答案：D**
   A done
   B jump
   C exit
   D break

2. 下面程序的执行结果为  **答案：B**

   ```java
   public class FooBar{
   
   public static void main(String[] args){
   
   int i=0,j=5;
   
   tp:for(;;i++){
   
   for(;;--j)
   
   if(i>j) break tp;
   
   }
   
   System.out.println("i="+i+",j="+j);
   
   }
   
   }
   ```

   A.i=1,j=-1

   B.i=0,j=-1

   C.i=1,j=4

   D.i=0,j=4

   E.在第4行产生编译错误

3. 下面程序段执行后，i、j的值分别为  **答案：D**

   ```java
   int i=1,j=10;
   
   do{
   
   if(i++>--j) continue;
   
   }while(i<5);
   ```

   A.i=6 j=5

   B.i=5 j=5

   C.i=6 j=4

   D.i=5 j=6

4. 给定下面程序段，求输出结果  **答案：A**

   ```java
   int i=1,j=0;
   
   switch(i){
   
   case 2:j+=6;
   
   case 4:j+=1;
   
   default:j+=2;
   
   case 0:j+=4;
   
   }
   
   System.out.println(j);
   ```

   A.6

   B.1

   C.2

   D.4

答案：DBDA



### 4

1. 设有定义语句int a[]={66,88,99}; 则以下对此语句的叙述错误的是  **答案：C**

   A、 定义了一个名为a的一维数组 

   B、a数组有3个元素

   C、a数组的下标为1～3 

   D、数组中的每个元素是整型

2. 下列数组 a 中，版本较新的能在程序运行时动态调整大小的是  **答案：C**

   A、int a[] 

   B、String[] a

   C、a=new ArrayList() 

   D、a=new Array()

3. 执行完以下代码int[]x=new int[25]; 后，以下哪项说明是正确的  **答案：A**

   A、x[24]为0 

   B、x[24]未定义

   C、x[25]为0 

   D、x[0]为空

4. 下列程序段的运行结果是？  **答案：B**

   ```java
   int index=1;
   int foo[]=new int[3];
   int bar=foo[index];
   int baz=bar+index;
   ```


   A.baz的值为0 

   B.baz的值为1 

   C.baz的值为2 

   D.抛出一个异常

5. 设数组Array由以下语句定义int Array=new int[10]则数组的第一个元素的正确引用方法为  **答案：B**

   A. Array[1]

   B. Array[0]

   C. Array[]

   D. Array

6. 执行下列语句后输出的结果是  **答案：B**  （\“是为了再字符串中有引号，相当于一个”符号）

   ```java
   String s="\"Hello,World!\"";
   
   System.out.println(s.length());
   ```

   A.12

   B.14

   C.16

   D.18

7. 有下列程序段：

   ```java
   byte[] array1,array2[];
   
   byte array3[][];
   
   byte[][] array4;
   ```

   如果数组元素都已经初始化，下列哪个语句会产生编译错误？  **答案：A**  （array1是一维数组，array2是二维数组）

   A.array2=array1

   B.array2=array3

   C.array2=array4

   D.array4=array3

8. 下列程序段的运行结果为  **答案：B**

   ```java
   int index=1;
   
   int foo[] =new int[3];
   
   int bar=foo[index];
   
   int baz=bar+index;
   ```

   A.baz的值为0

   B.baz的值为1

   C.baz的值为2

   D.抛出异常

   E.代码不能编译

9. 下列程序的输出结果为  **答案：D**

   ```java
   int []x[]={{1,2},{3,4,5},{6,7,8,9}};
   
   int [][]y=x;
   
   System.out.println(y[2][1]);
   ```

   A.3

   B.4

   C.6

   D.7

答案：CCABBBABD

### 5

1. 方法重载是指 （）  **答案：A**

   A、两个或两个以上的方法取相同的方法名，但形参的个数或类型不同

   B、两个以上的方法取相同的名字和具有相同的参数个数，但形参的类型可以不同

   C、两个以上的方法名字不同，但形参的个数或类型相同
   D、两个以上的方法取相同的方法名，并且方法的返回类型相同

2. 选出能与aMethod方法重载的方法。（）  **答案：ACD**

   ```java
   public class MyClass{
   
   public float aMethod(float a,float b){
   
   }
   
   //下面哪个方法的定义可以放在该位置。
   
   }
   ```

   A.public int aMethod(int a,int b){}

   B.public float aMethod(float x,float y){}

   C.public float aMethod(float a,float b,int c){}

   D.public float aMethod(int a,int b,int c){}

   E.public void aMethod(float a,float b){}

3. 下面的类定义，与setVar()重载的方法是。（）  **答案：ACD**

   ```java
   public class MyClass{
   
   public void setVar(int a,int b,float c){}
   
   }
   ```


   A. private void setVar(int a,float c,int b){}
   B. protected void setVar(int x,int y,float z){}
   C. public int setVar(int a,float c,int b){return a;}

   D. public int setVar(int a,float c){return a;}

4. 在下列类定义中，与MyClass方法重载的是 （）  **答案：AC**

   ```java
   public class MyClass{
   
   public MyClass(int x,int y,int z){}
   
   }
   ```

   A.MyClass(){}

   B.protected int MyClass(){}

   C.private MyClass(int z,int y,byte x){}

   D.public void MyClass(byte x,byte y,byte z){}

   E.public Object MyClass(int x,int y,int z){}

   

### 6

1. 已知如下代码：

   ```java
   Public class ArrayInit
   
   {
   
   Int a[]=new int[10];
   
   public static void main(String arg[]){
   
   System.out.println (a[10]);
   
   }
   
   }
   ```

   以下哪个说法是正确的？  **答案：B**

   A、编译通过，运行后输出null 

   B、编译有错

   C、编译通过，运行后输出0 

   D、编译通过，但运行时有异常发生

2. 下面关于java中类的说法哪个是不正确的  **答案：C**

   A、类体中只能有变量定义和成员方法的定义，不能有其他语句。

   B、构造函数是类中的特殊方法。

   C、类一定要声明为public的，才可以执行。

   D、一个java文件中可以有多个class定义。

3. 下面哪个修饰符修饰的变量是所有同一个类生成的对象共享的  **答案：C**

   A、public 

   B、private 

   C、static 

   D、final

4. 下列关于构造方法的说法正确的是  **答案：A**

   A、因为构造方法名与类名必须相同，所以构造方法的首字母必须大写

   B、构造方法是给对象赋初值，所以没有返回值，要用void来声明。

   C、构造方法不能被程序调用，也不可以重载。

   D、一个类只允许有一个构造方法。

5. 下列应用程序打印几行？   **答案：D**

   ```java
   public class HelloTest {
   {System.out.println("Hello.");}
   public static void main(String[] args) {
   // TODO Auto-generated method stub
   new HelloTest();
   new HelloTest();
   new HelloTest();
   }
   }
   ```

   A 0
   B 1
   C 2
   D 3


6. Student类的默认构造器是？  **答案：B**
   A new Student()
   B Student(){}
   C Student{}
   D public class Student

7. 给定接口Runnable的定义：

   ```java
   public interface Runnable{
   void run();
   }
   ```

   下面哪个语句创建了匿名内部类的实例？  **答案：D**

   A.Runnable r=new Runable(){};
   B.Runnable r=new Runable(public void run(){});
   C.Runnable r=new Runable{public void run(){}};
   D.System.out.println(new Runable(){public void run(){}});

8. 有下面类定义：

   ```java
   public class MyOuter{
   public static class MyInner{
   public static void foo(){}
   }
   }
   ```

   如果在其它类中创建MyInner类的实例，下面哪个是正确的？  **答案：A**

   A.MyOuter.MyInner mi=new MyOuter.MyInner();
   B.MyOuter.MyInner mi=new MyInner();
   C.MyOuter m=new MyOuter();
   MyOuter.MyInner mi=m.MyOuter.MyInner();
   D.MyInner mi=new MyOuter.MyInner();

9. 要设置一个类的属性为私有的，应使用关键字  **答案：B**

   A. public

   B. private

   C. pretected

   D. static

10. Java用来定义一个类时，所使用的关键字为  **答案：A**

    A. class

    B. public

    C. struct

    D. class 或 struct

11. 以下关于构造函数的描述错误的是  **答案：A**

    A. 构造函数的返回类型只能是void型。
    B. 构造函数是类的一种特殊函数，它的方法名必须与类名相同。
    C. 构造函数的主要作用是完成对类的对象的初始化工作。
    D. 一般在创建新对象时，系统会自动调用构造函数。

12. 编译并运行以下程序，以下描述哪个选项是正确的  **答案：D**

    ```java
    1 class A {
    
    2 protected boolean equals() {
    
    3 return super.equals();
    
    4 }
    
    5 }
    ```

    A. 编译通过运行无异常

    B. 编译通过但运行时出错

    C. 行2出错，不能成功编译

    D. 不能成功编译，行3出错

13. 在下列关于实例变量、类变量、实例方法和类方法叙述中，是不正确的？  **答案：A**

    A.实例方法可以访问实例变量和类变量

    B.类方法不能访问实例变量

    C.实例变量和类变量都可以通过类名访问

    D.类方法只能访问类变量

14. 在下列哪个表达式中，可以得到42度的余弦值？  **答案：C**

    A.double d=Math.cos(42);

    B.double d=Math.cosine(42);

    C.double d=Math.cos(Math.toRadians(42));

    D.double d=Math.cos(Math.toDegrees(42));

    E.double d=Math.toRadians(42)(42);

15. 给定接口Runnable的定义

    ```java
    public interface Runnable{
    
    void run();
    
    }
    ```

    下面哪个语句创建了匿名内部类的实例  **答案：D**

    A.Runnable r=new Runnable(){}

    B.Runnable r=new Runnable(public void run(){});

    C.Runnable r=new Runnable{public void run(){}};

    D.System.out.println(new Runnable(){public void run(){}});

    E.System.out.println(new Runnable(public void run(){}));

16. 在下列哪个表达式中，可以得到42度的余弦值？  **答案：C**

    A.double d=Math.cos(42);

    B.double d=Math.cosine(42);

    C.double d=Math.cos(Math.toRadians(42));

    D.double d=Math.cos(Math.toDegrees(42));

    E..double d=Math.toRadians(42);



答案：CCCAD BDABA ADACD C



### 7

1. 下面关于继承的描述哪项是正确的？  **答案：A** 

   A、在java中只允许单一继承。

   B、在java中一个类只能实现一个接口。

   C、在java中一个类不能同时继承一个类和实现一个接口。

   D、java允许多重继承。

2. 下面哪个方法不能被子类覆盖？  **答案：A**
   A final void methodda(){}
   B void final methoda(){}
   C static void methoda(){}
   D final abstract void methoda(){}

3. 在Java语言中，下面关于类的继承关系描述正确的是？  **答案：B**
   A 一个子类可以有多个父类
   B 一个父类可以有多个子类
   C 子类可以使用父类的所有属性和方法
   D 子类一定比父类有更多的成员方法

4. 下面是关于类及其修饰符的一些描述，不正确的是？  **答案：B**

   A、abstract类只能用来派生子类，不能用来创建abstract类的对象。

   B、final类不但可以用来派生子类，也可以用来创建final类的对象。

   C、abstract不能与final同时修饰一个类。

   D、abstract方法必须在abstract类中声明，但abstract类定义中可以没有abstract方法。

5. 关于私有访问控制符protected修饰的成员变量，以下说法正确的是？  **答案：D**

   A、可以被三种类所引用：该类自身、与它在同一个包中的其他类、在其他包中的该类的子类

   B、可以被种类访问和引用：该类本身、该类的所有子类

   C、只能被该类自身所访问和修改

   D、只能被同一个包中的类访问

6. Java中有句名言“一切皆对象”，那么，除本身以外的所有类也是()的子类。  **答案：A**
   A java.lang.Object
   B java.lang.Class
   C java.applet.Applet
   D java.awt.Frame

7. A派生出子类B，B派生出子类C，并且在Java源代码中有如下声明：

   A a0 =new A();

   A a1 =new B();

   A a2 =new C();

   问以下哪个说法是正确的？  **答案：D**

   A. 只有第1行能通过编译
   B. 第1、2行能通过编译，但第3行编译出错
   C. 第1、2、3行能通过编译，但第2、3行运行时出错
   D. 第1行、第2行和第3行的声明都是正确的

8. 关于super关键字叙述错误的是： **答案：D**
   A. 在子类中访问超类中被隐藏的成员变量；
   B. 在子类中调用超类中被覆盖的方法；
   C. 在子类中调用超类的构造方法；
   D.在子类对象中调用父类中被protected修饰的成员；

填空
1.实现类的继承的关键字是（ ），所有类的根类是（ ） 。**答案：extends,Object**

答案：AABBD ADD
\1. extends Object



### 8

1. 以下哪个接口的定义是正确的？  **答案:  D**

   A、

   ```java
   interface A
   
   { void print(){};}
   ```

   B、

   ```java
   abstract interface A
   
   { void print();}
   ```

   C、

   ```java
   abstract interface A extends A1,A2 //A1、A2为已定义的接口
   
   { abstract void print(){};}
   ```

   D、

   ```java
   interface A
   
   { void print();}
   ```

   

2. 构造方法何时被调用？  **答案：B**

   A、类定义时 

   B、创建对象时

   C、调用对象方法时 

   D、使用对象的变量时

3. 在 Java 中，能实现多重继承效果的方式是 。  **答案：C**

   A、内部类 

   B、适配器 

   C、接口 

   D、同步

4. 下列抽象类定义中，正确的是？  **答案：B**
   A class AlarmClock{abstract void alarm();
   B abstract class AlarmClock{abstract void alarm();}
   C class abstract AlarmClock{abstract void alarm();}
   D abstract class AlarmClock{abstract void alarm{System.out.println(“alarm!”);}}

5. 假定X、Y和Z都是接口，下列语句中哪个是正确的接口声明？  **答案：A**
   A public interface A extends X{void aMethod();}
   B interface B implements Y{void aMethod();}
   C interface C extends X,Y,Z{void amethod();}
   D interface C extends X{protected void aMethod();}

6. 下面有关接口的说法，正确的是  **答案：B**
   A 接口与抽象类是相同的概念
   B 实现一个接口必须实现接口的所有方法
   C 接口之间不能有继承关系
   D 一个类只能实现一个接口

7. 在使用interface声明一个接口时，只可以使用（）修饰符修饰该接口。  **答案：D**

   A. private

   B. protected

   C. private protected

   D. public

   

答案：DBCBA BD



### 9

1. 有下列程序：

   ```java
   import java.io.IOException;
   
   public class Test {
   
   public static void main(String[] args) {
   
   // TODO Auto-generated method stub
   
   try {
   
   methodA();
   
   }catch(IOException e) {
   
   System.out.println("Caught Exception");
   
   }
   
   }
   
   public static void methodA() {
   
   throw new IOException();
   
   }
   
   }
   ```

   该程序的输出结果为：  **答案：A**

   A.代码不能被编译

   B.输出Caught Exception

   C.输出Caught IOException

   D.程序正常执行，没有任何输出

2. 有下列程序：

   ```java
   public class Foo{
   
   public static void method(int i){
   
   try{
   
   if(i>0){
   
   return;
   
   }else{
   
   System.exit(1);
   
   }
   
   }finally{
   
   System.out.println("Finally");
   
   }
   
   }
   
   public static void main(String[] args){
   
   method(5);
   
   method(-5);
   
   }
   
   }
   ```

   该程序输出结果为：  **答案：B**
   A. 没有任何输出
   B. 输出“Finally”
   C. 编译错误
   D.1

3. 有下列程序：

   ```java
   public class Test{
   
   public static void main(String[] args){
   
   String foo=args[1];
   
   String bar=args[2];
   
   String baz=args[3];
   
   }
   
   }
   ```

   若用下面方式执行该程序，baz的值为  **答案：D**

   java Test Red Green Blue

   A.baz的值为null

   B.baz的值为“Red”

   C.代码不能编译

   D.程序抛出异常

   

答案：ABD



### 10

1. 下面哪个方法是获得String中的字符数？  **答案：B**
   A size()
   B length()
   C width()
   D 以上都不是

2. 代码“Green eggs”+“Ham”的结果是？  **答案：C**
   A “Green eggs+Ham”
   B “Green eggs Ham”
   C “Green eggsHame”
   D Error

  3.下列选项中，哪个是正确的Java字符串？  **答案：AB**
       A "\"\""
       B "Oxzabc"
       C \'\""
       D "\t\t\r\n'

4. 下列代码的执行结果是  **答案：C**

   ```java
   public class Test{
   public static void main(String[] args){
   String s1 = new String(“Hello”);
   String s2 = new String(“Hello”);
   System.out.print(s1 == s2);
   System.out.print(s1.equals(s2));
   }
   }
   ```
   
      A true false
      B true true
      C false true
      D false false
   
5. 执行下列程序段后foo的值为   **答案：C**

   ```java
   String foo="blue";
   
   boolean[] bar=new boolean[1];
   
   if(bar[0]){
   
   foo="green";
   
   }
   ```

   A.""

   B.null

   C.blue

   D.green

6. 下列哪个String类的方法返回指定字符串的一部分？  **答案：B**
   A. extractstring()
   B. substring()
   C. Substring()
   D.Middlestring()

7. 阅读下面代码，它完成的功能是  **答案：B**

   ```java
   String[] a={"Java","软件","编程","软件","技术"};
    for(int i=0; i<a.length; i++){
     if(a[i].equals("软件")){
      a[i]="软件工程";
     }
    } 
   ```

   A.查找

   B.查找并替换

   C.增加

   D.删除

答案：BCBCC BB





### 11

1. 下列流中哪个不属于字符流  **答案：D**

   A、InputStreamReader 

   B、BufferedReader

   C、FilterReader 

   D、FileInputStream

2. 能够写内存的类是  **答案：C**
   A FileOutputStream
   B PrintWriter
   C ByteArrayOutputStream
   D StringWriter

3. 下列不是InputStream子类的是  **答案：D**

   A. 文件输入流FileInputStream

   B. 对象输入流ObjectInputStream

   C. 字符输入流CharInputStream

   D. 压缩文件输入流ZipInputStream

4. 一个类要具备什么条件才可以序列化  **答案：C**

   A.继承ObjectStream类

   B.具有带参数构造方法

   C.实现Serializable接口

   D.定义了writeObject()方法

5. 文件debug.txt在文件系统中不存在，执行下列代码后哪个选项是正确的  **答案：C**

   ```java
   Path file=Paths.get("D:/study/debug.txt");
   
   try(InputStream in=Files.newInputSteam(file,StandardOpenOption.READ)){
   
   //操作in对象，略
   
   }catch(IOException e){
   
   e.printStackTrace();
   
   }
   ```

   A.代码不能编译

   B.代码能够运行并创建debug.txt文件

   C.代码运行时抛出NoSuchFileException异常

   D.代码运行时抛出FileNotFoundException异常

6. 若要删除文件，使用下面哪个类比较合适  **答案：D**

   A.FileOutputStream

   B.File

   C.RandomAccessFile

   D.Files

7. 使用createDirectory(Path dir)创建一个目录，若该目录已存在，将抛出异常()。  **答案：A**

   A.FileAlreadyExistsException

   B.NoSuchFileException

   C.DirectoryNotEmptyException

   D.DirectoryAlreadyExistsException

   


答案：DCDCC DA



### 12

1. 现有如下类型：

   a - java.util.Hashtable

   b - java.util.List

   c - java.util.ArrayList

   d - java.util.SortedSet

   和定义：

   1-使用本接口，允许用户控制集合中每个元素的插入位置。

   2-使用本集合，确保用户可以按照递增或元素的自然顺序遍历集合。

   3-本具体类型允许空元素及基于索引的访问。

   4-本集合是同步的。

   哪一组匹配是对的？  **答案：B**

   

   A. 2描述d； 3描述b。

   B. 1描述b； 3描述C。

   C. 3描述a； 4描述b。

   D. 4描述a； 2描述C。

2. 创建一个只能存放String的泛型ArrayList的语句是  **答案：B**
   A. ArrayList al=new ArrayList()；

   B. ArrayList al=new ArrayList();

   C. ArrayList al=new ArrayList()；

   D. ArrayList al =new List();

3. 下列哪些项是泛型的优点  **答案：AC**
   A. 不用向下强制类型转换

   B. 代码容易编写

   C. 类型安全

   D. 运行速度快

4. 下列方法不是Collection通用方法的有  **答案：C**

   A. iterator

   B. add()

   C. get()

   D. remove()

5. 在Java中，类课用于创建链表数据结构的对象  **答案：A**

   A. LinkedList

   B. ArrayList

   C. Collection

   D. HashMap

6. Set集合的特点是  **答案：B**

   A. 元素有序

   B. 元素无序，不存储重复元素

   C. 存储重复元素

   D. Set集合都是线程安全的

7. 将集合转成数组的方法是  **答案：C**

   A. asList()

   B. toCharArray()

   C. toArray()

   D. copy()

8. 使用 Treeset的无参构造创建集合对象存储元素时,该元素必须  **答案：A**

   A. 实现 Comparable接口

   B. 有main方法

   C. 有get和set方法

   D. 实现 Seria1 izable接口

9. Arraylist的初始化内容如下:

   ```java
   ArrayList list
   
   list. add (java)i
   
   list. add( aaa")i
   
   list. add ("java)i
   
   list. add( bbb")i
   ```

   下面可以删除list中所有的java"的代码是  **答案：A**

   A.

   ```java
    for (int i=list size()-1; i >=0;i--){
   
   if("java"equals(list. get (i))){
   
   list. remove(i);
   
   }
   
   }
   ```

   B.

   ```java
    for (int i =0; i< list size();i++){
   
   if("java"equals(list. get(i))){
   
   list. remove(i)
   
   }
   
   }
   ```

   C. list.remove("java");

   D. list. removeAll("java");

10. 将Map集中的键存储到Set集合的方法是  **答案：C**

    A. entrySet

    B. get()

    C. keySet

    D. put()

11. 下面代码运行的结果是  **答案：A**

    ```java
    Arraylist<string> al = new ArrayList<String>();
    
    al. add(true);
    
    a1.add(123);
    
    al. add( "abc");
    
    stem out. println(al);
    ```

    A. 编译失败

    B. [true, 123]

    C. [true, 123, abc]

    D. [abc]

12. 实现下列哪个接口,可以启用比较功能  **答案：D**

    A. Runnab1e接口

    B. Iterator接口

    C. Seria1 izable接口

    D. Comparator接口

13. 关于迭代器说法错误的是  **答案：D**

    A. 迭代器是取出集合元素的方式

    B. 迭代器的 hasNext()方法返回值是布尔类型

    C. List集合有特有迭代器

    D. next()方法将返回集合中的上一个元素

14. Vector类的特点是  **答案：A**

    A. 线程同步

    B. 线程不同步

    C. 增删快

    D. 底层是链表结构

15. Linkedlist类的特点是  **答案：B**

    A. 查询快

    B. 增删快

    C. 元素不重复

    D. 元素自然排序

16. ArrayList类的底层数据结构是  **答案：A**
    A. 数组结构

    B.链表结构

    C.哈希表结构

    D.红黑树结构

17. java的集合框架中重要的接口java.util.Collection定义了许多方法。选项中哪个方法不是Collection接口所定义的？  **答案：A**

    A. compareTo(Object obj)
    B. boolean remove(Object obj)
    C. boolean constainsAll(Collection c)
    D. int size

18. 集合框架的顶层接口是  **答案：B**
    A.java.util.Map

    B.java.util.Collection

    C. java.util.List

    D.java.util.Collections

19. 欲构造ArrayList类的一个实例，此类继承了List接口，下列哪个方法是正确的 ？  **答案：B**

    A、ArrayList myList=new Object（）； 

    B、List myList=new ArrayList（）；

    C、ArrayList myList=new List（）； 

    D、List myList=new List（）；

20. 在结合框架核心的基本结构中，对象群存储没有次序，并且不允许有重复对象的类是  **答案：A**
    A Set
    B Collection
    C Map
    D List

21. 下列哪一个类不是Set的实例类?  **答案：D**
    A. HashSet
    B. LinkedHashSet
    C. TreeSet
    D. SortSet

22. 下列哪一个类不是List的实例类?  **答案：D**
    A. Vector
    B. ArrayList
    C. Stack
    D. AbstractList

23. 下列哪一个不是泛型通配符?  **答案：C**

    A. ?
    B. ? extends T
    C. ? implements T
    D. ? super T

24. 下面哪个可以产生一个元素序列，然后可以使用nextElement方法检索序列中的连续元素  **答案：B**
    A.Iterator
    B.Enumeration
    C.ListIterator
    D.Collection
    E.HashMap

25. 有下列一段代码，执行后输出结果为  **答案：C**

    ```java
    TreeSet mySet=new TreeSet<>();
    
    mySet.add("one");
    
    mySet.add("two");
    
    mySet.add("three");
    
    mySet.add("four");
    
    mySet.add("one");
    
    Iterator it=mySet.iterator();
    
    while(it.hasNext()){
    
    System.out.println(it.next()+" ");
    
    }
    ```

    A.one two three four

    B.four three two one

    C.four one three two

    D.one two three four one

26. 如果要求其中不能包含重复的元素，使用哪种结果存储最合适  **答案：C**

    A.Collection

    B.List

    C.Set

    D.Map

    E.Vector

答案：1-2. BB 3. AC 4. C 5. A 6. B 7. C 8. A 9. A 10. C
11-15. ADDAB 16-20. AABBA 21-25. DDCBC 26. C



### 13

填空

1. 在JDBC中，事务操作方法都位于接口java.sql.Connection中。可以通过调用（ ） 来禁止自动提交。**答案：setAutoCommit(false)**   
2. 在JDBC中，事务操作成功后，系统将自动调用（ ）提交，否则调用（ ）回滚。**答案：commit() rollback()** 
3. （ ）对象自动维护指向当前数据行的游标。每调用一次 （ ） 方法，游标向下移动一行。**答案：ResultSet next()**
4. （ ） 对象是executeQuery()方法的返回值，它被称为结果集，它代表符合SQL语句条件的所有行，并且它通过一套getXXX方法（这些get方法可以访问当前行中的不同列）提供了对这些行中数据的访问。**答案：ResultSet**
5. 三种 Statement对象分别是（ ），（ ），（ ）。**答案：Statement | preparedStatemen | CallableStatement**
6. JDBC中与数据库建立连接是通过调用 DriverManager类的静态方法（ ）实现的。**答案：getConnection(url,user,password)**
7. 加载JDBC驱动是通过调用方法 （ ） 实现的。**答案：java.lang.Class.forName()** 
8. JDBC API：供程序员调用的接口与类，集成在（ ）和（ ）包中。**答案：java.sql | javax.sql** 
9. （ ）是一种用于执行SQL语句的Java API，为多种关系数据库提供统一访问。它由一组用Java语言编写的类和接口组成。**答案:JDBC**




选择

1. 以下选项关于PreparedStatement的说法错误的是  **答案：C**

   A. PreparedStatement继承了Statement ，可以执行预编译的SQL语句。

   B. PreparedStatement可以有效的防止SQL注入。

   C. PreparedStatement只能执行带问号占位符的预编译SQL，不能执行SQL语句。

   D. PreparedStatement可以存储预编译的SQL语句，从而提升执行效率。

2. SELECT COUNT(*) FROM emp;这条SQL语句执行，如果员工表中没有任何数据，那么ResultSet中将会  **答案：B**

   A. null

   B. 有数据

   C. 不为null，但是没有数据

   D. 以上都选项都不对

3. 下面的描述错误的是  **答案：B**

   A. Statement的executeQuery()方法会返回一个结果集 。

   B. Statement的executeUpdate()方法会返回是否更新成功的boolean值。

   C. Statement的execute ()方法会返回boolean值 ，含义是是否返回结果集。

   D. Statement的executeUpdate()方法会返回值是int类型，含义是DML操作影响记录数。

4. 以下选项中有关Connection描述错误的是  **答案：D**

   A. Connection是Java程序与数据库建立的连接对象，这个对象只能用来连接数据库，不能执行SQL语句。

   B. JDBC的数据库事务控制要靠Connection对象完成。

   C. Connection对象使用完毕后要及时关闭，否则会对数据库造成负担。

   D. 只用MySQL和Oracle数据库的JDBC程序需要创建Connection对象，其他数据库的JDBC程序不用创建Connection对象就可以执行CRUD操作。

5. ResultSetMetaData rsmd = rs.getMetaData()是什么意思?  **答案：B**

   A. 取得列数

   B. 得到结果集(rs)的结构，比如字段数、字段名等

   C. 返回表名

   D. 取得行数

6. SQL SELECT 语句中的WHERE 用于说明  **答案：B**

   A. 查询分组

   B. 查询条件

   C. 查询排序

   D. 查询数据

7. 在Java中，与数据库连接的技术是  **答案：D**

   A. 开放数据库连接

   B. 数据库厂家驱动程序

   C. 数据库厂家的连接协议

   D. Java数据库连接

8. JDBC中，用于表示数据库连接的对象是  **答案：C**

   A. PreparedStatement

   B. DriverManager

   C. Connection

   D. Statement

9. 以下对JDBC事务描述错误的是  **答案：D**

   A. JDBC事务可以保证操作的完整性和一致性

   B. JDBC事务是由Connection发起的，并由Connection控制

   C. JDBC事务属于JAVA事务的一种

   D. JDBC事务属于容器事务类型

10. Java中，JDBC是指  **答案：A**
    A. Java程序与数据库连接的一种机制

    B. Java程序与浏览器交互的一种机制

    C. Java类库名称

    D.Java类编译程序

11. 在JDBC API中完成和数据库提交带参数的SQL语句的类是？  **答案：B**
    A Statement
    B PreparedStatement
    C CallableStatement
    D ResultSet

12. 在JDBC API中，可通过对象执行SQL语句  **答案：C**

    A.java.sql.RecordSet

    B.java.sql.Connection

    C.java.sql.Statement

    D.java.sql.PreparedStatement

13. 下面叙述哪个是不正确的？  **答案：D**

    A.调用DriverManager类的getConnection()方法可以获得连接对象

    B.调用Connection类的createStatement()方法可以获得Statement对象

    C.调用Statement类的executeQuery()方法可以获得ResultSet对象

    D.调用Connection类的prepareStatement()方法可以获得Statement对象

14. 要加载Sun的JDBC-ODBC桥驱动程序应该调用哪个方法？  **答案：A**

    A.Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");

    B.DriverManager.getConnection();

    C.executeQuery()并给定一个Statement对象

    D.装载JDBC-ODBC桥驱动程序不需要做任何事情


答案：1-5 CBBDB 6-10 BDCDA 11-14 BCDA

### 14

1.Java UML类图的主要构成？**答案：类，包，接口**

2.Java程序中，参数的传值方式有几种？分别是？他们的区别是？**答案：两种，值传递与引用传递，区别：值传递实参传递给形参的是值形参和实参在内存上是两个独立的变量对形参做任何修改不会影响实参，引用传递实参传递给形参的是参数对于 堆内存上的引用地址实参和形参在内存上指向 了同一块区域对形参的修改会影响实参**

3.何为实例方法，何为类方法？实例方法和类方法的区别是什么？**答案：实例方法：当一个类创建了一个对象后，这个对象就可以调用该类的方法（对象方法）。类方法：用static修饰的方法。区别：类方法可以通过类名调用，实例方法不能通过类名调用。当该类创建对象后，类中的实例方法才分配入口地址，从而实例方法可以被类创建的任何对象调用执行。类方法在该类被加载到内存时，就分配了相应的入口地址。方法不仅可以被类创建的任何对象调用执行，也可以直接通过类名调用。**

4.包的用途？**答案：为了避免相同的类名带来的问题**

6.import关键字的用途？import语句在java程序中的位置？**答案：导入静态成员，导入接口类型，写在程序文件的开始部分**

7.假设现有一个A类，其成员变量和方法修饰符分别为private, protected, public，那么在B类中新创建一个A类的对象，请问该对象能不能访问到自己的成员变量和方法？**答案：可以访问方法，不能访问变量**

8.构造方法是否有类型的限制？**答案**： 没有

9.下面的类定义有什么问题？请修改错误，使程序运行时不会出问题   **答案：不能对类型Avg中的非静态方法findAvg进行引用。**

```java
class Avg {

   public static void main(String[] args) {

​     double a = 5.1;

​     double b = 20.32;

​     double c = 32.921;

​     System.out.println(findAvg(a, b, c));

   }

   double findAvg(double a, double b, double c) {

​     return (a + b + c) / 3.0;

   }

}
```

10.下面的类定义有哪些问题？**答案： import 包位置错误**

```java
import java.util.*;

package myClass;

public class lzw{

   public double avg(double a,double b){

​     return (a+b)/2;

   }

}
```





# Java代码

### 1

##### 1.求从1加到100的和

```java
public class One {

public static void main(String[] args) {

int i=1 ,sum=0;

for ( ;i <=100; i++) {

sum=sum+i;

}

System.out.println(sum);

}

}
```

##### 2.求从1加到100的奇数和

```java
public class Two {
	public static void main(String[] args) {
		int i=1 ,sum=0;
		for ( ;i <=100; i=i+2) {
			sum=sum+i;
		}
		System.out.println(sum);
	}
}
```



##### 3.求从1到10的阶乘和

```java
public class Three {
	public static void main(String[] args) {
		int sum=0,factorial =1;
		for (int i = 1; i <= 10; i++) {
			for (int j = 1; j <=i; j++) {
				factorial =factorial*j;
			}
			sum=sum+factorial ;
			factorial =1;
			
		}
		System.out.println(sum);
	}
}

```



##### 4.求100以内的素数

```java
public class Four {
	public static void main(String[] args) {
		for (int i = 2; i <=100; i++) {
			boolean flag=false;
			for (int j = 2; j <=i/2; j++) {
				if(i%j==0) {
					flag=true;
					break;}
				}
			if(flag==false)
				System.out.print(i+",");
		}
	}
}
```



##### 5.求1000以内能被7和9整除的数

```java
public class Five {
	public static void main(String[] args) {
		for (int i = 63; i <=1000; i=i+7*9) {
			if(i%7==0&&i%9==0)
				System.out.print(i+",");
		}
	}
}
```

### 2

##### 1.输出字符串：

在命令行输出“Hello Java!”

```java
public class HelloJvav {

  public static void main(String[] args) {
  
​   System.out.println("Hello Java!");
  }

}
```

##### 2.编写程序，从键盘上输入一个double型的数值，转换后输出：

编写程序，从键盘上输入一个double型的华氏温度，然后将其转换为摄氏温度输出，保留2位小数。转换公式如下：摄氏度=（5/9）*(华氏度-32）。

```java
public class tchange {
	public static void main(String[] args) {
		Scanner in =new Scanner(System.in);
		double C;
		double F=in.nextDouble();
		C=(F-32)*5/9;
		System.out.println("Celsius:"+String.format("%.2f", C));
		in.close();
	}
}
```

##### 3.从键盘输入一个矩形的长和宽，输出其面积：

从键盘输入一个矩形的长和宽，其类型为double类型，输出矩形的面积保留2位小数。

```java
public class area {
	public static void main(String[] args) {
		Double length;
		Double width;
		Double area;
		Scanner sc = new Scanner(System.in);
		length = sc.nextDouble() ;
		width = sc.nextDouble() ;
		area= length * width;
		System.out.println("The area is:"+String.format("%.2f", area));
		sc.close();
	}
}
```

### 3.

##### 1.求两数之间的奇数和:

  任意输入两个整数，求两数间m和n（含两端，n>m）的奇数和。

```java
public class oddsum {
	public static void main(String[] args) {
		Scanner in = new Scanner(System.in);
		int a = in.nextInt();
		int b = in.nextInt();
		int max , min ;
		int sum = 0 ;
		/*
		 * if (a>b) { max=a; min=b; }else if (a==b) { max=a; min=b; }else { max=b;
		 * min=a; }
		 */
		for(int i =a; i <= b;i++) {
			if(i%2==0) {
				continue;
			}
			sum+=i;
		}
		System.out.println(sum);
	}
}
```

##### 2.评委评分：

评分规则要求去掉一个最高分和一个最低分，求出平均分。

输入数据包括两行: 第一行为n，表示n个评委，n>2。 第二行是n个评委的打分，分数之间有一个空格。打分是可以带有小数部分的。

输出平均分，结果保留两位小数。

```java
import java.util.Scanner;

public class grade {

	public static void main(String[] args) {
		Scanner sc =new Scanner (System.in);
		int n = sc.nextInt();
		float []a =new float [n];
		float sum = 0 ;
		for(int i = 0;i<n;i++) {
			a[i]=sc.nextFloat();
			sum=sum+a[i];
		}
	
		float max = a[0];
		float min = a[0];
		for(int i = 0;i<n;i++) {
			if(a[i]>max) {
				max=a[i];
			}else if(a[i]<min) {
				min=a[i];
			}
		}
		float average=(sum-max-min)/(n-2);
		System.out.printf("average score:%.2f",average);
	}
}
```

##### 3.倒置整数:

输入一个正整数N,输出一个倒置正整数N'

```java
import java.util.Scanner;

public class reserve {
    public static void main(String[] args) {
        Scanner sc =new Scanner(System.in);
        int a = sc.nextInt();
        StringBuffer str= new StringBuffer(Integer.toString(a));
        str.reverse();
        System.out.println(str);
    }
}
```

### 4.

##### 1.计算圆的面积：

编写一个Circle类，至少包含数据域radius，构造方法SimpleCircle(double newRadius)，计算圆的面积的方法getArea()。编写主类TestSimpleCircle，输入圆的半径，输出圆的面积。
```java

import java.util.Scanner;

public class Circle {
	public static void main(String[] args) {
		TestPassObject c = new TestPassObject();
		Scanner in = new Scanner(System.in);
		double r = in.nextDouble();
		double area = c.getArea(r);
		System.out.printf("The area of the circle of radius %.2f is %.2f ", r, area);
	}
}

class TestPassObject {
	private double radius;

	public void SimpleCircle(double newRadius) {
		this.radius = newRadius;

	}

	public double getRadius() {
		return radius;
	}

	public double getArea(double radius) {
		return (Math.PI * radius * radius);
	}
}
```

##### 2.矩形类:

 *定义一个名为Rectangle的类表示矩阵，其中包含有length、width两个double型的成员变量表示矩形的长和宽。

 \* 要求为每个变量定义访问方法和修改方法，定义求矩形周长的方法perimeter()和求面积的方法area()。

 \* 定义一个带参数构造方法，通过给出的长和宽创建矩形对象。

 \* 定义默认构造方法，在该方法中调用有参数的构造方法，将矩形长宽都设置为1.0。
```java
public class RectDemo {

	public static void main(String[] args) {
		
		Rectangle rect = new Rectangle();
		rect.setLength(20);
		rect.setWidth(10);
		System.out.println("length:" + rect.getLength());
		System.out.println("width:" + rect.getWidth());
		System.out.println("perimeter:" + rect.perimeter());
		System.out.println("area:" + rect.area());
	}

}

class Rectangle {
	private double width = 1;
	private double length = 1;

	public void setLength(double length) {
		this.length = length;
	}
	
	public void setWidth(double width) {
		this.width = width;
	}
	
	public double getLength() {
		return length;
	}
	
	public double getWidth() {
		return width;
	}
	
	public double area() {
		return this.width * this.length;
	}
	
	public double perimeter() {
		return (this.length + this.width) * 2;
	}
}
```

### 5.

##### 1.给方法传递对象参数:

定义一个方法printAreas(myCircle, n)，其中myCircle为SimpleCircle类创建的对象，n为从键盘接收的正整数，0<n<10。printAreas()方法实现输出n个圆的面积（保留2位小数），每个圆的半径分为从1至n。

```java
import java.util.Scanner;

public class CircleTest {
	public static void main(String[] args) {
		SimpleCircle myCircle = new SimpleCircle();
		Scanner sc = new Scanner(System.in);
		int n = sc.nextInt();
		myCircle.printAreas(n);
	}

}

class SimpleCircle {
	public void printAreas(int n) {
		int i = 0;
		Double s;
		for (i = 1; i <= n; i++) {
			s = i * i * Math.PI;
			System.out.println("Area is:" + String.format("%.2f", s));
		}
	}

}
```

##### 2.多个类的使用:

定义Dog类，包含double weight、int age等属性，void run()和void jump()方法；定义Cat类，包含double weight、int age等属性，void run()和void jump()方法；定义Bird类，包含double weight、int age等属性，void fly()和void jump()方法。为上述类提供setter和getter方法，默认构造方法和带参构造方法。
```java
public class DogCatBirdTest {

	  public    static    void    main(String[]    args)    { 
	      Dog  dog=new  Dog(12,5); 
	      Cat  cat=new  Cat(0, 0); 
	      cat.setAge(3); 
	      cat.setWeight(6); 
	      Bird bird=new Bird(1,2); 
	      dog.run(); 
	      cat.run(); 
	      cat.jump(); 
	      bird.fly(); 
	   } 

}
     class Dog extends DogCatBirdTest{
    	 public void run()
    	 {
    		 System.out.println("Dog run...");
    	 }
    	 public void jump() {
    		 System.out.println("Dog jump...");
    	 }
    	 Dog(double weight,int age) {
		}
     }
     class Cat extends DogCatBirdTest{
    	 double weight;
    	 int age;
    	 public void run()
    	 {
    		 System.out.println("Cat run...");
    	 }
    	 public void setWeight(double weight) {

		}
		public void setAge(int age) {
	
		}
		public void jump() {
			 System.out.println("Cat jump...");
		 }
		 Cat(double weight,int age) {
		}
	 }
	 class Bird extends DogCatBirdTest{
		 double weight;
		 int age;
		 public void run()
		 {
			 System.out.println("Bird run...");
		 }
		 public void fly() {
			 System.out.println("Bird fly...");
			
		}
		public void jump() {
			 System.out.println("Bird jump...");
		 }
		 Bird(double weight,int age) {
		}
	 }
```

### 6.

##### 1.PeopleStudentUniverStudent:
```java
public class PeopleTest {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Student zhangsan = new Student();
		zhangsan.age = 17;
		zhangsan.number = 100101;
		zhangsan.showPeopleMess();
		zhangsan.tellNumber();
		int x = 9, y = 29;
		System.out.print("add:");
		int result = zhangsan.add(x, y);
		System.out.printf("%d+%d=%d\n", x, y, result);
		UniverStudent lisi = new UniverStudent();
		lisi.age = 21;
		lisi.number = 6609;
		lisi.showPeopleMess();
		lisi.tellNumber();
		System.out.print("add:");
		result = lisi.add(x, y);
		System.out.printf("%d+%d=%d\t", x, y, result);
		System.out.print("multi:");
		result = lisi.multi(x, y);
		System.out.printf("%dX%d=%d\n", x, y, result);
	}
}

class People {
	int age, leg = 2, hand = 2;

	protected void showPeopleMess() {
		System.out.printf("age:%d,foot:%d,hand:%d\t", age, leg, hand);
	}
}

class Student extends People {
	int number;

	public void tellNumber() {
		System.out.printf("number:%d\t", number);
	}
	
	public int add(int x, int y) {
		return x + y;
	}
}

class UniverStudent extends People {
	int number;

	public void tellNumber() {
		System.out.printf("number:%d\t", number);
	}
	
	public int add(int x, int y) {
		return x + y;
	}
	
	public int multi(int x, int y) {
		return x * y;
	}
}
```

##### 2.AutoBus:

设计一个汽车类Auto，其中包含一个表示速度的double成员变量speed和表示启动的start方法、表示加速的speedUp方法表示停止的stop方法。再设计一个Auto的子类Bus表示公共汽车，在Bus类中定义一个int型成员变量passenger表示乘客数，gotOn和gotOff表示乘客上下车方法，编写一个BusTest测试Bus类的使用。
```java
class Auto {
	double speed;

	public void start() {

		System.out.println("The auto is started.");
	}

	public void speedUp(double speed) {
		this.speed = speed;
		System.out.println("The auto is speed up to" + speed + "kilo/h.");
	}

	public void stop() {
		System.out.println("The auto is stopped.");
	}
}

class Bus extends Auto {
	int passenger;

	public void gotOn(int num) {
		passenger = passenger + num;
		System.out.println("The person on bus is: " + passenger);
	}

	public void gotOff(int num) {
		passenger = passenger - num;
		System.out.println("The person on bus is: " + passenger);
	}
}

public class BusTest {
	public static void main(String[] args) {
		Bus bus = new Bus();
		bus.start();
		bus.speedUp(60);
		bus.stop();
		bus.gotOn(10);
		bus.gotOff(5);
	}
}
```

### 7.

##### 1.人员toString多态:

设计Person能够打印类名，Student是Person的子类，GraduateStudent是Student子类;

要求使用m方法实现如下输出

GraduateStudent

Student

Person
```java
public class DifferentPeopleToString {

	public static void main(String[] args) {
		m(new GraduateStudent());
		m(new Student());
		m(new Person());
	}

	public static void m(Object x) {
		System.out.println(x.toString());
	}

}

class Person {
	public String toString() {
		return getClass().getSimpleName();
	}

}

class Student extends Person {

}

class GraduateStudent extends Student {

}
```

##### 2.输出我喜欢喝的酒

派生类JNC、WLY继承于父类Wine，并且重写了父类的drink()、toString()方法，程序运行结果是通过m(wine)方法输出JNC、WLY的名称。
```java
class Wine {
	private String name;

	public String getName() {
		return name;
	}

	public void setName(String name) {
		this.name = name;
	}

	public Wine() {
	}

	public String drink() {
		return "My  wine  is:" + getName();
	}

	// 重写toString()
	public String toString() {
		return null;
	}
}

class JNC extends Wine {
	public JNC() {
		setName("JNC");
	}

	// 重写父类方法，实现多态
	public String drink() {
		return "My wine is:" + getName();
	}

	// 重写toString()
	public String toString() {
		return "Wine:" + getName();
	}
}

class WLY extends Wine {
	public WLY() {
		setName("WLY");
	}

	public String drink() {
		return "My wine is:" + getName();
	}

	public String toString() {
		return "Wine:" + getName();
	}
}

public class PolymorphicTest {
	public static void main(String[] args) {

		Wine[] wine = new Wine[2];
		wine[0] = new JNC();
		wine[1] = new WLY();
		m(wine);
	}

	private static void m(Wine[] wine) {
		for (int i = 0; i < 2; i++) {
			System.out.println(wine[i].toString() + "--" + wine[i].drink());
		}

	}

}
```

### 8.

##### 1.ShapeTriangle:

定义一个名为Triangle的三角形类，使其继承Shape抽象类，覆盖Shape类中抽象方法perimeter和area两个方法。
```java
public class ShapeTriangleTest {
	public static void main(String[] args) {

		Triangle t = new Triangle(3, 4, 5);
		System.out.println(t.area());
		System.out.println(t.perimeter());
	}

}

abstract class Shape {
	private String name;

	public Shape() {

	}

	public Shape(String name) {
		this.name = name;
	}

	public void setName(String name) {
		this.name = name;
	}

	public String getName() {
		return name;
	}

	public double perimeter() {
		return 0.0;
	}

	public double area() {
		return 0.0;
	}
}

class Triangle extends Shape {
	double a, b, c;

	public Triangle() {
		super();
		// TODO Auto-generated constructor stub
		this.a = 0;
		this.b = 0;
		this.c = 0;
	}

	public Triangle(String name) {
		super(name);
		// TODO Auto-generated constructor stub
	}

	public Triangle(double a, double b, double c) {
		super();
		this.a = a;
		this.b = b;
		this.c = c;
	}

	public double perimeter() {

		return a + b + c;
	}

	public double area() {

		return a * b / 2;
	}

}
```

##### 2.乐器抽象类的实现:

定义Instrument类包含抽象方法void play(String)和void adjust()，String what()

play表示乐器演奏，参数为需要演奏的曲目；

adjust表示乐器调音；

what表示什么乐器；

另有Wind、Percussion、Stringed是Instrument的子类；

WoodWind、Brass是Wind的子类；
```java

public class Music {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Instrument[] orchestra = { new Wind(), new Percussion(), new Stringed(), new Brass(), new WoodWind() };
		tuneAll(orchestra);
	}

	static void tune(Instrument i) {
		i.play("Savage  gradon");
	}

	static void tuneAll(Instrument[] e) {
		for (Instrument i : e) {
			tune(i);
		}
	}
}

abstract class Instrument {
	public void play(String name) {

	}

	public void adjust() {

	}

	public String what() {
		return null;
	}
}

class Wind extends Instrument {
	public void play(String name) {
		System.out.println("Wind" + "	  " + name);
	}

	public void adjust() {
		System.out.println("Wind调音");
	}

	public String what() {
		System.out.println("Wind");
		return null;
	}

}

class Percussion extends Instrument {
	public void play(String name) {
		System.out.println("Percussion" + "	  " + name);
	}

	public void adjust() {
		System.out.println("Percussion调音");
	}

	public String what() {
		System.out.println("Percussion");
		return null;
	}

}

class Stringed extends Instrument {
	public void play(String name) {
		System.out.println("Stringed" + "	  " + name);
	}

	public void adjust() {
		System.out.println("Stringed调音");
	}

	public String what() {
		System.out.println("Stringed");
		return null;
	}
}

class Brass extends Wind {
	public void play(String name) {
		System.out.println("Brass" + "	  " + name);
	}

	public void adjust() {
		System.out.println("Brass调音");
	}

	public String what() {
		System.out.println("Brass");
		return null;
	}
}

class WoodWind extends Wind {
	public void play(String name) {
		System.out.println("WoodWind" + "	  " + name);
	}

	public void adjust() {
		System.out.println("WoodWind调音");
	}

	public String what() {
		System.out.println("WoodWind");
		return null;
	}
}
```

### 9.

##### 1.选择自己喜欢的播放方式:

定义Soundable接口，包含increaseVolume( ) 、decreaseVolume( ) 、stopSound( ) 、 playSound( )四个方法。定义Radio、Walkman、Mobilephone类，实现Soundable接口。定义People类，在类中定义listen方法，采用多态形式调用playSound( ) 方法，其方法头定义如下：public void listen(Soundable s)。What do you want? 0--Radio, 1--Walkman, 2—Mobilephone 输入数字，输出选择结果。

```java
package interfaceexperiment;

public interface Soundable {
	public void increaseVolume();

	public void decreaseVolume();

	public void stopSound();

	public void playSound();
}
```
```java
package interfaceexperiment;

import java.util.Scanner;

class People {
	public void listen(Soundable s) {
		s.playSound();
	}

}

class Radio implements Soundable {
	public void increaseVolume() {
		System.out.println("Increase Radio Volume");
	}

	public void decreaseVolume() {
		System.out.println("Decrease Radio Volume");
	}

	public void stopSound() {
		System.out.println("Stop Radio Sound");
	}

	public void playSound() {
		System.out.println("Play Radio Sound");
	}
}

class Walkman implements Soundable {
	public void increaseVolume() {
		System.out.println("Increase Walkman Volume");
	}

	public void decreaseVolume() {
		System.out.println("Decrease Walkman Volume");
	}

	public void stopSound() {
		System.out.println("Stop Walkman Sound");
	}

	public void playSound() {
		System.out.println("Play Walkman Sound");
	}
}

class Mobilephone implements Soundable {
	public void increaseVolume() {
		System.out.println("Increase Mobilephone Volume");
	}

	public void decreaseVolume() {
		System.out.println("Decrease Mobilephone Volume");
	}

	public void stopSound() {
		System.out.println("Stop Mobilephone Sound");
	}

	public void playSound() {
		System.out.println("Play Mobilephone Sound");
	}
}

public class InterfaceTest {
	public static void main(String[] args) {
		int i;
		People man = new People();
		Scanner sc = new Scanner(System.in);
		Soundable[] soundDevice = new Soundable[3];
		soundDevice[0] = new Radio();
		soundDevice[1] = new Walkman();
		soundDevice[2] = new Mobilephone();
		i = sc.nextInt();
		man.listen(soundDevice[i]);
		soundDevice[i].increaseVolume();
		soundDevice[i].stopSound();
	}
}
```

##### 2.选择合适的交通工具:

接口Transport定义travel() 和stop()两个抽象方法，Car、Ship、Plane分别为其实现类。Interfacetest为主类。你想驾驶什么?：0-小汽车 1-轮船 2-飞机。输入数字，输出选择结果。
```java
package interfaceexperiment;

public interface Transport {
    public void travel() ;
    public void stop();
}
```
```java
package interfaceexperiment;

import java.util.Scanner;

class Car implements Transport {
	public void travel() {
		System.out.println("Car is driving");
	}

	public void stop() {
		System.out.println("Car is stopping");
	}

}

class Ship implements Transport {
	public void travel() {
		System.out.println("Ship is driving");
	}

	public void stop() {
		System.out.println("Ship is stopping");
	}

}

class Plane implements Transport {
	public void travel() {
		System.out.println("Plane is Flying");
	}

	public void stop() {
		System.out.println("Plan is stopping");
	}
}

public class Interfacetest1 {
	public static void main(String[] args) {
		int i;
		Scanner sc = new Scanner(System.in);
		Transport[] soundDevice = new Transport[3];
		soundDevice[0] = new Car();
		soundDevice[1] = new Ship();
		soundDevice[2] = new Plane();
		i = sc.nextInt();
		soundDevice[i].travel();
		soundDevice[i].stop();
	}
}
```

### 10.

##### 1.InputMismatchException:

编写程序，要求从键盘输入半径，计算并输出圆面积；

测试，当输入数据不是数值类型数据则处理InputMismatchException异常。
```java
package exception;

import java.util.Scanner;

public class CircleArea {

	public static void main(String[] args) {
		System.out.print("Input a radius:");
		double r;
		Scanner s = new Scanner(System.in);

		try {
			r = Double.parseDouble(s.next());

			System.out.printf("area=%.2f", Math.PI * r * r);

		} catch (Exception e) {
			System.out.println("java.util.InputMismatchException");
			System.out.println("Number Format Error.");
		}
	}
}
```

##### 2.自定义异常类:

自定义一个异常类MyException，重写toString()方法。在主类ExceptionDemo中定义efun(int r)方法，声明MyException类型的异常。在efun()方法调用时捕获r值为负值时的异常。并在finally块中输出：Exception is processed。
```java
package exception;

import java.util.Scanner;

public class ExceptionDemo {
	public static void efun(int r) throws MyException {
		System.out.println("radius is: " + r);

	}

	public static void main(String args[]) {
		Scanner in = new Scanner(System.in);
		int r = in.nextInt();
		MyException.r = r;
		try {
			if (r < 0)
				throw new MyException();
			else
				efun(r);

		} catch (MyException e) {
			e.toString();
		} finally {
			System.out.println("Exception is processed");
		}

	}

}

class MyException extends Exception {
	static int r;

	@Override
	public String toString() {
		System.out.println("MyException:" + r);
		return null;
	}
}
```

##### 3. 声明、抛出和捕获异常。改写Circle类中的setRadius 方法:

演示声明、抛出和捕获异常。改写Circle类中的setRadius 方法，当输入半径大于0时，输出圆的面积，保留2位小数，当半径小于0时捕获异常并输出。
```java
package exception;

import java.util.*;

public class TestCircleWithException {
	public static void main(String[] args) {
		Scanner in = new Scanner(System.in);
		int radius = in.nextInt();
		try {
			CircleWithException circle = new CircleWithException(radius);
			System.out.printf("The area of the circle is:%.2f", circle.findArea());
		} catch (Exception e) {
			// TODO: handle exception
			System.out.println("java.lang.IllegalArgumentException: Radius cannot be negative");
		}
	}
}

class CircleWithException {
	private double radius;

	public CircleWithException(double newRadius) {
		setRadius(newRadius);
	}

	public double getRadius() {
		return radius;
	}

	public void setRadius(double newRadius) throws IllegalArgumentException {

		if (newRadius < 0) {
			throw new IllegalArgumentException();
		} else {
			radius = newRadius;
		}
	}

	public double findArea() {
		return radius * radius * 3.14159;
	}
}
```

### 11.

##### 1.操作日志开发:

开发一个操作日志，需要记录操作人员所有输入信息到oplog.txt文件中，输入#时结束。
```java
package file;

import java.io.*;

import java.util.Scanner;

public class oplog1 {
	public static void main(String[] args) {
		int b;
		File file = new File("oplog.txt");

		byte bytes[] = new byte[512];
		try {
			b = System.in.read(bytes);
			for (int i = 0; i < bytes.length; i++) {
				if (bytes[i] == '#')
					b = i;
			}
			FileOutputStream fos = new FileOutputStream(file);
			OutputStreamWriter osw = new OutputStreamWriter(fos);
			fos.write(bytes, 0, b);

			fos.close();
			osw.close();
		} catch (IOException e) {
			e.printStackTrace();
		}

	}
}
```

##### 2.读文件并显示内容:

从指定文件读取其中的所有内容，并在控制台进行显示。
文件名：readtxt.txt                                  文件存储在程序路径上
```java
package file;

import java.io.*;

public class Readfile {
	public static void main(String[] args) {

		File file = new File("readtxt.txt");
		try {
			byte bytes[] = new byte[512];
			FileInputStream fis = new FileInputStream(file);
			int rs = 0;
			while ((rs = fis.read(bytes, 0, 512)) > 0) {
				String s = new String(bytes, 0, rs);
				System.out.println(s);
			}
		} catch (IOException e) {
			e.printStackTrace();
		}

	}
}
```

### 12.

##### 1.利用LinkedHashSet实现集合元素的顺序输入输出:

利用LinkedHashSet实现集合元素的顺序输入输出。
```java
package aggregate;

import java.util.Iterator;
import java.util.LinkedHashSet;
import java.util.Scanner;

public class Distinct {
	public static void main(String[] args) {
		LinkedHashSet list = new LinkedHashSet();
		Scanner sc = new Scanner(System.in);

		String line = sc.nextLine();
		String[] str = line.split("[ //,]");
		for (String c : str) {
			list.add(c);
		}
		Iterator it = list.iterator();
		System.out.println(list);

	}
}
```

##### 2.利用Vector输出n以内的所有素数:

输入一个整数n，利用Vector输出n以内的所有素数。
```java
package aggregate;

import java.util.Scanner;
import java.util.Vector;

public class Primenum {
	public static void main(String[] args) {
		Vector vec = new Vector();
		Scanner sc = new Scanner(System.in);
		int n = sc.nextInt();
		for (int i = 2; i < n; i++) {
			boolean flag = false;
			for (int j = 2; j < i; j++) {
				if (i % j == 0) {
					flag = true;
					break;
				}
			}
			if (flag == false)
				vec.add(i);

		}
		System.out.println(vec);
	}

}
```

##### 3.集合求并交差:

创建两个HashSet规则集，用户输入若干姓名作为元素，求它们的并、差和交

 \* 输入的用户名用逗号分隔

 \* 注意观察元素输出时的次序

 \* 并排序输出
```java
package aggregate;

import java.util.HashSet;
import java.util.Scanner;
import java.util.Set;
import java.util.TreeSet;

public class Name {
	public static void main(String[] args) {
		Set<String> name1 = new HashSet<String>();
		Set<String> name2 = new HashSet<String>();
		Scanner sc = new Scanner(System.in);

		String line1 = sc.nextLine();
		String[] str1 = line1.split(",");
		for (String c : str1) {
			name1.add(c);
		}

		TreeSet<String> name11 = new TreeSet<String>(name1);
		System.out.println("enter names(separated by , ):your enter:" + name11);

		String line2 = sc.nextLine();
		String[] str2 = line2.split(",");
		for (String c : str2) {
			name2.add(c);
		}

		TreeSet<String> name22 = new TreeSet<String>(name2);
		System.out.println("enter names(separated by , ):your enter:" + name22);

		Set<String> intersection = new HashSet<String>();
		Set<String> sum = new HashSet<String>();
		Set<String> supplementary = new HashSet<String>();

		intersection.addAll(name11);
		intersection.retainAll(name22);
		TreeSet<String> intersection1 = new TreeSet<String>(intersection);
		System.out.println("and:" + intersection1);

		sum.addAll(name11);
		sum.addAll(name22);
		TreeSet<String> sum1 = new TreeSet<String>(sum);
		System.out.println("or:" + sum1);

		supplementary.addAll(sum);
		supplementary.removeAll(intersection);
		TreeSet<String> supplementary1 = new TreeSet<String>(supplementary);
		System.out.println("diff:" + supplementary1);

	}
}
```

### 13.

##### 1.计算PI:

编写程序，计算n=10000,20000,...,100000时pi的值。求pi的近视值公式如下：

pi=4*（1-1/3+1/5-1/7+1/9-1/11+1/13+...+1/(2n-1)-1/(2n+1))
```java
package task;

public class One {
	public static void main(String[] args) {
		double PI = 0;
		double a;

		for (int i = 10000; i <= 100000; i = i + 10000) {
			PI = 0;
			for (double j = 0; j < i; j++) {
				a = Math.pow(-1, j);
				PI = PI + (1 / (2 * j + 1) * a);

			}
			System.out.println("n=" + i);
			System.out.println("PI=" + PI * 4);

		}

	}
```

##### 2.利用DataOutputStream实现双精度值或字符串的输入:

利用DataOutputStream实现双精度值或字符串的输入，并保存到dat中。利用DataInputStream从dat读取数据，并输出。
```java
package task;

import java.io.DataInputStream;
import java.io.DataOutputStream;
import java.io.FileInputStream;
import java.io.FileOutputStream;
import java.io.IOException;
import java.util.Scanner;

public class Two {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		String file = sc.nextLine();

		try {
			DataOutputStream dos = new DataOutputStream(new FileOutputStream(file));
			dos.writeChars(sc.nextLine());
			double b = sc.nextDouble();
			dos.writeDouble(b);
			dos.close();

			DataInputStream dis = new DataInputStream(new FileInputStream(file));

			char[] c = new char[100];

			int i = 0;
			while (dis.available() > 0) {

				c[i] = dis.readChar();
				i++;
			}

			System.out.print(new String(c));
			double a = 0.0;
			while ((a = dis.readDouble()) != -1) {

				System.out.print(a);
			}

			dis.close();
		} catch (IOException e) {

		}

	}
}
```

##### 3.利用FileWriter和FileReader实现文本数据的读写:

利用FileWriter和FileReader实现文本数据的读写。读入一个后缀为txt的文件名，以覆盖的形式往该文件中写入“Hello world.”关闭该文件后再打开，读出数据并输出。
```java
package task;

import java.io.BufferedReader;
import java.io.FileReader;
import java.io.FileWriter;
import java.util.Scanner;

public class Three {
	public static void main(String[] args) throws Exception {
		Scanner sc = new Scanner(System.in);
		String file = sc.nextLine();
		FileWriter f1 = new FileWriter(file);
		String source = "Hello world.";
		char[] str = source.toCharArray();
		for (int i = 0; i < str.length; i++) {

			f1.write(str[i]);

		}
		f1.close();

		FileReader fr = new FileReader(file);

		BufferedReader br = new BufferedReader(fr);

		String s;

		while ((s = br.readLine()) != null) {

			System.out.print(s);

		}

		fr.close();

	}
}
```

##### 4.定义Rose类并测试使用:

定义Rose类，该类包含color和placeOfOrigin属性，并提供String info(msg)方法。要求提供getter、setter方法；所有的参数来自于命令行参数。
```java
package task;

import java.util.Scanner;

public class Four {
	public static void main(String[] args) {
//		Scanner sc=new Scanner(System.in);
		Rose rose = new Rose();
		rose.setColor(args[0]);
		rose.setPlaceOfOrigin(args[1]);
		System.out.println(rose.info(args[2]));

	}
}

class Rose {
	static String color;
	static String placeOfOrigin;

	public static String getColor() {
		return color;
	}

	public void setColor(String color) {
		Rose.color = color;
	}

	public static String getPlaceOfOrigin() {
		return placeOfOrigin;
	}

	public void setPlaceOfOrigin(String placeOfOrigin) {
		Rose.placeOfOrigin = placeOfOrigin;
	}

	public String info(String msg) {
		return "The " + color + " rose which come from " + placeOfOrigin + " is " + msg + ".";
	}

}
```

##### 5.最小公倍数和最大公约数:

从键盘输入两个整数，计算着两个数的最小公倍数和最大公约数并输出。
```java
package task;

import java.util.Scanner;

public class One {
	public static void main(String[] args) {
		Scanner in = new Scanner(System.in);
		System.out.print("x:");
		int a = in.nextInt();
		System.out.print("y:");

		int b = in.nextInt();
		int i = 0;

		int gcd = 0;
		while (true) {
			i++;
			if (a % i == 0 && b % i == 0) {
				gcd = i;
			}
			if (i > a || i > b)
				break;
		}
		System.out.println("gcd=" + gcd);
		while (true) {
			i++;
			if (i % a == 0 && i % b == 0 && i >= a && i >= b) {
				System.out.println("lcm=" + i);
				i = 0;
				break;
			}
		}

	}
}
```
