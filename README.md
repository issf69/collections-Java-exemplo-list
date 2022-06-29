# collections-Java-exemplo-list
Collections Java ExemploList exercício 1
## // Dada uma lista com 7 notas de um aluno [7, 8.5, 9.3, 5, 7, 0, 3.6], faça:

//      List notas = new ArrayList(); //antes do java 5
//      ArrayList<Double> notas = new ArrayList<>();
//      List<Double> notas = new ArrayList<>(Arrays.asList(7d, 8.5, 9.3, 5d, 7d, 0d, 3.6));
        /*List<Double> notas = Arrays.asList(7d, 8.5, 9.3, 5d, 7d, 0d, 3.6);
        notas.add(10d);
        System.out.println(notas);*/
        /*List<Double> notas = List.of(7d, 8.5, 9.3, 5d, 7d, 0d, 3.6);
        notas.add(1d);
        notas.remove(5d);
        System.out.println(notas);*/

        System.out.println("Crie uma lista e adicione as sete notas: ");

        List<Double> notas = new ArrayList<Double>(); //Generics(jdk 5) - Diamond Operator(jdk 7)
        notas.add(7.0);
        notas.add(8.5);
        notas.add(9.3);
        notas.add(5.0);
        notas.add(7.0);
        notas.add(0.0);
        notas.add(3.6);
        System.out.println(notas.toString());
         
        ### C:\Users\Irene\.jdks\openjdk-18.0.1.1\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.1.1\lib\idea_rt.jar=59300:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.1.1\bin" -Dfile.encoding=UTF-8 -classpath "C:\Users\Irene\Documents\ExercicioList Collections Java\exemploList\out\production\exemploList;C:\Users\Irene\.m2\repository\org\jetbrains\kotlin\kotlin-stdlib-jdk8\1.6.10\kotlin-stdlib-jdk8-1.6.10.jar;C:\Users\Irene\.m2\repository\org\jetbrains\kotlin\kotlin-stdlib\1.6.10\kotlin-stdlib-1.6.10.jar;C:\Users\Irene\.m2\repository\org\jetbrains\annotations\13.0\annotations-13.0.jar;C:\Users\Irene\.m2\repository\org\jetbrains\kotlin\kotlin-stdlib-common\1.6.10\kotlin-stdlib-common-1.6.10.jar;C:\Users\Irene\.m2\repository\org\jetbrains\kotlin\kotlin-stdlib-jdk7\1.6.10\kotlin-stdlib-jdk7-1.6.10.jar" yrene.com.br.ExemploList
Crie uma lista e adicione as sete notas: 
[7.0, 8.5, 9.3, 5.0, 7.0, 0.0, 3.6]

Process finished with exit code 0
