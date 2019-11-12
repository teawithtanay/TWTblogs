# Why Web Performance matters feat Saurabh Rajpal
In episode 6, Saurabh Rajpal, Technical Solutions Consultant at Google joins Tanay to talk about why *web performance* is something developers and companies must seriously consider.  
Saurabh is from Delhi and works as a mobile solution consultant at Google. Saurabh's job is to guide companies in improving web performance precisely on mobile devices. All mobile devices are not that powerful and Saurabh expertise in making web efficient for them.

## *How do you start working with a client?*
Saurabh says that every company has its own way of doing things. Some are in the early stage and they focus merely on building their core product while some are already big and they want to increase their revenue with more engagements.  
Saurabh's job is to look for potential areas for improvement and which are the new technology that they can adopt to increase the performance. After figuring out the problems, the next step is to educate the client about these issues and how solving them can benefit their overall business.  
> The key part is to make them realize how much money they are losing because of the slow web. This sometimes involves side by side performance comparison of two similar websites.

## *How do educate the client about performance?*
Saurabh's tells us a fact that you lose *53% of the users* of your site if it takes more than *3 seconds* to load. Most of the time, clients are unable to track that and that's where Saurabh helps them.  
Job is to record the real-time performance of the website with the help of a visual tool and show it in comparison with the other websites. By recording the boot-up time of multiple sites, the clients can see for themselves why it really matters. 

## *Why Web matters?*
Saurabh gave us an example of Demonetisation. He said that it's pretty obvious that people prefer to come to the bank for cash exchange when there are fewer people in the queue.
> The point is that nobody wants to wait. If you make people wait, they will prefer to leave and come back later when it's convenient.

This concept aligns well with web performance too. If your website is slow and it is making users wait to start engaging with it, they will prefer something else that's more convenient.  
Saurabh states that we are living in a very competitive world and there is a lot of *convenient* option available for almost every service. 
> If your website is not fast enough to get to the user first, you're probably going to lose them to someone else.

## *Can you explain render-blocking and deferred?*
The process of browser going through your code and painting the elements on the screen is called rendering.
By **render-blocking** it simply means that *while the browser is scanning through your code and it encountered a line which it has to process, it will block everything and process that line then it will move to next line and continue rendering.*  
The key is to load only the code that you really need for initial render and get more data as you need them. Dom manipulation is a heavy task and you should keep the load as low as possible.
Write about deferred.  
The defer attribute tells the browser that it should go on working with the page, and load the script “in the background”, then run the script when it loads.

## *How good or bad is their performance generally?*
Saurabh says that he works with both big companies and small ventures and if we talk about early 2015, people were not concerned about the performance.
The main reason could be that there was no one to educate them or propagate the idea that performance does matter.  
One more factor is that the user was not that hungry as they are now. Expectations were low back then and people were okay with waiting but that's not the case today. Now, people want their content instantly and within seconds.
Performance score in 2015 was about 20 to 30 but now when people are starting to care about performance, they can achieve even a perfect score of 100.  

## *Best way to learn about performance?*
Saurabh says that learning performance optimization is platform dependent. Tools or customization that you're going to apply will depend on the platform but the underlying concept is similar to all and you can apply the learnings everywhere.  
* [Web.dev](www.web.dev) is a great starting point for anyone who wants to start learning about performance techniques. You can easily find a lot of articles that help you to understand the concept better.  
* [Lighthouse](https://developers.google.com/web/tools/lighthouse) is really helpful to benchmark performance and to know where your site stands at the moment.  
* [HTTP Archive](httparchive.org) has a repository that includes performance data of millions of sites. 
[The Chrome UX Report](https://developers.google.com/web/tools/chrome-user-experience-report) (aka "CrUX") is a dataset of real user experiences measured by Chrome. It is used to capture user data like click interactions, permission interaction, etc. 
* [WebPage Test](https://www.webpagetest.org/) is one of the most popular and free tools for measuring webpage performance. Webpagetest enables you to run web performance tests on your site from many different locations across the world in different browsers. It lets you choose the environment like (network, location, configuration, etc). 
* [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
* [Firefox Developer Tool](https://developer.mozilla.org/en-US/docs/Tools)

## *Some tools/step for performance before starting to build?*
Saurabh suggests that you should :
* keep an eye on performance when you're starting to build the site because it becomes a lot more painful when the site is already built and you have to figure out the issues.  
* have a performance check, run through profiler whenever you're adding the new feature. It may slow down your development speed at first but it's definitely worth in the long run.  
* think carefully before adding any third party library. You may not need it at all.

## *What inspires you to code?*
Saurabh says that what keeps him going is the desire to learn. The idea of writing some lines that turn about to be visually appealing is really fascinating. And the possibility that the future holds with so many things coming.

## *“Website without visitors is like a ship lost in the horizon.”― Dr. Christopher Dayagdag*