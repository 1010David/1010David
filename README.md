public class Welcome {

    public static void main(String[] args) {
        System.out.println("👋 ¡Hola! Soy [Tu Nombre]");

        DeveloperBackendJunior desarrollador = new DeveloperBackendJunior(
            "Transición de carrera",
            "Formación técnica en desarrollo de software",
            "Estudiante en Oracle Next Education (ONE) con Alura"
        );

        desarrollador.mostrarHabilidades();
        desarrollador.mostrarMetasYValores();
        desarrollador.mostrarObjetivoProfesional();
        desarrollador.conectate();
    }
}

class DeveloperBackendJunior {

    private String transicionCarrera;
    private String formacion;
    private String estudiosActuales;

    public DeveloperBackendJunior(String transicionCarrera, String formacion, String estudiosActuales) {
        this.transicionCarrera = transicionCarrera;
        this.formacion = formacion;
        this.estudiosActuales = estudiosActuales;
    }

    public void mostrarHabilidades() {
        System.out.println("\n🚀 Habilidades y Tecnologías:");
        System.out.println("{");
        System.out.println("  Backend: Java, Spring Boot;");
        System.out.println("  BasesDeDatos: MySQL, PostgreSQL;");
        System.out.println("  Herramientas: Git, GitHub, IntelliJ IDEA;");
        System.out.println("  OtrosConocimientos: APIs REST, JSON, principios SOLID;");
        System.out.println("}");
    }

    public void mostrarMetasYValores() {
        System.out.println("\n🎯 Metas y Valores:");
        System.out.println("{");
        System.out.println("  Contribuir a proyectos de desarrollo backend que generen impacto;");
        System.out.println("  Aplicar habilidades en entornos colaborativos y de aprendizaje continuo;");
        System.out.println("  Desarrollarme profesionalmente aportando al éxito del equipo y de la empresa;");
        System.out.println("}");
    }

    public void mostrarObjetivoProfesional() {
        System.out.println("\n💼 Objetivo profesional:");
        System.out.println("{");
        System.out.println("  Buscar una posición como desarrollador backend junior;");
        System.out.println("  Aplicar conocimientos y crecer junto a un equipo experimentado;");
        System.out.println("  Aportar al desarrollo de soluciones innovadoras;");
        System.out.println("}");
    }

    public void conectate() {
        System.out.println("\n📫 ¡Conéctate conmigo!");
        System.out.println("LinkedIn: https://linkedin.com/in/david-beltrán-java/];");
        System.out.println("Email: [j.david.beltran.m@gmail.com];");
    }
}
