# R data Types
- atomic classes: numeric, logical, character, integer, complex
- vectors,lists
- factors
- missing values
- data frames
- names


##Explicit Coercion
x <- 0:6
class(x)
as.numeric(x)
as.logical(x)
as.character(x)

##List
x<-list(1,"a",TRUE,1+4i)
x

##Matrices : Special type of vectors with dimensions
m <- matrix(nrow=2,ncol=3)
m
dim(m)
attributes(m)
m<-matrix(1:6, nrow=2, ncol=3)
m

## Creating Matrix using dim() function
m<-1:10
m
dim(m)<-c(2,5)
m

## Creating a Matrix using cbind and rbind function
x<-1:3
y<-10:12
cbind(x,y)

## Factor is a spl type of data that is used to represent categorical data
x<-factor(c("yes","yes","no","yes","no"))
x
table(x)
unclass(x)

#setting factor levels -userdefined-
x<-factor(c("yes","yes","no","yes","no"),levels = c("yes","no"))
x

## Missing Values
# Na and NAN is used for undefined maths equation
is.na() -> NA ## is used to test objects if they are NA and Na values have a class also, so there are integer NA, character NA, etc.
is.nan() ->NaN ## a NAN value is also NA but the converse is not true

## Data Frame are used to store table data.
* It has a spl attribute called row.names()
* Data Frames are usually created by calling read.table() or read.csv()
* Can be concerted to a matrix by calling data.matrix()
x<-data.frame(foo=1:4, bar=c(T,T,F,F))
x
