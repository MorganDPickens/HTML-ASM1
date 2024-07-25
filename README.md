Purpose:
The purpose of this assignment is to create a simple web-based tool that allows the user to create a grocery list. The script enables the user to enter as many grocery items as they want.

Task
Accepting Input: The script gathers user input for grocery items, concentrating exclusively on collecting their names. It also validates for cases where no list is provided.

Storing in an Array: Each entered grocery item is stored in an array called groceryItems. Using an array allows for easy storage and manipulation of the grocery items.

Sorting the List: Once the user is finished entering the items.  The script sorts the list of grocery items alphabetically. Sorting helps to display the items in a neat and organized manner, making it easier for the user to review the list.

Displaying the List: After sorting, the script displays the grocery items on the web page, with each item listed on a separate line. The use of the <pre> element preserves the line breaks in the displayed list, enhancing readability.

Counting the Items: The script counts the total number of grocery items entered by the user. Instead of using a separate counter, it simply retrieves the length of the groceryItems array, which corresponds to the number of items entered. This provides an efficient way to calculate and display the total count.

Starter Code:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Grocery List</title>
  </head>
  <body>
    <h2>Grocery List</h2>
    Enter grocery items separated by commas.
    <br>
    <textarea id="groceryInput" placeholder='Enter grocery items and sperate with comma ","when finished.'></textarea>
    <br>
    <button onclick="createGroceryList()">Create Grocery List</button>
    <p id="groceryList"></p>
    <p>Total items: <span id="totalItems"></span></p>

  <script>
    function createGroceryList() {

    //Check for empty input from user
    
    // Split input string into array
    
    // Trim white space from each items by looping through array

    // Sort groceryItems alphabetically
    
    // Display grocery list to webpage
    
  </script>
  </body>
</html>
 

Example:

Grocery List Start

If the user clicks "Create Grocery List" without providing any items, they will be alerted to enter items.

Alert Prompt

Enter all grocery items separated by commas and click the "Create Grocery List" button when finished.

Entering Items

After clicking "Create Grocery List," your list will be printed.

List
