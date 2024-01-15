#include <stdio.h>
#include <math.h>

int cnt[1000001]={0};

int main(){
	int a[100], n;
	scanf("%d", &n);
	for(int i=0; i<n; i++){
		scanf("%d", &a[i]);
	}
	
	for(int i=0; i<n; i++){
		cnt[a[i]]++;
	}
	
	for(int i=0; i<n; i++){
		if(cnt[a[i]]!=0){
			printf("%d %d\n", a[i], cnt[a[i]]);
			cnt[a[i]]=0;
		}
	}
}
	
	
	
	
