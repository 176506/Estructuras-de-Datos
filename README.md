# Estructuras-de-Datos
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package poo;

/**
 *
 * @author Ale
 */
public class POO {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Rectangulo r = new Rectangulo(4,5);
    	System.out.println("\nArea: " + r.calculaArea());
    	System.out.println("\nArea: " + r.calculaPerimetro());
    	
    	ComplejoVacacional cv = new ComplejoVacacional("Complejo");
    	boolean resp = cv.altaAlberca(4,8);
    	if(resp)
        	System.out.println("Sí se pudo agregar la alberca.");
    	else
        	System.out.println("No se pudo agregar.");
    	cv.altaAlberca(2,3);
    	cv.altaAlberca(2, 2);
    	System.out.println("Los metros de lona requeridos para el Complejo Vacacional son: " + cv.calculaLona());
    	System.out.println("Los metros de cerca requeridos para el Complejo Vacacional son: " + cv.calculaCerca());
    	
    }
    
}
