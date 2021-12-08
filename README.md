# decubra-seu-IMC
package main;


import java.text.NumberFormat; 
import java.util.Locale;
import java.util.*;
import java.util.Scanner;
public class main {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
	  
		//Tendo como dados de entrada a altura de uma pessoa, construa um algoritmo que 
		//       calcule seu IMC, usando a seguinte fórmula: imc = peso / (altura * altura)
		//qual o problema? : converter peso e altura em imc.
		//como resolver? : criar um programa que receba em Altura e imprima peso ideal.
		//qual as variaveis de entrada? : altura
		//qual as variaveis de saida? : peso ideal
		//quais os passos a serem realizados? : pedi usuario <br> digitar qual sua altura, formula de conversão, imprimir para o usuario o resultado
		
		
		 Scanner scan = new Scanner(System.in);
		 
		   double  altura;
		   double  peso;
		   
		     
		   System.out.println("Digite sua Altura: ");
		   altura =scan.nextDouble();
		   
		   System.out.println("Digite seu Peso: "  );
		   peso =scan.nextDouble();
		   
		   double imc;
		   
		   imc = peso / (altura * altura);
		  
		   System.out.println("Seu IMC é: " +imc);
		   
		  
		   
		    		    
		 
	}

}
