
	clrscr();
	printf("Nhap cac so thuc a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);

	if (a + b > c && a + c > b && b + c > a)
	{
		printf("La ba canh mot tam giac ");
		deu = (a == b) && (b == c);
		vuong = (a *a + b *b == c *c) || (a *a + c *c == b *b) || (b *b + c *c == a *a);
		can = (a == b) || #include <stdio.h>
#include <conio.h>
#include <math.h>

void main()

{ tam giac ");
		deu = (a == b) && (b == c);
		vuong = (a *a + b *b == c *c) || (a *a + c *c == b *b) || (b *b + c *c == a *a);
		can = (a == b) || (a == c) || (b == c);

		if (deu) printf(" deu\n");
		else if (vuong && can) printf(" vuong can\n");
		else if (vuong) prin
