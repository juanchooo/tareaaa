/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication32;

import java.util.ArrayList;
import java.util.Scanner;

/**
 *
 * @author Juan Andres
 */
public class JavaApplication32 {

    /**
     * @param args the command line arguments
     */
    ArrayList<String> articulos = new ArrayList<String>();
    public static void main(String[] args) {
        while (true){
            System.out.println("que desea hacer");
            System.out.println("1: vendedor - 2:comprador  -  3:observador");
            Scanner entradaEscaner = new Scanner (System.in);
            int entradaTeclado = entradaEscaner.nextInt ();
            if (entradaTeclado==1){
                System.out.println("nombre de producto: ");
                Scanner name = new Scanner (System.in); //Creación de un objeto Scanner
                String nombre = name.nextLine ();
                System.out.println("precio: ");
                int precio = name.nextInt ();
            }
        }
    }
