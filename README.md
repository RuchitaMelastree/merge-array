# merge-array

import java.util.*;  
public class MergeArrayExample1  
{  
public static void main(String[] args)   
{  
int[] firstArray = {100,200,300,400};        
int[] secondArray = {10,20,30,40};   
int fir = firstArray.length;          
int sec = secondArray.length;  
int[] result = new int[fir + sec];  
System.arraycopy(firstArray, 0, result, 0, fir);  
System.arraycopy(secondArray, 0, result, fir, sec);  
System.out.println(Arrays.toString(result));     
}  
}
