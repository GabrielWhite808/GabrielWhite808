---
layout: essay
type: essay
title: "Recipe for Success"
# All dates must be YYYY-MM-DD format!
date: 2024-4-24
published: true
labels:
  - Software Engineering
  - Software Development
---


Imagine you are a chef given a task to create an exquisite dish of crab-stuffed filet mignon with whiskey peppercorn sauce. Instead of using a recipe to guide you or give inspiration, you decide to create the dish from scratch. After a few failed attempts at the dish, you realize that you have run out of time and your boss is expecting a completed meal. If you had used a recipe, it would have served as a guide and allowed you to make modifications to complete the task in an efficient manner. This example shows how important recipes are as a template of sorts for making meals. In the same way, design patterns act as a template for developing applications in the field of software development. They save vital time by providing developers with reusable functionality structures that can be used in many applications. This essay will delve into what design patterns are, the importance of understanding the design patterns used in a chosen platform, and specific examples of design patterns in Meteor.

<h2>Design Patterns</h2>

Design patterns in software engineering serve as templates for developers. By providing pre-determined structures, they allow developers to recreate patterns of behaviors with minor modifications. This parallels how a chef can make minor modifications to a recipe instead of starting from scratch. Now that developers have this framework, they are able to implement changes much faster. This allows them to spend more time on fixing glitches and implementing more complex aspects of their programs instead of spending countless hours working on the bare bone models of their application that design patterns would have supplied. This means that utilizing the design patterns of a platform allows developers to be much more efficient and productive.

<h2>Importance of Understanding Design Patterns</h2>

While design patterns do serve as a great tool for software developers to use, it is important to understand that not all are created equal. Before using a certain platform which utilizes design patterns, it is important to know what the design patterns used are and how they will apply to the application being created. For example, it would not be advantageous to use a design pattern geared towards user-interface and interaction for an application that is almost entirely used for back-end database functionality. This would be similar to a chef using a recipe for a sandwich to make a soup. The chef would have to rely on their own ability to make the soup and the recipe would likely make the process more complicated. As a result of different design patterns being implemented in various platforms, it is vital to understand and match the application's goal with a framework that suits it. This is something I have stumbled upon in my own interactions with the design patterns of Meteor.

<h2>Design Patterns in Meteor</h2>

<img class="img-fluid" style="width:50%" src="../img/meteor-logo-blue-orange.png">

Meteor is a web designer, open-stack, full-source platform that uses React and Bootstrap to provide a reactive environment for users. Meteor uses multiple design patterns as well as full on templates for developers. One of the main design patterns it uses is the Model View Controller (MVC) design pattern. Firstly, it models the data structure, this is usually done through collections in MongoDB. Secondly, it allows developers to display the data to the user through UI components. Finally, it controls the interaction between the model and the view. This is done through the additions and edits that the user can make to data. Another design pattern that Meteor offers is the Publish-Subscribe pattern. This allows data to be synchronized between the server and the client. The server publishes data, and the client subscribes to this data. This means that data can be quickly modified and will react to changes effectively. I have found that these design patterns are very helpful in making data management quick and efficient. However, one of the downsides of these models is that it is a bit complex to deal with data that should be hidden. Due to the fact that collections allow quick interaction with users, the users can usually have quick access to any data through the console. This means that making an application with data that users should not be able to access is a bit more complex. Once again, this demonstrates the importance of understanding a platform, in this case Meteor, and how its design patterns affect potential developers and applications.

Overall, design patterns serve as a great tool for web developers to use when developing an application. Meteor utilizes quite a few design patterns including the Model View Controller and Publish-Subscribe patterns. This makes it good for quick interaction between users and databases. When applied correctly, design patterns allow developers to reduce the amount of time and effort when implementing repeatable behaviors. The next time you have to create a web application, brainstorm what design patterns work well with your project. Don’t start from scratch. Don’t be a chef without a recipe.

*This essay used ChatGPT to find information regarding Meteor’s design patterns and for the recipe analogy.
