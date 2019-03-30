## Last Week's Accomplishments

I've made more refinements to the MarkerViews to make them better-behaved, as I mentioned in the last update.
Specifically, if one would end up offscreen, it will be offset from where it would otherwise be by the length or width of the view, respectively, depending on which is necessary (or both, if both are necessary).

Additionally, the MarkerViews now resize themselves to fit their content more appropriately, so they look a lot nicer with much less empty space when they're drawn now.

## This Week's Plan

We're at an interesting point: the feature set is finally complete enough that the app is beginning to look like it fits our initial goals for it.

I think what I'm going to work on next is, ironically, the MarkerViews. Right now, offsets *have* to be the width or height of the MarkerView, which causes the view to jerk away from the edge very suddenly when it is about to start going offscreen.

It'd be nice if, rather than a sudden motion, I could calculate the appropriate offset a bit more dynamically. I don't think it'd be something that should be too tough to figure out.

Nick mentioned that he wanted to see if we could color-code the data based on its value. I'll have to research the API a bit more to see if that's possible, but if it is, I'd like to implement that as well in the near future.

Past that? I guess I could add some personalization capabilities, just for fun... it'd need to store stuff to UserPreferences, but that'll be easy enough.

## Anything Blocking?

Nick is back (evidently he was sick or something), so I'm no longer worried about the Resources page having resources. That being said, I do wonder how he wants to implement it. I'll have to work with him on that.

With that out of the way, there's nothing left that I'm worried about that might block me.

## Notes

Today was tough; I came back to NYC on a bus around midnight and went on a couple of tours around nearby company offices on 6 hours of sleep. It was a nice experience, but it was exhausting!

Since I was here and not there: sorry about missing meeting. It should be an excused absence, and I did get an email that stated that Professors Turner and Goldschmidt were notified, but I will follow up with at least one of them in the near future, just to make sure.
