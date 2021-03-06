---
layout: post
title: "WEB101 And the World Wide Web"
categories: [WEB101]
description: "It has become common to refer to the Internet and the World Wide Web as if they were pretty much the same thing."
---


###### Web Communications 101/501


#### Module 1 Topic 1.2 ...And the World Wide Web?

### Introduction

It has become common to refer to the Internet and the World Wide Web as if they were pretty much the same thing. As we have seen this is not the case. The Internet is a system of hardware and siftware which enables the connection of multiple computers. The Web is an application that makes use of this functionality, just as email, Instant Messaging and other applications do. Accessed through clients named web browsers, the Web is a series of 'hypertext' documents all linked to each other to form a 'web' of information. 

However, it is the World Wide Web that constitutes the everyday 'public face' of the Internet, and which permeates our perception and cultural understandings of it. 

 

### Instructions

In this section we are going to examine the history and technologies behind the World Wide Web and the implications of hypertext on our understandings of information and writing.

Read through the information and videos below in your own time. You don't have to click every link, just pursue those that interest you and ignore those that don't. It's hypertext, after all...

Please complete the activities as you come across them in the text. These should be completed before the related discussions in either tutorials (for internal students) or Discussion Boards (for OUA & external students). 

## Part One - A Little More History

The ideas behind the Web had been fermenting in various ways since the end of the Second World War. The notion of an easily accessible and internally linked repository of information was first touted in the writings of Vannevar Bush in a 1945 article entitled 'As We May Think'. Although Bush's vision was limited somewhat by the technologies of the day (Bush imagined the information would be stored on Microfiche), he proposed a workstation called a 'memex' that would be used to store and access information in ways intuitive to the human mind:


"The human mind does not work that way. It operates by association. With one item in its grasp, it snaps instantly to the next that is suggested by the association of thoughts, in accordance with some intricate web of trails carried by the cells of the brain. It has other characteristics, of course; trails that are not frequently followed are prone to fade, items are not fully permanent, memory is transitory. Yet the speed of action, the intricacy of trails, the detail of mental pictures, is awe-inspiring beyond all else in nature.

Selection by association, rather than indexing, may yet be mechanized. One cannot hope thus to equal the speed and flexibility with which the mind follows an associative trail, but it should be possible to beat the mind decisively in regard to the permanence and clarity of the items resurrected from storage."

By the 1960s, computing technology had developed to the point where the idea of networking computers was now possible. In 1968 researcher Doug Engelbart, working on a project humbly entitled 'The Augmentation of the Human Intellect', had developed the first working mouse, bit-mapped computer screens and, most importantly for the development of the Web, 'Hypertext': (Video Duration 3 Mins.)

 
      

