# dharini1
#include<stdio.h>
int main()
{
char b;
scanf("%c",&b);
if((b>=67)&&(b<=90)||(b>=97)&&(b<=122))
{
if(b==65||b==97||b==69||b==101||b==73||b==105||b==97||b==111||b==85||b==117)
printf("Vowel");
else
printf("Consonant");
}
else
{
printf("Invalid");
}
return 0;
}
