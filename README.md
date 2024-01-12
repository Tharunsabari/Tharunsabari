
Program:


(a) To find odd or eveni 

echo Enter the number

read n 

C= $((n%2))

 if [ $C-eqo]

then 

echo the number is even

 else 

echo the number is odd

fi


Execution commands:


skcet @sk-mca-53 ~$ geedit.oddeven.sh 

skcet @sc-mca-53~$sh add Even.sh.


Input:


Entel the number 6.


Ourput.


Number even


Result This program to iruplement add a oven was done


_---------


To find greatest of three number:


echo Enter three numbers a b and c.


read a b c


if[$a-gt $b-a $a- gt $c] 

then


echo $a is greater


elif [$ b -gt $c) 

then


echo $b is greater 

else 

echo $c in greater 

fi.


Execution: SECET@SC-MCA-53:~$ gedit greum.sh SKCET@SK-MCA-58 ~$grumish


Input: Enter three umbers ab and c<11>20


Ocutput: 20 is greater.


Result


Thers the shell program 3 tumbars is done to find greatest




-----------


To find factorial of number.


echo Enter the number


read num


n= $ num


fact =1


while [$ num-gt 0]


do


fact = $ ((fact * num))


num = & ((num-1))


done


echo $ fact is the factorial of $n


Commands :


SKCET@SK-Mea-53:~$ godit fact.sh


SKCET @SK-Mea-53 ~$ shfact sh


Enput:


Enter the number 5 Output.


120 is the factorial of 5


Result


Thus jactorial of shell program to find the the shell a give number was done




----------


FCFS-DISK SCHEDULING ALGORITHM


To stimulate First Come Fint Serve disk scheduling algorithm


ALGORITHM


1. Mark the head as the initial position of disk head.


Let request array represent an array storing indexes of track that have been requested in ascending order of their time of arrival


2. 11 services the 10 requests in the order in which they arrive. There is no starvation this algorithm, every request is serviced


3. The same process repeats.


Program :


FCFS DISK

#include <stdio.h>

#include <stdlib.h>

int main(){

int queue[100], q_size, head, seek =0, diff;

float avg;

printf("__DISK SCHEDULING__(FCFS)\n\n");

printf("%s\n", "Enter the size of the queue");

scanf("%d", &q_size);

printf("%s\n", "Enter queue elements");

for(int i=1; i<=q_size; i++){

scanf("%d",&queue[i]);

}

printf("%s\n","Enter initial head position");

scanf("%d", &head);

queue[0]=head;

for(int j=0; j<=q_size-1; j++){

diff = abs(queue[j]-queue[j+1]);

seek += diff;

}

printf("\nNumber of cylinders are %d\t",seek);

return 0;}


input

9

246 1105 4053 324 40 1739 32 2467 500

356



RESULT:


Thus, the C program to implement FCFS disk scheduling was successfully and the output was verified. implemented

