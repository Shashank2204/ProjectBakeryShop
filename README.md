# ProjectBakeryShop
This application is made in javascript, Html and Css which serves as an online cake and cookie shop.


User Interface:
 The application is used to calculate the total for making a cake and cookie.
 The input text takes the input from user and total amount is displayed.
 There are three outputs when we press the submit button.
1. Total of the recipes.
2. The Total from each supplier.
3. The quantity of each ingredient from each supplier.
Assignment1.html :
The file contains the basic HTML page where the initial HTML tags and Javascript. The javascript function contains two major parts, one is the calculation logic and second is the display of HTML page based on Jason read data.
On the page load the recipe for making one cake and cookie is displayed on the left sidebar of the page which is read from the json file.
On the right of the page there are input text for the quantity along with submit and reset button. When the user enter any quantity and press the submit button the on click event is added where we get total rounded off to 2 digits and the combinations of all the ingredients for all the recipes. Also, the total cost per supplier and the quantity of ingredients are displayed. The reset button is used to clear the values and allow the user to re-enter and calculate the recipe total.
