# Assignment1.2
// Online Java Compiler

import java.util.HashMap;
import java.util.Map;

public class pascal2{

private static Map<Integer, Integer> mem= new HashMap<>();

public static void main(String[] args){

int a=10;

for(int i=1;i<n;i++){ 
    for(int j=1;j<=1;j++){

System.out.print(pas (i,j)+" ");

} 
System.out.println();
    
}

static int pas(int a, int b){

if (b==1 || a==b ){

return 1;
}

if(mem.containsKey((a*10+b))){
    return mem.get((a*10+b));
    
}

int result=pas(a-1,b-1)+pas (a-1,b); 
men.put((a*10+b), result);
return result;
}
}


















