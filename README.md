# AmyPearce_T1A1

# Question 1

- Markup lanaguages that are used in webdevelopment are HTML, XML, SGML, XHTML they are used to help structure and build a website. Anything you see on a website from headings, articles, links, and even images are created using these markup languages. The purpose of these languages is help organise and layout how your website will be presented online. There are many components and concepts to these languages and specfic steps to take.

## Components/Concepts

## Doctypes 

- Doctypes HTML help identify which HTML document it's coded in, the purpose is to communicate with the browser so it knows what should be on shown your website. Doctypes will always be the first line of code you should see. 

- HTML5 is the most reccent version and is the one that is reccomended, you can identify this doctype by seeing this code:
"< !DOCTYPE html >" HTML 4.01 and XHTML 1.10 are the other docutypes you may see in HTML but it can be more complex and complicated. You can also identify these by seeing: 
" < !DOCTYPE HTML PUBLIC > ", " < !DOCTYPE html PUBLIC "> 


## Tags

- HTML is structured by using different elements one of these elements are called "tags" A tag must start with an opening tag and finish with a closing tag. 

- "< header >" This tag is for your main header, usually the indicator of what the website is called.

- "< title >" This will be the name of the website and will apear in the title bar.

- "< body > " This is where all your content that is not a footer or a header should be placed.

- "< h 1 >" This is used to make smaller subheadings, you can use up to 6 different tags! For example h1, h2, h3, h4, h5, h6.

- "< p >" This is for paragraphs big or small! for bigger and blog type text you can also use "< article >"

- " < a >" This is used to add links for a example if you have a nav bar you can send them to your next html page or a completely different site. 

- "< div >" This is used so you can organise all your other tags into one container. You can also use " < div class ="Chocolate"> " to help style your content in CSS.

- "< img >" This is used to display images on your page, you will also need to use the "< alt >" tag to show where the content is from. 

## CSS 
 - Cascading style sheet is a very powerful and important part in HTML, with CSS you can go from changing your font colour/size to even creating borders on images. You can do many creative things with CSS, the great thing about CSS is it's ability to have several style sheets for each page. Using CSS will make your website more engaging and attractive. 

- To use CSS in HTML you must always link each style sheet individually using " < link rel="stylesheet" href="styles.css"> " into your " < head > " tag or the CSS will not be applied to your website. 


# Question 2

### Packets

- It's data that comes together with other data, it then gets sent to a computer network. Each packet has it's own job to be a part of a message to become a bigger message, this message carries important address information. Packets have limits as to how much data can be sent through each packet individually, that is why they come together to become bigger. Packets are a huge part of helping data transfer, without packets data can't breakdown and run through more than one path. This is essential as data can be in big chunks, the bigger it is the harder the transfer will be. 


### IP addresses (IPv4 and IPv6)

- IP stands for Internet Protocol, this is where the Packets of data move through and communicate so it is sent to the correct location. If you are sending something from one place to another these Packets of Data will break down, each packet will have IP, or the Packets will go to the wrong location.

- Every device will come with it's own IP address to help identify who it belongs to or where it is located. Packets of Data cannot route properly without an IP, this is why IP adresses are so important. We use IP addresses daily and it is the reason why we can use the internet. 

- IPv4 is one of the popular IP adresses used for devices, it is simple because it has a wide range for being used on many different electronic devices. The data that is quite large in the packets through IPv4 is broken down, this makes it easier for information to be sent through. 

- With IPv4 being used by a lot of people and the internet becoming so massive technologist had to make the decision to bring in a Network Address Translation. This helped shape how many devices at once you can have under a private/public IP address. 

- IPv6 isn't massively different to IPv4 but it is more advanced and better, you have bigger space for your IP address and better security for your more advanced devices. You can have a lot of different IP address that are different, if you are connected to a IP address that is under IPv6 you can customise the network settings. Overall it's better for our current generation, due to mobile devices that are connect to a IPv6 address will have decent security. 


### Routers and routing

- A router is a device that recieves packets and sends them from one location to another, this creates a local network connection. You can connect many devices at once with a router, it will usually find the best path. A router will still require you to have a modem as the job of the modem is to connect to the signal of your internet provider/phone company. Routers create a a stable wireless connection that helps improve the internet connection. The main reason why a router can be essential is the extra protection and gateways that a modem cannot provide.

- Routing is what makes a router run sucessfully, it starts a route that sends data packets through to a node. The node becomes the sender, it will then communicate with another node to transfer data to a router that is nearby. Routing has different three main purposes Static Routing, Dynamic Routing and Deafault Routing. 

### Domains and DNS

- Domain name 

- DNS stands for Domain Name System it works like a main source that has information, it communicates with the IP address. DNS has the job of making websites load their resources, without it we would need to memorize our own IP address. This also requires four steps the first is the DNS recusor, this works as a server searching for queiries from a device. The second is the root server this transfers host names to an IP address. The third step is the TLD namesserver this will search for the right IP address and become a host, it will host the end of the address name. The last step is Authoritative nameserver, this part is when everything comes together in order for it to work it must have access to the very original request, it will then sucessdully commincate with the Recusor. 


# Question 3

- There are different types of technologies that are essential to make web development possible. The ones that contribute to the development of client and server communication are TCP, HTTP, HTTPS, Request Methods, Rendering and Developer tools. 

### TCP

- TCP stands for Transmission Control Protocol, it's purpose is to be the messenger and works with the internet protocol. TCP is the reason information is sent through multiple network devices, it is that little boost to make sure information is accurate. It is affective by breaking down the big groups of data making information simple and have a smooth flow control. It is mainly about order and going to the correct destination, the TCP chooses the right IP address to every device connected to the the network.   

### HTTP and HTTPS

