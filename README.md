# Program-Exercise-1-A-B-Problem-
A+B Problem

时间限制：3000 ms  |  内存限制：65535 KB
难度：0

描述
    此题为练手用题，请大家计算一下a+b的值.

输入
    输入两个数，a,b
输出
    输出a+b的值
样例输入

    2 3

样例输出

    5

提示
    例如：
    C语言版：
    #include<stdio.h>
    int main()
    {
    int a,b;
    scanf("%d%d",&a,&b);
    printf("%d\n",a+b);
    }

    C++版：
    #include<iostream>
    using namespace std;
    int main()
    {
    int a,b;
    cin>>a>>b;
    cout<<a+b<<endl;
    }

    Java版：

    import java.io.*;
    import java.util.*;
    public class Main
    {
    public static void main(String args[]) throws Exception
    {
    Scanner cin=new Scanner(System.in);
    int a=cin.nextInt(),b=cin.nextInt();
    System.out.println(a+b);
    }
    }

    Java jdk 1.4 版
    import java.io.*;
    import java.util.*;

    public class Main
    {
    public static void main (String args[]) throws Exception
    {
    BufferedReader stdin =
    new BufferedReader(
    new InputStreamReader(System.in));

    String line = stdin.readLine();
    StringTokenizer st = new StringTokenizer(line);
    int a = Integer.parseInt(st.nextToken());
    int b = Integer.parseInt(st.nextToken());
    System.out.println(a+b);
    }
    }

    请注意不要输出过多提示性语句（如：“please input two numbers”），不然会WrongAnswer的
