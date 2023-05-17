# Calculate
This project allows client code to access a library of math methods that calculate and return an integer. Each method involves algorithms used in coding simple math problems/operations.

Here is some sample code: 

# public static String foil(int a, int b, int c, int d, String n) {
		return ((a*c) + n+"^"+ 2 + " + " + (b*c+a*d) + n + " + " + b*d);
	}
 returns a string of equation (ax+b)(cx+d) turned into the quadratic equation ax^2+bx+c 
  
# public static String toImproperFrac(int who, int numer,int den) {
		return ((who*den)+ numer + "/" + den);
	}
returns a string of a fraction converted into a improper fraction. The whole number is multiplied by the denominator which is then added to numer. It is then formated to act as the numerator over the den(denominator).

# public static String toMixedNum(int numer1, int den1) {
		return (numer1 / den1 + "_" + (numer1%den1) + "/" + den1);
	}
//returns a string of a an improper faction into a mixed number. The int who is first calculated by finding how many times the denominator goes into the numerator. This number is then multiplied by the denominator which acts as the whole number. The leftover numerator is then subtracted by the whole number times the denominator. The denominator remains unchanged.

This project was created to develop my skils writing methods that perform complicated tasks that could otherwise be done with a simple calculator. In essence, I was tasked with creating my own calculator algorithms. 
