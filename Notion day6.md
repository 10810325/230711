# 230711
0727重點整理📄​
VS Code寫Python的常用插件
https://www.notion.so/Day-6-e1e250f8802a49f9b787bf258de2f9c2?pvs=4#f3172e3a3b1e449cb148afbe1e359171
使用matplotlib得先於Terminal(終端機)中用pip install matplotlib安裝

List
import matplotlib.pyplot as plt
plt.plot([1,2,3,4])
​

Numpy
import numpy as np
from matplotlib import pyplot as plt
x = np.arange(1,11)
y = x*x*x
plt.title("Matplotlib demo")
plt.xlabel("x axis caption")
plt.ylabel("y axis caption")
plt.plot(x,y)
plt.show()
​

import numpy as np
from matplotlib import pyplot as plt
x = np.arange(1,25)
y = x*x+100
plt.title("Matplotlib demo")
plt.xlabel("x axis caption")
plt.ylabel("y axis caption")
plt.plot(x)
plt.plot(y)
​

Pandas
import pandas as pd
series = pd.Series(y)
series.plot()
​

