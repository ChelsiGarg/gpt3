# Modern UI/UX GPT-3

## Introduction
This is a code repository for the corresponding website. 
[LIVE SITE](https://gpt-3-modern-ui.netlify.app)

### Aim behind building the project
- The project could be built without using react as the project involved just designing the user interface.
- But, if built without using react then there would be 1000+ lines of code. Also, the way code is broken down to several components to increase readability for others would not have been possible.
- Some components were reused in the project which have made the code even more shorter. So, due to the reusability feature of react, writing & understanding the code has become even more easier.
- So, the aim was to understand the importance of react and how it has made creating the User Interfaces really simple. 

While building the website, I learnt:

- React Functional components and their reusability. <!-- The article component, for example, was resued to create blog section. We were able to render same skeleton of article with different images & title by passing them as props -->
- React file and folder structure
- Fundamental CSS properties to master flex & grid
- Fundamentals of the CSS BEM Model
- From soft and pleasant animations to complex gradients <!-- gradients is taken from the site [angrytools](https://angrytools.com/gradient/) & animation is taken from the site [animista](https://animista.net/play/basic/scale-up). When we are on mobile device, we will see 3 dots in top right corner. When we click on it, we will see the list of links & this list will be opened in scale-up animation -->
- Perfectly placed media queries for satisfactory responsiveness covering almost devices

<!-- Problems faced
- There were many images that were needed to be imported, for example, in blog section. Now, in order to write the clean code, I did not want to include so many imports in the file. So, after searching, I got to know the trick that we can create a separate file where we can import all required images & then in blog file, simply import that file which has all the images imports.
- This was for the first I have used CSS BEM model. So, I tried my best in naming the classes according to this convention. I chose this convention to improve code readability
- Since, I wanted to make the website responsive. So, when I ran the website on mobile devices, I realised that the navigation bar became too messy while displaying all the contents lile: Home, What is GPT3, etc. Till this time, I was unaware about react-icons. So, then again after reading more about react, I got to know about these & hence implemented react-icons in order to improve user experience.
- I always find styling the components a bit difficult. So, this was a quite challenging part as I had to see the colour combinations, animations, gradient etc. So, writing down CSS was quite challenging for me.
-->

<!-- The website was created from [Javascript Mastery](https://youtu.be/LMagNcngvcU?si=7LaSLsE6YA0n1Kab) -->
