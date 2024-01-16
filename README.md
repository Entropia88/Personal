300x427-Main.png
Website Development
Production

Jan 02, 2024

Aris B.

9min Read
Making a Website With HTML in 7 Simple Steps + Post Development Suggestions

Building a website nowadays is simple and doesn’t require coding knowledge. Platforms like Hostinger website maker offer a simple visual interface and drag-and-drop features to ease the development process.

However, you may want to build websites from scratch with Hypertext Markup Language (HTML). While it is more difficult, HTML websites are more flexible and faster as they require fewer resources to run.

To help you get started, this article will explain the steps in making a website with HTML. We will also provide you with post-development practices to improve your HTML site’s appearance and functionality.

Download Website Launch Checklist

    How to Make a Website With HTML
        1. Pick an HTML Code Editor
        2. Plan the Site Layout
        3. Write the HTML Code
        4. Create Elements in the Layout
        5. Add the HTML Content
        6. Include Layout CSS
        7. Customize Your Site
        8. Choose a Hosting Platform and Publish
    Tips on Optimizing an HTML Website
    Do I Need to Learn HTML to Build a Website?
    Making a Website With HTML FAQ
        Is HTML Enough to Create a Website?
        Is HTML Good for Creating Websites?
        How Long Does It Take to Code an HTML Website?

How to Make a Website With HTML

This section will provide step-by-step instructions to code a site with HTML. Before proceeding, refer to our HTML cheat sheet if you are unfamiliar with the standard markup language. Feel free to check out our guide on the basics of building a site to get more familiar.
1. Pick an HTML Code Editor

A code editor is software used to write your website. While you can create an HTML page with a default text editor like Notepad, it lacks features that help simplify the development process, such as:

    Syntax highlighting – marks HTML tags in different colors based on their categories. This makes the code structure easier to read and understand.
    Auto-completion – automatically suggests HTML attributes, tags, and elements based on the previous value to speed up the coding process.
    Error detection – highlights syntax errors, allowing a web developer to quickly notice and fix them.
    Integration – some code editors integrate with plugins, Git, and FTP clients to make the deployment process more efficient.
    Live preview – instead of opening HTML files manually on browsers, you can install a plugin to get a live preview of the site.

Live preview feature in Visual Studio Code

Since there are many options, we have listed some of the best HTML code editors to help you find one that fits your needs:

    Notepad++ – a free, lightweight text editor with added features for coding and plugin support.
    Atom – an open-source HTML editor with a live website preview feature and extensive markup and scripting language compatibility.
    Visual Studio Code (VSCode) – a popular tool for web development with a comprehensive extension library to expand its functionalities.

2. Plan the Site Layout

Creating a layout plan allows you to better visualize your website’s look. You can also use it as a checklist to track what elements to include in your site.

In addition, a layout plan helps you determine your site’s usability and navigation, which affect user experience. Some elements to consider when planning include the sites’ header, footer, and navigation.
A rough website layout plan

You can use pen and paper or web design software such as Figma to design a website layout. It doesn’t have to be detailed as long as it roughly represents the look and feel of your site.
3. Write the HTML Code

Once the tool and layout plan is ready, you can start writing your site’s code. The steps may vary depending on your code editor, but the general idea is similar.

In this tutorial, we will show you how to do it using VSCode:

    Create a new folder on your computer. It will be the directory for all of your site’s files.
    Open VSCode → File → Open Folder.
    Locate the new folder and click Select Folder.
    Select New File. Name the file index.html and press enter.
    Click Create File to confirm.
    Once prompted to the index.html editor tab, enter the following basic HTML document structure:

<!DOCTYPE html>
<html>
   <head>
      <title> </title>
   </head>
   <body>
   </body>
</html>

To help you understand the code, here’s an explanation of each tag:

    <!DOCTYPE html> – tells web browsers that the website is an HTML page.
    </html> – the HTML document opening tag indicating where the code starts.
    <head> – a tag containing the site’s metadata.
    <title> – defines the text shown on the browser tab when visiting the web page.
    <body> – contains all visible content on the web page.

Pro Tip

Learn the difference between making a website using WordPress vs HTML to know which technique suits you best.
4. Create Elements in the Layout

Add HTML code into the index.html file to create the elements of your planned layout. Depending on your website design, you will need different HTML semantic elements.

These elements will separate your site into multiple sections and become the containers for the content. Here are the tags we will use:

    <header> – container for introductory content or navigation.
    <main> – represents the primary content of a web page.
    <div> – defines a section in an HTML document.
    <footer> – contains the content displayed at the bottom of your website.

Put these elements within the <body></body> tags in your index.html file’s code. Ensure to close each element with a closing tag, or your code won’t work.

Here’s how the complete code looks:

<!DOCTYPE html>
<html>
   <head>
      <title>Personal Blog</title>
   </head> 
   <body>
      <header>   

      </header>
      <main>
         <div class=”row">
            <div class=”post-text-box”>

            </div>
            <div class=”profile”>

            </div>  
         </div>        
      </main>
      <footer>
            
      </footer>
    </body>
</html>

5. Add the HTML Content

After the layout is ready, start filling them with your site’s content, like text, images, hyperlinks, or videos. If the content is not ready, use dummy content as a placeholder and replace it later.

Here are some tags we will use to add the website content:

    <h1> and <p> – contain heading and paragraph text. Use <br> tag to create a line break if the text is too long.
    <nav> and <a> – specify the navigation bar and its anchor element. Use the href attribute to specify the anchor’s linked URL.
    <img> – container for the image element. It contains the img src attribute, specifying the link or name of the image file.

Pro Tip

The img tag also has an optional alt attribute. It describes the image in case the file doesn’t load.

Here’s what the code looks like:

<!DOCTYPE html>
<html>
   <head>
      <title>Personal Blog</title>
      </head> 
   <body>
      <header>   
      <h1>Your Personal Blog</h1>
      <nav>
         <a href=”domain.tld/home”>Home</a>
         <a href=”domain.tld/blog”>Blog</a>
         <a href=”domain.tld/about”>About</a>
      </nav>
      </header>
      <main>
         <div class=”row">
            <div class=”post-text-box”>
               <h1>Newest Post</h1>
               <section>
                  <h1>First Post</h1>
                  <p>The first post’s content</p>
               </section>
            </div>
            <div class=”profile”>
               <h1>About Me</h1>
               <img src=”Profile.jpg”>
               <p>About the author</p>
            </div>  
         </div>        
      </main>
      <footer>
         <a href=”twitter.com/author”>Twitter</a>
         <a href=”facebook.com/author”>Facebook</a>
         <a href=”instagram.com/author”>Instagram</a>
      </footer>
    </body>
</html>

