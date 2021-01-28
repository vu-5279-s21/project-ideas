# Project Ideas

Please add your project idea to the end of the file. Do not edit any of the other text. Do not remove the sample project idea or the template for ideas. Do not remove anyone else's project idea. Do not push an update with merge conflicts.

## Project Idea: Data Science Platform (Sample Description) [Don't Edit]

This project will build a platform for exploring large datasets and applying pre-built machine learning algorithms to the data. The team will implement a Java Spring-based web platform for uploading, browsing, and formatting datasets. In addition, the team will implement a variety of machine learning algorithms / techniques that can be applied to the data. The machine learning modules will primarily be implemented in Python.

The platform will focus on classification tasks. Users will be able to upload datasets in CSV or JSON and then select attributes of each data item to serve as labels. Once labeled datasets are available, users will be able to use graphical tools to draw a machine learning pipeline and choose algorithms to apply to the data without coding.

## Project Idea: Your Project Title Here [Don't Edit]

## Multiplayer Party Game
For my senior design project, I am going to build a multiplayer game where players will compete in a variety of mini-games in an effort to progress around a virtual game board. Players will be able to create persistent accounts and engage in synchronous online multiplayer games with one another, whether with randomly matched players, or with a local game hosted on a friend's device. This project is inspired by the success of multiplayer games such as quiplash, among us, and fallout guys. Games such as these have seen a huge uptick in popularity during COVID and have been a great source of entertainment for many of people - providing an outlet for social activity that doesn't have to break social distancing guidelines. 

This project will likely be written in react native in order to achieve cross platform compatibility for mobile devices, and will hopefully use a distributed game server to support concurrent multiplayer functionality. Having a wide array of potential minigames to develop will allow for our agile process to produce meaningful working content at each stage, while also allowing for enough potential creative leeway to keep pushing our development process forward with new content throughout the semester. We will have to use graphical tools to implement game sprites and such, and may have to implement basic physics engines for some of the minigames as well. As far as non-technical specs go, a significant chunk of time will probably be spent developing designs/ minigames that can be incorporated into the larger game.


## Project Idea: Music Theory Analytics Platform

The goal of this project is to develop a platform for analyzing and looking into the music theory
of songs by utilizing machine learning algorithms to first get the individual stems of a song (like bass, vocals,
instruments, percussion) and then performing different transformations on each waveform. Plenty of sites provide
basic lyrics transcriptions or information on the chords, but often skim past deeper harmonic structure, actual chord
progressions and voicings, or song form. The team will implement a Java Spring-based web platform with the goal of 
concrete functionailty to compute the basic song features, such as individual song stems, determine time signature, 
key signature, BPM, develop accurate chord charts and transcribe lyrics for a basic framework of the song. 
The actual algorithms for chord recognition, stem splitting, and downbeat tracking will be implemented in Python.

The platform will also seek to provide advanced analytics to the music based on genres. Users will upload a mp3 or a wav,
and by again implementing machine learning algorithms based on common chord progressions and Roman Numeral Analysis, songs 
that follow a similar harmonic structure can be compared to provide users with different voicings (e.g. closed and shell 
voicings) or different chord substitutions and reharmonization. This functionality is dependent on scraping existing 
data on chord structures of songs to recognize common substitutions, allowing users to explore new arrangements or methods
of song production and mixes.

## Web-scraping and data analysis on the stock market

Web-scraping is a crucial technique during the burst of big data, and handling the skills to make meaningful analyses from this information would help us gain important insights. Out of the vast amount of resources available on the internet, I'm distinctly interested in exploring the mysterious stock market. To achieve that goal, I propose the project to scrape financial stock-related information, such as the open price, bid, ask, volume, total revenue, and the market cap of a company, from credible finance websites. After the scraping algorithm performs well, the later stage of this project aims to perform a rudimentary or intermediate market analysis to recommend as to buy, hold, or sell a given stock. The project may point to various directions of development, such as statistical graphic generations, data analyses, or recommendation systems. 

I believe that this project is large in scale while manageable for students with all levels of expertise in python and web-scraping.  The project is adjustable and encompasses a wide range of possibilities concerning its potentials for developments and usages. From a developer's perspective, the web-scraping algorithm could be used for researching the market's sentiments, the prospects of an industry, or a straightforward graphic display of a stock's statistics. From a user's perspective, the final product might be used for personal interests in studying and investing in the stock market. Furthermore, the project has great potentials to be developed and supported on various technologies, imposing no limitation on computer systems -- such as iOS, Windows, or Linux -- that the developers are using. It doesn't need much extraneous support to work on this project, such as getting a compatible hardware device, borrowing a server, or matching dozens of software' deployment settings. 

