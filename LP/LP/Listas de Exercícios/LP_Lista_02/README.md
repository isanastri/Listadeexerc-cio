![senai_logo](https://transparencia.sp.senai.br/Content/img/logo-senai.png)

# Lista de Exercícios 02: variáveis e operadores lógicos/aritméticos 

Profº.: Cainã Antunes Silva  
Faculdade de Tecnologia **SENAI Sorocaba**  
Tecnólogo em Análise e Desenvolvimento de Sistemas (ADS)
___


> O objetivo desta aula é dominar a manipulação de variáveis e operadores lógicos e aritméticos exercitando o raciocínio lógico para a criação de algoritmos.  

Variáveis em linguagens de programação são espaços na memória que armazenam valores que podem ser manipulados durante a execução do programa, permitindo a criação de algoritmos dinâmicos e flexíveis. Operadores aritméticos, como soma (+), subtração (-), multiplicação (*) e divisão (/), realizam cálculos matemáticos essenciais para o processamento de dados. Já os operadores lógicos, como AND, OR e NOT, possibilitam a tomada de decisões ao avaliar expressões booleanas, controlando o fluxo do programa. A combinação desses elementos é fundamental para a construção de algoritmos eficientes e funcionais.

Para mais informações acesse [Aula 03: Fluxogramas.](https://cainaantunes.notion.site/Aula-03-Vari-veis-189bde521b3b8092a2dfdfef9190b15e?pvs=4)

***

1. Ler um número inteiro e exibir o seu dobro.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int number, result;

        System.out.println("Digite um numero: ");

        Scanner in = new Scanner(System.in); //Configura o Scanner
        number = in.nextInt();

        result = number * 2;
        System.out.println("O dobro de " + number + " é " + result);
    }
}

2. Ler um número inteiro e exibir o seu quadrado.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int number, square;

        System.out.println("Digite um número inteiro: ");

        Scanner in = new Scanner(System.in); // Configura o Scanner
        number = in.nextInt();

        square = number * number; // Calcula o quadrado
        System.out.println("O quadrado de " + number + " é " + square);
    }
}

3. Ler um número real e exibir a quinta parte deste número.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double numero, quintaParte;

        System.out.println("Digite um número real: ");

        Scanner in = new Scanner(System.in);
        numero = in.nextDouble();

        quintaParte = numero / 5;
        System.out.println("A quinta parte de " + numero + " é " + quintaParte);
    }
}

4. Ler duas notas N1 e N2 e exibir a média.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double nota1, nota2, media;

        Scanner in = new Scanner(System.in);

        System.out.println("Digite a primeira nota (N1): ");
        nota1 = in.nextDouble();

        System.out.println("Digite a segunda nota (N2): ");
        nota2 = in.nextDouble();

        media = (nota1 + nota2) / 2;
        System.out.println("A média das notas é: " + media);
    }
}

5. Ler uma velocidade em $Km/h$ e converter para $m/s$.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double velocidadeKmH, velocidadeMs;

        Scanner in = new Scanner(System.in);

        System.out.println("Digite a velocidade em Km/h: ");
        velocidadeKmH = in.nextDouble();

        velocidadeMs = velocidadeKmH / 3.6;
        System.out.println("A velocidade em m/s é: " + velocidadeMs);
    }
}

6. Ler uma velocidade em $m/s$ e converter para $km/h$.
import java.util.Scanner;
public class Main{
      public static void main(String[] args){
            double velocidadeMs, velocidadeKmH;

            Scanner in = new Scanner(System.in);

            System.out.println("Digite a velocidade em m/s: ");
            velocidadeMs = in.nextDouble();

            velocidadeKmH = velocidadeMs * 3.6;
            System.out.println("A velocidade em Km/h é: " + velocidadeKmH);
      }
}

7. Ler uma medida em milímetro e converter para polegadas.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double milimetros, polegadas;

        Scanner in = new Scanner(System.in);

        System.out.println("Digite a medida em milímetros: ");
        milimetros = in.nextDouble();

        polegadas = milimetros / 25.4;
        System.out.println("A medida em polegadas é: " + polegadas);
    }
}

8. Ler uma medida em polegadas e converter para milímetros.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double polegadas, milimetros;

        Scanner in = new Scanner(System.in);

        System.out.println("Digite a medida em polegadas: ");
        polegadas = in.nextDouble();

        milimetros = polegadas * 25.4;
        System.out.println("A medida em milímetros é: " + milimetros);
    }
}

 9.Ler uma medida de distância em quilômetros e converter 
para milhas.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double km, miles;

        System.out.println("Digite uma medida em quilômetros: ");

        Scanner in = new Scanner(System.in);
        km = in.nextDouble();

        miles = km * 0.621371; // Conversão para milhas
        System.out.println(km + " km equivale a " + miles + " milhas.");
    }
}

10. Ler uma medida de distância em milhas e converter para quilômetros.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double miles, km;

        System.out.println("Digite uma medida em milhas: ");

        Scanner in = new Scanner(System.in);
        miles = in.nextDouble();

        km = miles / 0.621371; // Conversão para quilômetros
        System.out.println(miles + " milhas equivale a " + km + " km.");
    }
}


