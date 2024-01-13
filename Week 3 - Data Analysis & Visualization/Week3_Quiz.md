# Week 3 - Data Analysis & Visualization - Review Quiz

1. Which of the followings are examples of categorical data?
- [x] Neighborhood
- [ ] Number of cars
- [ ] Net income
- [x] Gender

2. Given a DataFrame `df`, how do we access the row with index 'row_1'?
- [ ] `df.iloc['row_1']`
- [x] `df.loc['row_1']`
- [ ] `df.iloc[row_1]`
- [ ] `df.loc[row_1]`

3. Given a DataFrame df, how do we drop the rows where all values are NaN?
- [ ] `df.dropna()`
- [ ] `df.dropna(how='full')`
- [x] `df.dropna(how='all')`
- [ ] `df.dropna(how='all',axis=1)`

4. You are asked to create a line plot using matplotlib (already aliased as plt). Which line of code will be included in your program?
- [x] `plt.plot([1, 2, 3, 4, 5])`
- [ ] `plt.scatter([1, 2, 3, 4, 5])`
- [ ] `plt.bar([1, 2, 3, 4, 5])`
- [ ] `plt.pie([1, 2, 3, 4, 5])`

5. In matplotlib (already aliased as plt), how can you set the labels of the axes?
- [ ] `plt.set_xlabel('Name of the X-axis')` and `plt.set_ylabel('Name of the Y-axis')`
- [x] `plt.xlabel('Name of the X-axis')` and `plt.ylabel('Name of the Y-axis')`