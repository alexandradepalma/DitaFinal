To: Chris Lindgren
From: Alexandra DePalma
Subject: DITA topic model design rationale
Date: 22 December 2015


As part of this assignment for 4662W, I have put together this memo reflecting on my experiences constructing my DITA topic model and explaining the rational for constructing my topic model in the manner I have selected. I will cover my rationale and explanation in the following order: 1) What is included, 2) Why I organized in the manner I have, 3) The goals of my topic model 3) How each of the topics and relationships support this goal 4) My design decisions. For your reference, my topic model can be viewed at: github.com/alexandradepalma/ditafinal.

My topic model features a concept that explains what LZW compression is and how it relates to image files, a reference topics that explains what certain terms relating to LZW, GIF, and PNG mean, and three tasks that relate to PNG, LZW, and images. 

The first task is on how to choose between GIF and PNG files. Although I was uncertain whether or not this task was necessary (it seemed obvious to me in what instances GIF files are better than PNG), I came across research indicating that GIF and PNG files are used with almost identical frequencies across the Internet and  several infographics describing whether to choose between a PNG and GIF for your file format This task walks the reader through the selection process for choosing a PNG or a GIF format for their image files and, I believe, is a necessary step for the reader to make before continuous through my topic model. 

The second task I’ve included is on how to create  a GIF using the terminal. Prior to completing this topic model, I had never made my own GIF and had simply used GIFs available on the Internet. I downloaded software using Homebrew, a sort of open source software library for mac users. Unfortunately, this task topic only covers the process for making a GIF on a mac OSX system. I personally operate with an OSX system and did not feel comfortable writing instructions for how to do something on a machine I am not familiar with. Additionally, I wanted to be able to test my own instructions and would not have been able to do so on another operating system. 

The final task in my topic model focuses on how to convert files to the PNG format using the terminal. Initially, I was not going to include this task as I felt it silly—you can easily select “PNG” as a file format for saving after creating an image file in Photoshop. However, I believe that it is useful to know how to create PNG files using other methods (plus, using the terminal can be fun). As with the previous task, I performed this activity on an Apple computer and therefore the instructions are tailored towards an OSX terminal. 

I have organized my topic model to start with the concept piece explaining LZW compression. I think that it is important to begin with the explanation because the explanation provides background information about LZW and sets the stage for discussing the importance of image files. 

From explaining LZW, I moved into a reference topic in which key terms are defined. I believe that it is important for the reader/ user of this topic model to know this information prior to embarking on tasks. I considered including this information at the end of my project because many textbooks contain the glossary or dictionary at the end of the book, but I ultimately decided that this information was more powerful when presented early on in the topic model.

After the reference topic, I have my reader go through a task that helps them decide whether to choose a GIF or PNG file format for their image. I placed this prior to the following tasks because I thought it was important that the reader have a clear understanding of which file format is more appropriate in certain situations before deciding to make a GIF or convert to a PNG file. 

The task on GIFs shows the reader how to make a GIF using a video file and the terminal. I included this reference topic after the viewer selected between GIF and PNG and before how to convert to a PNG file because I believe that this is the more complex process and more interesting of the last two tasks.

Lastly, I included a task on how to convert to a PNG using the terminal. I included this because I believed that it is important to know how to convert to certain image files within the terminal. I closed my topic model with this task because it is very simple and straightforward and I believe that it is better to end on a simplistic high note rather than with the reader confused by a complicated task. 


The overarching goal of my topic model was to show a practical application of LZW. Initially, I intended to have one of my tasks be how to hand code LZW, but that proved to be tedious and something that had 1) no real world application and 2) no interest to anyone other than an encryption nerd like myself.  I believe that my topics support this goal. The concept topic supports this goal through explaining LZW and how it relates to images and what LZW is. The reference topic supports this goal through showing how certain terms tie LZW and image files together. My task in which the reader chooses between PNG and GIF supports the goal of showing practical applications of LZW through showing the pros and cons of two different image files that both use LZW or a variation of LZW. When I explain how to make a GIF using the terminal in my second task topic, I believe that this goal is supported because the reader has the option to demonstrate a live example of LZW. This also works with the PNG file task topic because it shows the application of LZW within the lens of another image file format.

My design decisions were fairly straightforward. I did not do anything very risky or dramatic with my formatting. I explained the order and organization of my topic model above and therefore do not believe that there is much more to say on the topics of design or organization. 


My biggest challenge in creating this DITA topic model was generating a working, cohesive output file. I struggled with the code and ultimately found that I had made silly mistakes—numerous tags not closed properly, the DOCTYPE tag not clearly defining if I was working with a task/ concept/ reference topic, my DITAMAP not featuring clear links to the my task topics… Overall, this demonstrated the importance of proper proof reading and very meticulous behavior when writing code. 


