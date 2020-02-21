---
description: 2/21/2020
---

# Practice

## Practice \#1

Calculate:  $$x = 1 -1/2 +1/3-1/4 +1/5...-1/10$$ 

```text
%% Method_1-------------------------
sum_o = 0
sum_e = 0
for idx = [1:2:9]
    sum_o = 1/idx + sum_o
end

for idx = [2:2:10]
    sum_e = 1/idx +sum_e
end

%% Method_2-------------------------
x = 0 
for idx = [1 :10]
    x = x + (-1)^(idx+1)*1/idx
end

%% Method_2_2 Use array x to store results
x(1)= 1
for idx = [2 :10]
    x(idx) = x(idx-1) + (-1)^(idx+1)*1/idx
end

%% Method_2_3 More detailed steps
n = 10
x = zeros(n, 1)
for idx = [2 :n]
    x(idx) = x(idx-1) + (-1)^(idx+1)*1/idx
end
```

### small tips

* root square: sqrt\(x\)
* round float : e.g  round\(pi, 4\) % keep 4 decimals



