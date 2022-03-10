## .converge()

# 🔬

If you think back to a high school algebra class, you may recall seeing equations where the goal was to find the value of an unknown variable, such as *x*. In more advanced applications, we are still interested in solving equations. For certain phenomena we wish to investigate, we can’t neatly solve for *x* by simply rearranging a formula. Instead we must use more advanced techniques. A common objective for problems in a field known as optimization is to find the minimum value of a function, which we approach in an iterative fashion.

In this card, it would be the bottom of right hand valley. We can make a *numerical approximation* to the solution by applying a technique known as gradient descent. We start at a given point, work out how steep it is (the *gradient*) and move in the direction of the gradient by a small amount proportional to the gradient (the *descent*). If it is steep, we’ll take a big step, and if it is almost flat, we’ll take a small step. When we are approaching the lowest point, we know we are getting close when the size of our steps gets progressively smaller. When our progress becomes sufficiently slow, we can declare victory and report back the result. 

You will notice that there are three shades of colors of dots: one at the hump between the valleys, and one color on the descent to each valley. This is known as a *non-convex* function, which has more than one minimum value. If we are on the hump point, we can go either left or right. If we go left, we will find a *local minimum*, which is the smallest value relative to its immediate neighborhood, but because we took a wrong turn, it is not the lowest value. This shows that while you will find a solution, there are some places to start that are better than others.

# 🧩

Many of the problems we encounter in life arise out of complex and ambiguous systems, which we cannot possibly understand fully. When we are interacting with such systems, we may start off with an expectation for where we want to end up, and make our best guess of a starting point. While we may wish to teleport directly to our desired end state, we can realistically move there only by taking incremental steps towards it, and gain more information about the direction to take as we make progress. 

# 🖋️

- Think back to a time when you’ve been unsure of the path to a goal you’ve had. What are some examples of the adjustments you’ve made based on receiving new information along the way?

# 📚

[Watch](https://www.youtube.com/watch?v=IHZwWFHWa-w) this beautiful video about Gradient Descent.

Return [home](../index.md).
