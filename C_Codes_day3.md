# Pattern -1 ------------------------------------------

#include <stdio.h>

int main()
{
    int i,j;
    for(i=65;i<70;i++)
    {
        for(j=65;j<=i;j++)
        {
            printf("%c ",j);
        }
        printf("\n");
    }
  
    return 0;
}

--------------------------------------------------------------

# Pattern -2:
#include <stdio.h>

int main()
{
    int i,j;
    for(i=1;i<6;i++)
    {
        for(j=1;j<=i;j++)
        {
           /* if(j%2==0)
            {
                printf("0");
                
            }
            else
            printf("1"); */
            
            (j%2==0)?printf("0"):printf("1");
        }
        printf("\n");
    }


    return 0;
}
=====================================================================
# Pattern 3::

#include <stdio.h>

int main()
{
    int i,j,k=1;
    for(i=1;i<=4;i++)
    {
        
        for(j=1;j<=i;j++)
        {
            printf("%d\t",k++);
        }
        printf("\n");
    }
    return 0;

}

=======================================================================
#Pattern -4:

#include <stdio.h>

int main()
{
    int i,j,k=1;
    for(i=1;i<=5;i++)
    {
        for(j=1;j<=5;j++)
        {
            if(i==1||i==5||j==1||j==5)
            printf("*");
            else
            printf(" ");
        }
        printf("\n");
    }
    return 0;

}
==========================================================================
# Pattern 5::

#include <stdio.h>

int main()
{
    int i,j,k=1;
    for(i=0;i<=5;i++)
    {
        for(k=5;k>=i;k--)
         printf(" ");
        for(j=i;j>=0;j--)
        {
            printf("%d",j);
            
        }
        for(j=1;j<=i;j++)
        {
            printf("%d",j);
            
        }
        printf("\n");
    }
    return 0;

}

==============================================================================
# Pattern 6::

#include <stdio.h>

int main()
{
    int i,j,k;
    for(i=7;i>=1;i--)
    {
        for(k=7;k>=i;k--)
         printf(" ");
        for(j=1;j<=i;j++)
        {
            printf("%c",j+64);
            
        }
        for(j=i;j>=1;j--)
        {
            printf("%c",j+64);
            
        }
        printf("\n");
    }
    return 0;

}

=================================================================================

#Pattern 7::
#include <stdio.h>

int main()
{
    int i,j,k;
    for(i=5;i>=1;i--)
    {
        //for(k=7;k>=i;k--)
         //printf(" ");
        for(j=i;j<=5  ;j++)
        {
            printf("%d",j);
            
        }
        for(j=2;j<=i;j++)
        {
            printf("5");
            
        }
        printf("\n");
    }
    return 0;

}
o/p::

55555
45555
34555
23455
12345

=================================================================================

#pattern 8:

#include <stdio.h>

int main()
{
    int i,j,k;
    for(i=1;i<=4;i++)
    {
        //for(k=7;k>=i;k--)
         //printf(" ");
        for(j=i;j<=4  ;j++)
        {
            printf("%d",j);
            
        }
        for(j=i-1;j>=1;j--)
        {
            printf("%d",j);
            
        }
        printf("\n");
    }
    return 0;

}

o/p:


1234
2341
3421
4321

=================================================================================
# Program 9::

#include <stdio.h>

int main()
{
    int i,j,k;
    for(i=1;i<=5;i++)
    {
        //for(k=7;k>=i;k--)
         //printf(" ");
        for(j=5;j>=1  ;j--)
        {
            if(i==j)
            printf("*");
            else
            printf("%d",j);
            
        }
       // for(j=i-1;j>=1;j--)
        {
         //   printf("%d",j);
            
        }
        printf("\n");
    }
    return 0;

}

O/P::
5432*
543*1
54*21
5*321
*4321
=================================================================================

#Pattern 10::
#include <stdio.h>

int main()
{
    int a, i,j,k=1;
    for(i=1;i<=4;i++)
    {
       a=k;
        for(j=1;j<=i  ;j++)
        {
          printf("%d ",k++);
            
        }
       for(j=k-2;j>=a;j--)
        {
           printf("%d ",j);
            
        }
        printf("\n");
    }
    return 0;

}

o/p:

1 
2 3 2 
4 5 6 5 4 
7 8 9 10 9 8 7






