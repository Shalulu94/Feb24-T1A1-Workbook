# Term 1 Assignment 1 - Workbook

This document includes my answers to the workbook assignement for Term 1 - Coder Academy

All questions and answers will be included in this markdown document

Please see link to Github repository for the readme file. https://github.com/Shalulu94/Feb24-T1A1-Workbook

## Q1: **Identify** and **explain** common and important components and concepts of web development markup languages:

A Markup language is text-encoding system which defines how the layout and presentation of text and images should appear in a digital document (Samy Sadok, 2023). It gives us the ability to structure and format content as well as a standardized way to define elements which makes it easier for computers and software applications to interpret and display content (Lenovo). 

Some examples of popular markup languages include:
- HTML
- XML
- XHTML
- SGML

Markup languages focus on the presentation and structure of content on a webpage and a well structured website facilitates easy use by humans and computer programs such as search engines. Based on this, a couple of markup language categories include Semantic Markup and Presentational Markup:

- Semantic Markup: Helps to define the different elements on your webpage. The same fomatting can be achieved using non-semantic tags such as <.div> or <.span> but semantic elements define each element which makesit easier for search engines or other parties to better understand the content (Samy Sadok, 2023). Some examples of semantic markup elements include:
    - Headings
    - Nav
    - Section
    - Article
    - Footer
- Presentational Markup: Directly affects contents appearance on the webpage by using specific tags within the content to impact display features. These tags are typically added directly within the markup language and within the content. This is now no longer best practise and we have other methods of updating design features away from the content and structure. 

Another important concept of markup languages in web web development is related to responsiveness and accessibility. Responsiveness relates to how a webpage's structure will change depending on the device that a user has accessed the webpage on. It is important for the structure of a webpage to shift fluidly across different devices to ensure that all information is present and continues to be displayed in an accurate and complete format. 

Proper accessbility enables user with a disabilityto access and interact with a website. Markup languages can be interpreted by screen readers and other assistive technologies allowing websites to reach all users. Semantic elements already assist with this as the already add meaning to the content structure of your website via their specific tags (Samy Sadko, 2023)

## Q2: Define the features of the following technologies that are essential in terms of the development of the internet. Explain how each technology has contributed to the development of the internet:
 - **Packets** - When data is transmitted over a network it is broken down into smaller parts known as "packets". The purpose of this is to ensure that network paths do not get congested with large files and allows for efficient transmission. A packet typically consists of a header and a payload. The header includes information about the source and destination addresses, sequencing information on how to reproduce the original file once all packets have been received and routing information. The payload includes the actual data that is being transmitted
 - **IP addresses (IPv4 and IPv6)** - An IP Address is short for Internet Protocol Address and is a unique identifier for a device or network that connects to the internet. It allows for computers within a network to identify, communicate and transfer data between each other. Two versions of commonly used IP Addreses are IPv4 and IP v6.IPv4 addresses utilize a 32-bit numerical format, accommodating around 4.3 billion devices. With the rapid expansion of users on the internet, these IP addresses were being consumed and would eventually become exhausted. In 1998, IPv6 was introduced which was a new protocol using a 128 
 Recognizing the impending depletion of available IPv4 addresses, IPv6 was introduced by the Internet Engineering Task Force in 1998. Employing a 128-bit scheme, IPv6 vastly expands the address pool to accommodate up to 340 trillion trillion trillion unique addresses, effectively resolving the address exhaustion concern and fostering the internet's continued growth. Moreover, IPv6 offers additional advantages over IPv4, including built-in Quality of Service (QoS), integrated network security via IPsec, support for multicasting, and larger packet headers.
 - **routers and routing** - Routers are devices that connect two or more networks together and manages the traffic between these networks by routing data packets to their corresponding IP addresses. A router could form part of a Local Area Network (LAN) or a Wide Area Network (WAN). Both are just networks, but a LAN can typically be managed by a single router which for example could be a single household in a neighbourhood. A WAN would be a collection of routers which form a Wise Area Network and could include all of the households within a neighbourhood all interconnected and able to send/receive data between each other. Through the utilisation of specific IP Addresses, the routers can route data to specific locations within the network. 
 - **domains and DNS** - 