## Restaurant Recommendations

This project idea is for a restaurant recommendation app that uses recommendations from people on various sources to determine which restaurants are most well-liked in an area for various different categories. For example, it can browse reddit posts discussing burger places in Nashville to find which places are most often recommended. Unlike traditional reviewing platforms, this project idea will focus on giving you a recommendation rather than an evaluation of a place you searched.

The application will browse the internet searching searching places where people often discuss restaurants and compile the different recommendations into a database that will list different restaurants, their frequency of recommendation, and their category. It can be set to automatically search for new discussion at set intervals. A key problem to solve will be interpreting the different ways people talk on the internet, including mispellings and multiple names for places. When users use the application, they will be able to select a location and some limiting factors such as type of cuisine, and the application will generate a list of recommendations for them in order based on popularity and how closely they match the user-given preferences (such as pricepoint).

## Stock Sentiment Analysis using Twitter

This project will build a platform for investors to track activity of a particular security or the overall market on social media for e.g., Twitter and use predictive analytics to flag stocks with unusual mentions. Previously, the data used to predict movement in stock prices was mostly objective in nature such as darkpool transactions, put/call ratio and unusual market orders etc. However, the increasing popularity of retail investing and its discussion on social media provides an opportunity to collect data on these platforms, correlate it with the objective metrics and finally flag/predict unusual activities in securities trading by providing the sentiment towards a security in real time.

The goal would be to classify a security in simple terms such as positive, negative or neural. A general Twitter dataset would be used to train the model. The tweets will then need to be processed in a form which is clean and appropriate for Natural Language Processing (NLP). Then, deep learning models (like Logistic Regression, Linear SVC, K-Nearest Neighbors etc.) would need to be used to train the model and find the most suitable model. This model is then used for real time predictions of tweets which are obtained using an API key. The goal is of this project is to provide users with an accurate analysis of subjective and objective information in real time and help identify market opportunities. 

Project contacts: Samarth Kalra
Team members: TBD


## Infinite Canvas Whiteboard

This project would, essentially, solve the issue of limited zooming when trying to take notes on a touchscreen/stylus based device. Right now, no platform has a great way to take notes that isn't pixel based, meaning when you zoom in you end up with a pixelated image, or if you zoom out you only have tiny controls that are hard to use to take notes. The few vector based drawing apps are hard to find, clunky to use, and aren't created with any specific users in mind.
There are a number of potential end users, and there would be a heavy load of design work upfront. The most obvious use of a fully vector based drawing program would be for diagraming, including scientific diagrams and more complex visualizations, that simply can't be done on the limited canvases most apps currently allow. It could also be very useful for making presentations in a similar manner as Prezi allows, but with less limits on the size of the canvas. Some people may use a social drawing board, where many people can work together on one "white board" of sorts, without running out of room. Finally, it could be useful for someone who wants to organize their notes visually, instead of in separate files. This project would focus on creating a useful and targeted design that would utilize an infinite, vector based canvas.

## Two-Factor Authentication Application

This project is focused on developing a basic authenticator application for use in a two-factor authentication system. The plan is to design and develop an application (mobile or otherwise) that uses a time-based one-time password system: after synchronizing the application with a website, both the site and the application will simultaneously but independently generate and refresh a single-use password. The user receives the password from the application, and enters it into the website or device, where it is validated allowing the user to log in.

In order to develop and test such an application, it would also be necessary to develop a basic website with a login system. This scope of this project therefore covers both mobile app development and basic web development, although the intent of the project is to focus on the application aspect. The application should ideally be a mobile application in order to reflect a practical two-factor authentication system, but because the focus is on understanding the underlying systems that allow for 2FA to work, the platform on which the authenticator application is made is flexible.

Project contact: Daniel Dong (daniel.p.dong@vanderbilt.edu)
Team Members: None committed

## Cooking Guru

Cooking Guru is a mobile and web application that will include two main services. As a mobile application, it will be available on both Android and Apple devices. The need for this application comes from the poor distribution of food currently in America. The first service is a pantry service which will allow users to enter in items that they currently have within their pantry. With this list of items, the users will then be able to search for a list of recipes that they can make given the items that they have listed within their account’s pantry. The application will be able to search for both recipes for cooking and recipes for drinks.

