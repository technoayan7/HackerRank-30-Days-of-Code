//Complete this code or write your own from scratch
import java.util.*;
import java.io.*;

class Solution{
    public static void main(String []argh){
        Scanner in = new Scanner(System.in);
        int n = in.nextInt();
        Map<String, Integer> tempPhoneBook = new HashMap<>();
        for(int i = 0; i < n; i++){
            String name = in.next();
            int phone = in.nextInt();
            // Write code here
            tempPhoneBook.put(name, phone);
            
        }
        while(in.hasNext()){
            String s = in.next();
            // Write code here
            if(tempPhoneBook.containsKey(s))
            {
                System.out.println(s +"=" + tempPhoneBook.get(s) );
            }
            else
            {
                System.out.println("Not found");
            }
        }
        in.close();
    }
}
