# Your First Website

## Overview

HTML is the standard markup language used for displaying documents in a web browser. This guide demonstrates the fundamentals of building a basic website. Topics include: headers,paragraphs, lists, links, and images.

## Creating The Project Folder

Before building your website, you need a dedicated folder to store all your files. Doing so encourages cleanliness and easier management of your website.

1. **Open** File Explorer by **Clicking** on File Explorer.

    ![Taskbar](images/stp1.png)

    ??? warning "I Do **Not** Have File Explorer Here!"
        File Explorer can be found by **clicking** on the search function, and **entering** File Explorer.

2. **Click** on your drive.

    ![File Explorer](images/stp2.png)

    ??? question "Why Use My Drive?"
        Why do I suggest your drive instead of Documents or OneDrive? This is to simplify the searching process in order to find your website and **especially** avoid conflicts with OneDrive.

3. **Click** the [New] dropdown and **Click** [Create].

    ![File Explorer](images/stp3.png)

4. **Enter** a name. Ensure to *not* include *symbols* or *numbers* in your folder name.

    ![File Explorer](images/stp4.png)

    !!! success "Success!"
        Well Done! You have made a folder!

## Creating The Home Page

At this point, you should have an empty folder and *should* be aware of the location of it. 

1. **Click** on the search function and **Enter** [VSC]. This will take you to a file explorer prompt.

      ![File Explorer](images/stp5.gif)

2. **Click** [Open Folder]. 

      ![File Explorer](images/stp6.png)

3. **Click** on your drive, then **click** on your folder, and lastly, **click** on select folder.

      ![File Explorer](images/stp7.png)

    ??? note "I Can't Find My Folder!"
        Tough Luck, Shouda Followed The Tutorial Buddy.

4. **Click** on the [New File] Icon and **Enter** "index.html".

      ![File Explorer](images/stp8.png)

## HTML Basics

### Template

Vscode is a major help due to the simplicity and extensions it has. For example, Vscode allows a simple template to start off with.

1. **Enter** an [!]. This generated template will provide the basics in order to load the website.

      ![File Explorer](images/stp9.gif)

    ??? note "What Is The '!'?"
        The [!] auto generates a template thanks to [Emmet], a *built-in* extension to Vscode.

### Creating Headers

1. **Enter** an [`<h1>`]. This is a *opening tag*. Vscode will end the *tag* automatically upon closing it with [>]. Writing after the [>], will display the text you write. This is a *header* and can be used as titles, section headings, or sub-sections.

      ![VsCode](images/stp10.png)

    ??? info "What Does The Tag Mean?"
        Everything together in [`<h1>`] is called a tag. The [<] marks the *start of the opening tag*. [h] stands for *header* while the [1] (can be any number from 1-6) stands for the level or size, and the [>] marks the end of the opening *tag*.

### Creating Paragraphs

1. **Enter** an [`<p>`]. This is a *paragraph* tag used for general text.

      ![VsCode](images/stp11.png)

### Creating Lists

1. **Enter** an [`<ul>`] **close** the opening tag, and **press** enter to create a space between the two tags. This is defining an *unordered* list. This is the same as a list of bullet points.

      ![VsCode](images/stp12.gif)

2. In the space between, **enter** a [`<li>`]. After the opening tag, write your desired text and *ensure* it has the closing tag after your text.

      ![VsCode](images/stp13.gif)

    ??? question "Do I Need The [`<ul>`]?"
        You do *not* need the [`<ul>`]. However, including it is considered good practice and supports clean code.


