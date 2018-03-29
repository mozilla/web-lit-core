---
layout: page
following: _articles/web-apps-and-build-with-thimble.md
toc:
- "Introduction"
- "Content and Storytelling"
- "Get Tagging!"
- "Go Online!"
- "Learning Experience Reflection"
---
![building blocks](../images/building-blocks-456616_640.jpg)

#### Description
In this activity, users will create their first web page using a basic text editor and a browser to view the results. They’ll interview each other to get content for a personal (or fictional) “About” page, organize and write up the content, and mark it up using HTML. Users can upload these files to a server (if available) and get their content on the web! 

#### Learning Objectives
* Create a simple web page
* Transfer web page online

#### Time Required
45 minutes to 1 hour depending on group size

#### Audience
Can be tailored for audiences from 13 up; with varying levels of experience with the web

#### Materials
* Laptop with internet connection

#### Web Literacy Skills
* Compose
* Code
* Design
* Revise
* Share (if they upload content to the Web)

#### 21st Century Skills
* Communication
* Collaboration

#### Earning Digital Badges
Digital badges capture the evidence and are the demonstration knowledge and achievement. Each Core Activity encompasses multiple web literacy skills. Completion of all Core Activities will enable anyone to earn all the web literacy plus 21C skills badges. Thus, we encourage you to complete all the Core Activities, and earn badges to capture what you've learned. Digitalme is offering web literacy badges through the [Open Badges Academy](https://www.openbadgeacademy.com/mozilladirectory). 

### Introduction 
[10 mins]
> Tip! Remind learners of their experience with Tags in the previous lesson (Recommend completing Tagging 101 with learners prior to this activity).
* Explain to learners that any web page you visit is actually an HTML file, which is just a text file-- a bunch of words--with HyperText or Markup Language added to the content. HTML is the language we use to write tags.
> Tip! If needed, provide a short tour of browser such address bar, home buttons, bookmarks, history.
* These files sometimes contain other kinds of code, like javascript or php, which makes pages-- when displayed in the browser- interactive and flashy and dynamic, pulling in browser code. 
* HTML files are just text and not very pretty to look at.
* The browser takes them and makes them readable and more visually interesting by layering in design and pulling in images and video.
* HTML file + Browser, like Firefox  = WEB PAGE AMAZINGNESS FOR YOU (hopefully).
> Tip! To show this idea, open a simple, static page and look. Explain: Let’s look! We can see what a web page looks like behind the scenes, before the browser gets to it, by exploring the “view source.” 
* Because HTML files are just text, they can be written in a basic text editor, and viewed in a browser. If you have a browser and a text editor on your computer-- and nearly EVERYONE does-- you can build a web page!
* Your pages won’t be ON the web-- for that to happen you need to take the file you create and to upload this to a server so people can access it there, via the URL or web address. 
> Tip! Remind people, maybe through a diagram, that client computers (web users like you) connect to the Internet and access pages that live on server computers out there on the internet. Servers are designed to “serve up” pages to users. The web pages are HTML files viewed in a browser, so they look great
* BUT, for now, you can practice making web pages right here, on your computer. They won’t be on a server on the internet, but you can still create the files and view them in the browser on your own machine. 
> Tip! Here you can point to the diagram, and show that you’re making a page on a client computer, one that’s not sharing files like a server!
* To get started, we need CONTENT-- because the web is all about communication and sharing of information and ideas. Let’s generate some content together!

### Content and Storytelling 
[20 mins]
> Tip! This next part is fun and interactive, and great for creating a friendly, positive classroom community. But if you’re short on time, and if giving learners a sense that they can have their own representation on the web is NOT a priority, you can provide canned pre-typed content as a .txt file and skip to the next section-- “Get Tagging.” 
* Write your Biography or “About” page. Have participants break into pairs and interview each other about their lives. As facilitator, keep track of time to ensure that each learner has equal time for their story. 
* Interview: Ask participants to take 5 minutes to tell their story, or if they don’t want to share personal stuff, they can make up fictional character and tell that character’s story. Have the listener take notes, or possibly record on a device. Prompt users to talk about what is most important to them (or their fictional character). Offer this list of questions to get started:
    * What’s your name, age, other details?
    * Where were you born? Where did you grow up? What was that like? 
    * What are you doing now? How do you spend your time? What are your favorite things to do, favorite places, foods, music, etc
    * Is there a favorite moment,  proudest moment that stands out?
    * What are your plans and dreams for the future?
