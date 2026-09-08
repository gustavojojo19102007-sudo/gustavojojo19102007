import java.util.Scanner;
import java.util.ArrayList;
public class Execicio_10 {
    public static void main(String[]arg){
        Scanner scanner=new Scanner(System.in);
        ArrayList<String> nome=new ArrayList();
        nome.add("Paulo");
        nome.add("laura");
        nome.add("Gustavo");
        System.out.println("Gustavo\nlaura\nPaulo");
        System.out.println("Qual você que tira:");
        String personagem=scanner.nextLine();
        if(personagem.contains(personagem)){
            nome.remove(personagem);
        }else{
            System.out.println("Não encontrado");
        }
        System.out.println(nome);
    }
