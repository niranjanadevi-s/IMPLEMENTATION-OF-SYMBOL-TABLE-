~~~
 Ex-2 IMPLEMENTATION-OF-SYMBOL-TABLE

 AIM :
To write a C program to implement a symbol table.

 ALGORITHM
1.	Start the program.
2.	Get the input from the user with the terminating symbol ‘$’.
3.	Allocate memory for the variable by dynamic memory allocation function.
4.	If the next character of the symbol is an operator then only the memory is allocated.
5.	While reading, the input symbol is inserted into symbol table along with its memory address.
6.	Stop the program. 
 PROGRAM

#include<stdio.h>
#include<conio.h> 
#include<ctype.h> 
#include<math.h>
void main()
{
int i=0,j=0,x=0,n,flag=0; void *p,*add[5];
char ch,srch,b[15],d[15],c; 
printf("Enter the Expression terminated by $: ");
while((c=getchar())!='$')
{
b[i]=c; i++;
}
n=i-1;
printf("\n Symbol Table\n"); printf("Symbol\taddr\ttype"); while(j<=n)
p=malloc(c); add[x]=p;
d[x]=c;
}
else
{
ch=b[j+1];
if(ch=='+'||ch=='-'||ch=='*'||ch=="=")
{
p=malloc(c); add[x]=p;
d[x]=c; printf("\n%c\t%d\tidentifier\n",c,p); x++;
}}} j++;
}
printf("\n The symbol is to be searched"); srch=getch();
for(i=0;i<=x;i++)
}
if(flag==0)
printf("\nSymbol Not Found"); 
getch();
}
~~~
# OUTPUT
![image](https://github.com/niranjanadevi-s/IMPLEMENTATION-OF-SYMBOL-TABLE-/assets/141748873/e17255d9-fa72-4439-8082-7549b7f6a27f)

# RESULT
The program to implement a symbol table is executed and the output is verified.