## Q5: Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.

- **Python**: Python is a simple and versatile programming language and is known to be extremely beginner friendly. Python is 'open source' which means it can be used by everyone and there are a lot of libraries and frameworks which can be imported into python to assist with data visualisation, data science, machine learning and data science.

Some drawbacks of python include the fact that it has high memory usage compared to some other programming languages and thus may not be the most efficient option for programs with an emphasis on performance. It is also a constantly updated programming language and thus some libraries and frameworks can only be used in certain versions of python which limits its capabilities for future proofing solutions. 

- **Javascript**: Javascript is another very beginner friendly programming language and is used to build dynamic and interactive web applications. Javascipt has high speed and efficiency due to it's ability to execute on the clients side which minimises reliance on server resources (Vaishnavi, 2004, Ellow.io). Javascript can also develop both front-end and back-end within a single language which reduces complexity and makes it easier to code and maintain websites. 

Most of Javascript's drawbacks come from security reasons. Given that code is visible to everyone on a webpage, this make it easier for unauthorised access and data breaches to occur and requires additional security measures to protect sensitive data. Also since Javascript runs within the users browser, if a user was ever to disable Javascript on a website due to security concerns, then this could cause significant loss in functionality on the website. Each browser also has slightly different implementation methods and capabilities and so there could be some inconsistencies between different browsers that must be considered if using javascript. 



 ## Q6: A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.

 Hi Alex,

 Thank you for your email and providing detail regarding your website requirements and objectives. The good news is that based on your requirements, we can definitely design and develop a website suitable to your needs and hopefully help attract more visitors to your museum. 

 In order to address your requirements, the website will require some key features such as:

 - **Multi-page website**: This essentially means that your website will have multiple different pages that users can navigate between using a navigation bar that will be present and static across all pages. By having multiple pages on a website, you will be able to separate different topics you want to display to your customers onto their own specific pages. This will also help users to navigate to the a specific page quickly if they wanted to quickly find the answer to something. For example, if a customer wanted to quickly find out your contact details to phone/email, they could navigate directly to the 'Contact Us' page. Some page titles you will need based on your requirements would be:
    - About us - Brief description about the museum, it's purpose and history
    - Exhibits - Outline what exhibits are on showcase in the museum
    - Gallery - Display page to showcase your artifacts. Can include pictures and descriptions
    - Contact Us - Contact details and potentially even a contact form they can fill out
    - Getting here - Direction details

- **Semantic HTML**: HTML will be the markup language used to input all of the text, visuals and elements that you want to include in your website. In order to make your website as accessible as possible, we will ensure to use semantic HTML tags where possible as this allows better access for users with impairments. It will also allow search engines to better read your website and return your website to users searching for it. 

- **CSS Styling**: After all the elements have been included, we will use CSS to style your website to make it look appealing to the user and include features that alow it to be more interactive and responsive. As we don't know whether your users will be accessing your website on their computer, tablet or mobile we need to ensure that the website is responsive and can adjust itself depending on the users device. This ensures that no matter how or when the users acces your website, it will always be presented in a format that is clear, appealing and easy to use. We can also add transitions and animation effects to different elements to help interactivity as users scroll through your website. All of these functions can be built according to your requests. 

- **Domain**: You will also want this website to have a domain name similar to your Super Awesome Museum name so that it is relevant and easier for users to find. We can ensure that a domain name is reserved for you and once we deploy the website online, people will be able to access it using something relevant such as www.Superawesomemuseum.com. 

We hope that this gives you a bit of an idea of what we can do when building your website. We want to ensure that your website delivers all the necessary information to your users in an interactive, responsive and meaningful manner. 

Hope to hear from you soon and assist in building this website. 

Thank you,

Shahrul

## Q7: Think back to a scenario or situation in your own software development projects or work. Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.

Our most recent project was the website portfolio assignment where we had to design and create our own website from scratch and was given full creative control over the design. Whilst the project was exciting, it was also daunting to get into building a website with despite having limited knowledge and understanding of the capabilities of HTML and CSS. 

