# BoardBudDocs

## Nicholas Ward T3A2-A

### Description

BoardBud is a surfboard booking tool that allows Users to hire a variety of different surfboards from my local surfshop.

GitHub Repository : <https://github.com/Board-Bud/BoardBudDocs>

---

### Purpose

The purpose of this website is to make booking a surfboard to borrow much more convenient and bring the booking system at the surf shop up to a standard expected of modern businesses. By doing this, it will improve customer satisfaction and increase efficiency of the surf shop staff. Some of the benefits of making this website are:

Accessibility and Convenience: In a fast-paced world, customers appreciate the convenience of accessing services online. A dedicated surfboard booking website will allow our customers to browse available surfboards, check rental rates, and make reservations from the comfort of their homes or on the go.

24/7 Availability: an online booking platform provides 24/7 accessibility so customers can make reservations at any time.

Efficient Management: A surfboard booking website will streamline the rental process, making it more efficient for both customers and staff at the shop. With an integrated booking system, our team can manage reservations, monitor inventory, and allocate resources more effectively.

Enhanced Customer Experience: A well-designed website can contribute to an enhanced customer experience. The website can provide valuable information about surfboard options, rental policies and pricing, helping customers make informed decisions. Additionally, features such as user reviews and testimonials can build trust and credibility, encouraging potential customers to choose our surf shop over competitors.

Marketing Opportunities: A surfboard booking website serves as an additional marketing tool. Through online promotions, discounts, and targeted advertising, we can attract new customers and retain existing ones both online and in the physical store.

Adaptation to Industry Trends: Embracing online booking aligns with current industry trends. Many customers prefer the convenience of digital services, and having a surfboard booking website positions our business as forward-thinking and customer-centric. Staying ahead of industry trends is crucial for maintaining competitiveness in the market.

---

### Functionality/features

The features and functionality for this website will be aimed at Admins and Users.

Everyone: All users will be able to log in to their account.

- Log in / Log out with usernames and passwords
- Username and passwords to be encrypted.

Admin: Administrators will be able to add, edit and remove surfboards to the website and to the hire list. They will also be able to delete Users.

- add, edit and remove surfboards (dimensions, style, photo, description).
- add and remove surfboards to the hire list.
- delete users.
- view bookings

Users: Users will be able to create a user account, edit their information and delete their account. They will also be able to browse a list of surfboards and book them using a calender style booking system.

- can create, edit and delete their account
- browse surfboards with images and descriptions.
- can browse a calendar and book surfboards with available/unavailable dates, similar to an appointment booking system.

Nice to haves: These will be features that will be nice to have, if there is enough time to implement them.

- Payment?
- Review/comment system for the surfboards?
- advertisement banners?

---

### Target Audience

- People who have travelled / are on holiday and could not take their own surfboard with them
- Beginner surfers who want to try a few different boards, enabling them to purchase one that suits them best
- Intermediate to advanced level surfers looking to upgrade their current board. This would allow them to try out different options before buying
- Staff at the Surf shop, to make managing inventory and reservations easier and more efficient

---

### Tech Stack

1. **MongoDB (Database):**

- MongoDB: A NoSQL database that stores data in a flexible, JSON-like format.
- Mongoose: An ODM (Object-Document Mapping) library for MongoDB and Node.js, providing a schema-based solution to model application data.\

2. **Express.js (Backend Framework):**

- Express.js: A minimalist and flexible Node.js web application framework that facilitates building robust and scalable web applications.
- Middleware: Various middleware packages for handling tasks such as routing, authentication, and error handling.

3. **React.js (Frontend Library):**

- React.js: A JavaScript library for building user interfaces, particularly for single-page applications (SPAs).
- React Router: A library for handling navigation and routing within a React application.
- State Management: Options like React Context or third-party libraries such as Redux for managing the state of the application.

4. **Node.js (Runtime Environment):**

- Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine, used for server-side development.
- npm (Node Package Manager): The default package manager for Node.js, used for installing and managing project dependencies.
- Express.js (again): Used on the server side for building the RESTful API and handling HTTP requests.

5. **Deployment:**

- Heroku: Platform as a Service (PaaS) for deploying and managing various applications with easy deployment, add-ons marketplace, automatic scaling, and a pay-as-you-go pricing model.
- Netlify: Platform specialising in hosting modern web projects, including static sites and Jamstack applications, with features like continuous deployment, serverless functions, branch deployments, and a free tier available.

6. **Testing:**

