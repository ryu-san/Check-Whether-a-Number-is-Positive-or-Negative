///Check-Whether-a-Number-is-Positive-or-Negative

#include <stdio.h>
int main()
{
	double number;

	printf("Enter a number: ");
	scanf_s("%lf", &number);

	if (number <= 0.0)
	{
		if (number == 0.0)
			printf("You entered 0.");
		else
			printf("You entered a negative number.");
	}
	else
		printf("You entered a positive number.");
	return 0;
}
