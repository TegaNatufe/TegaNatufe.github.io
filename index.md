# Welcome to the NHS 3D Printing Web Service Development Blog

In this blog, our team - called Team 31, will document how the development of the 3D printing web portal for the NHS progresses. We'll document each stage, starting from the gathering requirements stage all the way to the final prototype or product.

## Update 1

We created a MoSCoW document to give us a rough idea of what features are important and needed to be implemented, as well as the less important features.

The features that we decided were must-haves included:
* Ability for users to create accounts   
* Option for users to upload models online
* Users must be able to view other models
* Search through models using description (key words), or formats
* Users must be able to download models
* Send 3D models to destination 3D printers
* Web portal interface to access the service

Features that we decided were less important were:
* A smart search that would suggest models that fit user's previous requirements in terms of dimension and formats
* Ability to manipulate view of models e.g. zooming in/out, rotation, flipping
* A 'Remember Me' log in feature to reduce the number of log ins 

## Update 2

Our team held virtual meetings with our clients on Microsoft Teams, in order gather their requirements for the project. This included finding out how they wanted access to the web portal to look like, as well as the parameters that could be used to search for the 3D models.

## Update 3

Our team was given a HCI (Human-computer interaction) assignment where we were tasked with designing and evaluating a prototype for your software system for a 10-slide HCI report in PowerPoint. This included drawing a wireframe prototype in order to get an idea of the web portal's functionality and structure, as well as drawing sketches of the interface.

In this assignment we had to document the different stages of the development cycle. For example we wrote about how we discovered user requirements for the product.
Furthermore, we also wrote about how we designed alternatives and see which early prototypes were better. We also documented our thought process behind the use case scenarios. Considering who our target users were and their personas was also important in our assignment.

![image](/media/PHOTO-2020-11-09-20-16-15.jpg)
![image](/media/IMG_00B1DBA5F01E-1.jpeg)

## Update 4

Our team held a virtual meeting with our course teaching assistant (TA) on Microsoft Teams. We discussed the technical details of beginning the development of our prototype. These details included: 

* Putting great importance on the interface e.g. viewing 3D models
* Finding a way to import 3D models
* Comparing the advantages and disadvantages of using one solution over others
* Having to consider both the front end and the back end sides of development
* The early first prototype could just import models from the local drive, just to get something working

We found this meeting with the TA very helpful as it gave us a sense of direction as to where to focus development on.

## Update 5

To get a better sense of the structure of our project, we drew UML diagrams and sketched the front end of the web portal. We also started work on the backend, with the most important tasks being to create a 3D viewer page from a 3D file and returning the link to that page so that it can be embedded in containers in the frontend.

![image](/media/WhatsApp%20Image%202021-01-02%20at%2011.28.08%20AM%20(1).jpeg)
![image](/media/WhatsApp%20Image%202021-01-02%20at%2011.28.08%20AM.jpeg)
![image](/media/WhatsApp%20Image%202021-01-02%20at%2011.28.09%20AM%20(1).jpeg)
![image](/media/WhatsApp%20Image%202021-01-02%20at%2011.28.09%20AM.jpeg)
![image](/media/WhatsApp%20Image%202021-01-02%20at%2011.28.10%20AM.jpeg)
![image](/media/WhatsApp%20Image%202021-01-02%20at%2011.28.11%20AM.jpeg)

## Update 6 

We developed the first working version of our 3D printing web service prototype. Our team also did some research into what technologies to use, and we considered using Sketchfab. Sketchfab would allow us to upload 3D files and and store them, as well as generate a preview page - exactly what we needed. Additionally, we thought about using a table with meta data, so we wouldn't need to use file storage instead. We hosted this prototype on google servers instead of using other services such as Azure.

![image](/media/prototype1.jpeg)
![image](/media/prototype.gif)
 
## Update 7

We went further into the development of our prototype, successfully connecting the client with the CMS, and we got the embedded 3D model html file to generate automatically on upload. All we need is a backend, with which we could send the URL and model meta data to. 

![image](/media/update7-0.jpeg)

On our web portal, when we tried to use embeddedURL as the html page for the preview, we got this erroneous response. 

![image](/media/update7-1.jpeg)

## Update 8

We've made additional progress on our prototype. We implemented a Microsoft single sign-on feature, as requested by our clients at the NHS.

The first login page acts as a register, the web portal will then prompt you to choose the UCL one when the people at the NHS try and log in. (This prompt didn't occur when we ran it because we already had an account.) We only intend for NHS and UCL users to be able to log into the web service.

![image](/media/updateVideo1.gif)

This shows a full funnel through the NHS web app.

![image](/media/update8-1.gif)
![image](/media/update8-2.gif)

## Update 9

We designed a new UI for the web portal. We felt that this new user interface design made it easier for users to navigate the website. The colour and font of the text as well as the colour of the background in order to provide better colour contrast, and thus make it more readable.

In addition we used a lot more blue in this new design compared to the old design so that it would make the web portal look more like the other NHS webpages. We also incorporated more images to help bring the website to life. If you look near the top of the website you can see we implemented a navigation bar to make it easier for users to access what part of the 3D printing web service they needed. Whether that was finding a 3D printing facility or searching for a clinical 3D model for example.

![image](/media/update9.jpeg)


## Update 10

We again redesigned the web portal's UI. Acting on feedback from our clients, we decided to make the web portal look more like the real NHS website. For example, we created an A-Z index section to enhance navigation of the website and make searching easier. We also made a website footer at the bottom of the page to provide quick access to important links and information such as contact details.

In the 'Find a 3D printing facility' feature, we integrated Google Maps to allow users to locate nearby 3D printing facilities. It would've been much less efficient if we had taken the choice to 'reinvent the wheel' when there were preexisting solutions. 

![image](/media/newui1.jpeg)
![image](/media/newui2.jpeg)
