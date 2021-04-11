#include<stdio.h>
void main()
{
    int mark;
    printf("Enter your mark:");
    scanf("%d",&mark);
    if(mark>=85)
    {
        printf("Grade A");
    }
    else if(mark>=70&&mark<85)
    {
        printf("Grade B");
    }
    else if(mark>=55&&mark<70)
    {
        printf("Grade C");
    }
    else if(mark>=40&&mark<55)
    {
        printf("Grade D");
    }
    else
    {
        printf("Grade F");
    }
    return 0;
}
