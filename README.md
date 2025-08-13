#include <stdio.h> 

int main() 

{ 

    char a[20]; 

    printf("enter the student name:"); 

    scanf("%s", a); 

    int b; 

    printf("enter his roll number:"); 

    scanf("%d", &b); 

    char c[10]; 

    printf("enter his dept:"); 

    scanf("%s", c); 

    float d; 

    printf("enter his mark:"); 

    scanf("%f", &d); 

    printf("name:%s\nroll number:%d\ndepartment:%s\nmark:%f\n", a, b, c, d);	 

} 
