# anas///Bubble Sort.....
#include <iostream>


using namespace std;


int main()

{
   
 char name[7]="people";
    
int i,j,n=6,c=0,d=0;
    
for(i=1;i<n;i++)
   
 {
     
   for(j=0;j<n-i;j++)
      
  {   
 c++;
           
 if(name[j]>name[j+1])
           
      
     {
             
  swap(name[j],name[j+1]);
       
     d++;
               
           }
            
       
 }
   
 }
    
printf("After Bubble Sort:  %s\nIteration No :%d \nInterchange No:%d",name,c,d);

return 0;
}
