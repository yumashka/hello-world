# Java example 

```java
import java.io.*;
import java.util.Scanner;

public class Solution
{
    public static void main(String[] args)   throws Exception
    {
        InputStream in = System.in;
        Reader rd = new InputStreamReader(in);
        BufferedReader buff = new BufferedReader(rd);

        String s = buff.readLine();
        int a = Integer.parseInt(s);

        System.out.println("Я буду зарабатывать $" + a +" в час");
    }
}

```

# C example

```c
#include <stdio.h>

int main (void)
{
  puts ("Hello, World!");
  return 0;
}
```

# Python example
```python
# Solve the quadratic equation ax**2 + bx + c = 0
# Coeffients a, b and c are provided by the user

# import complex math module
import cmath

a = float(input('Enter a: '))
b = float(input('Enter b: '))
c = float(input('Enter c: '))

# calculate the discriminant
d = (b**2) - (4*a*c)

# find two solutions
sol1 = (-b-cmath.sqrt(d))/(2*a)
sol2 = (-b+cmath.sqrt(d))/(2*a)

print('The solution are {0} and {1}'.format(sol1,sol2))
```

