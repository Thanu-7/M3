# EX-11-EMI-CALCULATOR

## Name : Thanushree Vijayakanth
## Register Number : 212224110054

## AIM

To write a program to prepare EMI calculator using function without return type and with arguments.

## ALGORITHM

1.	Start the program.
2.	Read principal amount, rate of interest and months.
3.	Pass these values as arguments to function.
4.	Calculate EMI using the formula, amt=(prpow(1+r,t))/(pow(1+r,t)-1)
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
#include <math.h> 
void calculateEMI(float p, float r, int t);

int main() {
    float p, r;
    int t;
    scanf("%f%f", &p,&r);
    scanf("%d", &t);
    calculateEMI(p,r,t);
    return 0;
}

void calculateEMI(float p, float r, int t) {
    float emi;
    emi = (p* r * pow(1 + r, t)) / (pow(1 + r, t) - 1);
    printf("Monthly EMI is: %.2f\n", emi);
}
```



## OUTPUT
![image](https://github.com/user-attachments/assets/db98938e-9133-4017-b0f1-959b752694e8)




## RESULT

Thus the program to prepare EMI calculator using function without return type with arguments has been executed successfully
 
 


# EX-12-FIBONACCI-SERIES

## Name : Thanushree Vijayakanth
## Register Number : 212224110054
## AIM
To write a C program to generate the Fibonacci series for the value 6.

## ALGORITHM
1.	Start the program.
2.	Read number of terms to display.
3.	Add the previous two terms and store it in new term.
4.	Assign 2nd term to 1st term and 3rd term to 2nd term.
5.	Repeat steps 3 and 4 n number of times.
6.	Display the result.
7.	Stop the program.

## PROGRAM
```
#include <stdio.h>

int main() {
    int n = 6; 
    int a = 0, b= 1, next, i;
    for (i = 1; i <= n; i++) 
    {
        printf("%d ", a);
        next = a+b;  
        a = b;       
        b = next;         
    }
    printf("\n");
    return 0;
}
```

## OUTPUT

![image](https://github.com/user-attachments/assets/bcad4fa2-edec-4f29-a847-62faba4b5e4d)







## RESULT
Thus the program to generate the Fibonacci series for the value 6 has been executed successfully.
 
 


# EX-13-ONE-DIMENSIONAL-ARRAY

## Name : Thanushree Vijayakanth
## Register Number : 212224110054
## AIM
To write a C program to read n elements as input and print the last element of the array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	Print the last element.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>

int main() {
    int n, i;
    scanf("%d", &n);
    int arr[n]; 
    for (i = 0; i < n; i++) 
    {
        scanf("%d", &arr[i]);
    }
    printf("The last element is: %d\n", arr[n-1]);
    return 0;
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/466e8ff7-fff9-44f4-8ae0-7a46faa09d44)










## RESULT
Thus the program to read n elements as input and print the last element of the array has been executed successfully.
 
 


# EX-14-POSITIVE-ARRAY-ELEMENTS

## Name : Thanushree Vijayakanth
## Register Number : 212224110054
## AIM
To write a C Program to count total number of positive elements in an array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	If the array value can be divided by 2 then increment count by 1.
5.	Display result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>

int main() {
    int n, i, count = 0;
    scanf("%d", &n);
    int arr[n]; 
    for (i = 0; i < n; i++) 
    {
        scanf("%d", &arr[i]);
    }

    for (i = 0; i < n; i++) {
        if (arr[i] > 0) 
        {
            count++;
        }
    }
    printf("Total number of positive elements = %d\n", count);
    return 0;
}
```


## OUTPUT
![image](https://github.com/user-attachments/assets/ac75ce35-1e04-48f5-b141-0bb725d89050)






## RESULT
Thus the program to count total number of positive elements in an array has been executed successfully.





 
 


# EX -15 - Replace All Even Elements With 'E' In One Dimensional Array

## Name : Thanushree Vijayakanth
## Register Number : 212224110054

## Aim:
To write a C program to replace all even elements with 'E' in one dimensional array

## Algorithm:
1.	Input the array:
  Read the size of the array.
  Input the elements of the array.
2.	Iterate through the array:
 	For each element of the array, check if the element is even (i.e., if the element modulo 2 equals 0).
3.	Replace even elements with 'E':
     If an element is even, replace that element with the character 'E'.
4.	Output the updated array:
 Print the updated array after replacements.

## Program:
```
#include <stdio.h>

int main() 
{
    int n, i;
    scanf("%d", &n);
    int arr[n]; 
    for (i = 0; i < n; i++) 
    {
        scanf("%d", &arr[i]);
    }
    for (i = 0; i < n; i++) 
    {
        if (arr[i] % 2 == 0) 
        {
            printf("E ");  
        } else 
        {
            printf("%d ", arr[i]);  
        }
    }
    printf("\n");
    return 0;
}
```

## Output:
 ![image](https://github.com/user-attachments/assets/2c71b6ba-816b-4099-b970-0cd618db5312)


## Result:

Thus, the program to replace all even elements with 'E' in one dimensional array was verified successfully.



