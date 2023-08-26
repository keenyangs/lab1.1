# lab1.1
Pazenko Danila, ITS-bo-22-1, Osnovi krossplatformennogo programmirovaniya

Programm:
# include <stdio.h>
# include <math.h> 
#include <conio.h>
#include <locale.h>
int main()
{
 float x, sum;
	setlocale(LC_ALL, "Ruassian");
	int i,f, n, k;
	sum = 0;
	const double e = 2.7;
 printf("Write x: ");
	scanf_s("%f", &x);
	printf("write n: ");
	scanf_s("%d", &n);
 for (i = 2; i <= n; i++)
	{
    