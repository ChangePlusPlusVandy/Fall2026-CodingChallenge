# ChangePlusPlus Fall 2026 Coding Challenge
***Due 9/18 at 11:59 PM (CT)***. 
Remember to submit [this form](https://forms.gle/JfR4cwAEwn4HhBuX8) when complete.

Please read this document **CAREFULLY** and to its **ENTIRETY**\!

**SETUP INSTRUCTIONS**<br>
To begin programming, fork this repository by clicking the **fork** button on the top right of this repository (directly across from the name of the repository and in between *watch* and *star*). This creates your own version of the repository with these instructions on your own user account that you can freely edit and contribute to. You will link this forked repository when you submit the form above.

If you're unsure of where or how to start, you can look into setting up your repository with [Vite](https://vite.dev/) and selecting React as the framework when prompted with a [Node.js](https://nodejs.org/en) backend or any other option you have in mind (No choice is better than another, do what you're comfortable with). These will come pre-built with some starter code you can look into to give you an idea of the fundamentals and you can work your way up from there!

**Before You Begin**  
The first step is completing the following coding project. 

* **Time Requirement:** \~5 hours (depending on experience level and technical skills).  
* **Note:** We will be having workshop(s) (structured presentations/tutorials) and office hours (unstructured help like TA hours) during the coding challenge. Join the Anchorlink and keep an eye out for an email\!

We recognize that you’re all busy, but as Change++ team member, it’s expected that you’ll dedicate 4-6 hours every week on your project.

**What We’re Looking For**  
At Change++, our teams include members from first-year undergraduates to graduate students with varying technical skills. We consider your experience when reviewing your code.

You’ll often work with new technologies not covered in Vanderbilt CS courses, so we value initiative and resourcefulness in learning and completing tasks efficiently.

We believe in you! You should be able to finish this challenge using basic programming knowledge (e.g., AP CS, CS-1101, CS-2201) combined with online resources.

Key qualities we seek in your code include:

**(1) Functionality**  
As always, the most important criteria is whether or not your code works according to the requirements. You should not only work to meet the requirements given, but also do your best to deliver a quality product, which may mean more than just completing the specification as stated.

**(2) Good style and Readability**  
As this is an untimed challenge, we expect a certain level of quality. Be sure to comment and format your code as you might while working on an application for one of our non-profits. Keep in mind we will be reading and trying to understand your code. It’s in your best interest to include intentional comments and meaningful commit messages.

**(3) Organization and Extensibility**  
This goes along with good style. We want to see your ability to develop maintainable code. Although we will not actually build further upon this challenge, you should organize your work in an intuitive manner which would make it easy to build upon in the future.

**(4) Creativity**  
Change++ members are people who use creativity and initiative to get things done. There will likely be plenty of applicants who attempt this challenge, so it will benefit you to make your program stand out.

**The Challenge**  
Sometimes you find something online that you absolutely love. You save it somewhere, forget where you saved it, and then spend 20 minutes trying to find it again.

Your goal is to build a **Image Saving/Sharing App** where users can discover, save, organize, and share content with others.

Users can create their own **collections**, save and edit content in those collections.

Your application should allow users to:

- Create individual boards/collections
- Search for images or other content
- **save/edit** content in their collections
- Remove content from collections
- View their own collections
- Make the application look **good**

You can take inspiration from existing applications of this nature like Pinterest or make your own interpretation, **No option is necessarily better than the others.**

