<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
  - [Built With](#built-with)
- [Screenshots](#screenshots)
  - [Home (News In)](#news-in)
  - [Categories](#categories)
  - [Product](#product)
  - [Cart](#cart)
  - [Account](#account)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Issues / Feature Plans](#issues---future-plans)
- [Contributing](#contributing)
- [Questions & Answers](#q--a)
- [License](#license)
- [Contact](#contact)

<!-- ABOUT THE PROJECT -->

## About The Project

I saw a UI design on Dribbble by [Anton Mikhaltsov](https://dribbble.com/shots/9404340-Shop-Clothing-Web-Page). And I wanted to code this design. So I decided to make it a full working website with NextJS but in just 1 week as challenge myself. Some issues are still there but I will check out them later.

- Filter and Sort buttons are not working yet.
- ~~Website is not responsive %100 because of time was not enought. I am working on it currently.~~ Now, it is responsive.
- Firebase functions could be better
- Home page(News In) cards has no redirects. They are just placeholders.

### Built With

- [React](https://reactjs.org)
- [NextJS](https://nextjs.org/)
- [Firebase](https://firebase.google.com/docs/web/setup)
- [React Hook Form](https://react-hook-form.com/)
- [date-fns](date-fns.org/)
- [Sass](https://sass-lang.com/)

<!-- Screens -->

## Screenshots

### News In

![Home Image](https://i.ibb.co/ZzG3GtN/index.png)
- Cards have no links and they are static, they are just placeholders.

### Categories

![Categories Image](https://i.ibb.co/ScCBXDZ/index2.png)

### Product

![Product Image](https://i.ibb.co/mbsd2Y1/index5.png)

### Cart

![Cart Image](https://i.ibb.co/svHtw0H/index3.png)

### Account

![Account Image](https://i.ibb.co/JcR3x7F/index4.png)

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) version 10.13 or later
- [Git](https://git-scm.com/) (I used 2.20.1)

### Installation

1. You need to create a Firebase project.

2. Clone the repo and change the directory.

3. Install NPM packages

```sh
npm installIn the root folder (`next-e-commerce`), create a file named `.env.local` and add the following content with your Firebase keys:

```makefile
NEXT_PUBLIC_FIREBASE_API_KEY = your-firebase-api-key
NEXT_PUBLIC_FIREBASE_PROJECT_ID = your-firebase-project-id
NEXT_PUBLIC_FIREBASE_APP_ID = your-firebase-app-id
Run in Development Mode
To run the project in development mode, use the following command:

sh
Copy code
npm run dev
Issues - Future Plans
Filter and Sort buttons
Optimize Firestore query functions
On cart page, the "decrease item" button is not working
Website will be 100% responsive
Replace some HTML tags with semantic tags
Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

To contribute, follow these steps:

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
Q & A
Q: I created a Firebase project but I do not familiar with it. What should I do then?
A: You can contact me about setting up your Firebase project, I would gladly help you.

Q: I created a Firebase project but I do not have a database structure. What should I do then?
A: Please contact me to get the database structure I created.

Q: Why did you not share your database structure?
A: I just want to know if someone is interested in this project :D

Q: How can I contribute?
A: It makes me happy even if you just star this project. For code contributions, you can fork the repo and open a pull request after your changes. Any feedback is also important for me. You can open an issue or send me a message.

Q: Did you design the UI?
A: No, I did not design it. I found the homepage design on Dribbble by Anton Mikhaltsov. Except for the homepage, other UI choices are mine. While I made this website in limited time, I did not focus too much on UI/UX. So, you can also provide feedback on design.

Contact
Gautham
LinkedIn Profile - https://www.linkedin.com/in/gautham8325/