# Switch-case-
Public class SWITCHCASE {
    Public static void main(String[] args) {
       char grade = 'E';
       switch (grade)
       {
           case 'A':
               System.out.println("Execellent");
               break;
           case 'B':
               System.out.println("Good Job");
               break;
           case 'C':
               System.out.println("You Passed");
               break;
           case 'D':
               System.out.println("Better luck next time)");
               break;
           case 'E':
               System.out.println("Well Done");
               break;
           default:
               System.out.println("Invalid Grade”);
       }
    }
}

OUTPUT:

Well Done
