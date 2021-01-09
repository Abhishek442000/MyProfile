# MyProfile
## abhishek

* Item 1
* Item 2
  * item 3
  * item 4
1. item 1
2. item 2
   * item 2a 
   * item 2b

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSdlIfNYC2ChIWeE_ZpBL8aGeXG9nAclWNVIg&usqp=CAU)




[Google tokyo ghoul](https://www.google.com/search?q=tokyo+ghoul&tbm=isch&ved=2ahUKEwj2uZj1o47uAhVESXwKHY5eCfoQ2-cCegQIABAA&oq=tok&gs_lcp=CgNpbWcQARgAMgcIABCxAxBDMgcIABCxAxBDMgQIABBDMgQIABBDMgcIABCxAxBDMgQIABBDMgQIABBDMgQIABBDMgQIABBDMgUIABCxAzoICAAQsQMQgwE6AggAUJWwB1jdtgdgi8EHaABwAHgAgAFdiAGHApIBATOYAQCgAQGqAQtnd3Mtd2l6LWltZ8ABAQ&sclient=img&ei=1FT5X_b_GMSS8QOOvaXQDw&bih=657&biw=1366&rlz=1C1GCEU_enIN892IN892#imgrc=8FGrcB4GLnBqVM)


``` 
#include <iostream>
using namespace std;

int main() {
	int n,a[n];
	cin>>n;
	for(int i=0;i<n;i++){
	    cin>>a[i];
	}
	int count =0;
	for(int i=0;i<n-1;i++){
	    while(a[i+1]<a[i]){
	        a[i+1]++;
	        count++;
	    }
	}
	cout << count << endl;
}
```
