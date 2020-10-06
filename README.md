[![hackmd-github-sync-badge](https://hackmd.io/MVncTd4zQUeAirFL-UyefA/badge)](https://hackmd.io/MVncTd4zQUeAirFL-UyefA)
## HEADERS

* 心累累 *


# 20200929-test
## 20200929-test
### 20200929-test
#### 20200929-test
##### 20200929-test
###### 20200929-test

## EMPHASIS

*This test will be italic*

_This test will be italic_

**This test will be bold**

__This will also be bold__

*You **can** combine them*

## LISTS
### Unorderd

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Odered

1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b
  
## IMAGES
![Cute dog](./wadog.gif "內有惡犬")

## LINKS
https://www.nkust.edu.tw/
[國立高雄科技大學](https://www.nkust.edu.tw/)


## BLOCKQUOTES

As Kanye West said:
> We're Living the futures so
> the present is our past.

## BACKSLASH ESCAPES
\* literal asterisks\*

\( literal asterisks\)

\{ literal asterisks\}

## TASK LISTS

- [x] @mentions , #refs, [links](),

- [ ] this incomplete

## FENCED CODE BLOCKS

### `javascript 數字與字串相加`

``` javascript
var x, y, z;  // Declare 3 variables
x = 5;    // Assign the value 5 to x
y = 6;    // Assign the value 6 to y
z = x + y;  // Assign the sum of x and y to z

document.getElementById("demo").innerHTML ="The value of z is " + z + ".";

var carName1 = "Volvo-XC60";
var carName2 = 'Volvo-XC63';

document.getElementById("demo").innerHTML = carName1 + " " + carName2; 

```
### `python-SVM code`

``` python
import numpy as np
import cvxopt
from sklearn.datasets.samples_generator import make_blobs
from sklearn.model_selection import train_test_split
from matplotlib import pyplot as plt
from sklearn.svm import LinearSVC
from sklearn.metrics import confusion_matrix

class SVM:
def fit(self, X, y):
        n_samples, n_features = X.shape
# P = X^T X
        K = np.zeros((n_samples, n_samples))
        for i in range(n_samples):
            for j in range(n_samples):
                K[i,j] = np.dot(X[i], X[j])
P = cvxopt.matrix(np.outer(y, y) * K)

```
### `Markdown-數學公式`

``` markdown
$$ \sideset{^1_2}{^3_4}\bigotimes $$

$$ f(x,y,z) = 3y^2z \left( 3+\frac{7x+5}{1+y^2} \right) $$

$$ \left. \frac{{\rm d}u}{{\rm d}x} \right| _{x=0} $$

$$\frac{a-1}{b-1} \quad and \quad {a+1\over b+1}$$

$$ f(x_1,x_2,\underbrace{\ldots}_{\rm ldots} ,x_n) = x_1^2 + x_2^2 + \underbrace{\cdots}_{\rm cdots} + x_n^2 $$

$$ \lim_{n \to +\infty} \frac{1}{n(n+1)} \quad and \quad \lim_{x\leftarrow{sample}} \frac{1}{n(n+1)} $$

$$\sum_{i=1}^n \frac{1}{i^2} \quad and \quad \prod_{i=1}^n \frac{1}{i^2} \quad and \quad \bigcup_{i=1}^{2} R$$

```

## `TABLES`

| Frist | Second | Third |
|:----|:-------:|------:|
| cell 1 |cell 2 | number cell 3 |
| cell 1 |cell 2 | number cell 3 |
| cell 1 |cell 2 | number cell 3 |
| cell 1 |cell 2 | number cell 3 |
| cell 1 |cell 2 | number cell 3 |

## `enmotion`
bqcaihong,1=&#x1F308;

bqcaomei,1=&#x1F353;

bqdianhua,1=&#x1F4DE;

bqfengye,1=&#x1F341;

bqjiaoyin,1=&#x1F463;

bqlaba,1=&#x1F4E3;

bqmuzhi,1=&#x1F44D;

bqok,1=&#x1F44C;

bqpg,1=&#x1F34E; 

bqpg,2=&#x1F34F;

bqriqi,1=&#x1F4C6;

bqriqi,2=&#x1F4C5;

bqshijian,1=&#x1F554; 

bqshouzhi,1=&#x1F449; 

bqsongshu,1=&#x1F332;

bqtongji,1=&#x1F4CA; 

bqwenhao,1=&#x2753; 

bqwenjianjia,1=&#x1F4C2;

bqxigua,1=&#x1F349; 

bqyouxiang,1=&#x1F4E7;

bqzhibo,1=&#x1F3A6;

