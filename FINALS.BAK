#include <stdlib.h>
#include <stdio.h>
#include <ctype.h>

int main()
{
 int choice_int;
 clrscr();
 printf("Main menu\n\n");

 printf("[1] Display hello world\n");
 printf("[2] Arithmetic operators\n");
 printf("[3] Decision making statements\n");
 printf("[4] Loops\n");
 printf("[5] Arrays\n");
 printf("[0] Exit\n\n");

 printf("\nInput: ");
 scanf("%d",&choice_int);

 while(choice_int != 1 && choice_int != 2 && choice_int != 3 && choice_int != 4 && choice_int != 5 && choice_int != 0)
 {
  printf("Invalid input! try again");
  fflush(stdin);
  printf("\nInput: ");
  scanf("%d",&choice_int);
 }

 switch (choice_int)
 {
  case 1:
  submenu1();
  break;

  case 2:
  submenu2();
  break;

  case 3:
  submenu3();
  break;

  case 4:
  submenu4();
  break;

  case 5:
  submenu5();
  break;

  case 0:
  return 0;
 }

 return 0;
}

submenu1()
{
 char choice_char;
 clrscr();
 printf("This code prints hello world using printf statement.\n\n");
 printf("Hello world!");

 printf("\n\nPress any key to return to main menu: ");
 getch();
 main();
 return 0;
}

submenu2()
{
int con,mod;
char choice_char;
float n1,n2;
clrscr();


printf("Choose an OPERATOR");
printf("\n\n[1] Addition");
printf("\n[2] Subtraction");
printf("\n[3] Multiplication");
printf("\n[4] Division");
printf("\n[5] Modulos");
printf("\n[0] Return");
printf("\n\nInput: ");
scanf("%d",&con);


 while(con != 1 && con !=2 && con != 3 && con !=4 && con != 5 && con != 0)
 {
  printf("Invalid input! try again");
  fflush(stdin);
  printf("\nInput: ");
  scanf("%d",&con);
 }


 if(con == 0)
 {
  main();
  return 0;
 }


clrscr();

if(con == 1){
 printf("Addition\n\n");
}
else if(con == 2){
 printf("Subtraction \n\n");
}
else if(con == 3){
 printf("Multiplication\n\n");
}
else if(con == 4){
 printf("Division\n\n");
}
else if(con == 5){
 printf("Modulos\n\n");
}


printf("Enter first number: ");
scanf("%f",&n1);
printf("Enter second number: ");
scanf("%f",&n2);


 if(con == 1){
   printf("\nSum = %.2f",n1 + n2);
  }
  else if(con == 2){
   printf("\nDifference = %.2f",n1 - n2);
  }
  else if(con == 3){
   printf("\nProduct = %.2f",n1 * n2);
  }
 else if(con == 4){
   float quot = n1 / n2;
   printf("\nQuotient = %.2f", quot);
  }
  else if(con == 5){
   mod = (int) n1 % (int) n2;
   printf("\nModulo = %d",mod);
  }



printf("\n\nReturn to main menu? Yes[y], No[n]: ");
scanf("%s",&choice_char);

while(choice_char != 'y' && choice_char != 'n'&&choice_char!='Y'&&choice_char!='N'){
   printf("Invalid input! Try again: ");
   scanf("%s",&choice_char);
}

if(choice_char == 'y' || choice_char == 'Y'){
  main();
  return 0;
}
 else if(choice_char == 'n' || choice_char == 'N'){
  submenu2();
  return 0;
 }

return 0;
}


