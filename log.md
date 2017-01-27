# 100 Days Of Code - Log

## Day 14: January 27, 2017

**Today's Progress**: Added a "Project Meta Data" widget to pull tools used, a project link and the client information from the header to display in a side bar. The link is meant to be dynamic depending on if it's a video link or a project re-direct / download. Also fully responsive.

**Thoughts**: I added some data to the taxonomy, which i could probably pull out since I feel I might be mis-using taxonomy in this way, for the client, tools and link for the project. My intention for the link initially was to have it have different behaviour in the `project-video` template as opposed to the `project-image` template. I forgot that design decision when I started coding and implemented it in with the `project-image` template with the "Download Project" button. I ended up making it look pretty neat, but realized in the last 10 minutes or so that I wanted it to have that different behiaviour. The task for tomorrow is to get that working properly and from here on out I should probably remember and stick to my overall design decisions. Since I was streaming and my client was watching giving feedback, we did get distracted on color for a good 15 minutes or so. Things to remember for the future, that's for sure.

**Link to work:** [Twitch VoD](https://www.twitch.tv/videos/117695374)

## Day 13: January 26, 2017

**Today's Progress**: Fixed a couple bugs in the portfolio theme, got most of the information I needed from the similar projects widget and added a section in the base for a demo reel and resume link.

**Thoughts**: I was planning on streaming for another 45 minutes or so but everything I wanted to accomplish took a lot less time than I initially thought. The similar projects widget was pretty much done except for a bit of spacing and responsive feel. The only thing absolutely major that needs done is putting the content in the About Me page and figuring out exactly how the project templates are going to be set up. I'm still wondering how I want to organize the tools and whatnot used in a project. I believe adding them to the taxonomy under a new subject or two, like `software` or `tools` in the header and having the page render that down. Either way, it was a productive morning of cleanup and figuring a couple small things out. 

**Link to work:** [Twitch VoD](https://www.twitch.tv/bsb_krames/v/117451295)

## Day 12: January 24, 2017

**Today's Progress**: Today's goal was to work on a "projects like this" widget that is based on the category of the project the user is currently viewing. After a lot of frustration, I was able to at least get the projects that have the same category as the project currently being viewed.

**Thoughts**: I was under the impression that I was sending in a variable to be manipulated and used when using the partial that I created for this "projects like this" section. It still goes based off of the `page` information that is given by Grav regardless it seems. I also learned, far too late and it should have been obvious way sooner, how to enable debugging in ths CMS. Once I figured that out it didn't take too long before I was able to access the data I wanted. This was a very frustrating day, however I did learn that looking for a way to debug when in an unfamiliar environment is kind of important.

**Links to work:** [Twitch VoD](https://www.twitch.tv/bsb_krames/v/116991685)

## Day 11: January 23, 2017

**Today's Progress**: Was able to get the project category navigation working fully, transitioning to and looking nicely on mobile and the ability to filter which category of projects are shown with the default being the application projects.

**Thoughts**: I thought this would be a lot harder than it was. Not to say that it was easy, but I realized I was over thinking just a tad and already knew how to add all the event listeners on the project navigation as well as toggling which categories were showing or not. These are some things that I feel are fundamental to a lot of modern websites and a skill that is necessary in the industry no matter how simple or difficult it may be.

**Links to work:** [Twitch VoD](https://www.twitch.tv/bsb_krames/v/116773537)

## Day 10: January 21, 2017

**Today's Progress**: Finishing touches were put on the portfolio responsive navigation and I was able to get all of the 'portfolio projects' on to the home page with a class of the project type (application, 3d, design).

**Thoughts**: Figuring out how to use Twig, a PHP template language, was a very interesting experience but was made a lot easier by using Grav's documentation and looking at how the standard blog page was setup. Being able to look over some example code and translate that to your own project is always a good skill to have. I feel that by doing this portfolio theme project it has taught me a lot about how I learn best (which is having an audience in streaming) and how to adapt to a new environment.

**Links to work:** [Twitch VoD Part 1/2](https://www.twitch.tv/bsb_krames/v/116311782) | [Twitch VoD Part 2/2](https://www.twitch.tv/bsb_krames/v/116324265)

## Day 9: January 19, 2017

**Links to work:** ['convenient-currency' commit history](https://github.com/krames12/convenient-currency/commits/master)

**Today's Progress**: Finished 'Convenient Currency' up with a bit of styling to make it less default and feel a bit more comforting to look at.

**Thoughts**: I didn't have a whole lot of time today, but I did find enough time to finish this project. I would have put a bit more effort into the final stretch of it, but my care only lasted a couple days to be completely honest. This is it's final form as of now, but I might update it in the future.

**Links to work:** ['convenient-currency' commit history](https://github.com/krames12/convenient-currency/commits/master)

## Day 8: January 18, 2017

**Today's Progress**: Worked on some styling for the currency project I've been working on as a starter project for this endeavour.

**Thoughts**: I spent about 20 minutes wondering why my styles were going through on the second input, but not the first. It ended up being a mis-spelling of `container` the `<div>` above it. Wish I could have gotten a bit more done in that regard, but it did take a bit for me to get a bunch of other stuff working properly as well. Also thought of another idea for a project to help with remembering bits of info about people you network with for future reference. I haven't thought of all the details, but I'll be starting that after I finish the currency project.

**Links to work:** ['convenient-currency' commit history](https://github.com/krames12/convenient-currency/commits/master)

## Day 7: January 17, 2017

**Today's Progress**: Worked through part 6 of Wes Bos's [Javascript30](www.javascript30.com) dealing with flexbox and making an expandable panels.

**Thoughts**: I didn't have much time due to a few other commitments, but I at least was able to work through this particular part of JS30. It was something!

## Day 6: January 16, 2017

**Today's Progress**: Went through part 5 of Wes Bos's [Javascript30](www.javascript30.com) course and worked on a on hover overylay for a "project" preview that can be used when displaying portfolio sites.

**Links to work:** [Project Block: on hover overlay](https://codepen.io/krames12/pen/egdwNp)

### Day 5: January 15, 2017

**Today's Progress**: Learned how to make an animated hamburger menu as well as a responsive navigation. Also learned a bit of SASS implementation as well.

**Thoughts**: I've been wanting to figure out how to actually animate a hamburger menu and make a responsive navigation that makes sense for a long while. And what better time than now, when I'm currently working on my friend and I's portfolio websites. I had some issues with padding, but I always tend to forget to use `box-sizing: border-box;` for whatever reason, so this was another reminder of it and hopefully it will actually stick. Overall though, i now have a reference for a base responsive menu and an understanding of how and why these things work. It was also about time I started using SASS anyway. I actually like the layout and the ability to use variables, and yes I do know that css variables are a thing that's becoming more and more supported by modern browsers.

**Links to work:** [Animated Hamburger Icon](https://codepen.io/krames12/pen/QdKdoK) | [Responsive Navigation](https://codepen.io/krames12/pen/JERWaQ)

### Day 4: January 13, 2017

**Today's Progress**: Finished all of the functionality necessary for the conversion process. Implemented SASS/SCSS compilation into the server start and am going to start most of the styling tomorrow. 

**Thoughts**: I realized after a little longer than I'd like to admit that the DOM not changing was due to a lack of capitilization with innerHTML. Other than that today was mostly research in how to actually get SASS/SCSS to compile when starting the server and which implementation of SASS/SCSS to actually use. A little bit more styling could have been done, but I felt the research to be important enough to postpone some work there. I am debating, if I can find a very small resource for it, to add the flag of each currency to show either in the drop down or having it by the input/output boxes. 

**Link to work:** ['convenient-currency' commit history](https://github.com/krames12/convenient-currency/commits/master)

### Day 3: January 12, 2017

**Today's Progress**: I finished a skeleton layout of the currency conversion page and most of the functionality. The dynamic updating of the converted amount isn't quite working as intended though. Will hopefully finish the functionality of it tomorrow and make it look awesome as well.

**Thoughts**: It's been a week since my Day 2 and that was due to my own laziness and also a very busy couple of days that helped the laziness along. Project wise, I wanted to seperate the page manipulation and the calculation as to not make the conversion as standalone as possible. I believe that everything is getting properly passed into the convert function, but I will need to do some more testing and extra logging to verify that tomorrow. I'm a tad confused because my implementation is exactly the same as my [FizzBuzz Project](https://github.com/krames12/learn-mocha-fizzbuzz), but it might be an issue with data either not being passed properly or my own mis-handling of the flow and calls.

**Link to work:** ['convenient-currency' commit history](https://github.com/krames12/convenient-currency/commits/master)

### Day 2:  January 5, 2017

**Today's Progress**: Realized that the data I was sending on `res.render('index', { info: data });` only sends it to the template engine and stops there. Changed that to be the currency types only and moved the API call to the front end.

**Thoughts**: I have used NodeJS with Express and EJS previously so I feel like I should have known that it would not have gone through. With that being said, I wasn't exaclty sure if I wanted this to be a mostly front end application or if I wanted to re-render on submit. I decided on the mostly front end and now feel like I wasted a couple hours yesterday figuring all of those things out. Either way, it's a lesson learned that I won't soon forget. I would have liked to have gotten more done today however it just didn't happen.

**Link to work:** ['convenient-currency' commit history](https://github.com/krames12/convenient-currency/commits/master)

### Day 1: January 4, 2017

**Today's Progress**: Started a currency conversion app using the [fixer.io API](http://fixer.io/). Got the basic server code and was able to gather data from the API and feed it to the template engine, as well as filled out one drop down with every currency available.

**Thoughts:** Since I've done some basic Node and Express stuff before, the super basics were pretty easy as I just referenced my previous project. For the request itself though, I wanted to use the Request NPM module to make it easier. That wasn't quite the case, as it took about 1.5ish hour of hassle and not finding the answers I needed to get it to work properly. It wasn't an issue of making the request itself and getting the data back, it was getting that data and pushing it to the front end. It's probably really easy and I must have skimmed over, or just didn't understand, how to do it. I scrapped that and decided to create a Promise with the HTTP call to the Fixer API and was able to feed that into the front end no problem. 

**Link to work:** ['convenient-currency' commit history](https://github.com/krames12/convenient-currency/commits/master)

### Day 0: January 2, 2017

**Today's Progress**: Did some planning by forking the repo and thinking about what to work on through the duration.

**Thoughts:** I like to at least attempt to plan out a loose guide for what to do during any sort of journey or trip. I do have a mini-deadline on a personal project to update and a few other lists of things to possibly use as well. Updating my first public project, [PugCheck](http://pugcheck.com), so that it supports the newest World of Warcraft raid coming out in a couple of weeks is very high on that list. I am working towards becoming employed as a front end dev and I have a few other projects that I'd like to create for the purpose of learning new frameworks and ways of doing things and boosting up my portfolio a bit.

**Link to work:** No actual work done as of yet.
