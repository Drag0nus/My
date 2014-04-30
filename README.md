My
==class Class {
    
    private int age;
    private int size;
    private int salary;
    
    private String name;
    private String surname;
    private String zodiak;
    private String favBand;
    
    
    public void setAge(int age){
        this.age = age;
    }
    public int getAge(){
        return age;
    }
     public void setSalary(int salary){
        this.salary = salary;
    }
    public int getSalary(){
        return salary;
    }
    public void setSize(int size){
        this.size = size;
    }
    public int getSize(){
        return size;
    }
    public void setName(String name){
        this.name = name;
    }
    public String getName(){
        return name;
    }
    public void setSurname(String surname){
        this.surname = surname;
    }
    public String getSurname(){
        return surname;
    }
    public void setZodiak(String zodiak) {
        this.zodiak = zodiak;
    }
    public String getZodiak() {
        return zodiak;
    }
    public void setFavBand(String favBand) {
        this.favBand = favBand;
    }
    public String getFavBand() {
        return favBand;
    }
}


public class JavaApp extends Class{

    public static void main(String[] args) {
        
        JavaApp human = new JavaApp();
        
        String name;
        String surname;
        String favBand;
        int age;
        
        human.setName("Pasha");
        human.setSurname("Rusin");
        name = human.getName();
        surname = human.getSurname();
        human.setAge(18);
        age = human.getAge();
        human.setFavBand("Metallica");
        favBand = human.getFavBand();
        
        System.out.println("My name is " + name + " " + surname + ". I'm " + age + ". My favourite band is " + favBand);
    }
}

