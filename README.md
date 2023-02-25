# Brainnest_first_week 
  ## [Assignment 1](https://rawcdn.githack.com/tofy1234/Brainnest_first_week/1277ef99152c69442a7594b59e065319f49f2c43/index.html) 

## **Assignment Description**
### **Part1 (Lists):**

a. An unordered shopping list of your favorite foods

b. An ordered list of todo’s you need to get done today

c. An unordered list inside of an ordered list, of places you’d like to     visit someday

d. An ordered list inside of an unordered list, of your all time top 5 favorite video games or movies

***

### **Part2 (Links & Images):**

a. Create a new directory named links-and-images

b. Within that directory, create a new file named index.html

c. Fill in the usual HTML boilerplate

d. Set the title to “Links & Images”

e. Finally, add the following h1 to the body: Homepage

f. Create another HTML file named about.html

g. Back in the index page, add the following anchor element below the h1
element: <ahref=”https://theuselessweb.com/”>click me</a> <ahref="about.html">About</a>

h. Open the index file in a browser and click on the About link to make sure it is all wired together correctly. Clicking the link should go to the empty about page you just created (you can fill it in if you like)

i. Create a directory named pages within the links-and-images directory and move the about.html file into this new directory. Refresh the index page in the browser and then click on the about link. It will now be broken. This is because the location of the About page file has changed. To fix this, you just need to update the about link href value to include the pages directory since that is the new location of the about file relative to the index file. <ahref="./pages/about.html">About</a>

j. In many cases, this will work just fine; however, you can still run into unexpected issues with this approach. Prepending ./ before the link will in most cases prevent such issues. By adding ./ you are specifying to your code that it should start looking for the file/directory relative to the current directory. You can also add a link to get back from the About page to your homepage

k. To use images on your own websites, you can use a relative path:

    * Create a new directory named images within the links-and-images  project
    * Next, download any image .jpg/.png and move it into the images directory you just created
    * Rename the image to first-img.jpg/.png
    * Add the image to the index.html file: <img src="images/first-img.jpg">

v. Save the index.html file and open it in a browser to view your image in all its glory. Remember to use ./ before the images/first-img.jpg if your
image isn’t loading

l. As a bit of practice, add an alt attribute to the first-img you added to thelinks-and-images project.

***

### **Part3 (Main HTML project):**

For presentation make a few page presentation website about your hobby/favorite books/movies etc. Your website should contain a homepage with a link to go inside to the page where your material should be presented in list form, with links leading to pages with the description(text & image) of your chosen subject. As an added bonus, you can make each list element into a link, leading to the page where additional information about said subject can be found(images are always welcomed, just don't over do it :D)
***
