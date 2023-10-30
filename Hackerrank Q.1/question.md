Certainly, here's a rephrased question that you can use in your GitHub README:

### Reading and Printing Integers from Standard Input to Standard Output

When solving HackerRank challenges, it's common to read input from stdin (standard input) and write output to stdout (standard output). In Java, one way to read from stdin is by using the Scanner class. For instance, you can create a Scanner object and read integers from System.in as shown below:

```java
Scanner scanner = new Scanner(System.in);
int myInt = scanner.nextInt();
scanner.close();

System.out.println(myInt);
```

The code above reads an integer from stdin and prints it to stdout. To practice this, we have a task for you.

**Task:**

In this challenge, your task is to read a series of integers from stdin and print each integer to stdout, one per line. To make it a bit easier, we've provided part of the code in the editor.

**Input Format:**

You will receive several lines of input, each containing a single integer.

**Sample Input:**

```
42
100
125
```

**Sample Output:**

```
42
100
125
```

Feel free to use and adapt this code as a starting point for your HackerRank challenges that require reading and printing integers.