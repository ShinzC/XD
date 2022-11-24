package copiar;

public class Copiar {

    public static void main(String[] args) {
       
        String str = "Hello, World_123!!";
        String charsToRemove = ",_!";
        
        for (char c : charsToRemove.toCharArray()) {
            str = str.replace(String.valueOf(c), "");
        }
        System.out.println(str);
    }
    
}
