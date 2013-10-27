Rozwiązania zadań:

Zad3.
Wczyta liczbę i napiszę czy jest parzysta czy nieparzysta

```c
#include<stdio.h>
main(){
  int n, m;
  printf ("podaj liczbę ");
  scanf (" %d", &n);
  m=n%2;
    if (m==1)
      printf ("Wczytana liczba jest nieparzysta \n");
    else 
	   printf ("Wczytana liczba jest parzysta \n\n");
  
}
```

Zad4.
Wczyta dwie liczby i sprawdzi czy są sobie równe:

```c
#include<stdio.h>
main(){
  int n, m, l;
  printf ("podaj liczbę ");
  scanf (" %d", &n);
  printf ("podaj drugą liczbę ");
  scanf (" %d", &m);
  l=m-n;
    if (l==0)
      printf ("Wczytana liczba są sobie równe \n");
    else 
	   printf ("to są różne liczby \n\n");
  
}
```
Zad5.
Wczyta liczby i poda która jest większa

```c
#include<stdio.h>
main(){
  int n, m, l;
  printf ("podaj liczbę ");
  scanf (" %d", &n);
  printf ("podaj drugą liczbę ");
  scanf (" %d", &m);
  l=m-n;
    if (l<0)
      printf ("Pierwsza liczba jest większa od drugiej \n");
    else 
	   printf ("Pierwsza liczba jest mniejsza lub równa drugiej \n\n");
  
}
```

Zad6.
Obliczy i wypiszę na ekran sume kwadratów liczb od 1 do 20:

```c
#include<stdio.h>
main(){
  int n, m, l;
  l=0;
  for (n=1; n<21; n=n+1){
  	m=n*n;
  	l=l+m;
  }
        	printf ("Suma kwadratów liczb od 1 do 20 jest równa %i \n\n", l);
    
}
```

Zad8.
Program wczyuje liczbę całkowitą n>=0, a następne n liczb rzeczywistych (double %lf) i drukuje te liczby w trzech kolumnach w taki sposób, żeby zachować krycie (tzn. kropka dzisiętna zawsze była w tych samych kolumnach):

```c
#include<stdio.h>
main(){
	int n; int i;
//printf ("podaj n "); 
	scanf ("%i", &n);
// deklaracja tablicy
double tab[n];
//pętla wczytująca dane do tablicy
for (i=0; i<n; i++)
	scanf ("%lf", &tab[i]);
// pętla wypisująca dane z tablicy
	for (i=0; i<n; i++){
	printf (" %4.5lf |", tab[i]); if (i%3==2) printf ("\n");}
	printf ("\n\n");
}		
```


Zadanie z kartki nr 1
tablica 5 liczb całkowitych w następujący sposób: int tab[]={1,3,7,8,9} a następnie wypisze na ekran jej zawartość:

```c
#include<stdio.h>
int main (){
  int tab[]={1,3,7,8,9};
  int a;
    for (a=0; a<=4; a=a++)
    printf (" %i ", tab[a]);

  return 0;
}	
```

zad z kartki nr 5
wczytuje to tablicy 5 elementowej liczby i zamienia je miejscami (kolejność od ostatniej komórki do pierwszej)

```c
#include<stdio.h>
int main (){
  int tab[5];
int a;
  for (a=0; a<=4; a++)
  scanf ("%i", &tab[a]);
      for (a=4; a>=0; a=a-1)
    printf (" %i", tab[a]);

  return 0;
}
```

