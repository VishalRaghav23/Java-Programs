# Java-Programs

//Using String
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

// Without String

 for(int i = 1; i<10; i++){
            int o =10;
            int y = o - i; 
            for(int j = 0; j < i; j++){
                
                System.out.print(y);
                y++;
            }
            System.out.print(0);
            
            for(int j = 0; j < i; j++){
                o--;
                System.out.print(o);
            }
            System.out.println();
        }
