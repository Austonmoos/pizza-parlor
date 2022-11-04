# Pizza-Parlor 

# By Auston Moos

# Select topings and Pizza to see final price 

# Technologies Used
* HTML
* CSS
* Git
* GitHub pages
* JavaScript

# Enter amount of toppings, size of pizza to see the final cost of your meal. 

# Setup/Installation Requirements

1.Make a directory on your desktop where you would like to clone the repo.

2.Copy the repo link: https://github.com/Austonmoos/pizza-parlor

3.Open your terminal and change into the directory you made (cd /path/to/new/directory).

4.Type git clone and paste the URL.

5.Copy and paste the path to index.html into your browser's URL bar to open the page.

# Known Bugs
* No Known Bugs


 MIT License

Copyright (c) [2022] [Auston Henry Moos]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Test Driven Development 

Describe: Pizza()

Test: "It should return a Pizza object with two properties for toppings and size"
Code: const myPizza = new Pizza(["anchovies", "pineapple"], "medium");
Expected Output: Pizza { toppings: ["anchovies", "pineapple"], size: "medium" }