- HTTP stands for Hypertext Transfer Protocol it is the soul of the World Wide Web, it works as a link so you can view any webpage you like. HTTP is a client-server protocol this makes it possible for it to function correctly, it will peice the different recourses together. HTTP has come a long way since the 90s and with the ability to show more than just a text article HTTP can display images and videos. This all starts with a request that is sucessfully sent to the client-server protocol, this will then come up with a response, this is when proxies come into the process. HTTP is not a safe option if you are wanting to broadcast your senstive information because it is a different protocol, this is when HTTPS is so important. 

- HTTPS stands for Hypertext Transfer Protocol Secure, almost the same as HTTP but with the security. The purpose is to move very sensitive data from a web browser to a website, the type of data that you don't want other people to get their hands on. If you are doing something online that requires filling out information that is sensitive you will always want to use HTTPS instead of HTTPS. To identify if you are on a HTTPS website while in a webbrowser you will see the padlock at the very start of the search bar. If your url bar says "Not secure" you are not on a HTTPS covered by security of your sensitive information. The way the secuity works is by using encryption, this is apart of TLS and SSL. 

## Requests 
-	The way a request begins is with a Method, the web server can identify a type of Method by looking at the request line. There are many Methods they are called Get, Head, Post, Put, Delete, Connect, Options, Trace and Path. These Methods are so the server knows what data is being fetched depending on which request it is.

## Rendering
- Rendering is one of the most important parts of webdesigning, it brings a web site to life. Without rendering your code you wouldn't be able to interact with the website.  

# Developer tools
- Devloper tools let see what each part of code is doing on your website. This is always live so you can untick/tick boxes and see instant results. You should be able to bring it up in a seperate browser after you use a shortcut (CTRL, Shift, I or F12) This will take you to the menu bar just go to more tools then to Web Developer Tool. Keep in mind that Different browsers will have different steps to open the Developer Tool menu. This is handy as you can physically see where each elements are being applied, this way you are able to changed your code if you feel unhappy with your layout.

 (explain how each tech has contributed to the development of client and server communication over the internet 50 -150 words)


# Question 4

### Compilers and Interpreter 

- These two have different roles but work together to take the Source Code so it turns into a Machine Code, without this process the computer cannot understand the language clearly. The Interpreter takes the code and turns it into a high level language this way the Compiler can change it into a machine code. The Compiler has the more important job as it needs to pick up errors and needs to over look the entire program. 

# Question 5

### Python


### Javascript


# Question 6

### Email:

- Hi Alex,
Thank you so much for getting in touch! I would love to make a website to help your buisness grow. The first step would be sending me through some of your favourite images of any awesome artefacts, objects and paraphernalias followed by a discription for what each image is. I think this would be a key element to add to the website to help draw the right audience in! Any other information that you believe customers should know before visiting is also essential. For example the contact number for the venue, address opening/closing times and what you can see at SAM. I'm thinking a stoneage but minimalistic kind of style with light green, black and white colours? if you would like or have any particular style in mind please let me know, I want you to be satified with the result. If you have any other question don't hestiate to ask! Excited to hear back from you and start this website for you.

Kind Regards,

Amy Pearce. 

# Question 7

- My first time doing a tech project was when I had to create my own personal website portfolio for this bootcamp. It was challenging but along the way it became easier, I was understanding the languages better with practice. I would do a few things different if I had to do it again, one of them would be working harder on a draft. I would've then had more of guide as to what my website would've actually turned out to be like. I often found myself stuck on deciding the layout and focusing way too much on how it looked rather than if my code was organised correctly. Having a set draft would've made it all a lot easier and smoother sailing. 

# Question 8

- 



# Question 9

- Language-learning models work through AI and works as a chat assitant, basically like a bot chat. ChatGPT is one of the common AI models used as its very easy to use, it's so smart and effective it feels as though a real person is typing to you live. You could ask the model to write up a short story about something and it will respond back and write that story for you. ChatGPT is a free to use only if you already have account with OpenAI's as they are the creators. The purpose of a Language-learning model is to help a companys assit their customers without having to stress. 


# Question 10




# Question 11

## Hard Skills

### Programing Languages

- Having this skill is a highly reccomended skill to have if you want to become a software developer. When a company is intrested in hiring someone the main thing they will look out for is if you know enough languages, without this skill you're less likely to be successful or hired. It is a high-demand requirement as you can make many programs/websites using Python, HTML, CSS etc.

### Version Control Systems

- These systems help you keep all your code in check, you can have all your projects in one place. It can be seen by muliple companys/people if you want it to be viewed. This is fantatic for collabing with others if you are in a work space and want to show off all your hard work. Version Control Systems are also not something you can learn over night so having this skill will be impressive to developers. 

### API Inegration
- Stands for Application Programing Interface, the purpose is to help different applications talk to each other. API integration is an essential part in a development workplace without it you can't send data live and connect to external applications. You would need to go through a longer and slower process, more time means more money having to be spent on the company. API Inegration is useful in a development workplace because it's quicker and not as time consuming. If you don't want a company to have as much manual labour the it is something to really consider. 

## Soft Skills

### Attention to detail 

- This is a key personal skill to have because without it your projects can be very messy and may even not work correctly. Attention to detail is all about having a very good eye for many errors if you don't have this skill you will struggle. 

### Patience

- Software development is not an easy job you will bump into a lot of hiccups along the way. Having patience is so important as you need to always proof read everything, assesing exsactly where the error is coming from. When working in a team for a software development job always show you are willing to be patient and solve any issues. 

## Self-motivation
- Majority of time working in software development you have to self manage your projects. Self-motivation is so cruital because no one is going to push you to get your work done, it has to all come from you. It can be helpful to manage this by being organised and having set plans, for example using wireframes and trello.


# Question 12

- 

