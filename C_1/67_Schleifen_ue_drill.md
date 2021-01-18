---
title: Doc
type: assignment
cmds: ['md_html.bash --small']
---

# Schleifen (Übungen)

Überlege zuerst was folgende Programmausschnitte (exakt!) ausgeben, kontrolliere dann am Rechner. Gib Dir für jede richtige Antwort einen Punkt.


**Übung (Lesen von Schleifen II):**


```c
// (j)
int i;
int n = 1;
for(i=10; i>0; i--)
{
  n = n + i;
  if(n>20)
    break;
}
printf("%d %d\n", i, n);
```


```c
// (k)
int i=33;
int n=1;
while(i>0) 
{
	printf("%d ",i);
	i = i - n;
	n++;
}
printf("\nEnde=%d", i);
```


```c
// (l)
int i;
for( i=127; i > 0; i=i/2 )
{
  printf("%d\n", i);
}
printf("Ende=%d", i);
```

```c
// (m)
int i = 22;
while( i != 16 )
{
  printf("%d\n", i);
  if( i > 15 )
  {
    i = i - 7;
  }
  else
  {
    i = i * 3 - 1;
  }
}
printf("Ende=%d", i);
// Hinweis: 6 Durchläufe
```


```c
// (n)
int i = 40;
while((i  < 10) || (i >= 17))
{
  printf("%d\n", i);
  if(i  > 21)
  {
    i = i - 19;
  }
  else
  {
    i = i * 3 - 1; 	
  }
}
printf("Ende=%d", i);
// Hinweis: 6 Durchläufe
```


```c
// (o)
int i = 13;
while( i != 1 )
{
  if( i%2 == 1)
  {
    i = i * 3 + 1; 	
  }
  else
  {
    i = i / 2;
  }
  printf("%d\n", i);
}
printf("Ende=%d", i);
// Hinweis: 9 Durchläufe
```

---










