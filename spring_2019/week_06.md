## Last Week's Accomplishments

This past week, I made a few changes to the graph itself while also learning about the Charts API a bit as well. 
The grid behind the graph should be gone now, and I figured out a way to format the numbers so that they appear as Ints. Other small things, like the text that appears when there's no data in the graph, are also now customized. The API is intricate and feature-rich, so I expect that I can customize more things in ways I haven't yet discovered. 

Most significantly, the MarkerViews - the views that pop up when you tap on a point on the graph - are now (crudely) implemented. They display the date, precise score, and user-defined notes for that date. 

## This Week's Plan

This coming week, I'm going to try getting the MarkerViews to behave more nicely.

Right now, if you tap on a point that's too close to the right side or the bottom of the screen, the view will be drawn partially (or fully) offscreen. There's a way to calculate what the offset of the MarkerView should be, so I'm going to figure out a way to set that offset correctly if the view would otherwise be offscreen.

The MarkerViews also have a constant height. It'd be nice if the views varied their heights (and perhaps widths too) depending on the size of the content; I'll try figuring out something for that.

It'd also be nice if I could get them to look nicer. Right now, they have a slight drop shadow and a thin black outline. Maybe it'd be nicer if I got the outline color to match the color of the graph's line, or maybe it'd be nicer if I could just use only drop shadows? I'm not really sure, but I also don't think it's terribly important yet; it shouldn't be too tough to change.

## Anything Blocking?

I still haven't really touched the More Resources tab yet. I've planning on letting Nick do his thing there, but he hasn't shown up to small group meetings recently, so I'm wondering if I should get something started there. 

The problem is that I don't really know much about what other resources exist... so I'd still rather wait for Nick, but if I finish my graph and there's still nothing there, I'm going to have to implement it myself.

## Notes

This is a couple of days late, for which I apologize; this past Friday was pretty tough for me and it totally slipped my mind. I don't plan on making it a habit :P


