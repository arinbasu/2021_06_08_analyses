

```python
import pandas as pd
import matplotlib.pyplot as plt
```


```python
x = [1,2,3,4,5]
y = [4,5,6,7,8]
xydata = pd.DataFrame({"x": x,
                       "y" : y})
xydata.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>x</th>
      <th>y</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>4</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>5</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>6</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>7</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>8</td>
    </tr>
  </tbody>
</table>
</div>




```python
%matplotlib inline
plt.plot(x,y)
plt.scatter(x,y)
plt.title("X and Y plotted")
```




    Text(0.5, 1.0, 'X and Y plotted')




![png](2021_06_08_analyses_2_1.png)


## The Goal
Goal of this analysis is to develop a machine learning pathway for identification of the best classifying scheme. 
