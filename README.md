# .-java-2
package com;

import java.util.Scanner;

class Problem3 {
public static void main(String[] args) {
	Scanner scan=new Scanner(System.in);
	int a=scan.nextInt();
	if(a%2==0){
		for(int i=1;i<=(a-1)*2;i++){
			if(i%2==1){
				System.out.print(i+" ");
			}
		}
	}
	else{
		for(int i=1;i<=a*2;i++){
			if(i%2==1){
				System.out.print(i+" ");
			}
		}
	}
}
}
