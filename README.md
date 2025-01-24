class Calculadora {
    public int somar(int a, int b) {
        return a + b;
    }

    public double somar(double a, double b) {
        return a + b;
    }
}

public class TesteSobrecarga {
    public static void main(String[] args) {
        Calculadora calc = new Calculadora();
        System.out.println("Soma de inteiros: " + calc.somar(5, 10));
        System.out.println("Soma de doubles: " + calc.somar(5.5, 10.5));
    }
}