To get your images you you can refer to this API documentation [Pixabay API](https://pixabay.com/api/docs/) or any other APIs and methods you're comfortable with.

## Deliverables 
**Frontend**  
The frontend serves as the way that a user would interact with your application. You have a lot of flexibility in terms of how you choose to build it ranging from a simple executable (ran from the terminal) to a website, app, or any (reasonable) technology you can think of. Feel free to get creative with styling components\!

**Backend**  
The backend consists of a RESTful API that can be accessed by the frontend and should do the following:

* Be a separate server from the frontend.  
* Endpoints to save images to a collection, delete images from a collection, share collections.  
* Store collections in some sort of data structure. Props if you store it in a database\!

**README**  
Aside from adding, committing, and pushing your files to the repo, include a README.txt (not .md). INCLUDE YOUR FULL NAME AND VANDERBILT EMAIL IN THE README. A README is helpful because:

* We need information about how to download and run your program, especially if you are using an unconventional programming method. Please write down some instructions for us to follow to properly see your program.  
* We want you to include a brief (under 100 words) reflection about the challenge. Did you learn anything new? Reinforce any known concepts? Any issues come up?  
* We are interested in any feedback you provide about the coding challenge. If you have any critiques for us; workshops, office hours, or any part of the challenge itself, please let us know.

**Completion Form**

For your challenge to be considered complete, you must submit this short form: [Completion Form](https://forms.gle/JfR4cwAEwn4HhBuX8).



## Scoring

**Frontend Framework: 5pts**  
Necessary - Gameplay works <br>
1 Point: No framework used (raw HTML/CSS)<br>
3 Points: React, Vue or Angular used<br>
4 Points: React, Vue or Angular used with Typescript OR a component library<br>
5 Points: React, Vue or Angular used with Typescript AND a component library

**Frontend Coding Style: up to 3 points**  
1 Point: Code works but minimal organization  
2 Points: Components structured logically, basic comments, consistent formatting  
3 Points: Clean, modular components, meaningful commit messages, consistent style throughout

**Backend Framework: up to 3 points**  
2 Points: Django, Flask, Spring Boot, or other non-JS backend framework  
3 Points: Node.js (Express) or Next.js used

**Backend Coding Style: up to 3 points**  
1 Point: Routes work but little organization or comments  
2 Points: Routes separated, consistent naming, readable code  
3 Points: Well-structured project (routes, middleware, db schema), documented endpoints, clear error handling

**Core Features: up to 3 points**  
1 Point: Create collections, add to collections, remove from collections only (no sharing)<br>
3 Points: Also allows sharing with unique URL and collaboration on a collection<br>
5 Points: Allows user accounts and sharing with accounts to collaborate and edit a collection

**Data Handling: up to 5 points**  
1 Point: Local storage persistence only<br>
3 Points: MongoDB/PostgreSQL/etc… database usage

**Aesthetics: up to 3 points**  
1 Point: Plain but functional UI  
2 Points: Some styling, responsive layout  
3 Points: Polished look (consistent styling, responsive, feels like a real app)

**Creativity / Bonus Features: up to 8 points**  
Some EC features could be:

* Private/Public Collection toggling
* Notifications on edit for shared collections
* Attempt to achieve architecture with low latency + high reliability (speed optimizations, rollback, etc)
* Implements lazy/optimistic loading

**README: up to 1 point**  
1 Point: Well-written README.txt

**Completion form:** required for the application to be considered complete!



## Tips, Tricks, and Helpful Resources

**We will be holding workshops and office hours to help you out. The following are the dates for these workshops :**
1. **Workshop (project overview, Git, and backend):** September 15th, 7:00 PM in FGH 110
2. **Office Hours:** September 16th

**If you have any general questions or want advice on how to get started/learn something, please email both Ashrit Anala & Sophie Zhuang at ashrit.ram.anala@vanderbilt.edu & sophie.x.zhuang@vanderbilt.edu (in one email) **

<ul>
  <li>DO NOT TRY TO USE C++ FOR THIS PROJECT! We will be impressed if you manage to pull it off but it would also be really hard. Python or JavaScript are probably the easiest language to use to meet the base requirements and is not that hard to learn for someone who knows C++. Java is also doable, but might be slightly harder.</li>
  <li>We are trying to simulate "real world development" in this project so Google/LLMs are definitely your friend. Be resourceful!! (Specifically, if you don't know where to start, you can google how to make an API in Python/JavaScript/etc)</li>
  <li>RESTful API
    <ul>
      <li>If you have never made an API before, it might seem fairly tricky. It is supposed to be a bit challenging, but definitely achievable and should not require a massive amount of code. There is a working solution of the backend written in less than 50 lines of code (note that it is totally ok if your solution is longer and a shorter solution is not necessarily a better solution, aim for clarity in your code).</li>
      <li>If you want to write an API, my first suggestion would be to google "how to write an API in {language of choice}". Follow a tutorial and copy paste some code and work with it until you generally understand what it is doing, then try to modify it to work for this project</li>
      <li>For a general explanation of what RESTful APIs are and how they work, check out this link: https://searchapparchitecture.techtarget.com/definition/RESTful-API</li>
    </ul>
  </li>
  <li>Git
    <ul>
      <li>If you have never used git before it might seem a little daunting but it is actually, for this project at least, fairly straightforward. If you have any specific issues with it, try google and if you still can't figure it out, email ashrit.ram.anala@vanderbilt.edu or sophie.x.zhuang@vanderbilt.edu for help</li>
      <li>If you want a basic tutorial on Git, check out this link: https://hackernoon.com/understanding-git-fcffd87c15a3</li>
      <li>To get you on the right track, the only commands you should need to use for this are `git clone {repo}`, `git add .`, `git commit -m "message"`, and `git push`</li>
    </ul>
  </li>
  <li>Good luck! We believe in you, and are excited to see what you create!</li>
</ul>
