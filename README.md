# CSharp-Arrays

---------Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

string[] sajeev = {"s", "a", "j", "e"};
Console.WriteLine(sajeev[1]);                                                   //output : a

string[] sassy = {"EEE", "CSE", "MECH", "CIVIL"};
Shinpilla[4] = "ECE"
Console.WriteLine(shinpilla[4]);                                                   //output: ECE       


string[] kits = {"A", "N", "N", "A"};
for (int i = 0; i < kits.Length; i++) 
{
  Console.WriteLine(kits[i]);                                                //output:A N N A
}



-------------There is also a foreach loop, which is used exclusively to loop through elements in an array:


string[] ECE = {"Sajeev", "Sesu", "Krish"};
foreach (string i in ECE) 
{
  Console.WriteLine(i);                                                           //output: Sajeev Sesu Krish
}

---------Sorting(sorts an array alphabetically or in an ascending order:)

string[] Gubul = {"Publicis", "Sapients", "Bangalore", "Salesforce"};        //output:  Publicis Sapients Bangalore Salesforce
Array.Sort(Gubul);
foreach (string i in Gubul) 
{
  Console.WriteLine(i); 
  }
  
  
------------------  Other useful array methods, such as Min, Max, and Sum, can be found in the System.Linq namespace:

using System;
using System.Linq;

-------------------
---
int[] myNumbers = {5, 1, 8, 9};
      Console.WriteLine(myNumbers.Max());  // 9
      Console.WriteLine(myNumbers.Min());  // 1
      Console.WriteLine(myNumbers.Sum()); //23











