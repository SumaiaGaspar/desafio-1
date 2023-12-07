# desafio-1
Desafio projetando classes
package modelo;

public class Cliente {
    private String cpf;
    private String nome;
    private String endereco;
    private String telefone;
    private String email;

    // Construtor
    public Cliente(String cpf, String nome, String endereco, String telefone, String email) {
        this.cpf = cpf;
        this.nome = nome;
        this.endereco = endereco;
        this.telefone = telefone;
        this.email = email;
    }

    // Getters e Setters (métodos para acessar e modificar os atributos)
    // ...

    // Outros métodos, se necessário
    // ...
}



public class Veiculo {
    private String placa;
    private String modelo;
    private int ano;
    private String fabricante;
    private String cor;

    // Construtor
    public Veiculo(String placa, String modelo, int ano, String fabricante, String cor) {
        this.placa = placa;
        this.modelo = modelo;
        this.ano = ano;
        this.fabricante = fabricante;
        this.cor = cor;
    }

    // Getters e Setters
    // ...

    // Outros métodos, se necessário
    // ...
}

package controle;
import modelo.Cliente;
import modelo.Veiculo;

public class Principal {
    public static void main(String[] args) {
        // Exemplo de uso das classes Cliente e Veiculo
        Cliente cliente1 = new Cliente("123.456.789-00", "Fulano", "Rua A, 123", "123456789", "fulano@email.com");
        Veiculo veiculo1 = new Veiculo("ABC1234", "Sedan", 2022, "MarcaX", "Azul");

        // Aqui você pode adicionar mais lógica conforme necessário para atender aos requisitos do projeto

        // Exemplo de impressão para verificar o funcionamento
        System.out.println("Cliente: " + cliente1.getNome() + ", Veículo: " + veiculo1.getModelo());
    }
}


