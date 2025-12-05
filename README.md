# Display-string-character-wise.
[main.c](https://github.com/user-attachments/files/23962991/main.c)
#include <stdio.h>
#include <stdlib.h>
int main(){
char n[]="Hitler";
int i=0;
while(n[i]!='\0'){
    printf("%c\n",n[i]);
    i++;
}
return 0;
}
