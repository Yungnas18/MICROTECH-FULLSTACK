/* Part 1:Setup Variables*/
const studentName = "Jibril Nasiru Muhammed";
let weeklyAllowance = 4000;
let transportCost = 800;
let foodCost = 6000;
const airtimeCost = 500;

/* Part 2:Arithmetic Operators */
let totalExpenses = transportCost + foodCost + airtimeCost;
let remainingBalance = weeklyAllowance - totalExpenses;
let dailyFoodCost = foodCost / 7;
let monthlyAllowance = weeklyAllowance * 4;
let weeklyAllowanceRemainder = weeklyAllowance % 7;
let squareOfTransportCost = transportCost ** 2;

/* Part 3:Assignment Operators */
remainingBalance += 1000; //gift from a relative2
remainingBalance -=300; //sepnt on snack
weeklyAllowance *=2; //bonus week
remainingBalance /=2; //you share with a friend
let allowanceAfter1142Weeks = weeklyAllowance **= 2; /* Computes the Expected Allowance after approximately 1142 weeks which also 8000 days because the value of weekly allowance was updated just right above from 4000 to 8000*/
let monthlyAllowanceRemainder = monthlyAllowance %= 30; /* Remainder after monthly allowance is shared across daily expenses */

/* Part 4:Console Output*/
console.log(`Student name ${studentName}, Total Expenses:${totalExpenses}, Balance:${remainingBalance}`);
console.warn("Your balance is running low")
console.error("You have overspent")
console.log(allowanceAfter1142Weeks);

/*Part 5: Bonus Challenge*/

/* I noticed that the Balance became a negative number of -1300 */

