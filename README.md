# homework3_14_16
# 수치해석(Matlab)
# polyfit

![14 4-1](https://user-images.githubusercontent.com/58453290/70115764-11f5f200-16a4-11ea-86ec-ab2d37bea122.JPG)

![14 4-2](https://user-images.githubusercontent.com/58453290/70115769-13bfb580-16a4-11ea-817b-43541b015246.JPG)

![14 4-16](https://user-images.githubusercontent.com/58453290/70115772-14f0e280-16a4-11ea-826a-52348f5a3b64.JPG)


## 데이터
x=[2 4 6 7 10 11 14 17 20];

y=[4 5 6 5 8 8 6 9 12];
## 구간나누기
x0=linspace(1,20,20);

s=[x y];
## polyfit
polyfit(x,y,1)

f=3.2807+0.3678*x0;
## 보이기
plot(x0,f)

hold

plot(x,y,'o')

![noname02](https://user-images.githubusercontent.com/58453290/70115776-17533c80-16a4-11ea-9570-130e25f67c52.png)

