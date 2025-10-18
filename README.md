# webquest-programa-o-atual
#public class TesteVeiculo {
    public static void main(String[] args) {
        Veiculo v = new Veiculo();
        v.setPlaca("ABC-1234");
        v.setMarca("Toyota");
        v.setModelo("Corolla");
        v.setAno(2020);
        v.setValor(90000);

       public class Veiculo {
    // Atributos privados (características do veículo)
    private String placa;
    private String marca;
    private String modelo;
    private int ano;
    private double valor;

    // Métodos Getters e Setters - para acessar e modificar os atributos
    public String getPlaca() {
        return placa;
    }

    public void setPlaca(String placa) {
        this.placa = placa;
    }

    public String getMarca() {
        return marca;
    }

    public void setMarca(String marca) {
        this.marca = marca;
    }

    public String getModelo() {
        return modelo;
    }

    public void setModelo(String modelo) {
        this.modelo = modelo;
    }

    public int getAno() {
        return ano;
    }

    public void setAno(int ano) {
        this.ano = ano;
    }

    public double getValor() {
        return valor;
    }

    public void setValor(double valor) {
        this.valor = valor;
    }

    // Método para calcular o IPVA (4% do valor do veículo)
    public double calcularIpva() {
        return valor * 0.04;
    }
}
