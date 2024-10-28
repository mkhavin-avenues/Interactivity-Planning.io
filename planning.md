The two objects in this program will be:
  Object A: A circle with properties including x and y coordinates for its center and a radius.
  Object B: A rectangle with properties including x and y coordinates for its top-left corner, width, and height.

Conditions for Touching:
  To detect when the circle and rectangle are touching, the following conditions will be checked:

Circle-Rectangle Overlap Detection:
  Calculate the closest point on the rectangle to the center of the circle.
  Determine if this closest point is within the circle’s radius.
  If the distance from the closest point to the circle’s center is less than or equal to the circle’s radius, the circle and rectangle are considered touching.
Interaction Outcome:
  When the circle and rectangle are detected as touching:

Bounce Effect:
  The circle’s dx and dy (horizontal and vertical movement deltas) will reverse to simulate a bounce.
  This is achieved by swapping the dx and dy values for both objects and applying a negative sign to each (e.g., dx = -dx, dy = -dy).
