#include <stdio.h>
#include <math.h>
 
void main()
  {
    int s, a, b, c, area, height, width, d1, d2, base;
 
    printf("Enter the values of a, b and c \n");
    scanf("%d %d %d", &a, &b, &c);
    
   
    s = (a + b + c) / 2;
    area = sqrt(s * (s - a) * (s - b) * (s - c));
    printf("Area of a triangle = %d \n", area);
    
    printf("Enter height and width of the given triangle:\n ");
    scanf("%d%d", &height, &width);
    area = 1/2 * height * width;
    printf("Area of right angled triangle is: %d\n", area);
    
    printf("Enter the value for two bases & height of the trapezium: \n");
    scanf("%d%d%d", &a, &b, &h);
    area = 1/2 * (a + b) * h ;
    printf("Area of the trapezium is: %d", area);
    
    
    printf("Enter diagonals of the given rhombus: \n ");
    scanf("%d%d", &d1, &dl2);
    area = 1/2 * d1 * d2;
    printf("Area of rhombus is: %d \n", area);
   
   printf("Enter base and altitude of the given Parallelogram: \n ");
    scanf("%d%d", &base, &height);
    area = base * height;
    printf("Area of Parallelogram is: %d\n", area);
  }
