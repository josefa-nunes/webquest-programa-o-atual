# webquest-programa-o-atual
public class TesteVeiculo {
    public static void main(String[] args) {
        Veiculo v = new Veiculo();
        v.setPlaca("ABC-1234");
        v.setMarca("Toyota");
        v.setModelo("Corolla");
        v.setAno(2020);
        v.setValor(90000);

        System.out.println("Marca: " + v.getMarca());
        System.out.println("Modelo: " + v.getModelo());
        System.out.println("Ano: " + v.getAno());
        System.out.println("Valor: R$" + v.getValor());
        System.out.println("IPVA: R$" + v.calcularIpva());
    }
}