submenu3()
{
int con;
char choice_char;
clrscr();

printf("Decision Making Statements");

printf("\n\n[1] If ");
printf("\n[2] if-else");
printf("\n[3] if-else if-else");
printf("\n[4] Nested if");
printf("\n[5] Switch-case");
printf("\n[0] Return");

printf("\n\nInput: ");
scanf("%d",&con);

 while(con!=1&&con!=2&&con!=3&&con!=4&&con!=5&&con!=0)
 {
  printf("Invalid input! Try again: ");
  fflush(stdin);
  scanf("%d",&con);
 }


if(con == 0)
{
 main();
 return 0;
}

if(con == 1)
{
 int number;
 clrscr();
 printf("If Statement");

 printf("\n\nEnter a number: ");
 scanf("%d",&number);

 if(number > 0)
 {
  printf("you entered: %d",number);
 }
 printf("\nThe if statement is easy");
}


else if(con == 2)
{
int number;

clrscr();
printf("If-else Statement");

printf("\n\nEnter number: ");
scanf("%d",&number);

 if(number % 2 == 0)
 {
  printf("%d is an Even integer.",number);
 }
 else
 {
  printf("%d is an Odd integer.",number);
 }

}
else if(con == 3)
{
 int var1,var2;
 clrscr();
 printf("if-else if-else Statement");

 printf("\n\nEnter first number: ");
 scanf("%d",&var1);
 printf("\nEnter second number: ");
 scanf("%d",&var2);

 if(var1 != var2)
 {
  printf("%d is not equal to %d",var1,var2);
 }
 else if(var1 > var2)
 {
  printf("%d is greater than %d",var1,var2);
 }
 else if(var1 < var2)
 {
  printf("%d is less than %d",var1,var2);
 }
 else if(var1 == var2)
 {
  printf("%d is equal to %d",var1,var2);
 }

}

else if(con == 4)
{
 int var1,var2;
 clrscr();
 printf("nested if Statements");


 printf("\n\nEnter first number: ");
 scanf("%d",&var1);
 printf("\nEnter second number: ");
 scanf("%d",&var2);

 if(var1 >= var2)
 {
   if(var1 == var2)
   {
   printf("\n%d is equal to %d",var1,var2);
   }
   else
   {
    printf("\n%d is greater than %d",var1,var2);
   }
 }
 else
 {
  printf("\n%d is less than %d",var1,var2);
 }
}
else if(con == 5)
{
 int week;
 clrscr();
 printf("Switch-case statement");

 printf("\n\nEnter day number(1-7): ");
 scanf("%d",&week);

 while(week!=1&&week!=2&&week!=3&&week!=4&&week!=5&&week!=6&&week!=7)
 {
  printf("Invalid input! try again.");
  fflush(stdin);
  printf("\nInput: ");
  scanf("%d",&week);
 }

 switch(week)
 {
  case 1:
  printf("\nMonday");
  break;

  case 2:
  printf("\nTuesday");
  break;

  case 3:
  printf("\nWednesday");
  break;

  case 4:
  printf("\nThursday");
  break;

  case 5:
  printf("\nFriday");
  break;

  case 6:
  printf("\nSaturday");
  break;

  case 7:
  printf("\nSunday");
  break;
 }

}

 printf("\n\nReturn to main menu? Yes[y] No[n] ");
 scanf("%s",&choice_char);

 while(choice_char!='y'&&choice_char!='Y'&&choice_char!='n'&&choice_char!='N')
 {
 printf("Invalid input! try again: ");
 fflush(stdin);
 scanf("%s",&choice_char);
 }

 if(choice_char == 'y' || choice_char == 'Y')
 {
  main();
  return 0;
 }
 else if(choice_char == 'n' || choice_char == 'N')
 {
  submenu3();
  return 0;
 }


return 0;
}

