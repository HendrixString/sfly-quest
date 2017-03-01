## Canvas control Points in Android

hi there, in this assignment, you will design a custom layout component for
**Android** which we will call **Pit** from now on.

### general description of `Pit`:
* pit is a ViewGroup that renders an interactive horizontal 2D graph of points, between every point there is
a connected edge (linear edge).
* every point of Pit is draggable.
* Pit also draws the Origin axis lines
* when a point is dragged, the view is rendered again in order to show the edges,
that means Pit is responsive :)
* Pit also has a very unique feature, the reordering feature which goes like this:
if a user drags a point before or after another point, then Pit will change that point
order and therefore the edges will still render beautifully.
* Pit should have an interface to add point/s. every point is added at the origin axis (0, 0)

### restrictions of `Pit`:
* :warning: you **cannot use the built in Android drag functionality (i.e View.startDrag() etc..)**, you will have to write your own
drag logic with the help of your own custom `OnTouchListener`.
* :warning: each point can be extended from View itself, but you can also implement it otherwise (which will be
harder, but might be more efficient).

### Pit should be inside a very humble activity
* the activity should have a pit layout inside and a button to add a point into pit.
* Pit should start with 5 different initial points.

### Things we love to see
:heart: docs and comments for each new method.  
:heart: we love optimal code and memory optimizations.  
:heart: we love to see a programmer gainining deep insights about what he is programming.  
:heart: that means we love great practices  
:heart: but also feel free to be creative when you feel the time is right.  
:heart: we love communication. don't hesitate to ask questions and boldly asking questions
about your assignment.  
:heart: coolness and attitude, don't feel bad if you don't hit your goals, we will still consider
your efforts :2nd_place_medal:

### illustration of Pit

<div align="center"><img src="https://vectr.com/hendrixstring/f1BaUwHxiD.png?width=320&height=320&select=f1BaUwHxiDpage0"></div>

### How to submit Pit?
confidently open a github account if you don't have one, create a repository, push all of your code into the repository
and notify us when you are done. :octocat:

### Who wrote this thing ?
me, Tomer Shalev, feel free to open issues or to bash me if you don't like this assignment :writing_hand:
