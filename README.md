# Java-PR2-
//WAP to print highest and lowest number from an array

import java.util.*;
public class test
{
 public static void main(String[] args)
 {
  Scanner sc=new Scanner(System.in);
  int arr[]=new int[5];
  System.out.println("Enter elements to be entered in an array");
  int min=Integer.MAX_VALUE;
  int max=Integer.MIN_VALUE;
  for(int i=0;i<=4;i++)
  {
   arr[i]=sc.nextInt();
   if(arr[i]<min)
   {
    min=arr[i];
   }
   if(arr[i]>max)
   {
    max=arr[i];
   }
  }
  System.out.println("Highest element is "+max);
  System.out.println("Lowest element is "+min);
 }
} 

//WAP to find sum and average of numbers

import java.util.*;
public class Sum_Avg
{
 public static void main(String args[])
 {
  int i,n,sum=0;
  float average;
  Scanner sc=new Scanner(System.in);
  System.out.println("Enter no of element you want in array ");
  n=sc.nextInt();
  int a[]=new int[n];
  System.out.println("Enter all the elements ");
  for(i=0;i<n;i++)
  {
   a[i]=sc.nextInt();
   sum=sum+a[i];
  }
  System.out.println("Sum "+sum);
  average=(float)sum/n;
  System.out.println("Average "+average);
 }
}

//WAP to display even and odd number from given array

import java.util.*;
public class Even_Odd
{
 public static void main(String args[])
 {
  Scanner sc=new Scanner(System.in);
  int arr[]=new int[5];
  System.out.println("Enter the number to be entered in array ");
  System.out.println("Odd numbers are ");
  for(int i=0;i<arr.length;i++)
  {  
   if(arr[i]%2!=0)
   {
    System.out.println(arr[i]);
   }
  }
  System.out.println("Even numbers are ");
  for(int i=0;i<arr.length;i++)
  {
   if(arr[i]%2==0)
   {
    System.out.println(arr[i]);
   }
  }
 }
}
  