submenu4(){
char choice_char;
int con;
clrscr();
 printf("Loops");
 printf("\n\n[1] For loop");
 printf("\n[2] While loop");
 printf("\n[3] do...while loop");
 printf("\n[0] Return");

 printf("\n\nInput: ");
 scanf("%d",&con);

 while(con!=1&&con!=2&&con!=3&&con!=0)
 {
  printf("Invalid input! Try again: ");
  fflush(stdin);
  scanf("%d",&con);
 }


 if(con == 1)
 {
 int a,b,m;
 clrscr();

 printf("For loop");
 printf("\nThis loop displays a multiplication table.");
 printf("\n\nEnter value: ");
 scanf("%d",&b);
  for(a = 1;a<=10;a++)
  {
   m = a * b;
   printf("\n%d x %d = %d",a,b,m);
  }
 }

 else if(con == 2)
 {
  int sum=0,num,n,i=0;
  clrscr();
  printf("while loop");
  printf("\nThis loop lets you enter an certain number of integers\nto add then display the total sum.\n\n");

  printf("Enter how many numbers you will input: ");
  scanf("%d",&n);

  while(i<n)
  {
  printf("Enter integer: ");
  scanf("%d",&num);

  sum = sum + num;
  i++;
  }

  printf("\nTotal: %d",sum);
 }
 else if(con == 3)
 {
  long i=1,f=1,n;
  clrscr();

  printf("Do...while loop");
  printf("\nThis code gives you the factorial of your inputted number.");

  printf("\n\nEnter value: ");
  scanf("%ld",&n);

  do
  {
  f = f * i;
  i++;
  }while(i<=n);

  printf("\n%ld! = %ld",n,f);

 }
 else if(con == 0)
 {
  main();
  return 0;
 }






printf("\n\nReturn to main menu? Yes[y] No[n] ");
scanf("%s",&choice_char);

while(choice_char!='y'&&choice_char!='Y'&&choice_char!='n'&&choice_char!='N')
 {
  printf("Invalid input! Try again: ");
  fflush(stdin);
  scanf("%s",&choice_char);
 }

 if(choice_char == 'y' || choice_char == 'Y'){
  main();
  return 0;
 }
 else if(choice_char == 'n' || choice_char == 'N'){
  submenu4();
  return 0;
 }

 return 0;
}





submenu5()
{
 char choice_char;
 int con;
 clrscr();

 printf("Arrays");
 printf("\n\n[1] Inputted array");
 printf("\n[2] Not inputted array");
 printf("\n[0] Return");

 printf("\n\nInput: ");
 scanf("%d",&con);

 while(con!=0&&con!=1&&con!=2)
 {
  printf("Invalid input! Try again: ");
  fflush(stdin);
  scanf("%d",&con);
 }

 if(con == 0)
 {
  main();
  return 0;
 }
 else if(con == 1){
   int arr[100],i,n,max,min;
   clrscr();

   printf("Inputted array size.");
   printf("\nThis code lets you input array size.\nit then finds the maximum and minimum number of that array.");

   printf("\n\nEnter array size: ");
   scanf("%d",&n);

   for(i = 0;i<n;i++)
   {
    printf("Enter number: ");
    scanf("%d",&arr[i]);
   }
 max = arr[0];
 min = arr[0];

  for(i=0;i<n;i++)
  {
   if(max < arr[i])
   {
    max = arr[i];
   }
   else
   {
    min = arr[i];
   }
  }

  printf("\nMax number: %d",max);
  printf("\nMin number: %d",min);
 }

 else if(con == 2)
 {
  int i,change,replace,arr[5] = {10,20,30,40,50};
  clrscr();
  printf("Not inputted array size.)");
  printf("Array values: ");
  for(i=0;i<5;i++)
  {
   printf("\n %d",arr[i]);
  }

  printf("\nInput value to change: ");
  scanf("%d",&change);

  printf("Input number to replace: ");
  scanf("%d",&replace);

  for(i=0;i<5;i++)
  {
   if(change == arr[i])
   {
    arr[i] = replace;
   }
  }

  printf("\nUpdated values: ");
  for(i=0;i<5;i++)
  {
   printf("\n%d",arr[i]);
  }
 }


printf("\n\nReturn to main menu? Yes[y] No[n] ");
scanf("%s",&con);

while(con!='y'&&con!='Y'&&con!='n'&&con!='N')
{
 printf("\n\nInvalid input! Try again: ");
 fflush(stdin);
 scanf("%s",&con);
}

if(con == 'y' || con == 'Y')
{
 main();
 return 0;
}
else if(con == 'n' || con == 'N')
{
 submenu5();
 return 0;
}


return 0;
}
