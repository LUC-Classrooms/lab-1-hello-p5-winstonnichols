# Welcome to COMP 125 @ LUC on GitHub with Dr. Wetzel!
If you're seeing this, you have successfully created your account and joined up with COMP 125 @ Loyola University Chicago with Dr. David Wetzel.

In this lab, you will connect this project to the P5.js code library and run a simple P5 sketch to prove that it works. Once you have done that, submit your lab for course credit.
## setup instructions
In order to view this code as a web page, you will have to set up GitHub "Pages" for this repository (sorry, I can't automate this feature for you!):
1. Go to the "settings" tab and look for a menu item called "pages"
2. in the pages menu, you will see a dropdown menu under "Branch." Change it from "none" to "master" and hit "Save"
3. Now go back to the "Code" tab of your repository, and look for the "About" section on the right-hand side of the page. Click the "gear" icon for the "About" settings
4. In the pop-up window, you should see a field for "website." Check the box that says "Use your GitHub Pages website" and hit "Save Changes"

Now the **"About"** section of your repository will show a link to your web page created from your code. Click that link and it should open a new tab showing the output of your work. For now, it's a very bare-bones page that says "Hello P5!"

## coding instructions

1) Look at the "Files" list here in your new GitHub repository. You should see three files. Besides the file you are reading now (README.md) there are two essential files for this project (viewable as a web page): index**.html** and script**.js**. To complete this lab, you will edit each of these files a little bit ...

2) **Link your project to the P5.js Code Library** (Don't worry if that doesn't mean anything to you yet). Click on the link for "index.html" and find the little 'pencil' icon to edit the file. Copy and paste the following code block in _index.html_ at line 8:

  ``` html
  <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.0.0/p5.min.js"></script>
  ```
  ... then hit "Commit changes ..." to open a pop-up window. You can change the "commit message" if you like (this will be saved in a list of edits to your project so you can track changes), but more importantly make sure "commit directly to the main branch" is selected and press "commit changes"

3) **Prove that it works.** Open and edit _script.js_. Add the following code block on line 2 (after the ``` // comment```):

  ```javascript
  function setup(){
    fill(0);
    ellipse(50, 50, 50, 50)
  }
  ```
Save and commit your work like you did in step 2.

Open your page again in a separate tab to see the web page output.

If everything is correct, you should see a **black circle** on the upper left corner of the window, under the "Hello P5!" title text.

**Don't see it?** even though you did everything correctly? It might be that your browser is still looking at an older version of the page. You might need to "Force Reload" the page (Shift-Command-R on Mac/Chrome; CTL-F5 on most Windows browsers) 

### submit your work on Sakai under "Lab 1 - Hello P5!"
- download your code from this repository as a.zip file (it will probably be in your "Downloads" folder)
- Submit that .zip archive file as an attachment
- Add a link to your repository in the comments