Based on this, one of the greatest difficulties was in the design stage with the wireframing and sitemaps. I chose to do a simple website design simply because I was unaware of how much complexity and flexibility CSS provided. If i had to redo this task, I would firstly conduct more research into the capabilities of the languages that I was planning on using. Visit more websites, each with diverse target audiences and backgrounds and inspect the code used to develop all of the different elements. This would have exposed me to more design opportunities when first planning the layout of my own website and is something I would do differently. 

Secondly, the coding aspect of my website required multiple redo attempts to clean up and optimise my code. Not having a clear understanding of the coding and design functions resulted in a lot of errors and readjustments. I feel that if I had taken a bit more time to structure my plan and code certain elements in a planned sequence, then I could have created classes better, optimised semantic HTML and kept my code as clean as possible. 

## Q8: Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.

Within software development, networking is key to success within the industry and this has been re-iterated to us repeatedly. To ensure my success in this new role, I aim to leverage my existing contacts and network to create opportunities to penetrate into the industry and secure a role as a software developer. Currently I am already working together with internal teams at my current employer Vocus (Which is a telecommunications company) to better understand how we utilise technology within our own backend systems. I currently work as a Pricing manager and have senior contacts within the Data & BI, IT/Tech support and product management teams all of which utilise their own software and systems to develop programs to improve efficiency within the business. I am already working on data projects with the Data & BI team to create dashboards and tools to help improve internal processes and manipulate source data into a format that is informative, readable and modifiable by the end user. My plan is to continue to work closely with this team on projects and aim for a secondment to get first hand experience working within a team, utilise agile work methods and develop solutions to solve internal problems and inefficiencies. Some of the programming languages I have already been exposed to include SQL and Python. 

I will also keep a close eye out on any networking opportunities that come up within the Coder Academy ecosystem and attend these events whenever and wherever possible. This will help me to gain further exposure to industry professionals and build relationships to help kickstart my career. 

I do believe however that utilising my existing network and connections to work on projects now and gain first hand exposure will be the best sort of experience to complement my completion of this course and secure my first tech developer role. 

## Q9: Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.

Language-learning model technologies are vastly increasing in their popularity and utilisation in recent years. Primarily, these technologies are used as supportive AI companions to increase productivity and maintain accuracy. These tools are designed to assist people and provide a new avenue to enhance learning capability and instruction. technologies such as Chat GPT can be used within reports and software projects to develop ideas, summarise thoughts and even contribute to a written technical document after scouring the internet for information and completing its own research on the topic at hand. The benefits of using such technologies include:

- **Improving Efficiency**: These AI technologies have the ability to scan vast amounts of data almost instantaneously and return an output which can summarise it's finding's in response to an input by the user. This can be utilised to help technical writers complete a project much faster than were they to do it manually by feeding information to the tech and then requesting for an output. 
- **Proof Reading**: These technologies can be used as a proof reading software to detect and grammatical errors where applicable.
- **Rewrite, structure and summarise**: As stated above, these technologies can be used to summarise or rewrite your own content into a more concise, professional or readable format. 

(Kingson, document360, 2003)

## Q10: Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.

Whilst language-learning model technologies such as ChatGPT are highly intelligent tools used to support our own works, it is important to ensure that we do not become completely dependent on their outputs. Legally there are issues that need to be considered before using these assistive technologies such as:

- **Privacy Concerns**: Machine learning uses and stores inputs from a number of different users in order to generate and educated response. In combination with it's own research via scanning through the internet for source information, it utilises historical inputs to continue it's learning. This means that whatever information you put into these technologies has potential risk to be accessed by external parties.
- **Intellectual Property**: Similarly to the privacy concern, anything that you provide to this technology can be used in responses to other users. Thus you could lose your IP rights once you grant access for these AI models to use your work. 
- **Duty of Care/Negligence**: It is important to understand that the output of these tehnologies may not always be accurate and sufficient care should be taken into reviewing the work before using it within any written or technical works. Should there be a fault or incident which arises through the use of the information generated by technology such as ChatGPT, the responsibility falls onto the user who used this information without proper review. 

So while these assistive technologies help to improve our efficiency, it is important to understand that they should continue to be used in a supportive capacity and never without review.

## Q11:Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.

### Soft Skills:

