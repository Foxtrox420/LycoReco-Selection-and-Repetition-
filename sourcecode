#include <stdio.h>

int main(){
	
	int x = 0, y = 0, totalx=1, totaly=1, shot; 
	
	printf("Welcome to the Game!\n\n");
	printf("To start the game, please input the x values and y, given by a space: ");
		
	do{
		scanf("%d %d", &x, &y); 
		if(x > 1 && y > 1){
			printf("you move too fast!, try again");
		}
		else{
			totalx += x; //totalx = totalx + x  // || = OR && = AND 
		totaly += y;
		if(totalx > 10 || totaly > 10 || totalx < 1 || totaly < 1){
			printf("You have fallen to the backrooms, try again !\n\n"); 
			totalx = 1;
			totaly = 1; 
		}
		else if(totalx == 4 && totaly == 7){
			printf("You have encountered Majima, press 1 to shoot him: ");
			scanf("%d", &shot);  
			if(shot == 1){
			printf("\n\nYou have taken out Majima, proceed with your journey\n");	
			}
			else if(shot > 1 || shot < 1){
			printf("\n\nYou missed the shot!, you have been sent backwards to avoid confrontation!\n");
			totalx = 4;
			totaly = 4; 
			}
		}
		else if(totalx == 6 && totaly == 3){
			printf("You met chisato on the way, you get extra directions to LycoReco!\n\n");
			totalx = 8;
			totaly = 6;
		}
		printf("your current location is : %d %d\n\n", totalx, totaly); 
		}

	}while(totalx != 9 || totaly != 9);
	
	
	printf("You have arrived !\n\n"); 	
	
	return 0;	
}



////for(statements1 ; statement 2; statement 3) 
//
//int i = 0 ; i < t; i++ 
