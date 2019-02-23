## Last Week's Accomplishments

This past week, I prototyped a way in which data may be written to and read from Core Data, as a proof-of-concept. That submit button finally saves stuff to the database (after asking the user for any potential notes they may have about the day). Then, whenever viewDidLoad() is called on the GraphViewController (whenever we switch to the graph tab in the app), the contents of the Core Data database are printed to the console. The fact that it works proves that stuff is being saved to the database and that I know how to retrieve it, which is important for the next step in our plan...

## This Week's Plan

It's time: time to choose a graphing library. I have one in mind, but I'll have to get Carthage either way, which means it's time to install and use that too. Since the graphing library is not going to be standard (though it will be open-source), it'll probably take some getting used to, but I can't imagine it's something I can't handle.

Nick will handle the "More Resources" tab -- I need to make sure not to touch it. Worse comes to worst, we meet up over the weekend and I help him get it working.

Beyond that, it's going to be worth thinking about dynamically resizing some of the UI elements - the footer, the submit button, the text in the UISegmentedControls in the Table Cells - depending on the size of the screen. Apps look really different on a 5S when compared to a 10X, so it's important we make the most consistent experience we can! The fact that we can soon bring our attention to this means that we're getting all our core functionality down rather nicely, which is encouraging.

## Anything Blocking?

There are still no notable challenges I've run into yet. I'm not sure about Nick, but I should be able to help him if he gets stuck.

## Notes

The weekend is never long enough :P I wonder if I can get even half of what I want to get done done... at least RCOS is a lot of fun (actually the most fun I'm having here at RPI right now!).
