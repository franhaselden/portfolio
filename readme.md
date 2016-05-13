# Personal Portfolio - work in progress

This is my personal portfolio project. It's a pretty simple one-page design but I am planning some interesting features. 

## Technologies used

* Github for source control (well I'm sure you already guessed that)
* Sass for awesome CSS
* Grunt
    * Autoprefixer - doing all that modern stuff with less of the hassle!
    * Uglify - minified and efficient
    * Marked - used for parsing the markdown to HTML
    
## Writing posts

I like writing posts in markdown. It's low fuss and means I can focus on what I'm writing about not what it looks like. It also means I can write on any system without needing to login or have a special IDE. I can write in any native textpad!

In order to output my posts, I use [chjj/marked](https://github.com/chjj/marked) which parses `.md` files stores in the `posts` directory to HTML. I can then call them into the page with AJAX when requested. Easy peasy.

I run *marked* with Grunt task runner.