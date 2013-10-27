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