Soft skills in the workplace are those which can be applied to many different jobs/situations and are not specific to a particular role. These skills can be referred to as interpersonal skills and include a person's ability to communicate with their peers, how well you can work in a team and how well organised you are. These skills are important to ensure success and are much harder to develop as they also lean in towards people's personal traits. 

Within a software development workplace, having excellent soft skills would be an advantage as you would be able to communicate better with your colleagues. This would assist during information gathering phases before a project scope has been put together as you would be able to better understand the end requirements by asking the right questions and recording these appropriately. Also as a developer you will likely be working together in a team and a well functioning team needs to have a good working atmosphere and relationship. Soft skills directly relate to a persons attitude and attributes so having good soft skills will complement strong technical skills

### Hard Skills:

Hard skills are also known as technical skills and relate to a persons ability to perform a specific task or role. Unlike Soft skills, hard skills are easier to be picked up via further learning, education, practise and experience. In a software development workplace, hard skills would be very important as you will be dealing with specific programming languages and having better technical knowledge will allow you to create better products. For something such a software development, the technical skill can be more easily measured based on a person's ability to solve problems, answer questions or create a more efficient end product compared to someone else. So it is especially important to hone your hard skills in a software development workplace, but having soft skills to complement this will allow you to excel beyond that of just a technical developer.

## Q12: Explain multiple roles or job positions that would be found in a medium-sized software development company.

There are a number of different job roles and positions that could be found in a medium-sized software development company including:

- **Software Developer**: Software developers are the builders of a software system and utilise their programming skills to create software based on a list of requirements and guidelines. 
- **Software Architect**: This is an expert-level software developer who has an extensive understanding of software system structures. They create the technical standards of the software development lifecycle and ensure that any new software will meet the technical and functional requirements of the end user. 
- **Project Manager**: Project managers work together with developers, business analysts and product owners and oversee the entire development process. They ensure that a project is running according to schedule and within budget. They will also be aware of any issues that arise throughout the development process and can be a primary point of contact to get updates on a projects progress. 
- **Product Owner**: Project owners define the projects vision and priorities. They will be the ones to drive the intiatives forward and work with development team to deliver products that meet the needs of the users and business. They will be continually part of the project from conception through to completion and provide feedback throughout the production process. 
- **UI/UX Designer**: These designers are responsible for the front end interface of a software and ensure that it is both user friendly and visually appealing. They will work on wireframes, prototypes, user interfaces and perform constant testing. These designers are very important as they will be the ones who create the interface which will be seen by the end-user and need to ensure that it is easy to use but still retains all of its functionality. 
- **Scrum Master**: A Scrum master deploys agile working principles to ensure an efficient workplace. They will be able to identify any roadblocks by the development team through constant monitoring and frequent catch updates and encourage the team to share any concerns or findings in their work that could be relevant to other team memebers. They create a collaborative team and working environment. 


















## Reference List

- https://www.semrush.com/blog/markup-language/#what-is-a-markup-language 
- https://www.lenovo.com/us/en/glossary/markup-language/?orgRef=https%253A%252F%252Fwww.google.com%252F
- https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-packet/
- https://whatismyipaddress.com/ip-basics
- https://www.techtarget.com/whatis/definition/IP-address-Internet-Protocol-Address
- https://www.cloudflare.com/en-au/learning/network-layer/what-is-a-router/
- https://aws.amazon.com/compare/the-difference-between-ipv4-and-ipv6/
- https://www.actfl.org/news/the-role-of-technology-in-language-learning
- https://martinfowler.com/articles/2023-chatgpt-tech-writing.html
- https://document360.com/blog/chatgpt-for-technical-writing/
- https://www.ox.ac.uk/news/2023-05-05-tackling-ethical-dilemma-responsibility-large-language-models
- https://hallandwilcox.com.au/thinking/legal-and-ethical-issues-with-the-use-of-ai-including-chatgpt-in-healthcare/
- https://resources.workable.com/hr-terms/what-are-soft-skills#:~:text=Soft%20skills%20are%20general%20traits,re%20essential%20for%20professional%20success.
- https://www.intelivita.com/blog/roles-in-a-software-development-team/
- https://www.open.edu.au/advice/insights/what-are-the-most-popular-programming-languages