11. Entrar com o valor de temperatura em graus Celsius e exibir a temperaturacorrespondente em graus Fahrenheit.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double celsius, fahrenheit;

        System.out.println("Digite a temperatura em graus Celsius: ");

        Scanner in = new Scanner(System.in);
        celsius = in.nextDouble();

        fahrenheit = (celsius * 9/5) + 32; // Conversão para Fahrenheit
        System.out.println(celsius + " °C equivale a " + fahrenheit + " °F.");
    }
}
 12. Ler duas notas N1 e N2 e exibir a média. 

      >Obs.: N1 tem peso 1 e N2 tem peso 2 e resultadodeve estar entre 0 e 10.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double n1, n2, media;

        System.out.println("Digite a nota N1: ");
        Scanner in = new Scanner(System.in);
        n1 = in.nextDouble();

        System.out.println("Digite a nota N2: ");
        n2 = in.nextDouble();

        media = (n1 * 1 + n2 * 2) / 3; // Média ponderada
        if (media >= 0 && media <= 10) {
            System.out.println("A média ponderada é: " + media);
        } else {
            System.out.println("Notas inválidas. A média deve estar entre 0 e 10.");
        }
    }
}

13. Receber o raio e um círculo e calcular sua área.
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        double radius, area;

        System.out.println("Digite o raio do círculo: ");

        Scanner in = new Scanner(System.in);
        radius = in.nextDouble();

        area = Math.PI * Math.pow(radius, 2);
        System.out.println("A área do círculo é: " + area);
    }
}

14. Receber a base e a altura de um triângulo retângulo e calcular sua área.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double base, height, area;

        System.out.println("Digite a base do triângulo: ");
        Scanner in = new Scanner(System.in);
        base = in.nextDouble();

        System.out.println("Digite a altura do triângulo: ");
        height = in.nextDouble();

        area = (base * height) / 2;
        System.out.println("A área do triângulo é: " + area);
    }
}
15. Receber o raio e a altura de um cilindro e calcular seu volume.
import java.util.Scanner;
public class   Main {
    public static void main(String[] args) {
        double radius, height, volume;

        System.out.println("Digite o raio do cilindro: ");
        Scanner in = new Scanner(System.in);
        radius = in.nextDouble();

        System.out.println("Digite a altura do cilindro: ");
        height = in.nextDouble();

        volume = Math.PI * Math.pow(radius, 2) * height;
        System.out.println("O volume do cilindro é: " + volume);
    }
}


16. Receber o raio e a altura de um cone e calcular seu volume.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double radius, height, volume;

        System.out.println("Digite o raio do cone: ");
        Scanner in = new Scanner(System.in);
        radius = in.nextDouble();

        System.out.println("Digite a altura do cone: ");
        height = in.nextDouble();

        volume = (Math.PI * Math.pow(radius, 2) * height) / 3;
        System.out.println("O volume do cone é: " + volume);
    }
}


17. Receber velocidade inicial, aceleração e tempo de percurso de um corpo e calcular sua velocidade.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double initialVelocity, acceleration, time, finalVelocity;

        System.out.println("Digite a velocidade inicial (m/s): ");
        Scanner in = new Scanner(System.in);
        initialVelocity = in.nextDouble();

        System.out.println("Digite a aceleração (m/s²): ");
        acceleration = in.nextDouble();

        System.out.println("Digite o tempo de percurso (s): ");
        time = in.nextDouble();

        finalVelocity = initialVelocity + (acceleration * time);
        System.out.println("A velocidade final é: " + finalVelocity + " m/s");
    }
}

18. Receber os coeficientes $a$ e $b$ de uma equação do primeiro grau e imprimir a solução.

      >Equação do primeiro grau: $ax + b = 0$
      import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double a, b, solution;

        System.out.println("Digite o coeficiente a: ");
        Scanner in = new Scanner(System.in);
        a = in.nextDouble();

        if (a == 0) {
            System.out.println("Esta não é uma equação válida.");
        } else {
            System.out.println("Digite o coeficiente b: ");
            b = in.nextDouble();

            solution = -b / a;
            System.out.println("A solução da equação " + a + "x + " + b + " = 0 é: x = " + solution);
        }
    }
}

19. Receber os coeficientes $a$, $b$ e $c$ de uma equação do segundo grau e imprimir a solução.

      >Equação do segundo grau: $ax^2 + bx + c = 0$
      import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double a, b, c, delta, root1, root2;

        Scanner in = new Scanner(System.in);

        System.out.println("Digite o coeficiente a: ");
        a = in.nextDouble();
        System.out.println("Digite o coeficiente b: ");
        b = in.nextDouble();
        System.out.println("Digite o coeficiente c: ");
        c = in.nextDouble();

        // Calcula o discriminante (delta)
        delta = Math.pow(b, 2) - 4 * a * c;

        if (delta < 0) {
            System.out.println("A equação não possui raízes reais.");
        } else {
            root1 = (-b + Math.sqrt(delta)) / (2 * a);
            root2 = (-b - Math.sqrt(delta)) / (2 * a);

            System.out.println("As raízes da equação são: ");
            System.out.println("Raiz 1: " + root1);
            System.out.println("Raiz 2: " + root2);
        }
    }
}

20. Descobrir uma equação do segundo grau a partir de suas raízes:

      >Exemplo: <br>
      $x1 = 1$ e $x2 = 2$ <br>
      Então: <br>
      $(x -1) . (x -2)$ <br>
      Logo: <br>
      $x2 -3x -2 = 0$ <br>
      import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double x1, x2, a, b, c;

        Scanner in = new Scanner(System.in);

        System.out.println("Digite a primeira raiz (x1): ");
        x1 = in.nextDouble();
        System.out.println("Digite a segunda raiz (x2): ");
        x2 = in.nextDouble();

        // Considerando a = 1 para simplificar
        a = 1;
        b = -(x1 + x2); // Coeficiente b
        c = x1 * x2;    // Coeficiente c

        System.out.println("A equação do segundo grau é: ");
        System.out.println(a + "x^2 + (" + b + ")x + (" + c + ") = 0");
    }
}