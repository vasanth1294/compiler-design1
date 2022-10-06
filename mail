%{
//#include<stdio.h>
int valid=0;
%}
%%
[a-z]+@[a-z]+".com"|".in"|".edu" {printf("valid");}
.+ {printf("\ninvalid\n");}
%%
int yywrap(){
return 1;
}
int main(int argc,char*argv[]){
printf("enter the gmail:");
yylex();
return 0;
}
