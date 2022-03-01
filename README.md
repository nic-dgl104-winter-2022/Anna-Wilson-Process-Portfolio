# Anna-Wilson-Process-Portfolio
## **Week One:**

*RESEARCH:*
>potential "textbook production" technologies that we could use for the purposes of our course textbook. Make a list of potential technologies (with links!). Closely examine at least one technology and write a pros and cons list as it relates to our potential use of the technology.

potential "textbook production": 
Here is my thought on why you may give visme.co a chance,
pros:
1- Real time update for any edits

2- Team member can collaborate and work in the same project at the same time

3- You can choose different medium to rely your info

4- You can interactivity to your content

5- It's free! with different pre-made templet to choose from

cons:
1- depending on what machine & internet you use it may run slow

2- You need to sign up for free acc

*REFLECT:*
>on textbook that you've read for another course - what has worked, and what hasn't worked? What features would you like to see reproduced in our textbook? What should we avoid?

I liked having a digital book for its convenient use especially for coding where everything is online, I can search terms by highlighting text and click search google for .., open links, have the website read the content aloud for me, seeing the code block formated with color's clarify the code more as well. 


## **Week Two:**
*RESEARCH:*
> style guides. Find one for a programming language you are familiar with and give it  a careful read. What is new to you, or surprising? What is challenging, or difficult to understand?

Javascript Style Guides https://my.visme.co/view/dmy7ezjv-javascript-style-guides-2

*REFLECT:* 
> on your own coding practice. What have you done well, and where you could you improve in terms of style and best practices? Provide some examples from your own code.

* Use clear names for variables:
`    // used html markup to organize output in table & to add item in array
    todos.push(`<tr><th>${count}</th><td>${duration}</td><td>${description}</td></tr>`);`
* Using space around operators
`    count += 1;`
* Statement rules
`    todosEl.innerHTML = todos.join('');`


## **Week Three:**
*RESEARCH:* 
> an API or library belonging to a programming language that you are familiar with. What do you notice in particular about the documentation approach the author's take? Is the documentation clear? Well-organized? Do you think you'd be able to find what you're looking for?

What are JS APIs? 
It's the middle piece that can communicate information between two, It can take the user input preference or search to the main server to find a page or an item. 

You can use the API by inserting the URL to your code which will reflect the information requested, an example of this could be an API that asks public wifi users to agree in terms and conditions to use the wifi, another application to get feed from social media acc up to date to reflect on your website. 

More here:
- https://www.youtube.com/watch?v=ecT42O6I_WI
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction

Navigating MDN Web Docs API library 
the information is written in a clear direct format, on the left side you can choose what API you looking to use once that click more information will display on how to use it and what other action it can perform.
- https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API

API that would be helpful for my app:
- Alarm Manager API
- Time API
- Wather based on location

- https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/alarms/Alarm
- https://www.youtube.com/watch?v=xSrVWFCtgaE

*REFLECT: *
> on your own documentation efforts in past projects. What have you done well? What could be improved? What have you learned recently  about documentation that you hope to be able to take forward into future projects?

I notice that writing codes & adding a comment explaining each line make it easier to understand it when I'm lost
As well having a bookmark folder of important blogs or other material for each project make it easier to refer to it later.
Something I'm looking forward to in this documentation, 
to have one place for all related codes or articles for my app to be able to put them together once it's done 


## **WEEK FOUR**
*RESEARCH:* 
> find your community! Take some time to brainstorm your interests in the context of your personal goals. Do some searching around GitHub through open source repositories to find something that aligns with your interests. Remember to keep an eye on repository activity - make sure development is active! Does your community have a well-defined central hub (e.g. a Slack or Discord channel)? What are the key resources for your community? How will you go about finding more information as you need it? Who will you contact, or where will you look?



*REFLECT:*
>on your community. After spending time engaging with your community (e.g. looking at example code, repositories, reading discussion threads and forum posts, reading PRs and comments, watching tutorials, etc.) What do you think the goals of your community are? What excites you most about your community? How do you hope to contribute to your chosen community?


## **WEEK FIVE**
*RESEARCH: *
> For this activity you should choose an IDE that is familiar to you that supports debugging. Visit the IDE developer's website and read some of the documentation about debugging. Write some sample code and play around with the debugging tool to better understand it. What have you learned from this process?

Going over my last code, I found some errors that I corrected after checking the debugging steps I've set for myself, 
error msg:
`Corresponding method handler '`public void buttonPressed(android.view.View)`' not found
Method 'buttonPressed' in 'MainActivity' has incorrect signature
Typo: In word 'serach'`

after clicking at all error messages, it's taking me to the same lines of code in XML file 
`43        android:onClick="buttonPressed"
44        android:text="@string/serach"`

I noticed search wasn't spilled correctly & once I corected splling for search in main xml, I got 2nd error massage  
`android:text="@android:string/serch_go" `

then error msg showed up (Cannot resolve symbol '@string/search') in problem tap and suggested to add string value; 
going back to my code, I knew I didn't need an extra value, so I went to check the what's my code referencing.
I opened split screen in XML file to check the id & there was a red box around the button id. After updating the id, the issue is fixed now.
 
This link would be helpful for more complex debugging in android studio: https://developer.android.com/studio/debug


