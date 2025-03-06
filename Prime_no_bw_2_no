//In this code we find sum of prime numbers between two integer given by user
#include<stdio.h>

int main(){
    int minnum,maxnum,i,j,sum,flag;
    sum =0;
    flag =1;
    printf("In this code we find sum of prime number between two number\n");
    printf("Enter the minimum number ");
    scanf("%d",&minnum);
    printf("\nEnter the maximum number");
    scanf("%d",&maxnum);
    printf("\n");
    
        for(i=minnum;i<=maxnum;i++){
            if(i<4){
                sum = sum + i;
            }else{
                for(j=2;j<=i/2;j++){
                    if(i%j == 0){
                        flag =0;
                        break;
                    }
                }
                if(flag ==1){
                     sum = sum + i;
                }
                flag = 1;
                }
            }
    printf("Total number = %d\n",sum);
    return 0;
}
