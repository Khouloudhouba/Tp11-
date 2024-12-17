 #include<stdio.h>
int mian(){ char matrix[5][5]={{'1','2','3','4','5'},
                                {'7','a','c','d','e'},
                                {'6','9','z','8','3'},
                                {'5','6','p','n','3'},
                                {'2','9','t','m','k'},
                                }
int i,j;
printf("full marix:\n");
for(i=0;i<5;i++){
for(J=0;j<5;J++){
   printf("%C",matrix[i][j]);

}
printf("\n") ;
}
for(i=0;i<5;i+=2){ 
   for(J=0;j<5;J++){
   printf("%C",matrix[i][j]);
   printf("\n");
}  
}
for(i=0;i<5;i++){
   for(J=0;j<5;J+=2){
   printf("%C",matrix[i][j]);

}
printf("\n") ;
}retun0;
}


}
