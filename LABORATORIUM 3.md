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



