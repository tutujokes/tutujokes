public class Me {
    public String name = "Arthur Henrique";
    public String age = "22";
    public String skills = "Java Developer, SQL Database Management, Backend Developer";
    public String tech = "Linux, Git, Docker, Python, C, Java, SQL, PHP";
    public String extra = "x86_64 assembly, BrainFuck";
    
    private String secret = "Nothing Here...";

    public Me() {}

    public void sayHello() {
        System.out.println("Welcome to my profile!");
    }

    public static void main(String[] args) {
        Me arthur = new Me();
        arthur.sayHello();
    }
}
