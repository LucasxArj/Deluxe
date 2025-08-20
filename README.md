public class TestaMaiorEMenor {
    public static void main(string [] args) {

        carrinhoDeCompras carrinho = new CarrinhoDeCompras ();
        carrinho.adicional(new Produto("geladeira", 450.0));
        carrinho.adicional(new Produto("Liquidificador", 250.0));
        carrinho.adicional(new Produto("Jogo de pratos", 70.0));

        MaiorEMenor algoritmo = new MaiorEMenor();
        algoritmo.encontrar(carrinho);

        System.out.Println("0 menor produto: "+ algoritmo.getMenor().getNome());
        System.out.Println("0 maior produto: "+ algoritmo.getMaior().getNome());
    }
}
   }
    }
}       
