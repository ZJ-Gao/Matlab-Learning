# Function

```text
% one variable
g = @(x) x^2
g(2)

% two variales
f = @(x,y) x+y
f (1,1)
```

```text
function[s]=my_sum(n)
s=0;
for i=1:n
    s=s+i;
end
```

 注意：函数名（my\_sum）必须与文件名（my\_sum.m）一致  
调用函数的时候函数文件放在当前工作目录下面。

命令行加在语句结尾加上分号可以抑制输出，比如，一个矩阵或者变量值得末尾加分号可以抑制输出

[https://blog.csdn.net/kangkanglhb88008/article/details/84173311](https://blog.csdn.net/kangkanglhb88008/article/details/84173311)

