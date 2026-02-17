# Cadastro-Login
Sistema simples de cadastro de login.


import java.util.Scanner;

public class CadastroDeLoginAula22 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Digite o seu nome: ");
        String nome = input.next();
        if (nome.equals("") || nome.equalsIgnoreCase("admin") || nome.equalsIgnoreCase("administrador")){
            System.out.println(" Usuário invalido");
        }else {
        System.out.println(nome + " Cadastrado com sucesso ");
        }
    }
}
