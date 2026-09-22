#include <stdio.h>
int main() {
    int a[5];
    int b[2][3];
    int i, j;
    printf("Enter 5 elements of 1-D Array : \n");
    for (i = 0; i < 5; i++) {
        scanf("%d", &a[i]);
    }
    printf("Enter 6 elements of 2-D Array : \n");
    for (i = 0; i < 2; i++) {
        for (j = 0; j < 3; j++) {
            scanf("%d", &b[i][j]);
        }
    }
    printf("\n\nOne element from (1-D) Array : %d", a[2]); 
    printf("\n\nOne element from (2-D) Array : %d", b[0][2]); 
    printf("\n\nTraversing (1-D) array : \n");
    for (i = 0; i < 5; i++) {
        printf("%d ", a[i]);
    }    
    printf("\n");
printf("\n\n Traversing (2-D) Array :\n");
for (i = 0; i < 2; i++) {
    for (j = 0; j < 3; j++) {
        printf("%d ", a[i][j]); 
    }
    printf("\n");
}
return 0;
}
