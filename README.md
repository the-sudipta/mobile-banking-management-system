<br/>
<div align="center">
<a href="#">
<img src="https://raw.githubusercontent.com/the-sudipta/mobile-banking-management-system/main/DOCUMENTATIONS/images/Mobile%20Banking%20Management%20System.png" alt="Logo" width="100" height="100">
</a>
<h3 align="center">Mobile Banking Management System</h3>





<p align="center">
  <a href="#toolbox-getting-started">Getting Started</a> 
  <a href="#pushpin-api-endpoints">API Endpoints</a>
  <a href="#wave-contributing">Contribute</a>
  <a href="#warning-license">License</a>
  <a href="#handshake-contact">Contact</a>
  <a href="#gem-acknowledgement">Acknowledgement</a>
</p>


<p align="center">
An online banking system backend through email like bKash
<br/>
<p align="center">
  <a href="https://github.com/the-sudipta/mobile-banking-management-system/raw/main/DOCUMENTATIONS/Project_Manual_mobile-banking-management-system.pdf" download>📱 Explore the docs »</a>
</p>
</div>
<div align="left">

## :star2: About The Project

   ![Product Video Gif](https://github.com/the-sudipta/mobile-banking-management-system/blob/main/DOCUMENTATIONS/images/Mobile%20Banking%20Management%20System%20Backend%20Demo.gif?raw=true)
   
   The Mobile Banking Management System project is designed to streamline banking operations through mobile
   devices, enabling users to conduct tasks like fund transfers, bill payments, and account inquiries from
   their smartphones or tablets. This project aims to enhance accessibility, efficiency, and security in
   banking services, addressing the challenges of robust security measures, compatibility across various
   mobile platforms, scalability for a growing user base, and compliance with regulatory and legal
   requirements, ensuring a seamless and secure user experience in the modern digital age.
   
   
   ### :hammer: Tech Stack / Built With
   
   <div align="left">
      <details> 
        <summary>Backend Framework</summary> 
        <ul>
          <li><a href="https://nestjs.com/">NestJS</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Database</summary> 
        <ul>
          <li><a href="https://typeorm.io/">TypeORM</a></li>
          <li><a href="https://node-postgres.com/">pg (PostgreSQL)</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Authentication & Security</summary> 
        <ul>
          <li><a href="https://www.npmjs.com/package/bcrypt">bcrypt</a></li>
          <li><a href="https://docs.nestjs.com/security/authentication">JWT (JSON Web Token) - @nestjs/jwt</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Validation & Transformation</summary> 
        <ul>
          <li><a href="https://github.com/typestack/class-validator">class-validator</a></li>
          <li><a href="https://github.com/typestack/class-transformer">class-transformer</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Testing</summary> 
        <ul>
          <li><a href="https://jestjs.io/">Jest</a></li>
          <li><a href="https://github.com/visionmedia/supertest">Supertest</a></li>
          <li><a href="https://kulshekhar.github.io/ts-jest/">ts-jest</a></li>
          <li><a href="https://docs.nestjs.com/fundamentals/testing">NestJS Testing - @nestjs/testing</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Email & Session Management</summary> 
        <ul>
          <li><a href="https://nodemailer.com/about/">Nodemailer</a></li>
          <li><a href="https://www.npmjs.com/package/express-session">express-session</a></li>
          <li><a href="https://nestjs-modules.github.io/mailer/docs/">NestJS Mailer Module - @nestjs-modules/mailer</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Utility Libraries</summary> 
        <ul>
          <li><a href="https://www.npmjs.com/package/cors">CORS</a></li>
          <li><a href="https://www.npmjs.com/package/reflect-metadata">reflect-metadata</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Development Tools</summary> 
        <ul>
          <li><a href="https://prettier.io/">Prettier</a></li>
          <li><a href="https://eslint.org/">ESLint</a></li>
          <li><a href="https://www.typescriptlang.org/">TypeScript</a></li>
          <li><a href="https://www.npmjs.com/package/ts-node">ts-node</a></li>
          <li><a href="https://github.com/TypeStrong/ts-loader">ts-loader</a></li>
          <li><a href="https://www.npmjs.com/package/tsconfig-paths">tsconfig-paths</a></li>
        </ul> 
      </details>
      <details> 
        <summary>Miscellaneous</summary> 
        <ul>
          <li><a href="https://rxjs.dev/">RxJS</a></li>
          <li><a href="https://www.npmjs.com/package/source-map-support">source-map-support</a></li>
        </ul> 
      </details>
   </div>
   
   ### :dart: Features
</div>
   <div align="center">
     <table>
       <tr>
         <th colspan="2">Customer Features</th>
       </tr>
       <tr>
         <td>Sign up</td>
         <td>Sign in</td>
       </tr>
       <tr>
         <td>Sign out</td>
         <td>Create Customer Details</td>
       </tr>
       <tr>
         <td>View Profile Details</td>
         <td>Upload/Change Profile Picture</td>
       </tr>
       <tr>
         <td>View Profile Picture</td>
         <td>Cash out</td>
       </tr>
       <tr>
         <td>Cash in</td>
         <td>Bank to bKash</td>
       </tr>
       <tr>
         <td>bKash to Bank</td>
         <td>Change password</td>
       </tr>
       <tr>
         <td>Change profile details</td>
         <td>Bill payment</td>
       </tr>
       <tr>
         <td>View payment list</td>
         <td>Loan from bKash</td>
       </tr>
       <tr>
         <td>Send money</td>
         <td>bKash to card</td>
       </tr>
     </table>
   </div>


<div align="left">
   
   ### :key: Environment Variables
   To run this project, you will need to add the following environment variables to your database connection file
   
   ### Database Variables
    
   ```yaml
   DATABASE_URL: "postgresql://postgres:qWKzRVBvImHaoGJZhtZwfmoZzjZkwDKf@roundhouse.proxy.rlwy.net:21821/railway"
   PGDATABASE: "railway"
   PGHOST: "roundhouse.proxy.rlwy.net"
   PGPASSWORD: "qWKzRVBvImHaoGJZhtZwfmoZzjZkwDKf"
   PGPORT: 21821
   PGUSER: "postgres"
   
   ```
   
   ## :toolbox: Getting Started
   
   ### :bangbang: Prerequisites
   
   <div align="left">
      <ul>
        <li><a href="https://nodejs.org/en/download/">Node.js</a></li>
        <li><a href="https://nodejs.org/en/download/">npm (Node Package Manager)</a>
          <ul>
            <li><code>npm install</code></li>
          </ul>
        </li>
        <li><a href="https://docs.nestjs.com/cli/overview">NestJS CLI</a>
          <ul>
            <li><code>npm install -g @nestjs/cli</code></li>
          </ul>
        </li>
        <li><a href="https://www.postgresql.org/download/">PostgreSQL Database</a></li>
        <li><a href="https://www.typescriptlang.org/download">TypeScript</a></li>
        <li><a href="https://eslint.org/docs/user-guide/getting-started">ESLint</a></li>
        <li><a href="https://prettier.io/docs/en/install.html">Prettier</a></li>
        <li><a href="https://nodemailer.com/about/">Mail Server (Optional)</a></li>
      </ul>
   </div>
   
   ### :running: Run Locally
   ```bash
   # development
   $ npm run start
   
   # watch mode
   $ npm run start:dev
   
   # production mode
   $ npm run start:prod
   ```
   
   #### Download the project
   
   ```bash
   https://github.com/the-sudipta/mobile-banking-management-system.git
   ```
   
   #### Clone the Repository
   ```bash
   git https://github.com/the-sudipta/mobile-banking-management-system.git
   ```
   
   ## :pushpin: API Endpoints
   <h3 id="get-auth-detail">GET /authenticate</h3>
   
   **RESPONSE Example in Documentations**
   ```json
   {
     "name": "Suchona Saha",
     "age": 22,
     "email": "dr.suchona.saha@gmail.com",
     "password": "admin"
   }
   ```
   
   <h3 id="post-auth-detail">POST /authenticate</h3>
   
   **REQUEST Example in Documentations**
   ```json
   {
     "email": "dr.suchona.saha@gmail.com",
     "password": "admin"
   }
   ```
   
   **RESPONSE Example in Documentations**
   ```json
   {
     "token": "OwoMRHsaQwyAgVoc3OXmL1JhMVUYXGGBbCTK0GBgiYitwQwjf0gVoBmkbuyy0pSi"
   }
   ```
   
   
   ## :wave: Contributing
   
   <a href="https://github.com/the-sudipta/mobile-banking-management-system/graphs/contributors"> <img src="https://contrib.rocks/image?repo=Louis3797/awesome-readme-template" /> </a>
   
   Contributions are always welcome!
   
   ### :sparkles: Authors
   - [@the-sudipta](https://www.github.com/the-sudipta)
   
   ## :busts_in_silhouette: Used By
   
   This project is used by the following individuals:
   
   - Tripti Ahmed
   
   
   ## :warning: License
   
   This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License - see the [LICENSE](LICENSE) file for details.
   
   ## :handshake: Contact
   
   Sudipta Kumar Das - - engineer.sudipta.kumar.das@gmail.com
   
   Project Link: [https://github.com/the-sudipta/mobile-banking-management-system](https://github.com/the-sudipta/mobile-banking-management-system)
   
   ## :gem: Acknowledgement
   - [PostgreSQL Database](https://www.postgresql.org/download/)
   - [Mail Server](https://nodemailer.com/about/)
</div>