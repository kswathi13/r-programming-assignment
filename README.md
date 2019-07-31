# r-programming-assignment
 makeCacheMatrix &lt;- function(x = matrix()) { invmatrix &lt;- NULL setMatrix &lt;- function(y) { x &lt;&lt;- y invmatrix &lt;&lt;- NULL }  getmatrix &lt;- function() x setinverse &lt;- function(inverse) invmatrix &lt;&lt;- inverse getinverse &lt;- function() invmatrix list(setmatrix = setmatrix, getmatrix = getmatrix, setnverse = setinverse, getinverse = getinverse) }
