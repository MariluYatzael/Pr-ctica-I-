# Pr-ctica-I-
# Pr-ctica-I-
public interface Coleccion<T> {
    void insertar(T elemento);
    void eliminar(T elemento);
    T acceder(int posicion);
    boolean buscar(T elemento);
   
    // Devuelve el número total de elementos en la colección.
    int contarElementos();
   
    // Verifica si la colección está vacía.
    boolean estaVacia();
}
En esta definición, "T° representa el tipo genérico que será utilizado para los elementos de la colección. Cada método tiene los parámetros requeridos para llevar a cabo la operación correspondiente. Recuerda que esta es solo la definición de la interfaz; las clases que implementen esta interfaz deberán proporcionar la implementación concreta de estos métodos según el tipo de colección que estén utilizando.

Estos dos métodos adicionales agregados a la interfaz proporcionan funcionalidades comunes en muchas estructuras de datos:

contarElementos(): Este método devuelve la cantidad total de elementos presentes en la colección. Es útil para conocer la dimensión de la colección sin tener que acceder a cada elemento individualmente.

estaVacia(): Este método verifica si la colección está vacía, es decir, si no contiene ningún elemento. Ayuda a determinar si se requiere un procesamiento especial cuando la colección no tiene elementos.

Estos métodos complementan las operaciones básicas definidas en la interfaz y pueden ser implementados en las clases concretas que implementen la interfaz "Coleccion".

