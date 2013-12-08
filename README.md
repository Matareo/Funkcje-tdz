5.
zawiera funkcję, która sprawdza czy podana liczba rzeczywista należy do zakresu od
-sqrt(2) do sqrt(2); 
```c
#include <stdio.h> 
#include <math.h>

zakres(float liczba){
	if(liczba >= -sqrt(2) && liczba <= sqrt(2)){
		printf("Liczba %f należy do zakresu od %f do %f\n", liczba, -sqrt(2), sqrt(2));
	}else{
		printf("Liczba %f nie należy do zakresu od %f do %f\n", liczba, -sqrt(2), sqrt(2));
	}
}

main(){
	float rzeczywista;

	printf("Podaj liczbę rzeczywistą: ");
	scanf("%f", &rzeczywista);
	zakres(rzeczywista);

	return 0;
} 
```
