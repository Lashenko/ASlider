# ASlider

ASlider (name TBC), endeavours to be the most versatile and user friendly slider ever for developers! 

ASlider will aim to support use cases for the following:

* Multiple configurable layers for titles, subtitles, captions, images, call to actions and much more!
* Rich multimedia types, including images, audio and video
* Ecommerce, products and promotions
* Testimonials
* Articles, case studies and FAQs

## Demo

Run social-bar.html in the /test directory.

### Usages

#### Adding social icons to the social bar

        <script>
                socialBar.put("twitter", new Slider.SocialIcon({
                    title: "Follow me on Twitter",
                    imageUrl: "images/twitter.png",
                    url: "https://twitter.com"
                }));

                socialBar.put("facebook", new Slider.SocialIcon({
                    title: "Like me on Facebook",
                    imageUrl: "images/facebook.png",
                    url: "https://facebook.com"
                }));

                socialBar.put("gplus", new Slider.SocialIcon({
                    title: "Follow me on Google+",
                    imageUrl: "images/gplus.png",
                    url: "https://plus.google.com"
                }));

                socialBar.put("github", new Slider.SocialIcon({
                    title: "Fork me on GitHub",
                    imageUrl: "images/github.png",
                    url: "https://github.com"
                }));

                socialBar.put("email", new Slider.SocialIcon({
                    title: "Email me",
                    imageUrl: "images/email.png",
                    url: "mailto:me@myemail.com"
                }));

                socialBar.render();
            })
        </script>
 
Run social-bar.html in the /test directory to see the social icons. Positions can be changed in here too:

            $(function() {
                var socialBar = new Slider.SocialBar({
                    container: $(".test-container"),
                    position: {
                        y: "top",
                        x: "right"
                    },
                    isHorizontal: true
                });

## Author

Copyright (c) 2014 Sam Lashenko <sam@honeystone.com>
Portions Copyright (c) 2014 Honeystone Consulting Ltd.

## License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


## Changelog
