#include <stdio.h>
#include <string.h>
void loop();
int conection();
int main() {
    int resistors,i;
    printf("enter the number of resistors : ");
    scanf("%d",&resistors);
	char connection[20];
    for(i=0;i<=resistors;i++){
    	loop();
	}

    return 0;
}
void loop(){
	int resistance1, resistance2;
	char series[] = "series";
    char parallel[] = "parallel";
	conection();
    printf("enter the resistance value for 1st resistor : ");
    scanf("%d", &resistance1);

    if (strcmp(conection, parallel)) {
        printf("the equivalent resistance is : %f", (float)(resistance1 * resistance2) / (resistance1 + resistance2));
    } else if (strcmp(conection, series)) {
        printf("equivalent resistance = %d", resistance1 + resistance2);
    }
}
int conection(){
	char connection[20];
	printf("enter the connection type : ");
    gets(connection);
    return connection;
}