*REFLECT:*
> when has debugging been particularly challenging? Consider a project that you've worked on in the past where a bug was particularly difficult to solve. What techniques did you use? Knowing what you know now, would you be able to improve your process? How is what you've recently learned going to help you in the future? What debugging techniques will you adopt?


I've used vscode for writing and debugging codes in CPS100. I liked that it highlights the error in the code and appreciate the plugin that helps fix or format the code while writing. I've learned about the brake points which, allow me to test the code in parts. I've learned how to understand, read and search the error message while writing the code. I've also got myself somewhat familiar with the android studio by testing with the debugging tools while following tutorials/assignments. 

Steps I took to debug coding assignment:
* Comment what each line need to do
* Check any red words in main activity file.
* Check problem tap for error massage 
* Use system log


## **WEEK SIX**
*RESEARCH:*
> code review documentation and best practices. Find some documentation for established companies or groups (perhaps from your community!) that discusses some aspect of code review (i.e. it doesn't have to be a full code review protocol, but it should outline some of the processes through which code is approved). How does this process fit with what has been proposed in lecture? Do you think there are any improvements to be made?

I've found code-review-tips written by ryanmcdermott insightful with example of each step of the code review process. It goes hand in hand with some points mention in the lecture around respecting each other time for both by reviewing the code before submitting including checking out typo and formatting, and taking the time to understand the function of the app before suggesting changes that could be irrelevant. The article covers most review steps for basic apps that i would potently make, there might be more once code get more complicated but for now i would say all needed information is covered. 

*REFLECT:* 
> on the code review process. Find a friend and perform a code review on one of their previous projects (and vice versa!) What worked well about the process? What could have been improved? How do you think this process could help on a real project? How do you think it could fail?


## **WEEK SEVEN**
*RESEARCH: * 
> testing frameworks for a programming language and / or IDE that you are familiar with. Find some documentation related to the testing framework and read at least the basic principles. How easy is the documentation to understand? Could you use the tool right away? Try writing a simple test and deploying it? Did it work? What have you learned from this process?

*REFLECT:*
> when would testing have helped you most on past projects? Can you recall any past projects that would have benefitted from a test-first approach?  What is the most important learning you will take from this week (even if you don't feel comfortable using a testing framework, what can you take from the principles of testing and use in future projects)?


## **WEEK EIGHT**
*RESEARCH:*
> all the tools! We've collectively looked a lot of tools and technologies up to this point, and many of them have been reported on in Slack. Take a read through the #weekly-research channel and identify the tool that interests you the most (it doesn't have to be one of yours!) Do your own research on the tool by examining the official documentation, reading third-party articles or completing tutorials. If you can, try the tool out yourself to get a sense of how it works.

*REFLECT:*
> on your chosen tool. What about it captured your interest in the first place? (Maybe it's purpose? Perhaps the student who reported on it wrote a really compelling discussion about it?) Write a pros and cons list that examines the use of the tool in a context you're familiar with (i.e. as it relates to a particular IDE or programming language, etc.) What have you learned from this process? Would you recommend the tool to a peer? Why?



## **WEEK NINE**
*RESEARCH:*
> UI design patterns. Feel free to use resources from other courses (i.e. especially DGL 111). Compile a list of useful UI pattern resources that are most helpful from a development perspective (i.e. resources that specify not just how a UI might be designed, but also how it might be coded). Did you learn anything new from this process?

*REFLECT:*
> on the UI of an app that you use often. Feel free to make use of UI terminology and analysis that you've learned in other classes (e.g. especially DGL 111). Consider what works well with the UI and what doesn't, perhaps make a pros and cons list (consider all aspects, including navigation, menus, icons, device orientation, how the app interfaces with other apps or the system, etc.). Try to break the app: push the interface to its limits and try to find bugs - be intentional about this. Consider the UI from a developer's perspective: What would be difficult, based on what you know? What would be easy? Report on what you've learned.


## **WEEK NINE**
*RESEARCH:*
> design patterns and anti-patterns. Take a look at the list provided in lecture, or do some researching online to find a resource that provides a collection of design patterns (and / or anti-patterns) in a programming language that you are familiar with. Choose one pattern and examine it closely. What is the pattern for? In what situations would you expect to find it? What are the key elements of the pattern? What have you learned from your close examination?

*REFLECT:*
> on a past coding project. Choose a project of significant length that you haven't touched in at least some months (it could be from a course you've already completed, or from work you've done outside of class). Examine the code carefully and consider the main themes we've discussed in this course to date (i.e. from best practices and style, documentation, debugging, through UI concerns and design patterns). What stands out to you as you examine your code? Do you understand the code and your intentions fully? What is the biggest thing you could do to improve the code? Explain why.



## **WEEK TEN**
*RESEARCH: *
> either another software architecture pattern (e.g. MVP, MVI, VIPER, others), or a new resource that discusses one of the patterns discussed in lecture (i.e. MVC or MVVM). What did you learn from this resource? What will you be able to apply from what you've learned from this resource and from lecture?

*REFLECT:*
> On the diagramatic way in which software architecture patterns are typically presented. Have these been helpful to you understanding? Have they hindered your understanding? Is there a better approach? If so, describe it; if not, explain what you think the strength of the diagramatic approach is.


> Quoted from Ashley Blacquiere 
