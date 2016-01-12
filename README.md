# working-day-r-not
int main()
{
char a[8],b[8],d[8];
int c;
for(int i=0;i<8;i++)
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
