# ProgrammingAssignment2
Catching the Inverse of a Matrix:
Matrix Inversion is considered to be a costly computation and there may be some benefits to catching the inverse of a matrix rather than compute it it.
PLease find SPECIAL MATRIX object that can cache its inverse:
makeCacheMatrix <- function (x = matrix()) {
    inv <- NULL
    set <- function (y) {
       x <<- y
       inv << - NULL
}
get <- function () x
setInverse <- function(inverse) inv <<- inverse
getInverse <- function() inv
list(set = set,
setInverse = setInverse
getInverse = getInverse

cacheSolve <- function(x,...) {
    inv <- x$getInverse()
    if (!is.null(inv)) {
       messaage ("getting catched data"
       return(inv)
}
mat <- x$get()
inv <- solve (mat,...)
x$setInverse(imv)
inv
}
