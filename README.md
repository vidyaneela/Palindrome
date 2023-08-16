# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step1: Start

Step2: Create a class and declare two variable with string datatype

Step3: Loop over the entire string and reverse it

Step4: Use if condition to check whether the string and the reversed string is equal or not

Step5: print palindrome if it's equal else print not a palindrome.

Step6: stop
## Program:
```
Name : Vidya Neela.M
Reg No : 212221230120
```

```
using System;
namespace palindrome
{
    class stringl
    {
        public static void Main(string[] args)
        {
            string str,rev="";
            int n;
            Console.WriteLine("Enter a String :");
            str=Console.ReadLine();
            n=str.Length - 1;
            for(int i=n;i>=0;i--)
            {
                rev=rev+str[i];
            }
            if(rev==str)

                Console.WriteLine("{0} is Palindrome",str);
            else
                Console.WriteLine("{0} is not Palindrome",str);

        }
    }
}
```

## Output:
![image](https://github.com/vidyaneela/Palindrome/assets/94169318/c03d65fb-c90d-4b13-8fa1-a08252ac0bde)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
