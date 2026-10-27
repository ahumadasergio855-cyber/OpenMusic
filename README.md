# OpenMusic
## 1. Fundamentos del sistema
Este software se encarga de transformar las notas musicales de canciones, obras musicales/teatrales o ritmos de instrumentales a ondas ultrafi nas adaptadas al oído de personas con discapacidad auditiva o en periodo de casi pérdida de la audición.
Además de ello el sistema de sonido que sea a través de una API de Autotune y voice.

## 2. Análisis y especificación de requisitiso
Información sobre la especificación de requisitos acordada entre los clientes y el equipo.
Añade aquí todo lo que hemos ido haciendo sobre los requisitos.

Requisitos funcionales: 
Transformación de ondas ultra finas con un modificador de ondas vocales a través del mismo método que utiliza Autotune para poder modificar las ondas vocales de los cantantes para obtener los decibelios que desea el usuario.

Utilidad tanto para voces humanas como música con letra e instrumentales.
Dedicado a las personas con un porcentaje de discapacidad auditiva .
## 3. Diseño
Analiza las ondas sonoras de la instrumental musical. 
1. Análisis de las ondas sonoroas.
2. Modificación del sonido a sonidos bajos ultra finos.
3. Exportación de formato a mp3 para el usuario.
4. Testeo de las ondas sonoras adecuadas para el usuario.
5. Play del sonido modificado y adaptado para escuchar.

## 4. Implementación
public class Hola {
public static void main(String[] args) {
System.out.println("Hola mundo");
if (true) {
System.out.println("Condición verdadera");
} else {
System.out.print("Condición falsa");
}


/**
* clase Area
* contiene información de las variables del área
*/
public class Area {
public static void main(String[] args) {
/**
* variable del radio
*/
double r = 5;
/**
* variable del valor Pi
*/
double Pi = 3.14159 ;
/**
* Variable del area
*/
/**
* método para calcular el valor del área
*/
double area = Pi*r*r;
System.out.println("el area es"+area);
}

}

/*
* Metodo de calculo de operaciones matematicas
*/
public class OperacionesMatematicas {
public static int SumarNumeros(int NumeroUno, int NumeroDos)
{
return NumeroUno+NumeroDos;
}
/*
* Metodo para calculo de la resta
*/
public static int RESTAR(int A, int B)
{
return A-B;
}
/*
* Metodo para calculo para multiplicas
*/
public static int multiplicacion(int NUM1,int num2)
{
return NUM1*num2;
}
/*
* Metodo para calcular divisiones enteras
*/
public static int DivisionDeEnteros(int dividendo, int divisor)
{
return dividendo/divisor;
}
public static void main(String[] args){
System.out.println(SumarNumeros(3,4));
System.out.println(RESTAR(5,2));
System.out.println(multiplicacion(2,6));
System.out.println(DivisionDeEnteros(8,2));
}
}

## 5. Plan de pruebas del sistema
Añade aquí lo que hicimos para diseñar las pruebas

### 5.1. Pruebas de aceptación
Nada por aquí 

## 7. Los diccionarios de datos

No hagas nada por aquí
