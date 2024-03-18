# phase-2
# 1.Chosen Development Model:
Agile development techniques prioritise regular software delivery, user and customer participation, and flexibility in response to evolving requirements. You may react to changes fast and repeatedly without sacrificing quality or scope by utilising brief iterations, frequent reviews, and feedback loops.
# 2.User Requirements: 
  # End User Customers 
  Roles - End users are the people who will access and use the pharmacy website. Those requesting information about pharmaceuticals, health products, and pharmacy services are among them, both current and prospective clients.
  Interests - End consumers are drawn to websites with intuitive navigation, rapid access to product details, safe online transactions, and trustworthy health-related content. Customers anticipate a simple and easy way to browse products, make purchases, and access pharmacy services on the website. 
  # Client (Pharmacy Management Team):
  Roles - The client is a representative of the pharmacy management team that started and is in charge of the website development project. Throughout the project lifetime, they offer project needs, comments, and approvals.
  Interests - The client wants to improve the pharmacy's online presence, boost online sales, increase customer happiness, and improve operational efficiency by adding capabilities like online appointment booking and prescription refill requests. The website should fulfil the needs of the clients and represent the pharmacy's brand identity and values.
  # Developers (Web Development Team):
   Roles - The development team is in charge of creating and executing the website's technical features, which include coding, programming, and integrating features like content management, appointment scheduling, and e-commerce.
   Interests - Developers are interested in creating a scalable, secure, and well-structured website architecture that meets the project requirements and aligns with industry best practices. They aim to deliver a website that performs optimally, loads quickly, and provides a smooth user experience across different devices and browsers.
   # Content Creators / Copywriters:
   Roles - The creation and optimisation of online content, such as product descriptions, service pages, blog entries, and articles about health, falls within the purview of content creators.
   Interests - Content creators are responsible for the development and optimisation of web content, including service pages, product descriptions, blog posts, and health-related articles.
  # b. user stories 
  - End-User (Customer) - Purchasing Medications:
My goal as a customer using the pharmacy website should be to be able to quickly explore and search for the prescriptions I require.
I would like to see every medication's complete details, including cost, adverse effects, dose, and administration guidelines.
After deciding which prescription drugs I need, I want to put them in my cart and go through a safe checkout procedure.
I want to be able to pay with a variety of methods throughout the checkout process, such as credit/debit cards and online payment gateways, in order to safely finish my transaction.
I would want an email confirming my transaction and providing an anticipated delivery date as soon as I finish the purchase.
 - End-User (Customer) - Prescription Refill Request:
Refill requests should be simple to submit through the pharmacy website as an end-user with a prescription that needs to be filled.
I would like to get in touch with a refill request form specifically designed for entering prescription information such as drug name, dose, and prescription number.
After submitting the refill request, I would like to hear back from you to let me know that it has been received and is being handled.
I would also like to get email or SMS updates on the progress of my refill request, as well as notification when my prescription is prepared for pickup or scheduled for delivery.
 - Administrator (Pharmacy Staff) - Content Management:
I want to be able to simply update and maintain the website material as an administrator overseeing the pharmacy website so that it is correct and up to date.
I want to be able to add, amend, or remove product listings, service offerings, and informative articles via a user-friendly content management system (CMS).
Additionally, I would like to be able to add new pictures, documents, or multimedia to improve the look and feel of the website.
I also want to be able to trace revision history for auditing purposes, evaluate content changes before to posting, and plan content updates ahead of time.
# 3. Functional Requirements :
Make it simple for people to explore and search for prescription drugs and healthcare items.
Permit customers to examine comprehensive details about each medication, such as cost, dose, and usage guidelines.
Provide customers who want to buy prescription drugs online a simple and safe checkout experience.
Permit consumers to utilise an easy online form to seek refills for their prescriptions.
Give them access to educational health-related content, such as blog entries and articles.
Make sure the website is adaptable and functions properly on various screens and devices.
# b. accpetance criteria :
- Browsing and Searching for Medications and Health Products:
  Categories and subcategories of products are accessible to users.
 To find particular drugs or health items, users can utilise a search box.
 The search results are arranged and pertinently displayed.
- Viewing Detailed Medication Information:
Price, adverse effects, dosage, and usage guidelines are all given on each pharmaceutical page.
 The information is current and correct.
 Where appropriate, pharmaceutical pictures or images are supplied.
- Secure and Convenient Checkout Process:
After adding products to their cart, users can check out.
 Several safe payment methods are available during the checkout procedure.
 After completing a transaction, users receive emails confirming their purchase.
- Making a Prescription Refill Request:
  The website's refill request form is simple to find.
 Users can accurately enter prescription information.
 After submitting a refill request, a confirmation message appears.
- Responsive Design:
 Website layout adjusts dynamically based on screen size and device type.
 Content is displayed legibly and accessibly on all devices.
 Images and interactive elements resize and adapt to different screen sizes.
# 4. Non- functional requirements: 
- Performance - The website should react to user inputs rapidly and load smoothly.For users to have a seamless surfing experience, pages should render in a matter of seconds.
  Goal: Ensure that the website loads quickly, with pages rendering within a few seconds to provide a smooth browsing experience for users.
- Usability - Users of all skill levels should find the website to be intuitive and simple to use.Users ought to be able to locate information and do tasks without difficulty or aggravation.
  Goal: Design the website to be intuitive and easy to navigate, allowing users to find information and complete tasks without confusion or frustration.
- Security - To avoid unwanted access or data breaches, user data should be delivered and stored securely.
The website must abide by best practices and industry standards for privacy and data security.
Goal: Implement robust security measures to securely store and transmit user data, complying with industry standards and best practices for data security and privacy.
- Compatibility - Numerous operating systems, browsers, and devices should be able to access the website.
Regardless of the device or platform, users should be able to view and use the website properly.
Goal: Ensure the website is compatible with a wide range of devices and platforms, allowing users to access and use the website effectively regardless of their device or browser choice.
-Maintainability - is the degree to which a system can be easily updated and maintained over time.
Goal: Create a system that is easy to maintain and update by using modular code and comprehensive documentation. This will ensure that changes can be made fast and effectively without causing any problems.
# 5. Application Specifications:
  # Architecture:
  Scalable, secure, and modular architecture will be features of the pharmacy website's design. Below is a summary of the elements and how they work together:

-Client side (frontend) A number of parts will be made, including product listings, search capabilities, the checkout procedure, an interface for scheduling appointments, and informative pages.
Users will use their web browsers to engage with the frontend components.

- Server side (backend) The backend will be built using a microservices architecture for scalability and flexibility.
- Database - The relational database management system (RDBMS) for organising and storing structured data about orders, products, appointments, users, and content will be MySQL.
- Authentication and Authorization- To provide safe access control, JWT will be used for user authentication and authorization.
It will be possible for users to sign up, log in, and safely manage their accounts.
- Infrastructure - 

