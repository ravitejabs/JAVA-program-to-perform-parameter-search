# JAVA-program-to-perform-parameter-search
public class student {
    private String name;
    private int age;
    private String studentid;

    public student(String name, String studentid, int age) {
        this.name = name;
        this.studentid = studentid;
        this.age = age;
    }

    public void display() {
        System.out.println("name:" + name);
        System.out.println("id:" + studentid);
        System.out.println("age:" + age);
    }

    public static void main(String[] args) {
        student s1 = new student("s1", "21", 3);
        s1.display();
    }

}
