# Go Todo

A monlithic todo application written in GO and vanilla JS with redux. This application is a back to basics app where I wanted a break from React and all of those types of frameworks. I wanted to practice the "old" way again and refresh my memory of what all these frameworks do for you.


# Goals
- use as much of the Go standard library as possible. I may break a rule when it comes to the router. No one wants to parse regular expressions. 😀
- Make the application look close to the design. Design can be found [here](https://www.frontendmentor.io/challenges/todo-app-Su1_KokOW).


# Technology Choices
- Go is growing on me. What started out as a journey to learn a new language in 2023, has slowly become my go to language for most applications. Go is simple and while not the most "hip" language is a pure workhorse that gets the job done. I really love the fast compiler and deploying binaries rather than having to ship a runtime. 
- JS has eaten the world. However, most of the people I work with have learned JS from a framework like React. Which is sad. I wanted to go back to the basics and build a frontend the traditional way that was served from my Go backend like it is 2005 all over again. 
- For this app, I did not want to ship a database. My todos are not that important. However, I did want persistence. So, The application has a shutdown hook that writes out the todos to a file. On application startup it will use that file for the initial todos. 

