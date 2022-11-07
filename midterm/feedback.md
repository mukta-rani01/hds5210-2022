# Notes on the Midterm

* _Correctness    (out of 40):_ 36
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 0

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

The instructions stated that each function should have docstrings and test code. Since yours did not, I deducted 10 points from the _Docs / Testing_ category.

## Step 1
* Nice work. Easy to read and follow.

## Step 2
* This looks great. Works nicely.

## Step 3
* Rather than repeating all of the code from `get_rate()` you should have just called `get_rate()`. I deducted 1 point from _Good Practices_ for this.

## Step 4
* As written here, your code doesn't run. I've deducted 4 points from _Correctness_ for that.
* You have your variables (hospital_name, pat_age, etc) all defined under the `if "SYSTEM" in row[0]` condition. They never get run, so your code can't continue without those variables defined.
* You had a typo with capital `Y` in `year_month = row[6][:7]` since you referenced the lowercase version later.
