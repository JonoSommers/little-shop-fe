# Little Shop | Group Project | Frontend Starter Repo

# Little Shop FE 

### Abstract:
(Briefly describe what you built and its features. What problem is the app solving? How does this application solve that problem?)
This is the frontend part of an e-commerce admin site, Little Shop.  It's primary features are receiving data from the backend displaying all available merchants and items for the site.  Within the merchants view, admin users can create a new entry, edit details of a specific entry, and delete an entry entirely.  Additionally, this view can be used to access a merchatns specific items and view them in a filtered items view.  Within the items view admin users, can view all items and their details.  As a whole this frontend, allows admins to manage an e-commerce website. 

### Installation Instructions:
(What steps does a person have to take to get your app cloned down and running?)
1. Clone down this repo with the little_shop backend repo
2. Install node.js, ruby, and rails onto your machine
3. Open both files in vscode, frontend and backend
4. In terminal of backend, run command ```rails s```
5. In terminal of frontend, run command ```npm run dev```
6. ```command + click ``` the link provided in the frontend terminal
7. Enjoy the website

### Preview of App:
(Provide ONE gif or screenshot of your application - choose the "coolest" piece of functionality to show off. gifs preferred!)

### Context:
(Give some context for the project here. How long did you have to work on it? What specific work/improvements did you contribute to this FE application?)
As a group it took us two days to complete the frontend.  We refactored the methods filterByMerchant and findMerchant to use prototype methods to function rather than the for loops originally being used.  We also added a function to display an appropriate message when a merchant has no items and a user clicks on the view merhcants items. Lastly, we altered the design of the website by: adding flexbox, adding hovering mouse interactions, changing the button shapes, customising the header, adding effects to the aside, and changing the color palette.

### Contributors:
(Who worked on this application? Link to your GitHub. Consider also providing LinkedIn link)
Elysa Ward [LinkedIn](https://www.linkedin.com/in/elysa-ward/) <br>
Dustin Peukert [LinkedIn](https://www.linkedin.com/in/jonosommers/)
<br>
Jono Sommers [LinkedIn](https://www.linkedin.com/in/dustin-peukert/)

### Learning Goals:
(What were the learning goals of this project? What tech did you work with?)
The biggest learning goal for this project was to connect the frontend and backend of a website, using a combination of ruby on rails on the backend and javascript/html/css on the frontend.

### Wins + Challenges:
(What are 2-3 wins you have from this project? What were some challenges you faced - and how did you get over them?)
   1. Challenge - learning to use conditionals with the jsonapi serializer gam.
   2. Challenge - learning how routing order impacts the backend
   3. Win - getting all backend tests and postman passing and then seeing the functioning results in the frontend
