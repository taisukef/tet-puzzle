# tet-puzzle

https://user-images.githubusercontent.com/1715217/124520458-86b48380-de27-11eb-8a21-39c17e5f4a7b.mp4

- https://taisukef.github.io/tet-puzzle/
- https://fukuno.jig.jp/3267

## 6 lines program in JavaScript

```js
<body onload='onkeydown=e=>K=parseInt(e.key[5]||6,28)/3-8;Z=X=[B=A=12];Y=_=>{
for(C=[q=c=i=4];f=i--*K;c-=!Z[h+(K+6?p+K:C[i]=p*A-(p/9|0)*145)])p=B[i];for(c?0:
K+6?h+=K:B=C;i=K=q--;f+=Z[A+p])X[p=h+B[q]]=1;h+=A;if(f|B)for(Z=X,X=[l=228],B=[[
-7,-20,6,h=17,-9,3,3][t=++t%7]-4,0,1,t-6?-A:2];l--;)for(l%A?l-=l%A*!Z[l]:(P++,
c=l+=A);--c>A;)Z[c]=Z[c-A];for(S="";i<240;S+=X[i]|(X[i]=Z[i]|=++i%A<2|i>228)?i%
A?"■":"■<br>":"　");D.innerHTML=S+P;setTimeout(Y,i-P)};Y(h=K=t=P=0)'id=D>
```



