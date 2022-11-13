#include<stdio.h>
int max(int a[],int n){
	int sum,i,j,t;
	t=a[0];
	for(i=0;i<n;i++){
		sum=0;
		for(j=i;j<n;j++){
			sum+=a[j];
			if(sum>t) t=sum;
		}
	}
	return t;
}
int main(){
	int n,a[100],i,sum;
	scanf("%d",&n);
	for(i=0;i<n;i++)
		scanf("%d",&a[i]);
	sum=max(a,n);
	if(sum<0) printf("0");
	else printf("%d",sum);
	return 0;
}
