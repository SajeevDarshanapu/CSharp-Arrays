# CSharp-Arrays

---------Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

string[] shinpilla = {"Bakkama", "Gundama", "Petharamma", "Sakkanamma"};
Console.WriteLine(shinpilla[4]);                                                   //output : Sakkanamma

string[] shinpilla = {"Bakkama", "Gundama", "Petharamma", "Sakkanamma"};
Shinpilla[4] = "Panthulamma"
Console.WriteLine(shinpilla[4]);                                                   //output: Panthulamma        


string[] shinpilla = {"Bakkama", "Gundama", "Petharamma", "Sakkanamma"};
for (int i = 0; i < shinpilla.Length; i++) 
{
  Console.WriteLine(shinpilla[i]);                                                //output:Bakkama Gundama Petharamma Sakkanamma
}



-------------There is also a foreach loop, which is used exclusively to loop through elements in an array:


string[] shinpilla = {"Bakkama", "Gundama", "Petharamma", "Sakkanamma"};
foreach (string i in cars) 
{
  Console.WriteLine(i);                                                           //output: Bakkama Gundama Petharamma Sakkanamma
}

---------Sorting(sorts an array alphabetically or in an ascending order:)

string[] shinpilla = {"Bakkama", "Gundama", "Petharamma", "Sakkanamma"};        //output:  Bakkama Gundama Petharamma Sakkanamma
Array.Sort(shinpilla);
foreach (string i in cars) 
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











