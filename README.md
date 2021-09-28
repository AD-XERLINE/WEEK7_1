# WEEK7_1
โปรแกรมรายสัปดาห์ที่ 7 ที่ 1

    #include<stdio.h>

    int main() {
	    int n;
    	printf("Enter the number: ");
    	scanf("%d",&n);
	
    	for(int i = 0;i<n;i++){
    		for(int j=0;j<n;j++){
    			if(j<n){
    			printf("*");
    			}
    		}
    		printf("\n");
    	}
    }
