# (5-1)lecture summary 

2019732074 배성환  

___State Variables___  
___Inputs->States->Outputs___  
미분방정식안에 의미를 부여하고 싶은부분에 state 정의하고 푼다
state 중심으로 문제를 풀고 컴퓨터에 쉽게 일을 주기 위해 사용한다  
![image](https://github.com/seonghwan128/5weeks/assets/144310820/2cca2d6b-ca0a-45e8-abd5-d2564d775301)
![image](https://github.com/seonghwan128/5weeks/assets/144310820/9772d158-b26e-41b6-ae8a-d7189fcee060)  

___1st order state differential equation___  
If we define states, the differential equation is derived as
$\dot{x}(t) = ax(t) + bu(t)$  
$sX(s)-x(0)=aX(s)+bU(s)$  
$(s-a)X(s)=x(0)+bU(s)$  
$X(s)=\frac{1}{s-a}x(0)+\frac{1}{s-a}bU(s)$  
$x(t)=e^{at}x(0)+\int e^{a(t-\tau )}bu(\tau)d\tau$  
$x(t)=\Phi(t)*x(0) + \int\Phi(t-\tau)bu(\tau)dt $  
Transition from initial state / Effect of input  
Much more Meaningful!  



___State vector and state space equation___  
  state differential equation(다차미분방정식-> 여래개의 일차미방으로 바꿔서 일차행렬미분방정식
식)  
$\dot{x}(t) = Ax(t) + Bu(t)$

Output equation (state들과 input 조합해서 만드는것)  
$y(t) = Cx(t) + Du(t)$

장점 -컴퓨터에 시키기 쉽다  

![image](https://github.com/seonghwan128/5weeks/assets/144310820/a75c7781-a689-4494-b0c4-f4beffbdd383)  

![image](https://github.com/seonghwan128/5weeks/assets/144310820/b70eed30-9f1b-4877-a427-92326410e6fa)

![image](https://github.com/seonghwan128/5weeks/assets/144310820/368e8f03-e524-40b8-b89f-982b1d2d3fb1)















