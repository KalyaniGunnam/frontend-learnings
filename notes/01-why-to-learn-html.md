# Why Should We Learn HTML?
**HTML (Hypertext Markup Language)** is a *fundamental skill in web development and online communication. In today's digital age, having an online presence is crucial. Knowing how to create and manage this presence can give you a significant advantage.* For instance, understanding HTML could impress a potential employer and make you stand out from other candidates.

So, why not start learning HTML today?

# What is HTML?
*HTML stands for Hypertext Markup Language. It is the foundation of every webpage, using specific tags (markup) to convey to web browsers how content should be displayed.*

## Key Features of HTML:
**1. Tags and Markup:** *HTML uses tags to define content. These tags are usually in pairs, with the content placed between them.*
- `Header Tags (<h1>, <h2>... <h6>):` Typically used for titles or headings.
- `Paragraph Tags (<p>):` Used for paragraphs of text.
- `Anchor Tags (<a>):` Used for hyperlinks.
**2. Structure:** *HTML adds structure to a webpage. Think of it as the foundation or skeletal structure of a website.*

## HTML and CSS in the Web Development as a Building Analogy:
HTML and CSS can be understood by comparing them to building a house. Think of HTML as the basic structure of the house—it’s like building the walls, roof, windows, and doors. It creates the shape and layout of the house, making it functional but very plain and boring to look at.

CSS, on the other hand, is like decorating the house. It’s the paint on the walls, the style of the furniture, the curtains on the windows and the tiles on the floor. CSS makes the house look beautiful and inviting, giving it personality and style.

If you only had HTML, your website would work, but it would look like a plain house with no decorations—useful but not exciting. If you only had CSS without HTML, it would be like having a pile of decorations with no house to put them in. When you combine HTML and CSS, you get a house that’s both strong and beautiful, just like a website that is functional and appealing.

So we can say that,
- HTML: The foundation and skeletal structure supporting all content.
- CSS (Cascading Style Sheets): The design, decorations and colors—the visual styling of the webpage.

## Tools You Need to Start Working with HTML and CSS:
- A Modern Web Browser: Google Chrome, Firefox, Microsoft Edge, Safari.
- A Text Editor: Visual Studio Code (VS Code), a free and powerful code editor that acts as your workspace for writing code.

## Setting Up Your Environment
To begin working with HTML and CSS, follow these steps to download, install and configure Visual Studio Code (VS Code), and prepare a project folder.

## How to Download and Install VS Code:
Visit the Visual Studio Code website. Choose the version for your operating system (e.g., Windows, macOS, Linux).For Example: If you're using Windows, download the Windows version. Once the download is complete: Open the installer file.Accept the agreement (if prompted) and Follow the steps:
- Click Next.
- Choose installation preferences (e.g., create a desktop icon).
- Click Install.
- When the installation finishes, launch Visual Studio Code and click Finish.

## Creating a Project Folder and First HTML File:
    - Create a Folder for Your Website:
    - Open VS Code.
    - Go to File > Open Folder.
    - Navigate to where you want the folder to be (e.g., your desktop).
    - Create a new folder by clicking New Folder.
    - Name the folder, for example, vscode_workspace.
    - Select the folder to open it in VS Code.

## Create Your First HTML File:
- Inside the Website folder in VS Code:
- Click the New File button or use the shortcut.
- Name the file index.html.
You are now ready to start writing HTML code in your newly created file.

# Why index.html?
This is the default file most servers look for to serve as the homepage.Naming it index.html ensures compatibility and good practice.

# Installing the Live Server Extension:
- Open the extensions tab in the VS Code.
- Search for Live Server and install the extension.

# Purpose of Live Server:
It automatically updates your browser view whenever you save changes to your HTML file, saving time during development.

# Setting up basic HTML structure:
Open index.html file and start by declaring the document type:

`<!DOCTYPE html>`

This declaration specifies that the document is written in HTML5, the latest version of HTML.

## Creating the HTML Root Element:
### Add the root <html> tags:
```
<html>
</html>
```
Everything in your HTML document will be nested inside these tags. The `<html>` element represents the entire document.

### Adding the <head> Section:
Inside the `<html>` element, create a <head> section:
```
<head>
</head>
```
The `<head>` section contains metadata about your webpage, such as the title and links to stylesheets or scripts.

### Setting the Title:
Add a `<title>` element inside the `<head>`:
```
<title>My First Website</title>
```
The `<title>` sets the text displayed in the browser tab.

### Viewing the Page with Live Server:
- Right-click on the index.html file in the Explorer tab.
- Select Open with Live Server.
Your default browser will open and display the webpage.

*`Tip:`* Arrange the browser window side-by-side with VS Code for seamless updates while coding.
Example Code for the Setup:
```
<!DOCTYPE html>
<html>
  <head>
    <title>My First Website</title>
  </head>
</html>
```

### Benefits of Using Live Server:
Automatic browser refresh on file save.
Immediate feedback while working on your HTML file.
Saves time by eliminating the need to manually refresh the browser.