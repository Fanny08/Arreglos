//Arreglo unidimensional
  public class InicArreglo  {
 public static void main( String args[] ){ 
     int arreglo[]= {32,27,64,18,95,70,14,90,70,60,37};// crea el arreglo
        System.out.printf( "%s%8s\n", "Indice", "Valor" );
          for ( int contador = 1; contador < arreglo.length; contador++ )
               System.out.printf( "%5d%8d\n", contador, arreglo[ contador ] );             
 }   
}    
