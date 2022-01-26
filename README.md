# Muliplication-using-Recursion

public static void main(String[] args) {
			Scanner cs=new Scanner(System.in);
			int num1, num2;
		    System.out.print("Enter the two Number:");
		    num1=cs.nextInt();
		    num2=cs.nextInt();
		    System.out.print("Multiplication of Two Number Using Recursion is: "+Multiplication(num1,num2));
	        cs.close();
		}

	}

static int  Multiply_by_recursion(int num1, int num2) 
    { 
  //Enter your code here
  if(N==0){
    return 0;
  }
  return M + Multiply_by_recursion(M, N-1);
    }
