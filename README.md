> **IMPORTANT!** [Common Mistakes, Improvements, and Errata aka list of corrections](docs/errata/README.md)

# Real-World Web Development with .NET 9, First Edition

Repository for the Packt Publishing book titled "Real-World Web Development with .NET 9" by Mark J. Price

If you have purchased the paperback or Kindle edition, then you can request a free PDF copy at the following link: https://www.packtpub.com/page/free-ebook.

For questions about book pricing, distribution, and so on, please contact the publisher Packt at the following email address: customercare@packt.com

My author page on Amazon: https://www.amazon.com/Mark-J-Price/e/B071DW3QGN/ 

All of my books on Packt's website: https://subscription.packtpub.com/search?query=mark+j.+price

My author page on Goodreads: https://www.goodreads.com/author/show/14224500.Mark_J_Price

## Chapters and code solutions

**Introduction**
- Chapter 1 Introducing Web Development with Controllers
  - [code/MatureWeb/Northwind.EntityModels](code/MatureWeb/Northwind.EntityModels)
  - [code/MatureWeb/Northwind.DataContext](code/MatureWeb/Northwind.DataContext)
  - [code/MatureWeb/Northwind.UnitTests](code/MatureWeb/Northwind.UnitTests)

**ASP.NET Core MVC**
- Chapter 2 Building Websites Using ASP.NET Core MVC
  - [code/MatureWeb/Northwind.Mvc](code/MatureWeb/Northwind.Mvc)
- Chapter 3 Model Binding, Validation, and Data Using EF Core
- Chapter 4 Tag Helpers, Partial Views, and View Components

**ASP.NET Core shared functionality**
- Chapter 5 Authentication and Authorization
- Chapter 6 Performance Optimization Using Caching
- Chapter 7 Web User Interface Testing Using Playwright
  - [code/MatureWeb/Northwind.WebUITests](code/MatureWeb/Northwind.WebUITests)
- Chapter 8 Configuring and Containerizing ASP.NET Core Projects

**Web Services**
- Chapter 9 Building Web Services Using ASP.NET Core Web API
  - [code/MatureWeb/Northwind.WebApi](code/MatureWeb/Northwind.WebApi)
- Chapter 10 Building Web Services Using ASP.NET Core OData
  - [code/MatureWeb/Northwind.Odata](code/MatureWeb/Northwind.Odata)
- Chapter 11 Building Web Services Using FastEndpoints
  - [code/MatureWeb/Northwind.FastEndpoints](code/MatureWeb/Northwind.FastEndpoints)
- Chapter 12 Web Service Integration Testing
  - [code/MatureWeb/Northwind.IntegrationTests](code/MatureWeb/Northwind.IntegrationTests)

**Web Content Management Systems** [code/MatureWeb/Northwind.Cms](code/MatureWeb/Northwind.Cms)
- Chapter 13 Web Content Management Using Umbraco
  - [code/MatureWeb/Northwind.Cms](code/MatureWeb/Northwind.Cms)
- Chapter 14 Customizing and Extending Umbraco

**Appendix and online chapter**
- [Appendix, Answers to the Test Your Knowledge Questions](docs/B31470_Appendix.pdf).

## Code solutions for Visual Studio and Visual Studio Code

Visual Studio Code now has an extension named **C# Dev Kit** that includes a solution explorer so it can better work with Visual Studio solution files. Visual Studio for Windows, Visual Studio for Mac, and Visual Studio Code + C# Dev Kit can now use the same code solution files and projects for each chapter, found here: [/code](/code). 

> **For Visual Studio Code:** To use the chapter solution files with Visual Studio Code, install the **C# Dev Kit** extension. Then in Visual Studio Code, open the `ChapterNN` folder that contains a `ChapterNN.sln` solution file and wait for the **SOLUTION EXPLORER** pane to appear at the bottom of the **EXPLORER**. You can drag and drop to reorder the panes to put **SOLUTION EXPLORER** at the top. Learn more about C# Dev Kit at the following link: https://devblogs.microsoft.com/visualstudio/announcing-csharp-dev-kit-for-visual-studio-code/

