# uday

PREPARENEW
CERTIFY
COMPETE
Search
 208r1a05a61 
All Contests  Smart Interviews Basic  Print pyramid pattern
Print pyramid pattern
Problem
Submissions
Leaderboard
Print pyramid pattern using '*'. See example for more details.

Input Format

First and only line of input contains a single integer N - the size of the pyramid.

Constraints

1 <= N <= 50

Output Format

For the given integer, print pyramid pattern.

Sample Input 0

5
Sample Output 0

    *
   ***
  *****
 *******
*********
Explanation 0

Self Explanatory

Submissions: 14185
Max Score: 20
Difficulty: Easy
Rate This Challenge:

    
More
SOLUTION:- 

#include <stdio.h>

int main()

{

    int i,j,n,k=0;

    scanf("%d",&n);

    for(i=1;i<=n;++i,k=0){

        for(j=1;j<=n-i;++j){

            printf(" ");}

        while(k!=2*i-1){

            printf("*");

            ++k;

        }

      printf("\n");

    }

    return 0;

}

1
        
Line: 1 Col: 1
Run Code Submit CodeUpload Code as File 
Test against custom input
Interview Prep | Blog | Scoring | Environment | FAQ | About Us | Support | Careers | Terms Of Service | Privacy Policy | Request a Feature

