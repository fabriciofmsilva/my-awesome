# Full-Stack

## Table of Contents

* [Stacks](#stacks)
* [Questions](#questions)

## Stacks

### LAMP

Linux, Apache, MySQL, and PHP. (Abstractly: server software, web server, database, back-end language.)

### MEAN

MongoDB, Express.js, Angular and Node.js.

### STAR

Design Systems, TypeScript, Apollo and React.

### Apollo GraphQL

* [Apollo](https://www.apollographql.com/)

### JAMstack

* [JAMStack](https://jamstack.org/)

## Miscellaneous

The e-Commerce site final stack is the following:

* Node.js (Backend processing: payment webhooks)
* Stripe (Payment gateway)
* Heroku (Run server code)
* Netlify (Host static files)
* Amazon S3 (Host assets)
* CircleCI (Test code and generate assets)
* Mailgun (emails platform)

1. Automating the generation of the assets (PDF)
2. Hosting e-Commerce site
3. Processing Payments
4. Backend processing
5. Sending emails
  1. DNS settings and authentication (SPF, DKIM) (Sendgrid, Mailgun)
  2. Email Templates
6. Cost of running the e-Commerce store

* Hosting static websites: $0 (if you use Netlify or Github pages)
* Payment Gateway: $0 (Stripe will only a 2.9% charge if you sell something otherwise $0)
* Node.js server: $0 (Heroku, AWS, Google Cloud and many others have a free plan for developers)
* Email Service: $0 (Mailgun and Sendgrid both have free plans. The former allows you to send 10K emails per month)
* The total is: $0 / mo.
* Note: Like any website, If you want to use a custom domain as I do, you have to pay for it which is about $1/mo.

## Questions

* How is your visual design skill?
* Are you building design systems or implementing existing ones?
* How many years have you maintained systems?
* Do you have a good eye for the most painful kinds of technical debt?
* How are you at helping co-workers succeed?
* Can you facilitate a user testing session?
* How good are you at diagnosing performance bottlenecks?
* What if there are serious server problems?
* Does your full stack moniker help you comprehend server logs?
* Are you versed in accessibility audits?
* Have you ever dealt with tricky relational data and slow queries?

## Resources

* [What Does it Mean to Be “Full Stack”?](https://css-tricks.com/what-does-it-mean-to-be-full-stack/)

## Path

1. Node JS From Scratch
2. Node JS API Development from Scratch
3. React JS from Scratch
4. Modern JavaScript from Scratch
5. A FullStack Social Network Application from Scratch
6. Build Rock Solid Authentication with Password Forgot/Password Reset using JWT
7. Authorization
8. Implement Social Login using JWT
9. CRUD, Image Upload, User Posts Relationships, follow, unfollow, likes, comments and more
10. Super Admin based on Role
11. Custom reCAPTCHA
12. Pagination
13. Deploy FullStack React Node Social Network to Digital Ocean Cloud Hosting
14. Full Source Code is available for each major section and lectures
15. Direct help from Instructor if you ever get stuck!
16. In depth understanding of Modern JavaScript, React and Node JS
17. Each line of code is explained!
18. Easy to understand (Course starts from absolute basic and gradually makes progress)
19. Follow the best practices while coding
20. Fully understand the code you are writing
21. Best way of structuring Node Js and React application so that it scales in future

* [Digital Ocean](https://www.digitalocean.com/)
* [GitHub Education](https://education.github.com/pack)
* [AWS Free Tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=categories%23featured)
* [GCP](https://cloud.google.com/gcp/)
* [GOOGLE APP ENGINE](https://cloud.google.com/appengine/)
* [Firebase Hosting](https://firebase.google.com/products/hosting/)
* [CLOUD DATASTORE](https://cloud.google.com/datastore/)
* [Cloud SQL](https://cloud.google.com/sql/)
* [Cloud Build](https://cloud.google.com/cloud-build/)

---

1. Learn About SSH
  * Learn about how SSH works, and how to SSH into a server.
  * Learn a little about Symmetric and Asymmetric encryption as well as Hashing
  * Learn how to manage SSH keys
2. Learn Advanced Javascript
  * Learn common algorithms and data structures
  * Learn some common design patterns
  * Learn the difference between OOP and Functional Programming. Pros and Cons of each
  * Learn common Functional Programming techniques
  * Learn how to Optimize Code
  * Learn how modules work
3. Learn How to Improve Web Performance
  * Learn about network performance: improving delivery and minimizing files and images
  * Learn the differences between HTTP/2 vs HTTP/1.1
  * Learn how the Critical Render Path works 
  * Learn about pre-fetching resources
  * Learn about code-splitting
  * Learn about CDNs
  * Learn about compression
  * Learn about Caching and all the places you can use caching
  * Learn how to do Load Balancing using Nginx, then try load testing on it
  * Go over important performance topics following this tutorial
4. Learn About Progressive Web Apps
  * Learn how to build a Progressive Web App
  * Learn about the key things that allow us to create such apps: HTTPS, App Manifest, and Service Workers.
5. Learn a Popular Frontend Library + How to Manage Complex State
  * Learn a popular frontend library/framework like React, Vue or Angular to build large web applications. My choice is React (here, then here), but you can pick whichever suits you.
  * Learn the principles of Redux (or other state management tools) and not only how to manage state but how to think about data flow through your app as it grows. 
  * Learn about Event Sourcing and CQRS which inspired Redux
  * Learn a little bit about module bundling using Webpack 4 and Parcel
6. Learn About Testing
  * Learn the current testing landscape and the tools you can use
  * Learn about the different types of tests: Unit Tests, Integration Tests, End to End Testing
  * Learn how to write good tests
  * Learn about TDD and BDD
  * Learn how to write Asynchronous Tests
  * Learn how to use Mocks, Stubs and Spies
  * Learn about Snapshot testing
7. Learn About TypeScript
  * Learn the benefits of having static typing in Javascript
  * Learn how to use the TypeScript Compiler and how to write in TypeScript
  * Learn when and when not to use Typescript
  * Learn how to use DefinitelyTyped
8. Learn About Client Side Rendering vs Server Side Rendering
  * Learn about when to use Client Side Rendering and when to use Server Side Rendering
  * Learn the benefits of using Next.js or Gatsby.js instead of implementing your own server side rendering.
9. Learn About Securing Your applications
  * Avoid the most common security vulnerabilities like Injections
  * Learn how to avoid XSS or CSRF
  * Learn how to use HTTPS to make the web safer
  * Learn about Access Control, SQL Injections, Command Execution, etc…
  * Practice protecting against some of the most common attacks
  * Learn why you would want to keep all software up to date
10. Learn About Docker and Containers
  * Learn why containers are different (and sometimes better) than VMs
  * Learn to create a Docker container
  * Learn how to use Docker Compose to orchestrate services
  * Learn to use Docker Compose to make developers’ lives easier
11. Learn About Different Types of Databases
  * Learn about relational and non relational databases
  * Learn when one is better than the other in certain situations
  * Understand the benefits of in-memory data stores like Redis
12. Learn How to Manage Sign In + Sessions In Your App
  * Learn how to manage sensitive user information like passwords
  * Learn the difference between cookie based authentication and token based authentication
  * Learn how you can use JWTs
  * Implement your own authentication/authorization flow in your app
13. Learn About Infrastructure as a Service and Platform as a Service
  * Browse some of the most common offerings by the big players like AWS, GCP, Azure and IBM Cloud
  * Learn about functions as a service like AWS Lambda and using Serverless
  * Create your own Digital Ocean Droplet and run a server
  * Learn about serverless architecture
  * Learn about Monolithic vs Micro Services architecture
14. Learn About Continuous Integration, Delivery, and Deployment
  * Learn about Continuous Integration, Continuous Delivery and Continuous Deployment and how you can manage large projects to run smoothly.
  * Learn to set up tools like CircleCI or TravisCI on Github. 
  * Learn to work in teams
