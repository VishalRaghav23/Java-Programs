# Java-Programs
# Using String

public class Main
{
    public static void main(String[] args) {
        String rev="",  org ="";
            for(int j = 9; j >= 1; j--){
                org = org + j;
                rev = j + rev;
                System.out.println(rev + 0 + org );
            }
    }
}
