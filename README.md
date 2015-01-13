# grumpyCatMockup

### Approach:

- I used 'mobile-first' principal to design webpage for smaller screens and to reuse as much code as possible when scaling up in device screen size
- I would have preferred to include either off-canvas side menu or a drop-down menu for small screen navigation rather than display the navigation menu links on a new row below the page header, given the task was to implement only the HTML and CSS I tried to make the nav links as user-friendly as possible for this mockup.
- I only implemented one breakpoint in my design to keep the HTML and CSS easier to maintain as this was my first attempt at designing a responsive framework from scratch. (In the past, I have leveraged open source CSS frameworks to create a base foundation for developing responsive websites & web apps.)
- I would have preferred at least one more breakpoint for this design mockup in order to take advantage of the screen real estate available for medium devices (i.e., widths > ~400px and < ~900px)
- Since I only used one breakpoint, the design breaks the news feed content for some larger devices. Had I configured a medium breakpoint, then I would have taken advantage of the additional left & right margin area available and resolved the issue with the element's float property.
- I tried my best to keep the quality of the images intact and, as a result, this led to some viewports displaying slightly awkward layouts due to the images taking up the entire width of the view on multiple lines or displaying a 2-1 stacked layout. This could be resolved with an additonal breakpoint and tweaking how the images are displayed.