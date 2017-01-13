# 100 Days Of Code - Log

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
