using System;


public class Program_4 {
    public static void Main() {
        Console.WriteLine("Enter The Principal Amount");
        double prinAmt = double.Parse(Console.ReadLine());


        Console.WriteLine("Enter The Rate");
        double rate = double.Parse(Console.ReadLine());


        Console.WriteLine("Enter The Year");
        int year = int.Parse(Console.ReadLine());


        double amt = prinAmt;
        for (int i = 0; i < year; i++) {
            amt += amt * (rate / 100);
        }
        double compIntr = amt - prinAmt;


        Console.WriteLine("The Compound Interest is: " + compIntr);
    }
}
