#include<stdio.h>
#include<conio.h>

void display(int arr[],int n){ //Traversal
    
    for (int i = 0; i < n; i++)
    {   
        printf("%d ",arr[i]);
    }
    printf("\n");
}

int indInsertion(int arr[],int size,int element,int capacity,int index){
    if(size>=capacity){
        return -1;
    }
    for (int i = size-1; i >= index; i--)
    {
        /* code */
        arr[i+1]=arr[i];

    }
    arr[index]=element; //Insert element in place of that index
    return 1;
}

int main()
{
    /* code */
    int arr[100]={7,8,12,27,88};
    int size=5,element=45,index=3;
    display(arr,size);
    indInsertion(arr,size,element,100,index);
    size+=1; //First it had 5 elements after insertion it would have 6 elements
    display(arr,size);
    return 0;
}