The second service will be a social media platform that allows users to connect and share their personal recipes. Most importantly, users will be able to post personal recipes 
as well as images of the dishes they have created. Users will also be able to connect with each other and search for popular/trending dishes. In addition to this, they will be able to like and favorite posts from other users in order to save them for later. Finally, users will be able to leave ratings on recipes that they have seen or tried, altering a recipe’s visibility to other users.

## Daily Decision-Maker

My idea is to make an app that will make decisions for you. Personally, I stare at my closet for at least a few minutes in the morning trying to decide what to wear. My friends and I can never pick a movie to watch. We never know what we want to make for dinner, or whether we should get takeout. These all seem like very trivial decisions, but according to research done by the host of the podcast The Happiness Lab, Dr. Laurie Santos, we all make thousands of trivial choices every day that can sap our energy and leave us feeling exhausted and mentally worn out. She also describes research that shows when there are more options, you feel less happy about the one you end up choosing, no matter how positive that choice ends up being. 

The idea for the app is to minimize the trivial options that people have to choose from every day or make those decisions for them so that they can focus on more important things. For really common decisions like the ones I mentioned earlier, we can have a database of options from which an answer will be chosen. If someone wants to pick a movie, the app will ask them what genre or if they just want a random movie, then come up with a single suggestion so that the user doesn’t have to make a choice. For food suggestions, the app will ask whether they want to cook or eat out or if they just want to go random, and it will come up with recipes and a grocery store or a nearby restaurant. For what to wear, the user could input items from their wardrobe and the app could choose an outfit by taking the weather forecast into account. The app wouldn’t be limited to just these decisions. The users themselves could be a source of data for the app, and as more and more users add the daily decisions they have to make, the database of questions and possible answers will grow. 

Research shows that needing to make fewer decisions can lead to a happier life, and this app would aim to achieve that.

## Meal Recommender

Ever since COVID began, people have been cooking in far more than they used to. As a result, there is often a random assortment of groceries left over in people’s fridges and pantries. My idea is to create a mobile app that would allow people to enter the ingredients they had, and the app would suggest recipes that use those ingredients. In addition, the app would allow users to select the types of recipes that they preferred, so that those would be suggested. 

My vision is that the app would tap into some larger database of recipes. Once results for a certain group of ingredients is entered, the user could sort through the recipes using different filtering functions such as cuisine type or calories or spice level. Since I have a little bit of experience with python and react native, I am planning on using react native as my framework to complete the app. However, this is a place where I may change my plans should I find a more suitable framework to use in order to complete the app.

## ReFood
My project idea is a web application that has two main focuses- reduce food waste and eliminate 
hunger in communities. While interning at a non-profit serving people experiencing homelessness, 
I would visit Panera every Thursday evening to pick up unpurchased baked goods to give to those 
in need on Friday morning. The amount of food from one day at Panera served over 75 people, and I 
begun to think about how much food is thrown out the other six days of the week and how it could
help many organizations. Furthermore, I thought about the food waste at other restaurants and the 
need for food by a sizeable population in my community.
The web application would consist of two logins- one for a food supplier and one for a receiver.
The format is flexible and open-ended, but I envisioned a way for the food supplier to post 
availability days and a receiver to request days. Once the request is approved by the food supplier,
that day is no longer available for other receivers. A recurring option (weekly, monthly, etc) would
help with consistency between suppliers and receivers. Primary points of contact for each 
organization will be included to provide an ease of communication between the two parties. I am 
passionate about the idea but open to many different ideas and possible implementations. 

## Voice Controlled Website Navigation

The project goal is to build a platform that enables users to customize a voice controlled chrome navigation extension. Users will be able to link their specified voice commands for general navigation from opening up a website to creating their own command that works specifically on certain websites. This can be implemented using a variety of speech recognition APIs such as Google Speech API, Speech API, Web Speech API, etc. 

The project allows for a host of additional features such as the ability to recognize multiple languages, linking commands together with a single command, enable private mode and so on. Users will be able to create commands using drag and drop features linking a command to a single action or a chain of actions. From there, commands can be linked together possibly allowing sentence activated commands. 

## Web Scraping and Price Analysis 

