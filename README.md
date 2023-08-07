<H1 align ="center" >MERN EMPLOYEE SALARY MANAGEMENT<br/>{ SiPeKa }</h1>
<h5  align ="center"> 
SiPeKa (Employee Payroll System) is a system used by companies to manage employee payroll processes efficiently and accurately. This system plays a key role in automating various tasks related to payroll, such as calculating payroll, processing attendance, and paying employee wages.<br/> In SiPeKa, employee information such as personal data, position and salary level is stored centrally. Every month, the system will retrieve employee attendance data and perform salary calculations based on the available information. This includes factors such as relevant hours worked, leave, overtime and deductions.</h5>
<br/>

- [Configuration and Setup](#configuration-and-setup)
- [Key Features](#key-features)
- [Technologies used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
- [📸 Screenshots](#screenshots)
- [Meet The Teams](#meet-the-teams)
- [Author](#author)
- [License](#license)

## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the Frontend on one terminal and the server on the other terminal)

In the first terminal

```
$ cd Fronted
$ npm install (to install Frontend-side dependencies)
$ npm run dev(to start the Frontend)
```

In the second terminal

- Create your MySQL database, which you will use as your database
- Supply the following credentials

```
#  --- .env  ---

APP_PORT =5000
SESS_SECRET =

```

```
# --- Terminal ---

$ cd Backend
$ npm install (to install Backend-side dependencies)
$ npm start (to start the Backend)

```

## Key Features

- Login Admin
- Add employee
- Edit employee
- Remove employee
- Add position
- Edit position
- Remove position
- Display data, input attendance, edit attendance and delete employee absences
- Employee Salary Deduction Setting
- Display data, input salary data, edit salary data and delete employee salary data
- Print payroll reports, absences, and payslips
- Change admin and employee passwords
- Login Employees/Staff
- Print employees/staff salary reports from personal accounts
- 404 Page and many more
- Responsive Design

<br/>

## Technologies used

This project was created using the following technologies.

#### Frontend

- [React JS ](https://www.npmjs.com/package/react) - JavaScript library that is used for building user interfaces specifically for single-page applications
- [React Hooks ](https://reactjs.org/docs/hooks-intro.html) - For managing and centralizing application state
- [React Router Dom](https://www.npmjs.com/package/react-router-dom) - To handle routing
- [Axios](https://www.npmjs.com/package/axios) - For making Api calls
- [Tailwind CSS](https://tailwindcss.com/) - For User Interface
- [React icons](https://react-icons.github.io/react-icons/) - Small library that helps you add icons to your react apps
- [Redux](https://redux.js.org/) - Managing complex application state
- [Localforage](https://localforage.github.io/localForage/) - Saves data in the web browser asynchronously
- [React Vite](https://vitejs.dev/guide/) - Improved website speed
- [Redux Toolkit](https://redux-toolkit.js.org/) - To facilitate the development of web applications using Redux
- [Apexcharts](https://www.npmjs.com/package/apexcharts) - An open source library used to create interactive graphics on websites or web applications
- [Match Sorter](https://www.npmjs.com/package/match-sorter) - An open source library used to create interactive graphics on websites or web applications
- [Email JS](https://www.emailjs.com/) - For User Interface
- [Framer Motion](https://www.framer.com/motion/) - For User Interface
- [React Redux](https://react-redux.js.org/) - Managing complex application state
- [React to Print](https://www.npmjs.com/package/react-to-print) - Print PDF
- [Sweet Alert2](https://sweetalert2.github.io/) - Create various types of pop-up alerts such as regular alerts, error alerts, success alerts, confirmation alerts, and so on.

#### Backend

- [Node JS](https://nodejs.org/en/) -A runtime environment to help build fast server applications using JS
- [Express JS](https://www.npmjs.com/package/express) -The server for handling and routing HTTP requests
- [MySql12](https://www.npmjs.com/package/mysql2) - For authentication
- [Cors](https://www.npmjs.com/package/cors) - Provides a Connect/Express middleware
- [Bcrypt JS](https://www.npmjs.com/package/bcryptjs) - For data encryption
- [Dotenv](https://www.npmjs.com/package/dotenv) - Zero Dependency module that loads environment variables
- [Nodemon](https://www.npmjs.com/package/nodemon) - To monitor changes to the program code that is being developed
- [Jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - For authentication
- [Cookie Parser](https://www.npmjs.com/package/cookie-parser) - A middleware for web frameworks
- [Sequelize](https://www.npmjs.com/package/sequelize) - An Object-Relational Mapping (ORM) for Node.js that makes it easy to access relational databases such as MySQL, PostgreSQL, and SQLite using the JavaScript programming language.
- [Argon2](https://www.npmjs.com/package/argon2) - A password-hashing function that summarizes the state of the art in the design of memory-hard functions and can be used to hash passwords for credential storage, key derivation, or other applications.
- [Connect Session Sequelize](https://www.npmjs.com/package/connect-session-sequelize) - Implement authentication for users with site applications.

#### Database

- [MySQL ](https://www.mysql.com/) - It provides a free cloud service to store MongoDB collections.

## Screenshots

![img-1](https://i.ibb.co/XFXftxZ/256913222-a3f72509-8ca0-452b-b121-ff4ecf94580d.png)

---

![img-2](https://i.ibb.co/ccTtCGj/256913233-e7998109-d53d-4c93-80eb-f6e9c05f44b4.png)

---

![img-3](https://i.ibb.co/Qd97LfJ/256913238-0c2859cb-2d56-447c-bd19-fabe707988aa.png)

---

![img-4](https://i.ibb.co/xF4dYFS/256913235-f7424cc9-2b63-49af-a2b7-37bd9e79e342.png)

---

![img-5](https://i.ibb.co/84MFQps/256913239-ed0af932-ea78-44ac-ba91-48eb91449517.png)

---

![img-6](https://i.ibb.co/BB7pJ8N/256913242-3efac0b3-b2d5-45ec-b82c-82b9b191ffd2.png)

---

![img-7](https://i.ibb.co/kyZzMcy/256913246-5d6f9974-7b8e-4c12-a049-44368640dc62.png)

---

![img-8](https://i.ibb.co/cyq4N4f/256913250-be9c67c6-376f-450a-9ba3-c968bd9ec063.png)

---

![img-9](https://i.ibb.co/sbNVKf1/256913252-8ffef668-7cb1-4004-980c-d2463683ba3b.png)

---

![img-10](https://i.ibb.co/RH2KnW1/256913255-8067acac-dc49-4f6e-a6aa-f4baae2fa8a5.png)

---

![img-11](https://i.ibb.co/QNfCzrB/256913257-ecd09fb0-1f97-4856-ba4d-28170927e070.png)

---

![img-12](https://i.ibb.co/3Ttb31K/256913259-ecdafe57-1b4a-4ddf-9802-7a4c5d3be141.png)

---

![img-13](https://i.ibb.co/WpZFJm9/256913261-f5831815-3cd7-4f83-8193-12c16f859023.png)

---

![img-14](https://i.ibb.co/947Z5rY/256913263-8539843c-39f1-4642-84b6-cb9a2a4b09b9.png)

## Author

- Portfolio: [Daniel Lee](http://masterdev0218.portfolio.app)
- Github: [masterdev0218](https://github.com/masterdev0218)
- Email: [daniel.lee0218929@gmail.com](mailto:daniel.lee0218929@gmail.com)

## License

MIT License

Copyright (c) 2022 Daniel Lee

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
