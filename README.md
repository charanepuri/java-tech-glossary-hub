# Tech Glossary Hub
 
## Project Description
A terminal-based technical reference application that organizes software-development terminology into categories. Users can browse categories, search for a term, and view its definition, explanation, and example. Optional entry-management and file-persistence features can be added as the project evolves.
 
## Technology Stack
Java (JDK), object-oriented programming (OOP), Scanner, ArrayList, HashMap, Java Collections Framework, exception handling, and optional text/CSV file handling.
 
## Features
- Browse glossary categories from a menu-driven console interface.
- Search glossary terms by name or keyword.
- View definitions, explanations, and practical examples.
- Organize terms using Java classes and collections.
- Optionally add, update, or delete glossary entries.
- Optionally save and load glossary data using local files.
- Handle invalid menu choices and unmatched search terms gracefully.
 
## Database Design
No database is required for the basic console edition. The application can use ArrayList/HashMap in memory and optional text or CSV files for persistence. If a relational database is added later, a simple design could use Category(category_id, category_name) and Term(term_id, category_id, term, definition, explanation, example), with category_id referencing Category.
 
## Learning Outcomes
- Design classes such as Category and GlossaryTerm.
- Use ArrayList and HashMap to organize and retrieve data.
- Implement case-insensitive search and category filtering.
- Practice modular methods, encapsulation, and input validation.
- Read and write local files for optional data persistence.
 
## Explanation
The application starts with a menu that lets users browse categories or search for a specific technical term. Each glossary entry can contain a term, definition, explanation, and example. The console interface collects user input, the application logic searches the stored collection, and the matching information is displayed in a readable format. File storage may be used to preserve entries between runs.
 
## Conclusion
Tech Glossary Hub demonstrates how Java can be used to build a practical command-line learning tool. It brings together object-oriented programming, collections, searching, and optional file handling in one beginner-friendly application.
 
## Author
**Charan Teja EPURI**  
*Aspiring Full Stack Developer*
 
- [Django Portfolio](https://portfolio-site-django.onrender.com)
- [GitHub](https://github.com/charanepuri)
- [React Portfolio](https://charan-react-portfolio.vercel.app)
- [LinkedIn](https://www.linkedin.com/in/charan-teja-972aa9231)
- [Flask Portfolio](https://flask-developer-dashboard-portfolio.onrender.com/)
