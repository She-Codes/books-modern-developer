# Books.Modern Developer

The Books.Modern Developer UI.

## Project Goal

### Part 1:

In this project assignment, you will build the UI, using HTML and CSS, for Books.Modern Developer. The Books.Modern Developer project is a real site, and thus a real-world project that will give you a sense of building a real UI with varying complexity, even in this introductory course.

### Part 2:

#### Team Project Assignment 1: Add JavaScript to Your Team Project

In the first part of your team project assignment, you created the HTML/CSS user interface for an application using just HTML and CSS. In this second part of the team project assignment, you will add JavaScript to the same HTML/CSS UI you built earlier. Specifically, you will add the following JavaScript functionalities:

  1. Data Object for Your Application: Because the application you have built will be a dynamic application whose data (i.e., the actual content, specifically all the text) will be stored in a database, we need a way to organize and store all the data. To create a storage mechanism for the data, you will create a JavaScript object that stores all the content for your app. Every piece of text from your app will be stored in the object.As an example, imagine if your app simply displayed books and you want to store all the data for the app in an object. The data for the app could look like this:

  ```
  var entireData: {
    siteName: "Only Books About Cars",
    books:[
     {title: "Cars of 2020",
     cost: 22,
     coverImage: "onlyBooksAboutCars.png"  
     },
     {title: "Worst Cars of the Year",
     cost: 11,
     coverImage: "worstCarsOfTheYear.png"  
     }
    ]  
  }
  ```

  2. Data Validation for Forms: If the app that you have built has one or more forms, create data validation for the form fields so that when users fill out the form, they are notified when they enter incorrect data types. For example, if one of the form fields on your app asks for the user’s age as a string in the format “MM/DD/YYYY” (where MM represents a two-digit month, DD represents a two-digit day, and YYYY represents a four-digit year), your validation code should check whether the user has submitted the correct format (e.g. “12/22/1998”) for that data piece of data. Validate all the form fields.This part of the assignment should look familiar to you because it is almost identical to the first individual project assignment, Project Assignment 1: Create JavaScript Validation Functions.

  3. Save the User-Submitted Data: If the application you have built has one or more forms, save all the user-submitted data to an object, and print the data to the browser console using console.log(). Print the data only when the user clicks the form submit button and only if the user has entered all the correct information. Remember, you are validating the user-entered data as per the Data Validation for Forms requirement outlined in number 2 above.

Because our project did not have any forms in need of validation or user-submitted data, we included only the data object for this application. 

## Team Workflow

*Updates posted here*

### Completed Footer
Hey guys, here is what the completed footer looks like. It is not responsive. In the
next commit, I am going to clean it up.

 @wehelie
![](images/footer.png)

### Card Section 

rulep: Worked on HTML and CSS of Card Section of project for sections: 1, 2, and 4. Currently working on Section 3. 

### Header and Nav

nikia: Completed the header and nav portion of the project