> **Warning!** If you use both Visual Studio and Visual Studio Code to open these solutions, be aware that the build process can conflict. This is because Visual Studio has its own non-standard build server that is different from the standard build server used by .NET SDK CLI. My recommendation is to only have a solution open in one code editor at any time. You should also clean the solutions between opening in different code editors. For example, after closing the solution in one code editor, I delete the `bin` and `obj` folders before then opening in a different code editor.

## Bonus content

The appendix and color figures are available to download as PDFs:

- [Appendix, Answers to the Test Your Knowledge Questions](docs/B31470_Appendix.pdf).
- Color images of the screenshots/diagrams used in this book (coming November 2024).

## Important

Corrections for typos and other mistakes and improvements like refactoring code. Useful links to other related material. 

- [Command-Lines](docs/command-lines.md) page lists all commands as a single line that can be copied and pasted to make it easier to enter commands at the prompt.
- [Book Links](docs/book-links.md)
- [Common Mistakes, Improvements, and Errata aka list of corrections](docs/errata/README.md)
- [Ninth edition's support for .NET 10](docs/dotnet10.md)

## Microsoft Certifications

Announcing the New Foundational C# Certification with freeCodeCamp:
https://devblogs.microsoft.com/dotnet/announcing-foundational-csharp-certification/

Microsoft used to have professional exams and certifications for developers that covered skills like C# and ASP.NET. Sadly, they have retired them all. These days, the only developer-adjacent exams and certifications are for Azure or Power Platform, as you can see from the certification poster: https://aka.ms/traincertposter

## Microsoft .NET community support

- [.NET Developer Community](https://dotnet.microsoft.com/platform/community)
- [.NET Tech Community Forums for topic discussions](https://techcommunity.microsoft.com/t5/net/ct-p/dotnet)
- [Q&A for .NET to get your questions answered](https://learn.microsoft.com/en-us/answers/products/dotnet)
- [Technical questions about the C# programming language](https://learn.microsoft.com/en-us/answers/topics/dotnet-csharp.html)
- [If you'd like to apply to be a reviewer](https://authors.packtpub.com/reviewers/)

## Interviews with me

Podcast interviews with me:

- [The Modern .NET Show Podcast - January 26, 2024](https://dotnetcore.show/season-6/the-net-trilogy-and-learning-net-with-mark-j-price/)
- [The .NET Core Podcast - March 3, 2023](https://dotnetcore.show/episode-117-our-perspectives-on-the-future-of-net-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - December 2022](https://jesseliberty.com/2022/12/10/mark-price-on-c-11-fixed/)
- [The .NET Core Podcast - February 4, 2022](https://dotnetcore.show/episode-91-c-sharp-10-and-dotnet-6-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - May 2021](http://jesseliberty.com/2021/05/16/mark-price-on-c9-and-net-6/)
- [The .NET Core Podcast - February 7, 2020](https://dotnetcore.show/episode-44-learning-net-core-with-mark-j-price/)
- [Yet Another Podcast with Jesse Liberty - February 2020](http://jesseliberty.com/2020/02/23/mark-price-c-net-core/)
- [Packt Podcasts](https://soundcloud.com/packt-podcasts/csharp-8-dotnet-core-3-the-evolution-of-the-microsoft-ecosystem)

Written interviews with me:
- [C# 9 and .NET 5: Book Review and Q&A](https://www.infoq.com/articles/book-interview-mark-price/?itm_source=infoq&itm_campaign=user_page&itm_medium=link)
- [Q&A with Episerver's Mark J. Price, author of C# 9 and .NET 5 - Modern Cross-Platform Development](https://www.episerver.com/articles/q-and-a-with-mark-price)

![Book Cover](B31470_Cover.png)
