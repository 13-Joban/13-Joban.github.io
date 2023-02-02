---
layout: post
title: ' WPF app in C# '
published: true
---

_Hey there 🖐, glad you visited my blog this is my first time I am writing about what i have learned so without wasting your precious time lets gets Started 🚀.
In this tutorial, i will share my experience about creating an application in **WPF** using C# which creates rectangle, circle and triangle with given input parameters._

### What actually is WPF ?
Windows Presentation Foundation (WPF), a UI framework that is resolution-independent and uses a vector-based rendering engine, built to take advantage of modern graphics hardware. WPF provides a comprehensive set of application-development features that include Extensible Application Markup Language (XAML), controls, data binding, layout, 2D and 3D graphics, animation, styles, templates, documents, media, text, and typography. WPF is part of .NET, so you can build applications that incorporate other elements of the .NET API.

### Markup and code-behind
WPF lets you develop an application using both markup and code-behind, an experience with which ASP.NET developers should be familiar. You generally use XAML markup to implement the appearance of an application while using managed programming languages (code-behind) to implement its behavior. This separation of appearance and behavior has the following benefits:

-Development and maintenance costs are reduced because appearance-specific markup isn't tightly coupled with behavior-specific code.

-Development is more efficient because designers can implement an application's appearance simultaneously with developers who are implementing the application's behavior.

## Markup
XAML is an XML-based markup language that implements an application's appearance declaratively. You typically use it to define windows, dialog boxes, pages, and user controls, and to fill them with controls, shapes, and graphics.

The following example uses XAML to implement the appearance of a window that contains a single button:
![beautify-picture.png]({{site.baseurl}}/_posts/beautify-picture.png)

The following figure shows the user interface (UI) that is defined by the XAML in the previous example:

![markup-window-button.png]({{site.baseurl}}/_posts/markup-window-button.png)


## Code Behind
The main behavior of an application is to implement the functionality that responds to user interactions. For example clicking a menu or button, and calling business logic and data access logic in response. In WPF, this behavior is implemented in code that is associated with markup. This type of code is known as code-behind. The following example shows the updated markup from the previous example and the code-behind:

![markup-window-button-clicked.png]({{site.baseurl}}/_posts/markup-window-button-clicked.png)


That's enough for introduction lets deep dive into our main task that means creating an application in  WPF using C# 

## Step 1 Install Visual Studio 
The Visual Studio IDE is a creative launching pad that you can use to edit, debug, and build code, and then publish an app. Over and above the standard editor and debugger that most IDEs provide, Visual Studio includes compilers, code completion tools, graphical designers, and many more features to enhance the software development process.
Visit https://visualstudio.microsoft.com/

_Hope you are along  with me_
## Step 2 Setup of project

1. Open Visual Studio.

2. Select Create a new project.

![vs-create-new-project.png](./_posts/vs-create-new-project.png)

3.In the Search for templates box, type wpf, and then press Enter.

4. In the code language dropdown, choose C# or Visual Basic.

5. In the templates list, select WPF Application and then select Next.

![vs-template-search.png]({{site.baseurl}}/_posts/vs-template-search.png)

6.In the Configure your new project window, do the following:

	a. In the Project name box, enter Names.
	b. Select the Place solution and project in the same directory check box.
	c.Optionally, choose a different Location to save your code.
	d.Select the Next button.

### Important parts of Visual Studio

![vs-main-window.png]({{site.baseurl}}/_posts/vs-main-window.png)
