# Homework20
Task 1
#include <stdio.h>


    int main(){
            int num = 0;
            int sum = 0;
            printf("Enter the number");
            scanf("%d",&num);
            for(int i = 1;i<= num /2 ;i++){
                if(num % i == 0){
                    sum +=i;
                }
              }
                                  
            if(sum == num){
                printf("Kataryal e");
            }else{
                printf("Kataryal che");
                }

            return 0;

        }


        Task 2 


#include <stdio.h>


    int main(){

        int n = 0;
        printf("Enter the number");
        scanf("%d",&n);
        for(int i = 1; i <= n ; i++){
           for(int j = 1; j <= i; j++){
        printf("%d",i);
}

            printf("\n");

}

            
            return 0;

        }

        Task 3


        #include <stdio.h>


    int main(){
        
            int n = 0;
            int num = 1;
            printf("Enter the number ");
            scanf("%d",&n);
            for(int i = 1; num <= n; i++){
                for(int j = 1; j <= i;j++){
                if(num > n)break;
                printf("%d",num);
                num++;        
                
            }    
            printf("\n");
            
            }
            return 0;

        }

        Task 4
        
    #include <stdio.h>

int main(){
 	int num = 0;
	scanf("%d",&num);

	for(int i = 0;i < num;i++){
	  for(int j = 0; j <  num;j++){
		  printf("*");
	  }
	  printf("\n");
	}
	
	return 0;
}
Task 5

#include <stdio.h>

    int main(){
        int n = 0 ;
       
        printf("Enter  n ");
        scanf("%d",&n);
        for (int i = 0 ; i < n;i++){
            for(int j = 0 ; j <  n ; j ++){
             if( i == 0 || i == n-1||j == 0|| j == n -1 ){
                printf("*");
                }else{
                printf(" ");
           }
           }

           printf("\n");
           

       }
            return 0;
            }

            
