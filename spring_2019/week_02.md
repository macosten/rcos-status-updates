## Last Week's Accomplishments

Building upon the SurveyTableView and SurveyTableViewController, I have added a header view (currently it's just displays the title, but better customization is possible) and a footer view (which contains a button that's meant to save the survey result, but for now it only prints a message to the console). Again, further customization of both views is possible (as is the rest of the UI, honestly), but for now I'm focusing on factor over form, for the most part.

I have implemented the Survey object type I mentioned in my previous "This Week's Plan" segment.
```
Survey(withTitle: String, withQuestions: [String])
```
Not shown in the initializer is the .answers array, which keeps track of the answers (numerically) and is automatically allocated by the initializer.

## This Week's Plan

Time to stop putting it off: time to get CoreData working. You might have seen it, but I already have the beginnings of the database in the project already. However, no code interacts with it... yet. Getting us to save survey results as GraphDataPoints will be my main goal for this week.

Past this week, I'll start taking a more serious look into what third-party data visualization (graphing) libraries are available for us to use. As I discussed with Nick, we'll be using Carthage as our package manager; I've only used CocoaPods in the past, but I don't think it'll be particularly hard to adjust. Getting it to work with the stored GraphDataPoints will be the thing after that.

## Anything Blocking?

There are still no notable challenges I've run into yet.

## Notes

It's a long weekend this weekend, and Parallel Programming homework got an extension until the 19th. I might just have some time to sleep properly this weekend :P
