#include <iostream>
using namespace std;
int j;
bool linearsearch(int arr[],int size,int key){
    for (int i = 0; i < size; i++)          
    { 
        if (arr[i]==key)
        {    j=i;
            return 1;
        }
        
    }
    return 0;
}

int main(int argc, char const *argv[])
{int k;
   int array[10]={1,3,4,5,6,-1,0,22,-2,21};
   cout<<"enter the key"<<endl;
   cin>>k;
   bool Output =linearsearch(array,10,k);
   if (Output)
   {
    cout<<"Key is found at index " << j<<endl;
   }
   else{
    cout<<"No key found"<<endl;
   }
   
    return 0;
}
