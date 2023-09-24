# **Box Store**

[Live Site](https://box-store-90aa6734c1b0.herokuapp.com/)

![Box Store Concept](https://i.ibb.co/2MLB191/Box-Store-Concept.jpg)

## **Introduction**
Welcome to Box Store, my fourth and final project as part of the Code Institute's Full Stack Web Developer Course.

The objective of this project was to create a full-stack website centered around a business logic designed to manage a centrally-owned dataset. The technologies employed for this endeavor encompass HTML, CSS, JavaScript, Python, and Django. Online test payments are handled by Stripe, and Heroku Postgres serves as the relational database.

Box Store represents a fictitious brand, and transactions on this project are processed using Stripe's test card details. For specific card numbers to use, please consult Stripe's official documentation:

[Stripe Test Integration](https://stripe.com/docs/testing)

It's important to note that this project is solely for educational purposes, and no commercial revenue is generated from it.

---

## **UXD - User Experience Design**

Much of the motivation behind the project's planning was derived from my passion for boxing.

With a constant focus on the ideal customer throughout the project's design and development, ensuring a positive user experience became more attainable.

The project planning is organized into five key phases:

1. The Strategy Phase
2. The Scope Phase
3. The Structure Phase
4. The Skeleton Phase
5. The Surface Phase

---

## **The Strategy Plane**

### **Creator Goals**
- As a creator, I aim for a user-friendly site navigation.
- As a creator, I aim to enable users to filter products.
- As a creator, I aim to keep users informed about any actions.
- As a creator, I aim to grant administrators the ability to Add/Edit/Delete products.

### **User Stories**

#### **Returning User Stories**
- As a user, I desire clarity regarding the site's primary purpose to ensure it aligns with my needs.
- As a user, I seek seamless navigation to explore various pages on the site.
- As a user, I wish to have the option to register for a personal account on the site.
- As a user, I expect to receive an email confirmation upon registration, confirming the success of my account creation.

#### **Customer Stories**
- As a customer, I seek the ability to browse all available products to make informed purchasing decisions.
- As a customer, I desire the option to explore products in greater detail.
- As a customer, I expect a confirmation message when adding a product to my shopping bag to prevent inadvertent duplication.
- As a customer, I want to access my shopping bag to review its contents and make quantity adjustments as needed.

#### **Customers (Registered) Stories**
- As a registered user, I seek the capability to save my details for convenience, reducing the need for repeated data entry.
- As a registered user, I wish to access my previous orders, including order details and order numbers, for reference.
- As a registered user, I desire the option to add products to my wishlist for future consideration.
- As a registered user, I want the ability to remove products from my wishlist to maintain a curated list of desired items.

---

## **The Scope Plane**

**Phase 1**
- Development of a project addressing user needs.
- Creation of a Home Page featuring an introduction.
- Implementation of a Navbar for seamless page navigation.
- Establishment of a Products page for comprehensive product viewing.
- Crafting of a detailed product page.
- Integration of e-commerce functionality to facilitate user purchases.

**Phase 2**
- Progressing beyond Phase 1 by introducing additional elements.
- Provision for users to filter products.
- Enabling users to search for products.

**Phase 3**
- The final planned phase would be to ensure customers can checkout and receive emails.

---

## **Structure Plane for E-Commerce Project**

In the development of my e-commerce website using I will establish a well-structured framework to ensure an effective user experience. Here's an overview of the structure:

1. *Homepage:*
   - The homepage will serve as the central hub of the e-commerce site.
   - It will feature a clear call to action.
   - A navigation bar at the top and bottom of the page will provide easy access and clear orientation to users.
   - A search bar will be prominently placed for users to quickly find products.

2. *Product Pages:*
   - Each product category will have its dedicated page.
   - Products will be displayed with high-quality images, detailed descriptions and prices.
   - Filters and sorting options will allow users to refine their product searches.
   - An "Add to Cart" button will be present on each product page.

3. *Shopping Cart:*
   - Users can access their shopping cart at any time through the navigation bar.
   - The shopping cart will display a list of added items, their quantities, and the total cost.
   - Users can modify quantities, remove items, or proceed to checkout directly from the cart.

4. *Checkout Process:*
   - The checkout process will be straightforward and user-friendly.
   - It will consist of multiple steps, including shipping information, payment details, and order confirmation.
   - Users will have the option to save their shipping information for future purchases.
   - Payment processing will be secure and integrated with appropriate payment gateways.

5. *User Accounts:*
   - Users can create accounts or log in to access order history and manage personal information.
   - Account-related options will be available in the navigation bar.

6. *Footer:*
   - Social media links

7. *Responsive Design:*
   - The website will be designed to be fully responsive, ensuring compatibility with various devices, including mobile phones and tablets.

This well-structured e-commerce website will provide a seamless shopping experience for users while ensuring the efficient management of products and orders on the backend.


---

## **The Skeleton Plane**

### Wireframes

#### Homepage

![Homepage](https://i.ibb.co/Xx4j0HW/Homepage.png)

#### Products Page

![Products Page](https://i.ibb.co/L9RZ8jN/Products-Wireframe.png)

#### Product Detail Page

![Product Detail Page](https://i.ibb.co/yQ8tFRJ/Product-Detail-Page-Wireframe.png)

#### Shopping Bag Page

![Shopping Bag Page](https://i.ibb.co/5h64b6G/Shopping-Bag-Wireframe.png)

#### Checkout Page

![Checkout Page](https://i.ibb.co/rGrgW7h/Checkout-Page-Wireframe.png)

#### Thank You Page

![Thank You Page](https://i.ibb.co/5B5HLrt/Thank-You-Page-Wireframe.png)

#### Sign Up Page

![Sign Up Page](https://i.ibb.co/ph7jLxN/Sign-Up-Wireframe.png)

#### Sign In Page

![Sign In Page](https://i.ibb.co/HPFNdcg/Sign-In-Wireframe.png)

#### My Profile

![My Profile](https://i.ibb.co/Y7Mtm3T/My-Profile-Wireframe.png)

---

### Databse Schema

![Database Schema](https://i.ibb.co/n763ZDy/database-schema.jpg)

---

## **The Surface Plane**

*Responsive Navigation Bar*
- The navigation bar is consistently present on all pages and adapts seamlessly to different screen sizes.
- Users enjoy effortless navigation throughout the entire site.
- For shoppers, the current shopping basket's cost is prominently displayed on larger screens.

![Nav Bar](https://i.ibb.co/F3btbDy/Nav-Bar.png)

**Introduction**
- The homepage provides a welcoming introduction, informing users about the site's purpose.

![Homepage Introduction](https://i.ibb.co/vYnW0Vk/Hero.png)

**Products Page**
- On the Product page, products are presented in rows of five on larger screens, featuring attention-grabbing, large images. Clicking on an image will redirect users to the product detail page.

![Products Page](https://i.ibb.co/YLCPwDy/Products-Page.png)

**Search Functionality**
- Utilizing the search function in the navigation bar, users can easily search for products or descriptions.
- Search results are displayed in a straightforward format, accompanied by a link that directs users to the general store page.

![Search Results](https://i.ibb.co/JHWKYqb/Search-Results.png)

**Toasts**
- Nearly all user actions trigger informative feedback through Bootstrap toasts.
- Shoppers can easily monitor their shopping bag's contents and the total cost, along with the visible delivery cost and the remaining amount required for free delivery.
- A convenient link to the checkout page is provided at the bottom of the toast notifications.

![Toasts](https://i.ibb.co/SXGgsHs/Toast.png)

**Shopping Bag**
- The shopping bag page is completely responsive, providing users with images of the items, their names, unit prices, and total prices.
- Users have the flexibility to adjust item quantities by increasing or decreasing them and can update prices with a single click.
- To empty the bag entirely, users can simply click the "remove" link, removing all items regardless of quantity.
- At the page's bottom, users can easily access the bag's cost, delivery cost, the overall total, and the required amount for free delivery eligibility.

![Shopping Bag Page](https://i.ibb.co/sPhV6nJ/Shopping-Bag.png)

**Checkout Overlay**
- When users proceed to checkout, they will encounter a straightforward overlay featuring a spinning icon during the payment processing.

![Loading Overlay](https://i.ibb.co/FxQp3K3/Loading-Overlay.png)

**Social Media Links**
- Each page within the project features a footer containing social media links.
- When users click these social media links, they are redirected to the respective social media pages in new tabs to ensure a seamless user experience.

![Social Media Links](https://i.ibb.co/L9R0V9h/Social-Media-Links.png)

---

## **Technologies Used**

- [Python](https://www.python.org/) 
    - The following Python modules were used on this project, 
		- asgiref==3.7.2
		- boto3==1.28.48
		- botocore==1.31.48
		- dj-database-url==0.5.0
		- Django==3.2.20
		- django-allauth==0.41.0
		- django-countries==7.2.1
		- django-crispy-forms==1.14.0
		- django-storages==1.14
		- gunicorn==21.2.0
		- jmespath==1.0.1
		- oauthlib==3.2.2
		- Pillow==10.0.0
		- psycopg2==2.9.7
		- python3-openid==3.2.0
		- pytz==2023.3
		- requests-oauthlib==1.3.1
		- s3transfer==0.6.2
		- sqlparse==0.4.4
		- stripe==6.4.0
		- urllib3==1.26.16

- [Heroku Postgres](https://www.heroku.com/postgres)

- [AWS S3](https://aws.amazon.com/)
 
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

- [CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

- [Bootstrap](https://getbootstrap.com/)

- [jQuery](https://jquery.com/)

- [JavaScript](https://www.javascript.com/)

- [Google Fonts](https://fonts.google.com/)

- [Font Awesome](https://fontawesome.com/)

- [Google Developer Tools](https://developers.google.com/web/tools/chrome-devtools)

- [Github](https://github.com/)

- [Git](https://git-scm.com/)

- [Gitpod](https://www.gitpod.io/)

- [Balsamiq](https://balsamiq.com/)

- [AutoPrefixer](https://autoprefixer.github.io/)

- [Grammarly](https://www.grammarly.com/)

---

## **Testing**

## **Manual Testing**

**Navigation Bar** 
- The navigation bar seamlessly adapts to various screen resolutions, including large, medium, and small.
- At 320px, all navigation links remain inline without wrapping onto another line.
- All links effectively redirect users to their respective pages.
- When signing out, the dropdown displays the options "Log in" and "Register" accurately.
- Upon signing in, the dropdown appropriately shows the options "My profile" and "Logout."
- Administrators enjoy an additional option in the dropdown menu, providing access to the "Product Management" page.

**Footer**
- Links redirect to the correct social media page.
- Links open in a new browser tab. 

**Products**
- Upon loading, products are displayed in the correct SKU order.
- The sorting functionality functions as intended, accurately arranging products in either descending or ascending price order.
- Product names and prices are verified against their corresponding database fields.
- Products are correctly labeled with the appropriate tags.
- Tags effectively redirect and filter products by their respective category names.

**Products Details**
- Clicking the product image correctly redirects users to the corresponding product.
- Product details are accurate and align with the information in the database.
- Quantity buttons for products are appropriately disabled when reaching 1 or 99.
- The "Add to Wishlist" button only appears for logged-in users as intended.
- All links function correctly, effectively redirecting users back to the products page and adding the selected product to the shopping bag.

**Admin**
- The Product Management page in the account dropdown is exclusively accessible to administrators.
- Only administrators can view the Edit and Delete buttons on the product details page.
- Links within Product Management accurately redirect to the add product page.
- The process of adding a product functions correctly, ensuring the product receives accurate information from the form and appears correctly within the database.
- The Delete button effectively triggers a modal to confirm deletion.
- Deleting a product correctly removes it from the database.

**Shopping Bag**
- The shopping bag link in the navbar accurately displays the current session's bag value.
- Quantity buttons are functioning correctly, ensuring users cannot exceed 99 or go below 1.
- The shopping bag displays the correct products as intended.
- Adding items to the bag and subsequently logging in retains the current bag contents as expected.
- The shopping bag correctly reflects the total cost.
- The free delivery threshold updates as expected and displays the accurate values.

**Checkout**
- The checkout page accurately carries over the correct items from the shopping bag.
- The form responds appropriately to invalid inputs, ensuring a smooth user experience.
- The redirection to the checkout success page is executed flawlessly.
- Stripe consistently displays 200 status webhooks for orders, indicating successful processing.

**Search Bar**
- The search function accurately displays results for the searched words.
- When adding a new product and searching by its name, the product is correctly shown.
- User feedback is precise and reliable.


**Chrome Dev Tools**

Throughout the project's development, Chrome DevTools were employed for responsive testing. Various devices were emulated using DevTools to assess responsiveness, including:
- Iphone SE
- Iphone XR
- Iphone 12 Pro
- Iphone X
- Ipad
- Ipad Pro

**Browser Testing**

During the development phase, testing primarily focused on Google Chrome. In the production phase, the website underwent testing across multiple browsers, including:

- Google Chrome
- Mozilla Firefox
- Opera
- Microsoft Edge

**Accessibility Assessment With Lighthouse**

***Overview***

This project focuses on evaluating the accessibility and performance of a web application using Google Developer Tools Lighthouse. The goal was to ensure that our web application meets high standards in terms of accessibility for both mobile and desktop users. The Lighthouse audits were conducted, and the following scores were obtained:

***Mobile Scores***

Performance: 87
Accessibility: 87
Best Practices: 100
SEO: 73

![Mobile Lighthouse Score](https://i.ibb.co/RBC3Rn1/Box-Store-Lighthouse-Mobile.jpg)

***Desktop Scores***

Performance: 98
Accessibility: 81
Best Practices: 100
SEO: 89

![Desktop Lighthouse Score](https://i.ibb.co/3vhtyBt/Box-Store-Lighthouse-Desktop.jpg)

***Key Findings***

***Mobile:***

Performance (87): The mobile performance score indicates that our web application is optimized and loads reasonably fast on mobile devices.

Accessibility (87): The accessibility score shows that our web application is largely accessible on mobile devices, but there is room for improvement.

Best Practices (100): We have adhered to best practices in web development for mobile devices, achieving a perfect score.

SEO (73): The SEO score suggests that there is room for optimization to improve search engine rankings on mobile devices.

***Desktop:***

Performance (97): The desktop performance score indicates that our web application performs exceptionally well on desktop devices.

Accessibility (81): While the accessibility score for desktop is good, some improvements can be made to enhance the user experience for individuals with disabilities.

Best Practices (100): Our web application complies with best practices for desktop devices, achieving a perfect score.

SEO (89): The SEO score suggests that our web application is well-optimized for search engines on desktop devices, but there is still potential for improvement.

***Action Items***

Based on these Lighthouse audit results, we will focus on the following action items:

Mobile Accessibility: Address accessibility issues identified in the mobile audit to ensure an inclusive user experience for all mobile users.

Mobile SEO Optimization: Optimize the mobile version of our web application to improve its search engine rankings.

Desktop Accessibility: Enhance the accessibility features of the desktop version to further improve the user experience for individuals with disabilities.

---

## **Customer Stories**

### **Customer Shopper Stories**

- As a shopper I would like to be able to view all products in one place so I can decide what to buy.
	+ Users can use the links on the nav bar to be directed to the products page. The All Products link will show every product that exists on the store. The other links on the nav bar will show the products based on the category.

![Nav Bar](https://i.ibb.co/F3btbDy/Nav-Bar.png)

The products page will show the customer all the products within the store.

![Products Page](https://i.ibb.co/YLCPwDy/Products-Page.png)

- As a shopper I would like to be able to view products in more detail.
	+ Shoppers can click on a product and they will be taken to the product detail page, where they can select the quantity of the item and add to their bag.
	
![Product Detail Page](https://i.ibb.co/TqX36Sc/Product-Detail-Page.png)

- As a shopper I would like to be able to see confirmation when a product is added to the bag.
	+ Shoppers who add a product to their bag are notified in the form of a Bootstrap to let them know what has been added to the bag.

![Add To Bag](https://i.ibb.co/YDt9nW9/Add-To-Bag.png)

- As a shopper I would like to be able to view my bag to see what is in it, and also be able to adjust quantities.
	+ Users can view the bag by clicking on it.
	+ Users can adjust the quantity in their bag by clicking the plus or minus symbol next to Qty.
![Shopping Bag](https://i.ibb.co/sPhV6nJ/Shopping-Bag.png)

### **Registered Shopper Stories**

- As a logged in customer I would like to be able to save my details, to make it easier to checkout next time.
	+ Registered customers can locate the Profile page by going to the navigation bar and clicking on the Account link where they can update their information.

- As a logged in customer I would like to be able to see my Order History.
	+ Registered customer can view ther order history on the Profile page next to their information.
	
![Profile Page](https://i.ibb.co/C80zGnf/Profile-Page.png)

## **Validation**


[W3C HTML Validator](https://validator.w3.org/)
- 0 Errors
- 0 Warnings

[W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- 0 Errors
- 6 Warnings
    - These warnings are in relation to a unknown vendor extentions.

[JSHint JavaScript Validator](https://jshint.com/)
- 0 Errors

[Python](https://www.python.org/)

- Alot of the Python errors were fixed during development.
- Any errors that related to files that were auto generated by Django were left untouched.
	- Migration files.
	- Project setting.py
	- ./manage.py
	- checkout/init.py

---

### **Bugs and Fixes**

- Missing 500 error pages.
    - Credit to Code Institute tutor support chat for assisting me in finding this issue and offering a solution.
    - Key mismatch on code and Heroku configuration variables.

- Profile page showing with raw code.
    - Credit to Code Institute tutor support chat for assisting me in finding this issue and offering a solution.
    - Indentation problems.

- Add to bag button was not working, instead of adding to bag was refreshing page.
    - Credit to Code Institute tutor support chat for assisting me in finding this issue and offering a solution.
    - Typo in views.py

- Add to bag button was not working, instead of adding to bag was refreshing page.
    - Credit to Code Institute tutor support chat for assisting me in finding this issue and offering a solution.
    - Typo in views.py

## **Deployment**

The main branch in this repository represents the latest version and serves as the basis for the deployed site.

This project was built using the Code Institute student template as a foundation.

[Code Institute Full Template](https://github.com/Code-Institute-Org/gitpod-full-template)

- Click the *Use This Template* button.
- Give your repository a name, and description if you wish.
- Click the *Create Repository from Template* to create your repository. 
- Click the *Gitpod* button to create a gitpod workspace, this can take a few minutes.
- When working on project using Gitpod, please open the workspace from Gitpod, this will open your previous workspace rather than creating a new one.
Use the following commands to commit your work, 
- `git add . ` - adds all modified files to a staging area.
- `git commit -m "A short message exlaining your commit"` - commits all changes to a local repository.
- `git push` - pushes all your commited changes to your Github repository.

**Requirements**

- [Python 3](https://www.python.org/downloads/)
- [Pip](https://pypi.org/project/pip/)
- [Git](https://git-scm.com/)
- [AWS S3](https://aws.amazon.com/)

**Creating a Clone**

1. From the repository, click *Code*
2. In the *Clone >> HTTPS* section, copy the clone URL for the repository
3. In your local IDE open Git Bash
4. Change the current working directory to the location where you want the cloned directory to be made
5. Type `git clone`, and then paste the URL you copied in Step 2 - ``git clone https://github.com/imransal/box-store.git``
6. Set the following values in a `env.py` file.
```
import os

os.environ.setdefault("SECRET_KEY", "<app secret key of your choice>")
os.environ.setdefault("DEVELOPMENT", "True")
os.environ.setdefault('STRIPE_PUBLIC_KEY', '<key generated by Stripe>')
os.environ.setdefault('STRIPE_SECRET_KEY', '<key generated by Stripe>')
os.environ.setdefault('STRIPE_WH_SECRET', '<key generated by Stripe>')
```

- Stripe keys are generated by Stripe, each individual have their own unique key values.
- *PLEASE MAKE SURE NEVER TO PUBLISH THESE KEYS, ADD THE `env.py` TO A `.gitignore` TO AVOID PUSHING KEYS TO GITHUB.*
7. Install the project requirements - `pip3 install requirements.txt`
8. Apply database migrations - `python manage.py migrate`
9. Create a superuser - `python manage.py createsuperuser`
10. The project can be run with the following - `python manage.py runserver`

**Heroku Deployment**

1. Log into Heroku
2. Create a new app, choose a location closest to you
3. Search for Heroku Postgres from the resources tab and add to your project
4. Make sure to have `dj_database_url` and `psycopg2` installed.
```
pip3 install dj_database_url
pip3 install psycopg2
```
5. Login to the Heroku CLI - `heroku login -i`
6. Run migrations on Heroku Postgres - `heroku run python manage.py migrate`
7. Create a superuser - `python manage.py createsuperuser`
8. Install `gunicorn` - `pip3 install gunicorn`
9. Create a requirements.txt file - `pip3 freeze > requirements.txt`
10. Create a `Procfile` (note the capital P), and add the following,
```
web: gunicorn moose_juice.wsgi:application
```
11. Disable Heroku from collecting static files - `heroku config:set DISABLE_COLLECTSTATIC=1 --app <your-app-name>`
12. Add the hostname to project settings.py file
```
ALLOWED_HOSTS = ['<you-app-name>.herokuapp.com', 'localhost']

```
13. Connect Heroku to you Github, by selecting Github as the deployment method and search for the github repository and pressing `connect`
14. In Heroku, within settings, under config vars select `Reveal config vars`
15. Add the following, 
```
AWS_ACCESS_KEY_ID =	<your variable here>
AWS_SECRET_ACCESS_KEY =	<your variable here>
DATABASE_URL =	<added by Heroku when Postgres installed>
DISABLE_COLLECTSTATIC =	1 
EMAIL_HOST_PASS = <your variable here>
EMAIL_HOST_USER = <your variable here>
SECRET_KEY = <your variable here>
STRIPE_PUBLIC_KEY = <your variable here>
STRIPE_SECRET_KEY = <your variable here>
STRIPE_WH_SECRET = <different from env.py>
USE_AWS = True
```
16. Go back to the Deploy tab and under Automatic deploys choose `Enable Automatic Deploys`
17. Back in your CLI add, commit and push your changes and Heroku will automatically deploy your app
```
git add .
git commit -m "Initial commit"
git push
```
18. Your deployed site can be launched by clicking `Open App` from its page within Heroku.

**AWS S3 Bucket setup**
1. Create an Amazon AWS account
2. Search for S3 and create a new bucket
    - Allow public access
3. Under Properties > Static website hosting
    - Enable
    - index.html as index.html
    - save
4. Under Permissions > CORS use the following:
```
[
  {
      "AllowedHeaders": [
          "Authorization"
      ],
      "AllowedMethods": [
          "GET"
      ],
      "AllowedOrigins": [
          "*"
      ],
      "ExposeHeaders": []
  }
]
```
5. Under Permissions > Bucket Policy:
    - Generate Bucket Policy and take note of Bucket ARN
    - Chose S3 Bucket Policy as Type of Policy
    - For Principal, enter *
    - Enter ARN noted above
    - Add Statement
    - Generate Policy
    - Copy Policy JSON Document
    - Paste policy into Edit Bucket policy on the previous tab
    - Save changes
6. Under Access Control List (ACL):
    - For Everyone (public access), tick List
    - Accept that everyone in the world may access the Bucket
    - Save changes

**AWS IAM (Identity and Access Management) setup**
1. From the IAM dashboard within AWS, select User Groups:
    - Create a new group
    - Click through and Create Group
2. Select Policies:
    - Create policy
    - Under JSON tab, click Import managed policy
    - Choose AmazongS3FullAccess
    - Edit the resource to include the Bucket ARN noted earlier when creating the Bucket Policy
    - Click next step and go to Review policy
    - Give the policy a name and description of your choice
    - Create policy
3. Go back to User Groups and choose the group created earlier
    - Under Permissions > Add permissions, choose Attach Policies and select the one just created
    - Add permissions
4. Under Users:
    - Choose a user name 
    - Select Programmatic access as the Access type
    - Click Next
    - Add the user to the Group just created
    - Click Next and Create User
5. Download the `.csv` containing the access key and secret access key.
    - **THE `.csv` FILE IS ONLY AVAILABLE ONCE AND CANNOT BE DOWNLOADED AGAIN.**

**Connecting Heroku to AWS S3**
1. Install boto3 and django-storages
```
pip3 install boto3
pip3 install django-storages
pip3 freeze > requirements.txt
```
2. Add the values from the `.csv` you downloaded to your Heroku Config Vars under Settings:
3. Delete the `DISABLE_COLLECTSTATIC` variable from your Cvars and deploy your Heroku app
4. With your S3 bucket now set up, you can create a new folder called media (at the same level as the newly added static folder) and upload any required media files to it.
    - **PLEASE MAKE SURE `media` AND `static` FILES ARE PUBLICLY ACCESSIBLE UNDER PERMISSIONS**


---

## **Credits**

**Product Images / Names / Descriptions**
-  Credit to Box Fit UK for providing the images and products used in my project.
- [Box Fit UK](https://www.boxfituk.com/)
	- This project is made solely for educational purposes. There is no financial gain from the project. 

**Code**
- A significant portion of the code is derived from the Code Institute's Boutique Ado Project.
- [Code Institute](https://codeinstitute.net/)
    - Boutique Ado served as a tutorial project at Code Institute, providing students with an introduction to Django, AWS S3, Stripe, and Heroku Postgres.
    - The foundational functionality of Box Store is directly borrowed from the Boutique Ado project.

**Bootstrap**
- The project extensively utilized the Bootstrap Library, specifically version 4.6.
- [Bootstrap](https://getbootstrap.com/)
    - Key elements such as Toasts, Navigation Bar, Forms, Dropdown Menu, and Buttons were all incorporated into the project, building upon Bootstrap's comprehensive components section.

**Django Documentation**
- Django boasts exceptional documentation, featuring a tutorial project and in-depth explanations of its core components.
- [Django Documentation ](https://docs.djangoproject.com/)
