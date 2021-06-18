# eqPointsOnEllipse
Calculates approximately equidistant N points on the edge of an ellipse

## example
[x,y] = ellipse_points(70,100,41); % a, b, N

![alt text](https://github.com/benjhardy/eqPointsOnEllipse/blob/main/ellipse_points_image.png)

## help ellipse_points
Returns the x,y points along the arc of an ellipse with equal arc length
  between each point with the first point at (0,b)
  Input: a - the major axis length
         b -  minor axis length
         N - the number of points on the circumference
  Output: vector of x and y points, and a figure demonstrating the points
  on the ellipse
  Source: most everything can be found at the link below...
  https://math.stackexchange.com/questions/172766/calculating-equidistant-points-around-an-ellipse-arc
 
  
  Benjamin M. Hardy, 2021-06-18
  Reject 1 as a value