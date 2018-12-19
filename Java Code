import java.util.Scanner;

 public class SavingsAccountDemo {


        public static void main(String[] args) {

            int monthsPassed = 0;
            String demoAccount;

            Scanner userInput = new Scanner(System.in);

            // Get starting balance & create demoAccount object
            System.out.print("Please enter the starting balance: $");
            SavingsAccount.demoAccount;
            demoAccount = new SavingsAccount(userInput.nextDouble());

            // Gets annual interest rate
            System.out.printf("Enter the annual interest rate (decimal): ");
            demoAccount.setAnnualInterestRate(userInput.nextDouble());

            // Gets numbers of months that have passed since the establishment of the account
            System.out.print("Enter the number of months that have passed since the account\'s establishment: ");
            monthsPassed = userInput.nextInt();

            // Loops through all of the
            for (int count = 1; count <= monthsPassed; count++) {
                // Display month number
                System.out.println("\n-----MONTH " + count + "-----");

                // Gets amount deposited into account for the month
                System.out.printf("Enter the amount deposited into the account: $");
                demoAccount.deposit(userInput.nextDouble());


                // Gets amount withdrawn from the account for the month
                System.out.printf("Enter the amount withdrawn from the account: $");
                demoAccount.withdraw(userInput.nextDouble());

                // Displays and adds monthly interest
                System.out.printf("This month\'s interest is: $%.2f\n",
                        demoAccount.getMonthlyInterest());
                demoAccount.addMonthlyInterest();

                System.out.printf("\nEnding balance: $%.2f",
                        demoAccount.getBalance());
                System.out.printf("\nTotal deposits: $%.2f",
                        demoAccount.getAccumulativeDeposits());
                System.out.printf("\nTotal withdrawals: $%.2f",
                        demoAccount.getAccumulativeWithdrawals());
                System.out.printf("\nTotal interest: $%.2f",
                        demoAccount.getAccumulativeInterest());

            }
            userInput.close();


        }

    }
