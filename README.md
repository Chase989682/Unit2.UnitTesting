# Unit2.block18Testing 
**A function called "multiplication" that returns the product of the two input numbers.

A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
...should result in [-1, 1, 3, 9, 15]
Think about the following; you may need to make assumptions or decisions about the prompt and how the code should behave:
What should happen with unexpected inputs?
What kinds of unexpected inputs should we worry about?
What should happen when there are multiples of the same odd number in the arrays? (Hint: We gave you the answer to this one in the example above.)**

-function - multiplication: create a function that takes the parameters of x and y and return x * y. 
-call function - create a variable and call that function with any numbers as the parameters to test the function.  Or you can console log the function with your own numbers as parameters.
-function - create a user prompt that asks the user to enter 2 numbers separated by a space.  Create a split with a variable and return the 2 strings as numbers.
when the user enters 2 numbers, the output will be the product of the 2 numbers.
when the user only enters 1 number or anything that is not a number, the prompt will return an error message.

-function: odds -a function is created to return the odds of an array.  When the array contains non numerical elements, those elements should be excluded from the returned odds array.  When the array contains duplicate odd numbers, it will return all the odds including each iteration of a duplicate.  When the array contains negative odd numbers, it will return those numbers.  When the array contains no odd numbers, it will return null

**A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:
What should happen if the cart is empty?
What needs to be shown to the user at each step of check out?
What behaviors of this feature does the prompt miss or gloss over?
Hint: Observe the shopping cart and checkout features of some popular websites to get some ideas!**
- Functionality tests - when the user clicks the checkout option, it takes them to a page where they have 2 options: checkout as guest, or log in and checkout.  If the user is already logged in, the user is directed to the shipping address section.  If the user is not logged in, they must select either option and it will direct them contingent upon which option they selected.  If the logged in user has shipping information in their profile, the page will autofill and have the user confirm the information.  The page should also give them an option to use a different shipping address.  If incorrect data is entered such as an invalid zip code, the page will return an error message.  If correct data is entered, the user will be directed to the billing page.  The same process is done with this page.

- 
- 
