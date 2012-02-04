SAY Media Front-end Coder Test
==============================

Overview
--------

This worksheet is intended to provide an opportunity for you, an engineering applicant, to demonstrate your software engineering knowledge.

For any exercise which requires coding, we are looking to see how you solve the problem. The logic you employ and the approach you take to solve the problem are the most interesting to us. Each of the given problems have at least a handful of valid solutions, and possibly other solutions weʼve never seen. So, donʼt worry about finding “the” solution. Provide a solution that you like. You should NOT use any 3rd party plugins to solve any of the exercises.

Please review the exercises first. If anything is unclear or confusing, please contact us in the first 30 minutes and we will help clarify any issues.

Most importantly, have fun! 

Exercise #0
-----------
To get started you'll fork our project at GitHub found at [http://github.com/thrashr888/frontend_code_test](http://github.com/thrashr888/frontend_code_test "Frontent Code Test Repo at GitHub").

    git clone git@github.com:thrashr888/Frontend-Code-Test.git

Commit each exercise when you're done with it. For example:

    git add .
    git commit -m'Exercise #1'

Exercise #1
-----------
Create an HTML5 page with header, footer and main sections in index.html. The main section should contain a content section and a sidebar. Set the width of the content section to 660 pixels and the sidebar section to 300 pixels. Make the sidebar float to the right side of the content section.

Index.html should include these scripts:

- https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.js
- test.js
- test.css

The header section should contain a nav with three links:

- Home ( index.html )
- About ( /about )
- Blog ( /blog )

Exercise #2
-----------
In the sidebar section, create a form for a poll with 4 options. The last option will be an input box for custom text. It will POST to the url "/poll/submit". In the browser, it should look something like this:

    My Favorite Dog Breed
    
    * Boxer
    * Hound
    * German Shepherd
    * [ Custom Input ]
    
    [ Submit Button ]
    
Exercise #3
-----------
![HTML Layout](https://img.skitch.com/20120204-rhp7q6h6er1j2dwsm8pf3yd4pa.jpg "HTML Layout")

In the content section, rebuild this design in HTML5 and CSS3. You don't need to perfectly match exact pixel sizes, fonts, or colors for this exercise but it should look as similar as possible. You can also use lorem-ipsum or placeholder text.

The image for the comment count can be found in the img folder. You can use placekitten.com for the larger images (e.g. &lt;img src=&quot;http://placekitten.com/140/120&quot; /&gt;).

Exercise #4
-----------
Make a new link called "Sidebar" in the nav that hides and shows the sidebar 3 seconds after you click on it. On hover, make a new link called "Blue" in the nav that turns all the links on the page blue except for the "Blue" link.

Exercise #5
-----------
Write documentation about the project, including code comments.

Exercise #6
-----------
Before the time is up, commit your changes into git and push them back to the server.

    git push origin master

Send us a link to your fork in GitHub and you're all done!
