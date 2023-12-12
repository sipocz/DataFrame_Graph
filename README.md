# DataFrame_Graph
DataFrame to Graph
~~~
!wget "https://raw.githubusercontent.com/sipocz/DataFrame_Graph/main/grafikon.py"

from grafikon import grafikon

import pandas as pd    
    
    
df=pd.DataFrame(data={"x":[1,2,3,4,5,6],"y":[22,33,44,55,66,77]})
    
 
plt1=grafikon(df,"y","y_desc", "x","x_desc",n_graf=2,x="x",x_label="x", title="Hallo World", title_2="teszt_1")

li=[99,45,32,12,39]
plt2=grafikon(li,"y","y_desc",x_label="xdata")
plt1.show()
plt2.show()
~~~