An application that will show competitive prices for a certain product. These prices will be obtained through some form of web scraping and displaying the data on the site, as well as in the database. 

The idea behind this project is to create an application that functions as a hub or a "one stop shop" for a certain product. This will contain pertinent information to the user, such as the price of the product. This project is vague at the moment because there are numerous options for what the product can be (including shoes, clothes, textbooks, etc). Deciding on this product will come with more research on what websites allow scraping, to be extremely careful on what is done.

An example of the product is shoes. Say someone is looking for shoes from FootLocker, Finish Line & EastBay. Scraping the product pages from these websites will allow for the data, such as price, to be obtained and displayed on the website. With this website, users can look in one spot and compare prices from different competitors, lessoning the hassle of visiting many different websites to see prices and important information.


## Public Speaking Skills Enhancer

This project will build an application for users to practice their public speaking skills. The implementation of this application could change, but it is currently planned to be implemented using various Amazon Web Services tools including Amazon Transcribe, Lambda functions, DynamoDB, and Amazon Comprehend, etc. The user will speak to the device (phone, computer, etc.) for practice and this application will highlight possible fixes to enhance your public speaking. 

Some of the highlights will include identification of user customized keywords such as "umm", "uhh", and "like", analysis of both long and short pauses, and calculation of the tempo of the overall speech. The application will allow users to analyze both live and recorded speeches. The application will first display the transcribed speech with highlighted possible fixes and allow comparisons to other users/famous public speakers. Further development of this application could include identification of the tone and the volume of the speeches.


## Tinder Meets Netflix

 This project will build an application for users to help figure out what to watch on netflix or other streaming services with your friends. How this application works is you group up with the friends you want to watch with, in the group you select which streaming services you have available to check from, then you just swipe on movies until you all match on one together to watch. 
 
 This will help get rid of the struggle of trying to figure out what yo uall want to watch on different streaming services. This will also have some features such as allowing you to check genres you want and dont want to watch. You can have a friends list to make it easy to group with your friends when you want, and can see a history of past movies watched. 

## CityPark

I call my project City Park. Tell me how many times have you gone to any city (especially its downtown area) and found yourself circling countless city blocks before you can finally parallel park your big SUV into that spot that’s probably only meant for sedans? If I were a betting man, I’d guess your response would be “numerous” or “a lot”. Well, the idea for my project is an application to help combat all of this wasted time if you know your destination. Maybe think of it as Waze, but for parking. 

I see 3 main features of this application. I’d like it to be able to take an input location and based on how easily other users can park, output all available parking options if there are any. These parking options include parallel parking required, metered parking, garage, completely free parking, etc. Next, I’d like to store parking availabilities for certain areas and make predictions on availability in the case that no users are currently reporting data for that area. Finally, in the scenario that there is paid parking, I’d like to have a feature that interfaces between the customer who wants to park and the company/person who offers parking. This type of information would help the predictive feature but also would help customers so that they don’t have to be running back to their cars to put a ticket stub to say they paid for parking for the next 2 hours.

## ResQ

The fostering and adoption community of Nashville is in need of a platform to centralize communication between animal shelters, rescue organizations, and volunteers. As a proud member of the foster community, I receive 3-4 emails a week requesting an available foster for dogs in need – all ranging from sick dogs, to newly-born puppies, to pregnant moms. However, the communication between all parties is highly inefficient. Due to their frequency, the emails are often sent to spam, and if I reply to foster, I am left scrambling for information in a long email chain of information easily lost in my inbox. The volunteer often picks up directly from the animal shelter, where information from the rescue organization is not always transmitted clearly. On the other hand, the rescue organization deals with a large influx of responses, and it is not discernable whether or not the requested foster is equipped to deal with large dogs, small dogs, medical cases, etc. The current system can be greatly improved and I propose a platform to do so: ResQ.

