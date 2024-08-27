#include<stdio.h>
#include<ctype.h>
#include<string.h>
 int checkpassword(char str[])
 {
 if(length<4)
 {
 return 0;
 }
 int hasdigit =0;
 int hasupper =0;
 if(isdigit(str[0]))
 {
 return 0;
 }
 for(int i=0;i<length;i++)
 {
 if(isdigit(str[i]))
 {
 hasdigit=1;
 }
 if(str[i] ==''|| str[i] == '/')
 return 0;
 }
 }
 if(hasdigit && hasupper)
 {
 return 1;
 }
 return 0;
 }
 int main()
 {
 char password1[]="bB1_89";
 char password2[]="abc_@89";
 char password3[]="aA_1";
 char password4[]="Abc @89";
 printf("password:%s, output: %d\n", password1, checkpassword(password1));
 printf("password:%s, output: %d\n", password2, checkpssword(password2));
 printf("password:%s, output: %d\n", password3, checkpassword(password3));
 printf("password:%s, output: %d\n", password4, checkpassword(password4));
 return 0;
 }
 
 return 1;
