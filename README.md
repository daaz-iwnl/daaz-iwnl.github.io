MIDTERM DOCUMENTATION



======== PT 1: HOMEPAGE ========

Functionally, I wanted the homepage to be essentially an interactive splash page and focus on capturing the attention than being functional. In settling on a theme, I went with something simple, and I chose the nostalgia look through the type and images. Since the site only has two other pages, I linked them to different parts of the splash page. The homepage only has a title/subtitle, and a graphic--which hopefully will invite people to click somewhere on the graphic. The photographs link to the portfolio, and the handwriting leads the user to an "about me" page. Initially, I was going to make a navbar that would show and hide--however, the homepage started to feel like just a glorified table of contents. All pages use 996 grid, and scale to device.

======== PT 2: PORTFOLIO ========

The portfolio page is the most advanced of the three. Aesthetically, it is still a simple page with a title header, and different projects are separated based on category--animation, graphic design, photography, video--each contained in a different row. Each thumbnail is 300x300, and upon hover, displays the project name and description over a red to blue-green gradient--the image underneath turns greyscale so the gradient is clean. In keeping with the nostalgia theme, the color palette is pulled from the splash page image. Clicking on each thumbnail would open a modal window that provides more details on each project and a gallery of images of the project. The title links back to the splash page. One issue was nesting grid_4 elements into one grid_12 element, which ended up messing with the media queries.

======== PT 3: ABOUT ========

The about page is relatively simple at the moment, since it only contains text and a mailto and download link. I wanted to keep the lines horizontally constrained to make reading easier, and also ensure that it was responsive. At first, I made the containing elements fluid in size, but then later realized that using the grid_8 from 996 would be much easier.
 