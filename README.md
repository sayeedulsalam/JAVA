# JAVA
// Program to reverse a String using recursion
public class ReverseString {

	public static void main(String[] args) {
	ReverseString strReverse = new ReverseString();
		String s1 = "Nipun";
		System.out.println("Reverse of " + s1 + " is " + strReverse.reverse(s1));
		
			public static String reverse(String str){
		if((str == null)||(str.length()<=1)){
			return str;
		}else {
			return reverse(str.substring(1)) + str.charAt(0);
		}
	}
