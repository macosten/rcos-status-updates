## Last Week's Accomplishments

I implemented a prototype of the SurveyTableView and SurveyTableViewController. 

Whenever you touch one of the UISegmentedControls in the cells, that cell calls a member function of the SurveyTableViewController that updates an array that keeps track of the survey response values. These are all zeroed out by default. Keeping track of them is useful for two reasons: firstly, we can sum them up quickly at the end of the survey to calculate the final score; secondly, it helps ensure that a question's response does not change when the question's cell is scrolled offscreen and marked for reuse (with the way cells are reused when dequeued, the same cell is not guaranteed to end up showing the same element every time it is used).

## This Week's Plan

Later this week I plan on adding a header and a footer to the SurveyTableView, based at least in part on Nick's work. It shouldn't be hard... at all. The header will probably just show the title of the survey. The footer will probably

I will probably implement a Survey object type as a frontend data model. It'll just store the title and question array for the survey. The point of this would be to make the code easier to read, understand, and maintain; you could define a new survey with something like 
```
Survey("My wonderful Survey", [Question1, Question2])
```
which might be more intuitive than manually setting titles and question arrays.

Past that, as a goal that may stretch beyond the week, I will try getting CoreData working - saving the results of surveys to the database and the like. Actual data visualization/graphing will come later.

## Anything Blocking?

There are no notable challenges I've run into yet.

## Notes

I will try to comment my code a lot to make it easier for Nick to understand what I'm doing, since I'm more experienced with Swift than he is and my intention may not always be obvious.

