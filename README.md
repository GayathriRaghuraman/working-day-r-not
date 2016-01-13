# working-day-r-not
include<stdio.h>
include<string.h>
int main()
{
char a[8],b[8]="sunday",d[8];
int c,i;
for( i=0;i<8;i++)
{
scanf("%s",a);
strcpy(d,a);
}
if(strcmp(a,d) == 1)
printf("hoilday");
else 
printf("working day");
return 0;    
}
