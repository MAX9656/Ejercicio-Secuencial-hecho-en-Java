# Ejercicio-Secuencial-hecho-en-Java
Este ejercicio estaba hecho en pseudocódigo y ahora lo pase a Java
package ejerciciosecuencial;

import java.util.Scanner;
public class EjercicioSecuencial {

    /*
     )_ En un hospital existen 3 áreas: Urgencias, Pediatría y Traumatología. El presupuesto anual del hospital se reparte de la siguiente manera:
     * urgencias 37%
     * pediatría 42%
     * traumatología 21%
     */
    public static void main(String[] args) {
      int pres;  
      int urgencias;
      int pediatría;
      int traumatología;
     Scanner presupuesto = new Scanner (System.in);
     System.out.println("Presupuesto anual");
     pres = presupuesto.nextInt();
     { urgencias = pres*037;
     pediatría =pres*042;
     traumatología=pres*021;
    }
     
     System.out.println("Imprimir presupuesto para urgencias es de;" +urgencias);
     System.out.println("Imprimir presupuesto para pediatría es de; " + pediatría);
     System.out.println("Imprimir presupuesto para traumatología" + traumatología);
     
    }

}

     
 
    
