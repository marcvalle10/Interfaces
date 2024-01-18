// Definición de la interfaz
interface OperacionesMatematicas {
    int suma(int a, int b);
    int resta(int a, int b);
    int multiplicacion(int a, int b);
    int division(int a, int b);
}

// Implementación de la interfaz
class Calculadora implements OperacionesMatematicas {
    @Override
    public int suma(int a, int b) {
        return a + b;
    }

    @Override
    public int resta(int a, int b) {
        return a - b;
    }

    @Override
    public int multiplicacion(int a, int b) {
        return a * b;
    }

    @Override
    public int division(int a, int b) {
        if (b != 0) {
            return a / b;
        } else {
            System.out.println("No es posible dividir entre cero.");
            return 0; // Puedes manejar esto de acuerdo a tus necesidades
        }
    }
}

public class Main {
    public static void main(String[] args) {
        // Crear una instancia de la implementación
        Calculadora calculadora = new Calculadora();

        // Ejemplos de uso de los métodos
        System.out.println("Suma: " + calculadora.suma(5, 3));
        System.out.println("Resta: " + calculadora.resta(8, 2));
        System.out.println("Multiplicación: " + calculadora.multiplicacion(4, 6));
        System.out.println("División: " + calculadora.division(10, 2));
    }
}
