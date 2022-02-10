First let's understand what is difference between structured and unstructured data? 


 **Unstructured data** includes content such as video, email, images, podcasts, social media posts and PDFs. *In short, unstructured data has no internal identifier to let search functions recognize it.* Common examples of unstructured data include audio, video files or No-SQL databases. 
 
 **Structured data** exists in a format created to be captured, stored, organized and analyzed.  It’s neatly organized for easy access. Structured data is data that adheres to a pre-defined data model and is therefore straightforward to analyse. Structured data depends on the existence of a data model – a model of how data can be stored, processed and accessed. If structured data was an office it would contain many file cabinets that are efficiently set up, clearly labeled and easy to access. 
 
 **Structured Data are**
 
 - Highly organized
 - Clearly Defined
 - Easy to access
 - Easy to analyze
 
 **Examples of SD**
 
 - Name, Age, Gender, Address, Currency, Dates etc.
 
 **Where does the SD come from?**
 
 - The two primary examples of where structured data is generated are databases and search algorithms.  The term structured data is often associated with relational database management systems,
 - In addition to relational databases, spreadsheets are also common sources of structured data.
 - While relational databases and SQL have a long history, more recently, structured data also plays a major role in internet searches and offers benefits to organic search. 
 - According to Google’s Introduction to Structured Data, **"When information is highly structured and predictable, search engines can more easily organize and display it in creative ways."** 
 - To create a structured data standard for web-based application, email messages and forms of internet content, Google, Microsoft, Yahoo and Yandex created [Schema.org](https://schema.org/), an open community.
 
**Understanding how SD works in Google search**

- Google Search works hard to understand the content of a page. You can help us by providing explicit clues about the meaning of a page to Google by including structured data on the page.
-  is a standardized format for providing information about a page and classifying the page content; for example, on a recipe page, what are the ingredients, the cooking time and temperature, the calories, and so on.
- Google uses structured data that it finds on the web to understand the content of the page, as well as to gather information about the web and the world in general. 
- Because the structured data labels each individual element of the recipe, users can search for your recipe by ingredient, calorie count, cook time, and so on
- Example: 

   ```
   {
         "@context": "https://schema.org/",
         "@type": "Recipe",
         "name": "Party Coffee Cake",
         "author": {
           "@type": "Person",
           "name": "Mary Stone"
         },
         "datePublished": "2018-03-10",
         "description": "This coffee cake is awesome and perfect for parties.",
         "prepTime": "PT20M"
       }
   ```
- Google Search also uses structured data to enable special search result features and enhancements.
- Structured data can be written in the following formats [JSON-LD](https://json-ld.org/) (Most popular one), [RDFa](https://rdfa.info/), MircoData etc. 
 

**References**

- https://developers.google.com/search/docs/advanced/structured-data/intro-structured-data
- https://www.datamation.com/big-data/structured-data/
