 # MENTROSHOP APP
 A web based ecommerce application developed using NodeJS. The app come with features that allow publishing of new product entries, adding product pictures through URL. Products are managed through the admin. In databse I used stored MongoDB for storing product information, user information(eg:- user credentials, products under particular user), cart information.
 
 ## Tech Stack
 
 1. NodeJS
 2. HTML
 3. CSS
 4. JavaScript
 5. MongoDB
 
 
 ## Screenshots

1. This is the landing page. User has the option to login in with his/her loging credentials after signing up. Unauthenticated user wont see protected routes over the navbar.

![300](https://user-images.githubusercontent.com/51373298/151177220-08cbd0f3-f921-418d-a52f-bd192bfcc508.JPG)

2. User need to signup/login with proper credetials else it will give validation error. Validation was implemented using express-validator package. Once signup is done user to redirected to login page.

![302](https://user-images.githubusercontent.com/51373298/151177783-e2c817df-14f8-458a-acf5-2c22d1c3715a.JPG)

3. Once user logs in session to be created for the user and stored in session collection. Now user can see other options in the navigation bar along with logout functionality. User can add the required item to their cart and it will be stored. Once user places an order the cart gets empty. Relations are maintained across different mongoose collections.

![303](https://user-images.githubusercontent.com/51373298/151178504-ca6706c5-bbc3-442c-8eaa-6d31c5f2ef02.JPG)

4. Cart option will contain products added by respective user along with a functionality to delete any product. Once order is placed user cart to become empty.

![304](https://user-images.githubusercontent.com/51373298/151179515-3e3ebd7e-1980-4abb-9b7e-b9956ccc0bcc.JPG)

5. Placed orders to be viible under the orders tab along with order id. Order details are being stored in another orders collection.


![305](https://user-images.githubusercontent.com/51373298/151180316-566def50-810f-424d-9a1f-c7841339ba27.JPG)

6. Admins can add product by providing the required details.

![306](https://user-images.githubusercontent.com/51373298/151180919-551f2eab-8ed7-446b-b8d7-1e4d0a7dcd3c.JPG)




## Lessons Learned

- How to perform CRUD operations using NodeJS.
- Work with API endpoints and templating engines.
- Work with multiple collections having relationship with each other.
- Get data from database and rendering it to client side.
- How to implement basic authentication & authorization.
- Handle exception and validate user input.
- Working with NoSQL database.
