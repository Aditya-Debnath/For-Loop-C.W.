# For-Loop-C.W.
20.07.2022 Lab Class Works

1st Problem

#include<stdio.h>
int main()
{
    int A,N;
    scanf("%d",&N);
    for(A=N;A>=1;A = A-1)
    {
        printf("Aditya Debanth\n");
        printf("\n");
    }
}

2ed Problem

#include<stdio.h>
int main()
{
    int n, i, sum;
    scanf("%d",&n);
    for(i=1;i<=n;i = i+1)
    {
        printf("%d\n",i);
    }
}

3rd Problem

#include<stdio.h>
int main()
{
    int n, i,sum = 0;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        printf("%d",i);
        if(i<n){
            printf("+");
        }
        sum = sum + i;
    }
    printf("=%d",sum);
}

4th Problem

#include<stdio.h>
int main()
{
    int i,n;
    scanf("%d",&n);
    int fact =1;
    for(i=1;i<=n;i=i+1)
    {
        fact = fact*i;
    }
    printf("%d",fact);
}

5th Problem

#include<stdio.h>
int main()
{
    int a,i,n,r;
    int fact = 1;
    int fact2 = 1;
    scanf("%d %d",&n,&r);
    a = n-r;
    for(i=1;i<=n;i++)
    {
        fact = fact*i;
    }
    for(i=1;i<=a;i++)
    {
        fact2 = fact2*i;
    }
    printf("%d",fact/fact2);

}

6th Problem 

#include<stdio.h>
int main()
{
    int n,i,a=0;
    scanf("%d",&n);

    for(i=2;i<n;i++)
    {
        if(n%i==0)
            a = 1;
    }
    if(a ==0)
    {
        printf("this is a prime number.\n");
    }else{
    printf("Not prime.\n");
    }
}

7th Problem 

#include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    for(;n > 0;)
    {
        int digit = n % 10;
        printf("%d\n",digit);
        n = n/10;
    }
}

8th Problem

#include<stdio.h>
int main()
{
    int i, n;
    scanf("%d",&n);
    for(i=n;i > 0;i = i/10)
    {
        int digit = n % 10;
        printf("%d\n",digit);
    }
}

🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩
9th Problem is not solve, because of lack of time & ইচ্ছার অভাব। 

There is another code that not written here,(Also, আমি ওই কোডটা করি নাই।) the problem is that 
🚩"you have to write a C program, that's make a sum of all the even number that you give as input".🚩
