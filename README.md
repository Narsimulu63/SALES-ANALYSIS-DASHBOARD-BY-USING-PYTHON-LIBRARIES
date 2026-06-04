# SALES-ANALYSIS-DASHBOARD-BY-USING-PYTHON-LIBRARIES
Sales Analysis Dashboard using Python  This project is a Sales Analysis Dashboard developed using Python to analyze and visualize sales data. The dashboard provides valuable business insights by transforming raw sales data into interactive charts and reports.


FEATURES
Sales performance analysis
Monthly and yearly sales trends
Product-wise sales analysis
Revenue and profit visualization
Top-performing products identification
Interactive data visualizations
Business insights for decision-making

TECHNOLOGY USED
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook

PROJECT OBJECTIVE

The main objective of this project is to analyze sales data, identify trends and patterns, and help businesses make data-driven decisions through effective data visualization and reporting.

JUPITER NOTES

import pandas as pd                                                          
import numpy as np                                                  

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

X= [20000,25000,30000,35000,40000,85000,50000,75000,60000,65000,70000,150000]
Y=[['JAN','FEB','MARCH','APR','MAY','JUNE','JULY','SEP','OCT','NOV','DEC']]

total=np.sum(sales)  
maximum=np.max(sales) 
minimum=np.min(sales)
average=np.mean(sales)

print("total sales:",total)
print("maximum sales:",maximum)
print("minimum:",minimum)
print("average:",average)
plt.figure(facecolor='lightblue')
plt.plot(month, sales, marker='o')
plt.title ("DMART SALES")
plt.xlabel("month")
plt.ylabel("sales")
plt.show()
import matplotlib.pyplot as plt

sales = [2000000,2200000,3300000,150000,12300,130000,
         230000,123334,2344434,2424443,56577566,34445345]

month = ['Jan','Feb','March','April','May','June',
         'July','Aug','Sept','Oct','Nov','Dec']

plt.plot(month, sales, color='blue')

plt.title("DMART SALES")
plt.xlabel("Month")
plt.ylabel("Sales")

plt.show()


# I need 4 months sales
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

x = [20000,23000,34000,50000]
y = ['jan','Feb','March','April']

plt.plot(x,y)
plt.title("4 Months Sales")
plt.show()



#SALES

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

X= [20000,25000,30000,35000,40000,85000,50000,75000,60000,65000,70000,150000]
Y=[['JAN','FEB','MARCH','APR','MAY','JUNE','JULY','SEP','OCT','NOV','DEC']]

total=np.sum(sales)  
maximum=np.max(sales) 
minimum=np.min(sales)
average=np.mean(sales)

print("total sales:",total)
print("maximum sales:",maximum)
print("minimum:",minimum)
print("average:",average)
plt.figure(facecolor='lightblue')
plt.plot(month, sales, marker='o')
plt.title ("DMART SALES")
plt.xlabel("month")
plt.ylabel("sales")
plt.show()

# TOP  3 SALLING PRODUCTS

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
y=[200000,150000,180000,700000]
x = (['cloths','electronics products','home material ', 'grocessary'])

plt.bar(x,y)
print("Top 3 products:"'grocessary','cloths','home material')
plt.title("TOP 3 PRODUCTS SELLING")
plt.xlabel("Products Sales")
plt.ylabel("Sales")
plt.show()


# sales by category

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
sales=[200000,150000,180000,700000]
category=(['cloths','electronics','home material','grocessary'])

plt.pie(sales,labels=category, autopct='%1.4f%%')
plt.title("SALES BY CATEGORY")
plt.show()


#Order to Distribution on histogram 

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

sales=[200000,150000,180000,700000]
plt.hist(sales,bins=2)
plt.title("Distribution on sales")
plt.show()







