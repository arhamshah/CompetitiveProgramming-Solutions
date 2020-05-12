#include <stdio.h>
void space(int a){
    for(int i=0;i<a;i++){
        printf(" ");
    }
}
void printStar(int a){
    for(int i=0;i<a;i++){
        printf("*");
    }
}
int main(void)
{
    int n,blank,rem;
    scanf("%d",&n);
    blank=(n-5)/2+1;
    rem=n-blank-1;
    if(n<5 || n%2==0)
        return 1;
 //****************************** First Line ****************************************************           
    printStar(1);
    space(blank);
    printStar(rem);
    printf("\n");
//****************************** Middle Rows with Blank Spaces ***********************************            
    for(int j=0;j<blank;j++){
        printStar(1);
        space(blank);
        printStar(1);
        printf("\n");
    }
//****************************** Centre Line *****************************************************   
    printStar(n);
    printf("\n");
//****************************** Middle Rows with Blank Spaces ***********************************
for(int j=0;j<blank;j++){
        space(blank+1);
        printStar(1);
        space(blank);
        printStar(1);
        printf("\n");
    }
//****************************** Last Line ***********************************
    printStar(rem);
    space(blank);
    printStar(1);
        
    }

