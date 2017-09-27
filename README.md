# Brady-BunchJupyter NotebookLogout Brady Bunch Quiz Last Checkpoint: 5 minutes ago (autosaved) Python 3
Python 3 Trusted
File
Edit
View
Insert
Cell
Kernel
Widgets
Help

In [9]:

statistics
import pandas as pd
import numpy as np
import statistics
In [32]:

brady_kids
brady_kids = [14,12,11,10,8,6,8]
np.mean(brady_kids)
​
Out[32]:
9.8571428571428577
In [33]:

kids)
np.median(brady_kids)
Out[33]:
10.0
In [34]:

kids
statistics.mode(brady_kids)
Out[34]:
8
In [35]:

brady_kids
np.var(brady_kids)
Out[35]:
6.408163265306122
In [36]:

kids
np.std(brady_kids)
Out[36]:
2.5314350209527641
In [38]:

)
np.std(brady_kids)/ (len(brady_kids)-1)
Out[38]:
0.42190583682546068
In [40]:

#2. I would pick the mean as the one estimate of central tendency because there are no real outliers in the dataset
#I would pick the standard deviation as the one estimate of variance because it provides a tangible number showing how just two data points are more than one sd away from the mean
​
brady_kids2 = [14,12,11,10,8,7,8]
In [41]:

np.mean(brady_kids2)
Out[41]:
10.0
In [42]:

brady_kids2)
np.median(brady_kids2)
Out[42]:
10.0
In [43]:

)
statistics.mode(brady_kids2)
Out[43]:
8
In [44]:

_kids2)
np.var(brady_kids2)
Out[44]:
5.4285714285714288
In [45]:

_kids2)
np.std(brady_kids2)
Out[45]:
2.3299294900428702
In [47]:

np.std(brady_kids2)/(len(brady_kids2)-1)
np.std(brady_kids2)/(len(brady_kids2)-1)
Out[47]:
0.3883215816738117
In [48]:

#The median and mode stayed the same while all other values were slightly altered.
jessica = [14,12,11,10,8,7,1]
np.mean(jessica)
Out[48]:
9.0
In [50]:

np.median(jessica)
Out[50]:
10.0
In [27]:

 Mode
statistics.mode(df['Jessica'])
#No Mode
---------------------------------------------------------------------------
StatisticsError                           Traceback (most recent call last)
<ipython-input-27-53dc8d879b00> in <module>()
----> 1 statistics.mode(df['Jessica'])

C:\Users\Connor\Anaconda3\lib\statistics.py in mode(data)
    505     elif table:
    506         raise StatisticsError(
--> 507                 'no unique mode; found %d equally common values' % len(table)
    508                 )
    509     else:

StatisticsError: no unique mode; found 7 equally common values

In [51]:

jessica
np.var(jessica)
Out[51]:
15.428571428571429
In [52]:

jessica
np.std(jessica)
Out[52]:
3.927922024247863
In [55]:

-1
np.std(jessica)/(len(jessica)-1)
Out[55]:
0.6546536707079772
In [57]:

/3
#In this dataset I would use the median instead of the mean because due to the 1 year outlier it more accurately represents the data.
#I would still use standard deviation
​
#Sci magazine represents niche market so we can probably throw out that data and use mean of next three numbers.
(23+20+17)/3
Out[57]:
20.0
In [ ]:

#Expect 20% of population to be interested.