ResQ is a platform where animal shelters, rescue organizations, volunteers, and potential adopters can communicate to achieve the mission of finding all dogs a forever home. Depending on your affiliation with one of the four above groups, the platform showcases different functionalities. Rescue organizations can post animals in need of fostering as well as any other relevant information: pictures, age, breed, pounds, personality, medical needs, behavior (i.e. potty trained), space requirement (i.e. large yard), pickup place and time, etc. If a request to foster is received, the organization can easily cross check stored information about the foster to make sure the individual is equipped to handle the animal’s needs. Foster volunteers are notified as soon as a new posting is up, and can scroll through the postings with highlighted relevant information, eliminating the inconvenience of many lengthy emails. Volunteers can also set their notifications to filter animals in certain categories; for example, Jane is only able to foster dogs under 40 pounds in her apartment and prefers puppies. Once a foster exchange is confirmed by the rescue organization, ResQ takes care of everything on the backend. ResQ communicates shelter information, directs the foster to the shelter, and schedules a time for supply pick up, removing the need for repetitive conversations with every foster. ResQ will also directly notify the animal shelter, and feature a messaging service in case additional information is needed between parties. Potential adopters will be able to scroll through a message board of dogs currently available for adoption, and apply through the platform – handling the paperwork for the rescue organization. As an added bonus, community members, adopters and fosters alike, will be able to donate to the shelters, rescue organizations, and urgent medical cases! ResQ streamlines the rescue, foster, and adoption process with a platform that gets dogs into homes – efficiently and lovingly. 

## YESplus
My software project idea is to add and/or extend some functionalities of Vanderbilt’s Your Enrollment Services (YES) site. This can be done through the use of a Google Chrome extension which students can choose to install or, for better accessibility, an integrated widget which launches specified “extra” functionalities. I see this project as a way to learn more about web integration and containers while also potentially helping out future Vanderbilt students during course registration.

A widget display popup in the Student Registration section could allow students to see useful resources, such as their degree audits or weekly schedule based on enrolled and/or in-cart courses, while browsing for courses. Another useful resource that once existed as a Chrome extension for YES, the Rate My Professor extension which displayed professors’ ratings according to RMP next to their names under courses, could be remade and reintegrated. These functions could be created and extended to YES through use of Java/JS.


## Spotify Friend Recommendations

One of the best features of Spotify is how social it is with the ability to follow your friends, see what they're listening to, and easily share playlists. Additionally, Spotify has robust algorithms used to create recommended playlists based on individual preferences. For my senior design project I plan to combine these features to make it easier to share music recommendations with friends. I will create a web application to generate customized playlists for Spotify users based on the music their friends are listening to.

Spotify has a large collection of personalized playlists already-- Discover Weekly, Release Radar, Daily Mix, etc. The application will use a similar algorithm to create a playlist consisting of songs chosen from another user’s public playlists. This project will involve using the Spotify Web API to access a user’s profile and preferences, as well as creating the user interface for the web app.


## recruit.com: All-in-One Solution for Undergraduate Recruitment

As we are now entering the second semester of our senior year, we all have seen countless friends engage in months-long frenzies to recruit for internships and jobs. I found that this recruitment process, one that begins in freshman year for some, was extremely overwhelming and complicated. The information necessary to navigate the complexities of this process was scattered, varied, and certainly not consolidated onto a single platform. While resources like company websites, online forums, the Vanderbilt career center, and employer information sessions were helpful in navigating the internship/job market, I never came across an all-in-one resource that could help guide a college student through this process of transitioning into the working world. My project proposal is to attempt to create an all-encompassing online resource in the form of a website that streamlines the recruitment process for undergraduate students and helps them both discover the employment possibilities that exist as well as how they can obtain such possibilities. This could be thought of as a DoreWays on steroids. (It could also be integrated with DoreWays and websites like Vault.com.)

While the scope of this project will certainly need to be narrowed, I would like to mention just a few of the potential features this website could have:

Multi-Industry Exploration: A section of the website dedicated to informing students of some of the most popular industries for Vanderbilt graduates. This section could include statistics related to the number of recent Vanderbilt graduates who entered various industries, their salaries, and the positions they hold. It could also include contact information and interviews with former students about their current roles and industries. (The school of engineering publishes similar data yearly.)

Single-Industry Exploration: A section of the website dedicated to a specific industry such as the technology industry. Such a section could include popular entry-level positions (SWE, PM, Data Scientist), their associated salaries, difficulty of attainment, recruitment process, Vanderbilt alumni, etc. (Such a section could be linked to external ranking and informational sites such as Vault.com.)

Role-Specific Recruitment Pipeline: Such a section would give a comprehensive overview of a single recruitment pipeline, such as that of SWE. It could provide the user with features such as the overall process and timeline for general internship/job recruitment, the skills necessary for position-specific interviews, as well as links to preparation resources.

User Candidate Hub: Such a section would allow users to conglomerate industries, companies, and roles they are interested in as well as track their “progress” in their overall recruitment strategy. This “progress” could be companies they are in contact with, scheduled an interview with, received an offer from, etc.

