# Jekyll is out...

<time>July 18th 2021</time>



Jekyll is a static site generation tool that solves an easily solvable problem, it gobbles up markdown (.MD) files and spews forth HTML files which can be viewed within the browser. I understand that Jekyll is not the only *static site generator* tool, nor is its only use turning markdown into HTML - there is an optimisation process, a more complex build layer, inclusion of the *Liquid* templating language, among other things I'm sure... However, this is all that **I** happen to use Jekyll for, a very simple mechanic of converting my markdown format posts into readable webpages with the correct stylesheet tacked-on.

I, at one point, ran my blog using Jekyll, hosted via Github, but have come to realise that the program I use to write up my posts - [Typora](https://aur.archlinux.org/packages/typora/) - already solves half of my problem for me. It can export markdown files to HTML without styling. Do you see where I'm going with this? An hour-or-so and a hundred-or-so lines of Python later, the posts on my blog are now converted by Typora and inserted into a standard HTML template, with a seperate *main* and *post* stylesheet, copied across to a new static file ready to be hosted on the site. 



See you later, Jekyll. 