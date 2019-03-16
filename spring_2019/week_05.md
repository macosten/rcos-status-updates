## Last Week's Accomplishments

This one's more of a "since the last update" kind of update rather than a "last week" kind of update, since I didn't create an update over Spring Break (evidently, it wasn't necessary). 

Since the previous update, I finally implemented basic support for Charts. The chart it actually creates is not that good-looking -- I personally think the chart itself looks a bit crappy because of the (ugly) default visuals. Luckily, I'm pretty sure that those problems can be addressed. The point of the past week or two was not to get the Chart to its final state, but to get it up and running in some fashion instead. I'm not sure how difficult beautification will be, but I get the feeling I'm going to become quite familiar with this API in the meantime.

Besides that, I added a few features and fied a layout constraint problem brought to my attention by the survey object Nick pushed over the break. 

The survey cell layout is now more robust and won't break on big questions; before, the "questions" were just things like "Test question X." Now, they're more substantial, which naturally ended up warranting the next change.

I added the ability to specify default options for the segmented control in the survey, and additionally the ability to specify different options for a specific question's segmented control. You can also (indirectly) change the scale used on a specific question (say, a 0-5 scale instead of a 0-3 scale like the old default) by specifying whatever number of options you choose for a specific question (default or otherwise). It's odd that I didn't think of that before, but I guess it's a result of my view of myself as the coder and Nick as the designer.

## This Week's Plan

This week, I think I'll try working on getting the Chart to behave closer to how I want it to. I want to say goodbye to the grid, I want to change the way the numbers are formatted, and I want to make the points, when tapped, bring up the corresponding notes (though I suspect I might have to save that feature for last).

I'm thinking that I might possibly look into adding the ability to specify custom point amounts for each question's answers, but I haven't quite thought of a way to implement that yet, and it's not something that I feel is particularly urgent yet.

## Anything Blocking?

There are still no notable challenges I've run into yet.

## Notes

I wonder if allowing the user to customize the colors or something like that is worth implementing?

Nick also mentioned some sort of UX feedback committee. It'll be interesting to get their feedback and advice.
