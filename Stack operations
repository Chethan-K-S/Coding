#include<stdio.h>
#define size 5
void push(int value);
void pop();
void display();

int top=-1;
int stack[size];
 int main()
 {
     int value,choice;
     while(1)
     {
        printf("Stack operations\n");
        printf("1. Push 2. Pop 3. Display 4. Exit\n");
        scanf("%d",&choice);
        switch (choice)
        {
        case 1:
            printf("Enter the value to be pushed\n");
            scanf("%d",&value);
            push (value);
            break;
        case 2:
            pop();
            break;
        case 3:
            display();
            break;
        case 4:
            return 0;
        default:
            printf("Invalid input");
            break;
        }
     }
 }

 void push(value)
 {
     if (top==size -1)
     {
         printf("The stack is full");
     }
     else
     {
         top ++;
         stack[top]=value;
     }
 }
 void pop()
 {
     if (top==-1)
     {
         printf("Stack is empty");
     }
     else
     {
         printf("Popped value is %d",stack[top]);
         top--;
     }
 }
 void display()
 {
     if(top==-1)
        printf("Stack is empty");
     else
        {
            printf("Stack elements are\n");
            for(int i=top;i>=0;i--)
            {
                printf("%d",stack[i]);
            }
        }
 }
