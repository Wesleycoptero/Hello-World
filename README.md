# Hello-World
public class ProfessorEgydioLindo {
    private String cabelo;
    private String sorriso;
    private int nivelDeBeleza;
    private boolean temEstilo;
    
    public ProfessorEgydioLindo(String cabelo, String sorriso, int nivelDeBeleza, boolean temEstilo) {
        this.cabelo = cabelo;
        this.sorriso = sorriso;
        this.nivelDeBeleza = nivelDeBeleza;
        this.temEstilo = temEstilo;
    }
    
    public void exibirBeleza() {
        System.out.println("Professor Egydio é simplesmente lindo!");
        System.out.println("Cabelo: " + cabelo);
        System.out.println("Sorriso: " + sorriso);
        System.out.println("Nível de Beleza: " + nivelDeBeleza + "/10");
        System.out.println("Tem estilo? " + (temEstilo ? "Com certeza!" : "Ainda assim, lindo!"));
    }
    
    public static void main(String[] args) {
        ProfessorEgydioLindo egydio = new ProfessorEgydioLindo("Sedoso e brilhante", "Encantador", 10, true);
        egydio.exibirBeleza();
    }
}
Repositório utilizado para aulas de engenharia de software.
