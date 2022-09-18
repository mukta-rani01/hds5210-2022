# Feedback

Refer to the homework rubric posted on Canvas (https://canvas.slu.edu/courses/28045/rubrics/23670) for additional notes on the approach I take to grading weekly assignments. Basically, you'll receive 4 points for correctness of your multiple choice responses, 4 points for correctness of the programming exercises, and 2 points based on your level of programming "craft", i.e. Did you use good variable names, format code in a way that was easy to read, etc.

You will see your grades with a brief explanation in Canvas.

If I have more substantial feedback or what to show you code examples / corrections, I'll post them in a file like this back to your repository.  You'll need to make sure you do a `git pull` in your Jupyter repository to retrieve my comments before you can submit your next batch of exercises.

# Your density function

You wrote:
```python
def density=mass/unit volume
   ### begin solution
    density = mass_kg/volume***3
    ### end solution
     return =density
```

Here are some issues, line by line.
1. A function definition takes the form `def function_name(parameter1, parameter2):`
2. Your calculation of density looks like you're saying "mass divided by volume cubed" but that wouldn't be correct. Density is just "mass divided by volume"
3. The syntax for "cubed" or "to the power of 3" is just `x**3`
4. When you return a value from a function, you don't say `return = variable`, just `return variable`
5. Your indenting has to be perfectly consistent to work in Python