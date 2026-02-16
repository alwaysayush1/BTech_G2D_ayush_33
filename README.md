# BTech_G2D_ayush_33
C Program 
#include <stdio.h>
int main() {
float s1, s2, s3, s4, s5, total, percentage; 
printf("Enter marks for 5 subjects: ");
scanf("%f %f %f %f %f", &s1, &s2, &s3, &s4, &s5); 
total = s1 + s2 + s3 + s4 + s5;
percentage = (total / 500.0) * 100.0; 
printf("Total Sum: %.2f\n", total);
printf("Percentage: %.2f%%", percentage); 
return 0;
}
