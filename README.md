## PROYECTO 1 COMPARTIDO
pau silvestre y ferran rebollar y mario mincu

El programa que ha pedidio gerard chavales :

        import java.util.Scanner;

        public class Main { 
        public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int opcion = 0;

        System.out.println("--- MENÚ ---");
        System.out.println("1. Insultar");
        System.out.println("2. Agradecer");
        System.out.println("3. Salir");

        while (opcion != 3) {
            System.out.print("Elige una opción: ");
            opcion = scanner.nextInt();

            switch (opcion) {
                case 1:
                    System.out.println("Bujarraaaa");
                    break;
                case 2:
                    System.out.println("Gracias chaval");
                    break;
                case 3:
                    System.out.println("Saliendo del programa");
                    break;
                default:
                    System.out.println("Opción no válida");
            }
        }
    }
    }
