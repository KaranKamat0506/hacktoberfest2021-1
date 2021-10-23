#include<stdio.h>
#include<conio.h>

void display(int arr[],int n){ //Traversal
    
    for (int i = 0; i < n; i++)
    {   
        printf("%d ",arr[i]);
    }
    printf("\n");
}

void indDeletion(int arr[],int size,int index){
    
    for (int i = index; i < size-1; i++)
    {
        /* code */
        arr[i]=arr[i+1];

    }
}

int main()
{
    /* code */
    int arr[100]={7,8,12,27,88};
    int size=5,index=0;
    display(arr,size);
    indDeletion(arr,size,index);
    size-=1; //First it had 5 elements after deletion it would have 4 elements
    display(arr,size);
    return 0;
}

