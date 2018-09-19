# DA_Assignment_7.2
Create a scatterplot matrix by gear types in mtcars dataset.
> scatterplotMatrix(~mpg+disp+drat+wt|gear,
+                   data=mtcars,
+                   main="Three Gear Options")

Write a program to create barplots for all the categorical columns in mtcars.
> boxplot(mtcars$mpg, col = 'red', main = "boxplot of Mpg")
> boxplot(mtcars$cyl, col = 'red', main = "boxplot of cyl")
> boxplot(mtcars$gear, col = 'red', main = "boxplot of cyl")
> boxplot(mtcars$disp, col = 'red', main = "boxplot of disp")
> boxplot(mtcars$hp, col = 'red', main = "boxplot of Hourse Power")
> boxplot(mtcars$drat, col = 'red', main = "boxplot of drat")
> boxplot(mtcars$wt, col = 'red', main = "boxplot of wt")
> boxplot(mtcars$qsec, col = 'red', main = "boxplot of qsec")
> boxplot(mtcars$vs, col = 'red', main = "boxplot of vs")
> boxplot(mtcars$carb, col = 'red', main = "boxplot of carb")
