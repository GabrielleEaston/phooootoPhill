# **Digi East**

## Project Planning

> – Image App that allows you to search differnt images and pin it to your Board
> – When you click on Image it takes you to a new Image page to show the deatails.

<br>

### Overview

_**Project Title** Digi East_

<br>

### Wireframes

> Use the Wireframes section to display desktop, tablet and mobile views.

![Dummy Link](url)

- Desktop Landing

![Dummy Link](url)

- Desktop Body

![Dummy Link](url)

- Desktop Resource Index

![Dummy Link](url)

- Desktop Resource Show

![Dummy Link](url)

- Tablet Resource Index

![Dummy Link](url)

- Mobile Resource Index

<br>

### MVP

> The Minimum Viable Product should be a well-planned and easily-communicated product, ensuring that the client's deliverable will be achievable and meet specifications within the time frame estimated.

_The **Project Title** Digi East._

<br>

####  MVP Goals

- Get a data from unspalsh Api when user enter a value in search Bar
- Add button that allows the user add favorite image to the board
- Clicking on image takes you to the ImageInfoPage to display the details about the image
- Responsive design on 3 screens Desktop, Ipad and Mobile
- Still debating between writing the tests vs component library

<br>

#### Libraries

> Use this section to list all supporting libraries and their role in the project.

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|   React Router   | _Lorem ipsum dolor sit amet, consectetur._ |
|   Axios          | _Lorem ipsum dolor sit amet, consectetur._ |
      

<br>

#### Data

> Use the Data Section to define the API(s) you will be consuming for your project, inluding sample URL queries.

|    API     | Quality Docs? | Website       | Sample Query                            |
| :--------: | :-----------: | :------------ | :-------------------------------------- |
| unSplashApi |      yes      | unspalsh.com | _https://api.unsplash.com/photos/_ |

<br>

#### Component Hierarchy

> Use this section to define your React components and the data architecture of your app.

```
src
|__ assets/
      |__ images
      |__ mockups
|__ components/
      |__ App.js
      |__ Header.js
      |__ SearchBar.js
      |__ SearchResults.js
      |__ PinBoard.js
      |__ ImageInfoPage.js
      |__ Footer.js
```

<br>

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
| Header       | functional |   n   |   n   | _The header will contain the navigation and logo._               |
| App          |   class    |   y   |   n   | _Will make the api call and store the state._                    |
| SearchBar    |   class    |   y   |   n   | _._      |
| SearchResults|   class    |   y   |   n   | _._      |
| Pin Board    |   class    |   n   |   y   | _._                 |
| ImageInfoPage|   class    |   y   |   y   | _Will make an Api call ._                                        |
| Footer       | functional |   n   |   n   | _The footer will show info about me._                             |

<br>

#### Component Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.


<br>

> _Why is this necessary? Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evalute possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe._

<br>

#### Helper Functions

> 

<br>

### Post-MVP
- Adding a like button for images
- Adding Categories to the search
- Displaying 10 popular images in a Featured Images section on the main page

> 

<br>


- 
<br>

#### Post-MVP Data

- 

<br>

***

## Project Delivery

> 

### Code Showcase

> 

```

```

### Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution.

| Error                                                   | Resolution                                             |
| :------------------------------------------------------ | :----------------------------------------------------- |
| `app.js:34 Uncaught SyntaxError: Unexpected identifier` | Missing comma after first object in sources {} object. |

***

