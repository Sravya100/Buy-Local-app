# Buy-Local-app

Buy Local, a shopping app for selling and buying organic products produced locally. The main purpose of our app is to provide users with a unique experience of online shopping that not only caters to their organic needs but also promotes local and small-scale businesses. For the scope of this class, we majorly focused on the user interaction design by implementing the design principles and techniques that we learnt through the course of this semester, and plan to develop it further by transforming it into a fully functional application that can be used in real life. We implemented the following use cases in our application, focusing mainly on the design.


Key use cases: 


1)	Navigation bar
This is a small component on the application but plays an important role as the user can navigate to every component on the application via navbar. It contains the application name, a dropdown button for selecting the category of products, and few icons for navigating to the home page, contact page, cart, and the user login/signup page that help user easily recognize what they mean and the action that they can perform using them. 

2)	Product Catalog
This section is one of the main components of the application as it lists all the products that are available to the users to purchase and are divided based on the subcategories for reducing the search time. The products are displayed in box-containers that displays the image, name, original price, discounted price, and discount on the product. It also consists of an “Add to cart” button and when the user clicks on it, the product gets added to the cart with a confirmation message that says, “Item added to cart”. The user can get to this section by clicking on “Products” on the navbar or by selecting a category from the dropdown menu beside it.

3)	Cart
This component displays the items that get added on clicking “Add to cart” button. The cart describes the item added, price of the item and quantity. The quantity can be increased or decreased by clicking on the up and down arrow buttons beside the number. We added a dustbin icon for removing items from the cart. At the bottom of the cart, the total price of all the items in the cart is calculated and displayed. A “Purchase” button is added that gives a message “Thank you for your purchase” when the user clicks on it. This component can be reached by clicking on the cart icon on the navbar.


Interesting revisions:

The following are the two interesting revisions that we made to our app:

1)	The original design of the navbar was text heavy and the contents help the user redirect to different components on the app. We used the principles from Visual Design and identified that it does not follow approachability and minimalistic design. The issue was that the navbar contained a lot of content which did not look clean and simple, as there wasn’t enough negative space to differentiate similar action items. Moreover, there were redundant items on the navbar, and it was clumsy. In the revised design, the text was replaced with icons, and they were grouped in such a way that similar action items were placed together. Now, the navbar looks cleaner and the users can easily find what they are looking for by just looking at the icons. Although this was a small change in the design, we were surprised by how much of a difference it made to the look of the app and improved how quickly a user could navigate to a desired section of the app.

2)	The original design of the product catalog listed all the products available under a single section. We used the guidelines from Site Design and identified that there is no hierarchy in the catalog itself and the users must browse through each item for finding the products they need. The products listed in the product catalog do not have proper grouping of items. We have addressed this issue by creating subcategories such that similar products in the catalog are grouped together. We added subcategories for fruits, vegetable, dairy, and nuts. We also added a dropdown on the navbar where the user can directly select a subcategory of products and get redirected to that specific section of the catalog. This has majorly improvised the user experience on the app as they can now easily find the products that they are looking for without having to browse through the entire catalog which takes a lot of time.



Key insights:

During the development our web application, we understood the importance and impact of Human Computer Interaction (HCI). As a team, we intended to provide the users with the best-user experience through our application and this enabled us to establish a practical understanding of the HCI techniques and guidelines that we learnt during this course. It was reviewed by many users during and after the development, and the users gave positive feedback on the accessibility and usability after we implemented the design principles. The following are the two of the lessons we learnt while working on this project besides many other interesting takeaways:


1)	The web application's design must convey the meaningful information and enable the user to understand the current state. We had to ensure that the layout followed a logical workflow, and the user could have control on what analysis one could perform and their corresponding visualization.


2)	A well-designed application adhering to HCI concepts will allow developers, engineers, and researchers to approach it with intuition and a natural workflow. Designing applications is more of a "technical art." It is a blend where you need to understand the application and be able to visually organize the required process/analytics. 
