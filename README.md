#Zadania odpowiedzie

Zad. 1
Program wczytuje wartość liczby naturalnej n i drukuje wartość sumy kwadratów:
1^2 + 2^2 + 3^2 + ... + n^2

```c
#include<stdio.h>
main(){
  int x,n,kwadrat,suma;
  suma=0;
  printf ("Podaj liczbę ");
  scanf ("%i", &n);
  for (x=0; x<=n; x=x+1){
    kwadrat=x*x;
    suma=suma+kwadrat;
  }
 printf ("Wartość sumy %i\n", suma);
}
```

Zad. 2
Napisać program obliczający wartość wyrażeń, n1, n2, n3

```c
#include<stdio.h>
main(){
  int n1, n2, n3;
  n1=5+3*8/2-3;
  n2=2%2+2*2-2/2;
  n3=2*4*(5+9/2);
  printf (" \n n1= %i\n ",n1);
  printf (" \n n2= %i\n ",n2);
  printf (" \n n3= %i\n ",n3);
}
```

Zad. 3
W miejsce kropek wpisz kod by powstał działający program.
/*Program wypisuje liczby z tablict[] w odwrotnej kolejności, tj.: 12,6,4,2,1*/


```c
#include<stdio.h>
int main (){
  int tabela[]={1,2,4,6,12};
  int a;
    for (a=4; a>=0; a=a-1)
    printf (" %i", tabela[a]);

  return 0;
}
```

Zad. 4
Wypisz potęgi liczby 2 do 2010

z for:

```c
#include<stdio.h>
/*wypisuje potęgi 2 do 2010 */
main (){
  int potega;
    for (potega=1; potega<=5010; potega=2*potega){
    printf (" %i",potega);
    }
}
```

z while

```c
#include<stdio.h>
/*wypisuje potęgi 2 do 2010 */
main (){
  int potega;
  potega=1;
    while (potega<=5010){
    printf (" %i",potega);
    potega=2*potega;}
}
```

Zadanie 5.

```c
#include <stdio.h>
main(){
int liczba=8;
int i;
int wynik[20];
printf("Podaj liczbę w systemie 10: ");
scanf("%i",&liczba);
i=0;
while(liczba!=0)
{
    wynik[i]=liczba%2;
    printf(" RESZTA %i przez 2 = %i ",liczba,wynik[i]);
    liczba=liczba/2;
    printf(" PO PODZIELENIU LICZBA =  %i \n", liczba);
    i++;
}
printf("\nWYNIK:");
for(i=i-1;i>=0;i--) printf(" %i ",wynik[i]);


}
```


    Status
    API
    Training
    Shop
    Blog
    About

    © 2013 GitHub, Inc.
    Terms
    Privacy
    Security
    Contact


