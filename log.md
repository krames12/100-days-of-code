# 100 Days Of Code - Log

## Day 8, January 18, 2017

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
