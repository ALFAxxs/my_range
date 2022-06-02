#include<stdio.h>
#include<stdlib.h>

int* my_range (int Min_included, int max_included){
  int *res;
  res =(int*)malloc((max_inluded-min_inluded)*sizeof(int));
  int index =0;
  
  for (int i=min_inluded; i < max_inluded; i++){
    res[index]=i;
    index++;
  }
  return res; 
}