> Tip! The interviewer can ask follow-up questions to get at more details, or a fuller story. He or she can ask  open-ended “why” questions about motivations, about preferences, about future plans, to help draw out more insights, or he or she can ask questions to clarify ideas in the story. 
* Review/Edit: Have each learner take the notes from their story and review them-- consider adding details, think of what you left out.
* Organize, and Type Up: Have learners type up their stories in a basic text editor, being sure to use “plain text mode” (not Rich Text mode).  As they type up the story, they might consider organizing and structuring the story into a beginning, middle, and end. Maybe they can think of titles for the sections: “Early Days” “These Days” “What’s Next” Or they can find ways other ways to organize the content, if they talked more about interest  sections-- “My favorite songs” “My favorite places” etc. Creating these sections will help structure the biography for easy reading as a web page. 
* Title Your Story! Come up with a snappy title for your story or content or go with something basic. 
* Make a new folder on your computer and call it “xx-webpage” using your initials. 
* Save your story in the folder with .txt as the extension-- Give it a title with no spaces or punctuation other than dashes or underscores, like “about-zm.txt” This is the text version of your story, the raw content.
* Also, save your story in the folder with .html as the extension, instead of .txt-- this will be your web version. The .html tells the browser to look for html code in the file. Give it a title with no spaces or punctuation other than dashes or underscores, like “about-zm.html”

### Get Tagging! 
[10 mins ]
* Explain to users that they’ll be marking up their story-- the .html version-- with HTML, to make it ready for display in the browser. Explain that since coding HTML and thinking of and writing content are two different ways of thinking, they should always have content written before they mark it up, rather than write and mark-up at the same time. 
> Tip! A great way to help learners do this, if you have access to an instructor’s computer and projector, is to do the activity on your own content along with learners, and project the results so everyone can see what you’re doing. 
* Start the file with a doctype tag-- this is one of the only tags that doesn’t have content inside, and no closing tag-- it’s a lonely single tag, reminding the browser, again that we’re writing html<!DOCTYPE html>
* Add an <html> and </html> tags that wrap around the ENTIRE page-- so everything inside can get tagged with markup language. 
* After this, make a section with a set of tags called <head> </head> at the top of the page, before all your written content. We’ll put one bit of content in here for the browser, but we won’t see it appear on the main page itself. This is the page title, which:
    * defines a title in the browser tab
    * provides a title for the page when it is added to favorites
    * displays a title for the page in search engine results. 
* Next, add the tags-- these should be around the entire text for the page. 
* Use h1 for your page’s top headline, the on-screen title for your story (different from the title tag)
* Use h2 or h3 tags for section headings
* Use p tags for paragraphs
* Don’t forget your closing tags!
* For extra credit, add links to other sites (such as a page about your hometown, your favorite sports team, artist or musician, or a favorite recipe). You can also download and add images, just make sure they are in the “xx-webpage” folder. 
* Finally, when you’ve added all your tags, save the page! 
* Now, open your favorite browser, and go to File > open file. Navigate to your folder, and click on the html file you just made. 
How does it look? Are you seeing your content formatted for the web? Do you see your title appearing in the tab at the top of the browser bar? If things don’t look right, what might have happened? 
> Tip! Facilitator can troubleshoot here--- common problems are missing tags, especially closing tags, typos in tags, a document not saved as html, problems with image file names, etc. Facilitator can walk around and check pages, and discuss or even demo on the projected example what happens when tags are left off (for example, never closing an h1 tag is a great way to show the importance of closing tags).  
* Congratulate everyone on the pages they’ve made! They are now web designers! Remind folks that the pages are still on their local computers, and not actually on the web! But they are ready to go there. 
* Have a brief discussion about uploading to servers, about web hosting, what it means, how it works, how much it costs, what hosting companies do. 

### Go Online! 
[15 mins]
* If your institution has server space and resources available, show participants how to use a file transfer application (such as fetch) to transfer their pages to a folder on the server. Talk about UPLOADING vs DOWNLOADING
* Discuss how the URL will be constructed, ask users to figure out their own URLs -- domain name, class folder name, personal folder name, page name.
* Once all the pages are on the server, have users point their browsers to the URL on the web to see their pages. You’re on the web for real! Woo-hoo!
> Tip! If time, have a brief discussion of web hosting, what it means, how it works, how much it costs, what hosting companies do. 

### Learning Experience Reflection 
[5 mins]
* What did you like about this activity?
* If you might teach this activity to a particular audience, what might you change about the process, structure, or content to better meet the needs of that audience? 

### Feedback on Core Curriculum
* Tell us [how and where you're using the curriculum](https://github.com/mozilla/web-lit-core/issues/8) and [what you've learned and what you might change](https://github.com/mozilla/web-lit-core/issues/9).
