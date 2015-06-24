# What is this?

You may have seen [debugCSS](https://github.com/yahoo/debugCSS) before. This is pretty much the same thing, but with the magic of [Sass](http://sass-lang.com/).

By factoring out codifying the repeated selectors and their various rules, `debugCSS.scss` is a lot easier to maintain.

See the [debugCSS Readme](https://github.com/yahoo/debugCSS/blob/master/README.md) if you're confused about anything.

## Usage

To use this, you can either embed the `debugCSS.css` in your project, to see if you've got any errors in the way you're using (X)HTML.

Or you could use the handy bookmarklet to try it out on any site:

[debugCSS](javascript:(function(d,i,l){l=d.getElementById(i);if(l){l.parentNode.removeChild(l);return;}l=d.createElement('link');l.id=i;l.rel='stylesheet';l.type='text/css';l.href='https://blog.omgmog.net/debugCSS.scss/debugCSS.css';d.getElementsByTagName('head')[0].appendChild(l);}(document,'debugCSS')))


## License

Copyrights for code authored by Yahoo! Inc. is licensed under the following terms: MIT License Copyright (c) 2011 Yahoo! Inc. All Rights Reserved. Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.