- Jest: JavaScript testing framework emphasising simplicity and speed, featuring snapshot testing, built-in support for mocking, and async testing.
- Manual Testing: Testing approach executed manually, including exploratory testing, usability testing, ad-hoc testing, and user acceptance testing (UAT).

7. **Other Technologies:**

- JWT (JSON Web Tokens): For implementing authentication and securing API endpoints. 
- Figma
- Draw.io

---

### User Stories
  
1. As a Surfer, I want to easily browse the available surfboard options, so that I can choose the one that suits my preferences and skill level.

2. As a Tourist, I want to be able to check surfboard availability and make a reservation online so that I can secure the equipment I need before arriving at the beach.

3. As a Local Enthusiast, I want to see any ongoing promotions or discounts on surfboard rentals, so that I can take advantage of cost-saving opportunities.

4. As a Parent, I want to easily reserve multiple surfboards for my family, so that I can ensure everyone has the right equipment for a day at the beach.

5. As a Beginner, I want the website to provide information on safety guidelines and beginner friendly surfboards, so that I can feel confident and prepared for my surfing experience.

6. As a Regular Customer, I want the option to create an account and save my preferences for future bookings so that I can streamline the reservation process for subsequent visits.

7. As a Shop Staff Member, I want a user-friendly dashboard to manage surfboard inventory and reservations, so that I can efficiently handle customer bookings and maintain accurate stock levels.

---

### Architecture Diagram

![Architecture Diagram](/docs/ArchitectureDiagram.png)

---

### Dataflow Diagram

For my dataflow diagram I followed this style guide I found online <https://www.lucidchart.com/pages/data-flow-diagram/data-flow-diagram-symbols>

![DataFlow Diagram](/docs/DataflowDiagram.png)

---

### Wireframes

I have decided to keep the design of the website nice and simple, to enable the users to have an easy to navigate website with minimal clutter. This will make booking surfboards more efficient and a more enjoyable experience.  
Here is a link to my Figma page: <https://www.figma.com/file/0A3Yrw4ZJ1BM5LOME2sXDv/BoardBud?type=design&node-id=1%3A31&mode=design&t=ZxfcpvqoZrytt2H5-1>

The LogIn Page will also act as the homepage. Users and admins will be able to log in using a username and password, or create an account.

![LogIn Page](/docs/LoginPage.jpeg)

The Boards Page will be a card style list. Each card will consist of an image, the board type, a description, a price, and a book now button.

![Boards Page](/docs/BoardPage.jpeg)

The booking page will have a drop down menu at the top to select what board you would like to hire. Then the calender will load with availiable dates, green for availiable, red for un availiable.

![Booking Page](/docs/BookingPage.jpeg)

---

### Planning Methodology

For this assignment I am using GitHub Projects, so I can reduce the amount of applications I need to use throughout the project and it has all the functionality required for me to manage my assignment.

I plan on writing a list of items need to be completed prior to starting, then add more as I go if un foreseen or missed tasks present themselves. For the bigger tasks in the project, I will create a list of dot points within each card so I can break the task down into manageable steps.

By using GitHub Projects I can drag cards into the In progress or Done columns to keep track of my progress. I find this really helpful because it feels like you are constantly making progress when you get to move cards to the Done column. This is another advantage of breaking things down into small tasks. You get to constantly mark things as Done which keeps motivation high as it feels like progress is constantly being made.

---

### GitHub Projects Screenshots

![GitHub Projects 1](/docs/GitHub%20Projects%201.png)

![GitHub Projects 2](/docs/GitHub%20Projects%202.png)

![GitHub Projects 3](/docs/GitHub%20Projects%203.png)

![GitHub Projects 4](/docs/GitHub%20Projects%204.png)

![GitHub Projects 5](/docs/GitHub%20Projects%205.png)

![GitHub Projects 6](/docs/GitHub%20Projects%206.png)

![GitHub Projects 7](/docs/GitHub%20Projects%207.png)

![GitHub Projects 8](/docs/GitHub%20Projects%208.png)


---

### Testing Screenshots

Testing user login  
URL: http://localhost:3000/auth/login  
Expected result: Return user JWT token  
Pass: Yes

![User Login](/docs/User%20Login.png)

Testing JWT is verified and working correctly  
Pass: Yes

![JWT verified](/docs/JWTverified.png)

Testing CREATE/POST a surfboard
URL: https://board-bud-c9fcbefcb666.herokuapp.com/surfboards/  
Expected result: New surfboard data is saved in database and visable on deployed endpoint.  
Pass: Yes  

![Post test](/docs/deployed%20post%20test.png)

Testing Heroku is running

![Heroku Running](/docs/HerokuRunning.png)

<!-- ![]() -->

