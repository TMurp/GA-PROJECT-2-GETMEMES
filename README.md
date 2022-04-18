# GA-PROJECT-2-GETMEMES

### Deployed Project Link

https://bit.ly/3K59zYL

## Overview & Concept

### Contributors

Contributors: [Tom Murphy]([github.com/TMurp) & [Tony Haunschmidt](https://github.com/tonyhaunschmidt)

### Brief

This was my second project during my Software Engineering Immersive Bootcamp by General Assembly, it was completed 5 weeks into the course and the start of my coding journey.

This was a pair project with a timeframe of two days. The goal was to create a front-end React App using a third party API. This was my first project working in a group and using my newly acquired React, SASS and API interaction knowledge.

This app takes data from the following API developed by [Dev Daksan](https://github.com/D3vd): https://github.com/D3vd/Meme_Api

### Concept

The website we created is called .get(memes). We created a user experience that allows for endless randomised meme browsing. After pair-coding to set up the React app and page basics we split the workload, since we had limited time my partner Tony focused on functions for randomisation and searching whilst I focused on styling and animations.

We decided to go for an unusual and unique page layout. The central control bar allows users to search for a certain meme topic or simply click either the logo or randomise button to refresh the meme collage surrounding the control bar (our aim was to take full advantage of the quick loading of new assets without refreshing the page that React provides). 

If the user clicks on a certain meme it will take them to the show page, here the meme is shown in a bigger size and related memes are displayed in a grid on the right half of the page.

### Technologies Used

- JavaScript
- React
- JSX
- CSS
- SASS

## Approach Taken

### API selection

To ensure we could achieve our vision we had to thoroughly research and test third-party APIs. We used Insomnia to send requests and review the data returned.
We found Dev Deskan's public Meme API detailed above, we decided to use this because of its simple data structure and good documentation regarding end points.

### Wireframing

We used excalidraw.com to create our wireframes for each page. We used these to visualise the front-end and the styling needed.

![image4](https://user-images.githubusercontent.com/94997077/163825024-6d6cac4c-9a43-496e-ac61-a416b79e45cb.png)

### React

This was our first project using a framework, in this case React. Unlike my previous Vanilla JavaScript project that had all of the JavaScript on a single page, we split the code into 5 components;

- Home page
- Centre bar
- Meme show page
- About page
- Spinner

I found this great for organising and keeping code clear, we had the DRY principle in mind.
This was also our first time using the React Router DOM for navigating to different pages of the website. 

![image5](https://user-images.githubusercontent.com/94997077/163825173-97dc8774-a150-46c5-86cd-006426cc5af8.png)

Hooks were a strange concept to me at first but during this project I discovered how useful they are. We used useEffect to send a get request, save that data to an array then take a small sample of that data and add it to our useState smallMemeSample.

![image3](https://user-images.githubusercontent.com/94997077/163825207-7fb331ae-d023-4ecc-b81e-a27be777beb8.png)

Also seen in the code above is our use of Axios. This was our first project that uses an API so we learn a lot about end points and how to make requests with the front-end. The Meme API we used had various custom endpoints where you can specify which subreddit you wanted the memes to come from as well as sample size. Below is our code for the search function and it’s get request via Axios.

![image1](https://user-images.githubusercontent.com/94997077/163825249-e54a54bc-40b8-44c8-8763-a1c834c0faca.png)

## Styling

After pair-coding the core functionality of the site my main focus was styling. We decided that having a good user experience and interesting page design would be better than a couple extra features.

Our vision was a centralised control bar with the memes clustered in a collage around it. We kept the amount of meme images displayed low to encourage the use of the quick loading randomisation of new images.

To create the centralised page layout I used 6 flexboxes. Each using different flex-direction, justify-content and align-items to place the images in the centre of the page.

<img width="194" alt="image2" src="https://user-images.githubusercontent.com/94997077/163825313-a2221106-19b5-43f6-9cf6-b3543a7b067e.png">

My next challenge was that each meme image could be drastically different in size and aspect ratio. The images would overlap and be unreadable, so using max and min widths and heights I made sure no images would overlap no matter their size and aspect ratio.

## Challenges, Bugs & Wins

### Challenges

The biggest challenge for me this project was achieving the centralised image collage. It took a lot of tweaking and testing for all the different image sizes and aspect ratios.

### Bugs

The search function can cause errors when entering certain words, we were unsure exactly why this was occuring.

![image6](https://user-images.githubusercontent.com/94997077/163825393-d8e0a4a6-ac90-4756-87e3-bed93ac505e7.png)

### Wins

Successfully using React hooks to send requests to API and display that data on the page.
Creating a unique and fun design, I learnt so much about CSS flexboxes and animations in this project.

### Future Changes / Improvements

Further tweak CSS to make fringe case images display properly.
Add more animations.
Fix the search bug.

### Key Learnings

I learnt so much about React, the React-router, hooks, Axios and JSX. I now feel very confident using it and further increase my competency in my next two projects.

Group coding. This was my first time group coding and using GitHub to collaborate on the same project. By the end of this project I was very comfortable with pushing and merging our branches.

APIs. I understand how the front-end interacts with an API, the different requests and data structures received.

### Contact

Email - tommurphyse@gmail.com

Social - [linkedin.com/in/tom-j-murphy/](https://www.linkedin.com/in/tom-j-murphy/)

Project Link - https://bit.ly/3K59zYL

GitHub - [github.com/TMurp]([github.com/TMurp)

