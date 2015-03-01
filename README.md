# Second-Price-Auction
#include &lt;iostream> #include &lt;algorithm> using namespace std; int main () { int i,s=0; cin>>i; int *a= new int [i]; for (int j=0;j&lt;i;j++) { cin>>a[j]; } for(int k=1 ;k&lt;i;k++) { if (a[k]>a[k-1]) { s=k; } }  sort(a,a+i); cout&lt;&lt;s+1&lt;&lt;' '&lt;&lt;a[i-2]&lt;&lt;endl; return 0; }