[https://www.youtube.com/watch?v=mT_PhstIBIA] (2007)

Hypertext is a way of referring to the linking system that enables us to jump from one page to another by intuitively 'clicking' our mouse on a highlighted word.

In 1989, drawing on previous hypertext systems, CERN researcher Tim Berners-Lee proposed the notion of "a large hypertext database with typed links" that could operate using the backbone of the Internet and thus be shared by all computers that were connected to it. Although his idea did not gain much support at the time, Berners-Lee continued to work on it until, by the end of 1990, he and his colleagues had developed all the tools required for a working World Wide Web. These consisted of:
•A Transfer Protocol (HTTP - HyperText Transfer Protocol)
•A Web Server
•A Language to Display the Information (HTML - HyperText Markup Language)
•A Web Browser (Named WorldWideWeb)
•The First Web Pages

In August 1991, Berners-Lee posted a short summary of his project on the newsgroup alt.hypertext:


"The WorldWideWeb (WWW) project aims to allow all links to be made to any information anywhere. [...] The WWW project was started to allow high energy physicists to share data, news, and documentation. We are very interested in spreading the web to other areas, and having gateway servers for other data. Collaborators welcome!"

This post coincided with the debut of the Web as a publicly available service.

Although Berners-Lee had developed a graphical web browser, it only ran on the little-used NEXT operating system. In 1992 students Marc Andreessen and Eric Bina developed a graphical web browser named Mosaic for the Unix operating system, followed shortly after by releases for the Apple Macintosh and Microsoft's Windows. The pair went on to form Netscape and released the proprietry browser Navigator in 1994.

From 1993 onwards, public awareness of the Internet and the Web skyrocketed. It is estimated that Internet useage during the 1990s grew by 100% every year. The World Wide Web was the public face of the Internet, and within a few years, URLs become a common sight as business moved onto the Web. On the other hand, the simplicity of HTML meant that anyone with access to a computer and a modem could create thier own personal 'home page' on the Web. 

The Web was a many-to-many communications medium.

Media(2007)

 

## Part Two - Understanding HTML and the Web

A web browser is a piece of client software with which we can access the WWW. In this case, by access we mean retrieve and display hypertext documents that are stored on web servers around the world. Our browser requests the page, the server delivers it, and the results are displayed in the browser window. In this section we will be looking a little more at how that happens, both the recovery and the display.

### About URLs

The addresses on the Web with which we have become so familiar are known as Uniform Resource Locators (URLs). URLs were one of Berners-Lee's ideas to aid in remembering specific places on the web. When we type an address (i.e. http://www.curtin.edu.au), our browser makes a request to a Domain Name Server that translates that address into an IP address (i.e. http://134.7.179.56). 

While most users think of URLs as being ‘www’ addresses, there are a number of different URL formats, (referring to the ‘service’ part of the URL format):
• Web : http://www.
•FTP : ftp://ftp.
•Email : mailto:user@host
•Usenet : news://user:password@host:port/newsgroup

### HTML and Hypertext

The documents we view on our browsers are predominantly written in Hypertext Markup Language (HTML). HTML is a language that describes how a page should look when it is viewed in a web browser.

Have a look now. Go to the menu of your browser and locate a menu item named 'view page source' or similar. 
 You should see something like this:

 



This is the source code of the HTML document you are looking at.

Although HTML can first appear somewhat intimidating, especially if you haven't been exposed to computer code before, it is actually quite simple. 
 Importantly, despite the name, HTML isn't code in the programming sense, it is a 'markup' language that describes how the page looks. 

Most of this is done through the use of 'tags' that are surrounded by angle brackets <>.

As an example, a web page that looks like this in your browser:



Will have source code that looks like this:



But if we add a new tag to the source code (in this case a tag indicating a bold typeface)...



...the appearance of the page changes:



This is just a tiny example of how HTML works.

As well as formatting text, images can be added and, most importantly, hyperlinks can be created to other pages. This is Hypertext.

## Activity One - Show me the HTML!

Unless you are embarking on a career as a web designer it is unlikely that you will be encountering HTML code frequently. In fact most contemporary designers don't even create HTML code by hand anymore. Commonly they will use a WYSIWYG (What You See Is What You Get) application that creates the HTML on-the-fly in the background, while the designer concentrates on getting the layout right.

You yourself will have encountered WYSIWYG HTML editors in this course when using Blackboard.
 In this activity we are going to use Blackboard to demonstrate how HTML is created automatically when you post a message to the boards:
•Open up Blackboard in a separate window.
•Log in (if you aren't already) and go to the message boards for this unit.
•Create a new post and name it "My Test message"
•Type the phrase "Hello World" into the body of the message. It should look like this:

### Blackboard
•Now click on the HTML button (see above).
•A new window should open showing the HTML code that the editor has created from your text.
•Now close that window.
•Highlight the text and use the bold button to make it, well, bold.
•Now click the HTML button again.
•What has changed?
•Now close the window again, remove the bolding and convert the text to italics.
•Again, click the button to see how the underlying code has changed.
•Feel free to continue experimenting to see the impact of your changes to the HTML - try adding a link to the text and see what happens...
•When you're done, you can just hit the 'cancel' button so your test post doesn't appear on the boards.


Please note: in some browsers the full set of editing tools may not appear in Blackboard - try a different broswer if the tools above do not appear for you. 

## Part Two - Hypertext (Why the Fuss?)

Although the idea of Hypertext had been around for quite a while before the Web, it was Berners-Lee's technology that really saw the idea come to fruition. The term was originally coined by computing pioneer Ted Nelson in the 1960s:


"By hypertext, I mean non-sequential writing -- text that branches and allows choices to the reader, best read at an interactive screen. As popularly conceived, this is a series of text chunks connected by links which offer the reader different pathways" (Nelson, 1981)

The arrival of hypertext caused a great deal of excitement for post-structural theorists who had been announcing the 'death' of the author for quite a while. What hypertext meant to them was the literal embodiment of the idea that it is not authors who create texts, but readers. 
 If you find this notion a little confusing, try reading these short excerpts from George Landow's 1992 book, Hypertext, which go some way towards explaining these ideas...

1.The Definition of Hypertext and Its History as a Concept

2.Annotation in a Print Text

3.Roland Barthes and the Writerly Text

4.Reading and Writing in a Hypertext Environment

So, read any good hypertext novels lately? Probably not.

As it turns out, hypertext hasn't been particularly well suited to the creation of literary fiction, although there have been some interesting examples:

Excerpts from Victory Garden by Stuart Moulthrop

What Fits by Adrienne Eisen

Twelve Blue by Michael Joyce

Hypertext has, however, been incredibly powerful in demonstrating the applicability of Vannevar Bush's ideas about the way we approach information. Who hasn't experienced the pleasure of 'surfing' the Web? Jumping from one fragment to another, riding waves of information, turning our attention to whatever takes our fancy at any given moment?

This is the website of Justyn Allyn Hall. It's a great example of the kind of ways that people started using hypertext when it first emerged. This fragmentation is typical of the kind of experience hypertext can offer.

At the same time, a website like the online encyclopedia Wikipedia demonstrates the power of hypertext systems to literalise Bush's notion of "selection by association". 

The early web was built on the idea of these static pages, all interlinked to form an enormous repository of information. But since those early days, the technologies behind the web have changed dramatically and web pages are no longer limited to a static form - they can be generated dynamically.
 Next week, we shall look at the implication of the web as a platform for applications - Web 2.0

How Big is the Web?

In July 2008, Google reported that it had indexed 1 trillion individual URLs:

1,000,000,000,000

It's that big. (2008)

## Activity Two - Going Way Back...

One of the most interesting resources on the Internet is archive.org's wayback machine. Since 1996, this non-profit organisation has been archiving web content in order "to help preserve those artifacts and create an Internet library for researchers, historians, and scholars." We are going to take a little look at the early days of the web by using the wayback machine:
•Click this link to open a page in a new browser window.
•You are now at the front page of the Internet Archive. Type www.curtin.edu.au into the wayback machine and perform a search.
•Take a look at the Curtin web site from January 1997, January 1999, January 2002 and January 2005 to see how the front page of the website has evolved. Well, at least it's better than the University of Western Australia's site!
•Now, open the wayback machine again and have a look at the early web pages of some of these companies:
•Apple.com (October 1996)
•Google.com (November 1998, back when it was a prototype)
•Wikipedia.org (July 2001, back when they had over 6,000 articles!)
•dominos.com (February 1997 - To find out where their 1000th store was...)
•Have fun exploring the history of other sites....and when you're posting personal information to the web in the future, remember the Wayback machine!




##### Something Optional - "The Web That Wasn't" (Alex Wright)

For those who are particularly interested, here is a fascinating talk (Duration: 1 hr.) that details the earlier attempts to develop hypertext systems prior to Tim Berners-Lee. The talk covers the work of Vannevar Bush, Doug Engelbart and Ted Nelson amongst others, offering a glimpse at some ideas that were left by the wayside in the development of the Web, but maybe should not have been.

###### References

(2007). Doug Engelbart 1968 Demo - 3 of 9. Retrieved April 1st, 2009, from http://www.youtube.com/watch?v=tYCMlMidvTM.
 (2007). newmedia2.jpg [Image].: schwartztronica.
 (2008). We knew the web was big. Retrieved April 4th, 2009, from http://googleblog.blogspot.com/2008/07/we-knew-web-was-big.html.

###### Links 

 

*NEXT: Module 2 Introduction - Web 2.0*
