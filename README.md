Clase principal
public class Vehiculo{
public static void main(String[] args){

System.out.println(" ");
System.out.println("           Datos del Vehiculo");
String marca="Honda";
System.out.println("Marca: "+marca);
int noSerie=2546;
System.out.println("Numero de serie: "+noSerie);

caracteristicas carac =new caracteristicas();
carac.color();
carac.modelo();

otrasCaracteristicas otrasCarac =new 

otrasCaracteristicas();
otrasCarac.tapizado();
otrasCarac.transmision();
}
}
 
 
 Clase 1
 
 class caracteristicas{
public void color(){
System.out.println("Color: Rojo");
}

public void modelo(){
System.out.println("modelo: 2000");
}

}


Clase 2

class otrasCaracteristicas{
public void tapizado(){
System.out.println("Tapizado de cuero");
}

public void transmision(){
System.out.println("Transmision: Mecanico");
}

}
