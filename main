import java.util.Scanner;
import java.util.ArrayList;
import java.util.List;
public class U5E5 {
    public static void main(String[] args) {
       Scanner sn=new Scanner(System.in);
       U5E5 obj=new U5E5();
      
        List <Integer>numeros=new ArrayList<Integer>();
        for (int i = 0; i < 5; i++) {
            System.out.println("Dame los elementos a ordenar:");
            int elemento=sn.nextInt();
            numeros.add(elemento);
        }         
        System.out.println("ista ordenada:");
       obj.sellsort(numeros);        
         for(int j=0;j<numeros.size();j++){
          System.out.print(numeros.get(j)+" ");
      }
    }//main
    public  void sellsort(List <Integer>numeros){
        int division = numeros.size()/2, aux,salto, i;
        for(salto=division; salto!=0; salto/=2){
            boolean cambio=true;
            while(cambio){
                cambio=false;
                for(i=salto; i<numeros.size(); i++){
                    if (numeros.get(i-salto)>numeros.get(i)){
                        aux=numeros.get(i);
                        numeros.set(i,numeros.get(i-salto));
                        numeros.set(i-salto,aux);
                        cambio=true;
                    }
                }
            }
        }
    }
    }//class

//zamora esparza yezier cruz
