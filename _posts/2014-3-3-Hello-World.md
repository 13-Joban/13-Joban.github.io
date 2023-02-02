---
layout: post
title: WPF
published: true
---
title: WPF app in C# 
In this tutorial, i will share my experience about creating an application in **WPF** using C# which creates rectangle, circle and triangle with given input parameters.

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


