Open Source font specimens
--------

This is an ongoing collaborative project exploring the creative typographical
possibilities of Open Source fonts. Originally inspired by
[femmebot](https://github.com/femmebot)'s
[google-type project](https://github.com/femmebot/google-type)

## Contribute

Below are the requirements, along with some places where you will find some good sources and instructions on how to submit.

### Submission rules

Must include

1) One or more Open Source fonts

- [Google Fonts](http://fonts.google.com)
- [Use & Modify](http://usemodify.com/)
- [Open Font Library](https://fontlibrary.org)
- [Font Squirrel](https://www.fontsquirrel.com/)
- [Open source fonts on Github](https://github.com/showcases/fonts)

2) A text source from the public domain, this can be anything from a quote to a passage from a novel.

- [Project Gutenberg](http://www.gutenberg.org/wiki/Main_Page)
- [Literature Page](http://www.literaturepage.com/)
- [Jane Austen](https://www.janeausten.org/)
- [Brainy Quote](https://www.brainyquote.com/quotes)
- [Wikipedia list: books in the public domain](https://en.wikipedia.org/wiki/Category:Public_domain_books)

3) A specimen in your style of choice, you must honor the license of any content you use. You might want to use:

- Public Domain images from [Unsplash](https://unsplash.com/) and [elsewhere](https://medium.com/@dustin/stock-photos-that-dont-suck-62ae4bcbe01b)
- Public Domain or Creative Commons icons from [The Noun Project](https://creativecommons.org/publicdomain/zero/1.0/) and [many](https://www.iconfinder.com/) [other](http://fontawesome.io/) [places](https://material.io/icons/)

4) Must be at an acceptable standard, including the body text being legibile. For inspiration and to gain an understanding, take a look at some of the links below:

- [Buttericks Practical Typography Manual](http://practicaltypography.com/)
- [Type Inspiration](http://typespiration.com/)

### Submitting a specimen

I've tried to make it as simple as possible to submit a specimen to the project
by providing a few options, at the very least all you need to know is HTML and CSS.

#### Option 1: Submit a static design
If you dont have any coding knowledge, simply send me a design with [this form](#) (either raw or flattened) including a list of fonts you used and any specifications, and I will code it.

#### Option 2: Submit directly to me

- Create your HTML and CSS locally
- Use the template in [_speciments/_template.html](_speciments/_template.html)
to include the HTML and CSS that you've made, and your author information.
- Send to me for review by uploading the file to [this form](#), including any
assets required.

#### Option 3: Create a pull request

- Clone the project locally (in terminal
`git clone git@github.com:mattgreydesign/font-specimens.git`) and branch off
master `git checkout -b your-branch-name`

##### Create locally (Basic)
- Create your HTML and CSS locally, include any assets required in the [_images/](_images/) directory

##### Create and preview locally (intermediate)

You can contribute without having to run any builds, but it recommended.
The project is built with [Jekyll](https://jekyllrb.com/) static site generator, which is quite [simple to set up](https://jekyllrb.com/docs/quickstart/).

- Make sure you have Ruby installed, in your terminal run
`gem install jekyll bundler` to install Jekyll and Bundler on your machine
- From the project directory you just cloned, run `bundle install` and to get the server running
locally, run `bundle exec jekyll serve`

## License

[MIT License](LICENSE)

### Inspiration

- Grids with CSS http://labs.jensimmons.com/, http://labs.jensimmons.com/2017/03-004.html
