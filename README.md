# NYC-Trees
NYC TNC mapping trees

*This is a repository!

library(raster)

library(rgdal)

a <- raster("")

plot(a)

b <- readOGR("")

plot(b, add=TRUE)

this_is_my_function <- function(x){
abx <- a*b*x
print(abx)
}

new_var <- this_is_my_function(17)

class(new_var)
