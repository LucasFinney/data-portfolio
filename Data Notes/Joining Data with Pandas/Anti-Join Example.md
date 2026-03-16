```python
# Imports for Obsidian
import micropip
await micropip.install("pandas")

import pandas as pd
data1 = {"a":[1,2,3,4], "b":[5,6,7,8]}
data2 = {"b":[5,7,9,10], "c":[9,10,11,12]}
df1 = pd.DataFrame(data1)
df2 = pd.DataFrame(data2)

# Merge with an indicator
df3 = df1.merge(df2, on="b", how="left", indicator=True)
# Create a filter
f = df3["_merge"]=="left_only"
# Create the filtered DF1
df1 = df1.loc[f]

print(df1)
```





