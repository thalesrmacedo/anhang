public class Main
{
	public static void main(String[] args) {
	    Cachorro bicho1 = new Cachorro();
	    Gato bicho2 = new Gato();
	    bicho1.fazersom();
	    bicho2.fazersom();
	}
}
--------------------------------
class Animal {
    private String nome;
    
    public Animal(String nome){
        this.nome = nome;
    }
    
    public String getNome(){
        return nome;
    }
    
    public void setNome(String nome){
        this.nome = nome;
    }
  -----------------------------
  class Cachorro extends Animal{
    void fazersom() {
        System.out.println("Au Au");
    }
}
---------------------------------
class Gato extends Animal{
    void fazersom() {
        System.out.println("Miau");
    }
}
