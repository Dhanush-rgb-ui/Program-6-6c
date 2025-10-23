# Module-6 Day-3 SEB
## AIM:
To write a program to store information of Books (id, name, title and subject) using function with structure.

## Program:
```c
#include<stdio.h>
struct book{
    char title[50];
    char name[50];
    char sub[50];
    int id;
};
int main(){
    struct book to;
    scanf("%s",to.title);
    scanf("%s",to.name);
    scanf("%s",to.sub);
    scanf("%d",&to.id);
    printf("Book Title is =%s\n",to.title);
    printf("Book Name is =%s\n",to.name);
    printf("Book Subject is =%s\n",to.sub);
    printf("Book Id is =%d",to.id);
    return 0;
}
```
## Result:
<img width="751" height="140" alt="image" src="https://github.com/user-attachments/assets/6313842c-5bc8-4f99-ab2f-61928e2755d7" />
