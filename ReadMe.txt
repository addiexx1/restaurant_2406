
/* Font Awesome icons were used to replace add.png and remove.png */

1. Skeletons design:

<body>

<div>****select options****</div>
<div>****restaurant headers: name, min_order, delivery_charge****</div>

<div>
    This is the ***** main restaurant Container ***** in 3 coloums: Category, menu, order
    display: flexbox
    Under each coloums, div tags are used in the following structure:
    - For Category: categoryDiv > categoryHeader + categories
    - For Menu: menuDiv > menuList
    - For Order: orderDiv > groupDiv > orderHeader + orderDetail + totalDiv + submitDiv

</div>


</body>

2. Global variables: 
    - Document Objects
 * restaurantSelect: drop-down list to select restaurant
 * container: where categories, menu and order summary display
 * order: object has 3 keys: name, price, quantity
    - variables
 * orderArr[]: to store all the orders
 * int restaurantIndex: index in the restaurants[]

3. Functions:

function selectRestaurant(); // handles events on chaning restaurant

function display();  //render html page

function addOrder(); //when add "+" icon is clicked, add order to orderArr[]

function removeOrder(); //remove order from orderArr[]

function calculateTotal(); //calculate subtotal and return subtotal