## Used Textbook Marketplace
This project will address the difficulties that students face in buying and selling college textbooks. Used textbooks are sold at meager 20%-30% discounts from publishing houses and bought back at 60-70% discounts, revelaing a large profit margin that could be returned to students by removing the monopolistic grip that publishers hold over this market.
This project would establish a marketplace for buyers and sellers to transact, in hopes of helping both parties, and lessening the assymetric information gap that publishers leverage and exploit. 

The platform would require students to validate their identity with their email address and phone number. When submitting a bid or an ask, the students would have to specify the course, the book name, author, and volume/edition, the desired/existing condition, a few pictures of the book in the case of an ask, and the price of the bid/ask. Upon placement of a bid/ask, the publishers of an existing listings would be notified via email/text of the bid/ask details, regardless of if the request falls within their acceptable margins, to facilitate negotiation and exchange. The application wouldn't be responsible for the negotiation process or the financial transaction, as those responsibilities would fall on text/message/social media apps and cash/check/online payment apps, respectively. 


## HeartbreAKA Website Phase 2
Every year, the Elegant Eta Beta Chapter of Alpha Kappa Alpha Sorority, Inc. has hosted a date auction event where attendees can donate money and art supplies to receive AKA dollars which can be used to bid on the bachelors during the event. Due to COVID, the chapter can not hold their event in person this year. Therefore, they wanted a website to be built that could be used to facilitate gathering donations and hosting the live auction.

Last semester, the website was built to their standards. However, the current state of the website requires that someone with coding experience would need to know how to change anything on the website. That is the goal for this semester! As a team, we would work  to create a localized database structure that could serve as a place to store all the data that is currently hardcoded in the website (i.e. text and pictures). We would also work to create a UI that can allow for a future member of the chapter to change the contents of the website. In addition to that, we will work on implementing a way for the colors and layout of the website to be changed based on their preference. This project will be a great opportunity to learn new skills in website design and database management.

## Crafting-centric roguelike
Roguelikes are a genre of role-playing games with a long history, and they are known for characteristics like high degree of randomness in the generation of levels, permanent character loss with little inheritance between playthroughs, emergent gameplay due to systems interacting with each other, and a focus on management of limited resources in the form of randomly generated items (both permanent equipments and single-use items). In addition, they are often turn-based, set in an enclosed "dungeon" setting (courtesy of DND campaigns, one of their main inspirations) and features tile-based ASCII graphics. My idea is to create such a game but with a highly integrated crafting and equipment-customization system, with enhanced ASCII based graphics, modernized UI, and cross-platform support.

In this idea, instead of generating items with unidentified but unchanging purpose, raw materials would be generated in the map instead. The player would need to find or construct crafting stations to make raw materials into equipments and single-use items useful for survival and progression. The said equipments would be highly modular, and spending more materials to enhance, modify and add new attributes to existing equipments would be the main form of progression in this game. Crafting and modifying of equipments require recipes which can be character innate, found through progression in the form of randomly generated blueprints, or discovered via consuming raw materials and enemy drops. 

## Survival iOS app
This project will create an iOS app that is level based. The objective of the app is to avoid obstacles by tilting a player around a map with a limited number of lives. This app will utilize the tilt features of iOS development and will require basic object interactions. While the first game mode will consist of a basic survival playstyle where losing all lives requires starting over at level 1, different game modes can then be built out from this.

Development of this app will not require sophisticated background design and should focus on smooth playthrough with difficult but rewarding levels which are creative and unique. By the end of this development, a strong understanding of tilt mechanics within iOS, the in-game physics, and basic object design will be required to create the final product. Development of this project would be most effective with 3 or less members.

Email: james.e.hancock@vanderbilt.edu
Team Members: James Hancock

## ML Model Generator Interface

This project will build an interface with the Vanderbilt TV News Archive that will allow for the creation and training of AI (primarily machine learning) models. Primary component will consist of a python based program utilizing at least PyTorch and Scikit Learn if not additionally Tensorflow, and possibly other deep learning frameworks. This program recieve the following parameters: Task category (classificaiton, regression, etc.), task target (classifying segment type, generating captions for audio, etc.) model structure and training parameters.

Once model creation has been tested and is functional, additional time will be spent adding additional options for model creation, as well as developing a django based API for requesting and sending models.

