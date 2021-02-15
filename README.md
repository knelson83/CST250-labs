public class Arrays{
    
    public static void main(String[] args){
        
    String[] array1 = {"word1", "word2", "word3", "word4"};
    String[] array2 = array1;
    for (String element : array2){
    System.out.println(element);
        array1[0] = "_word1";
        array1[1] = "_word2";
        array1[2] = "_word3";
        array1[3] = "_word4";  
    for (String element : array1){
    System.out.println(element);
