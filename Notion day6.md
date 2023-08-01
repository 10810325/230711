# 230711
0727重點整理📄​
VS Code寫Python的常用插件

使用matplotlib得先於Terminal(終端機)中用pip install matplotlib安裝
![Untitled](https://i.imgur.com/cWAj2GX.png)

List
import matplotlib.pyplot as plt
plt.plot([1,2,3,4])

​![Untitled](https://i.imgur.com/uxOi7ZI.png)

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

​![Untitled](https://i.imgur.com/5poXWqa.png)

import numpy as np
from matplotlib import pyplot as plt
x = np.arange(1,25)
y = x*x+100
plt.title("Matplotlib demo")
plt.xlabel("x axis caption")
plt.ylabel("y axis caption")
plt.plot(x)
plt.plot(y)

​![Untitled](https://i.imgur.com/1xw5Aly.png)

Pandas
import pandas as pd
series = pd.Series(y)
series.plot()

​![Untitled](https://i.imgur.com/m1PsoLf.png)

