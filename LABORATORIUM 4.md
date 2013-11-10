Rozwiązania zadań:

Zad1.
Program sdprawdzi czy podana liczba jest liczbą pierwszą.

```c
#include<stdio.h>
//program sprawdzi czy dana liczba jest pierwsza
main(){
  int n, m, l, k;
  k=0;
  printf ("Podaj liczbę \n");
  scanf (" %d", &n);
//sprawdzamy reszte z dzielenia podanej liczby przez kolejne liczby począwszy od 1 kończąc na podanej liczbie  
  for (m=1; m<=n; m=m+1){
    l=n%m;
    //printf ("Reszta z dzielenia przez  %d ", m);
    //printf ("wynosi %d \n\n", l);
//zliczamy wyniki - ile razy reszta z dzielenia wynosi 0    
    if (l==0)
      k=k+1;
  }
  printf ("Liczba ma %d dzielniki(dzielników) \n\n", k);
//jeśli k=2 mamy liczbę pierwszą, jeśli k jest większa niż 2 mamy liczbę złożoną
    if (k==2)
      printf ("Podana liczba jest liczbą pierwszą \n\n");
    else 
      printf ("Podana liczba nie jest liczbą pierwszą! \n\n");

}
```

Zad2.

```c
#include<stdio.h>
//program dla wczytanej liczby obliczy najmniejszą liczbę n, taką że:
//1+2+3+...+n>=M
main(){
  int M, k, l, n;
  k=0;
    printf ("Podaj liczbę \n\n");
    scanf (" %d", &M);
    printf ("\n\n");
  for (l=1; k<M; l=l+1){
      k=k+l;
      if (k>=M)
        //k=k-l;
        printf ("Szukana liczba to %d \n\n", l);
    }
    printf ("Suma wynosi %d \n\n", k); 
}
```

Zad3.

```c
#include<stdio.h>
//program dla wczytanej liczby wypisze wszystkie jej dzielniki
main(){
  int n, m, l, k;
  k=0;
  printf ("Podaj liczbę \n");
  scanf (" %d", &n);
//sprawdzamy reszte z dzielenia podanej liczby przez kolejne liczby począwszy od 1 kończąc na podanej liczbie  
  printf ("Dzielniki liczby n = %d \n\n to: ", n);
  for (m=1; m<=n; m=m+1){
    l=n%m;
    //printf ("Reszta z dzielenia przez  %d ", m);
    //printf ("wynosi %d \n\n", l);
//zliczamy wyniki - ile razy reszta z dzielenia wynosi 0    
        if (l==0)
    	printf (" %d ", m);   
  }
}
```

