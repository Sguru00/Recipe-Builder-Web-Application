

R1: Home page:
    Every page is hyperlinked to the home page. The home page acts as a navigation tool to surf the different web pages. 

R2: About page: 
    Tell the user what this web application is about what to expect.

R3: Register page:
    There are 5 input fields first and second name, email, username and password. This information is store in a database called myFoodshop. The password is stored as a hashedpassword. The user are also redirected to a page that tell them that their data has been safely stored.

R4: Login page:
    Contains 2 inputs for username and password. If either the password of the username is incorrect then they are redirected to webpage that tell users that there has been an incorrect input.

R5: Logout:
    Will redirect user to successful logout message when they logout.

R6: Add food page:
    User are able to add a food and fill in details such as Name,Typical values per,Carbs,Fat,Protein,Salt,Sugar.

R7: Search food page:
    Users are able to search for food by typing in an input field. 

R8: Update food page:
    Users are to update details of said food and delete certain food items. Users are also given a change if they accidently click on delete. A messgae promt wll show up and ask they user if they want to delete the selected item. 

R9: List food page:
    Shows a the whole list of food a saved in the database.


R10: API:
    shows the food searched or the whole list of food in json format.


R11: form validation:
    Email must have an @ in the inputbox. Password must be at least 8 digits long and 50 digits max. First name last name and user cannot be left empty or it will redirect you back to the register page.


R12:
    Web application is on node.js and I am using MySQL to structure my backend.
    It will also be hosted on the goldsmiths servers. My database consists of 2 tables.
    One table is called shop and the other table is called userdata. 

    Shop is where I store all my food information.
    This is an example of a record in my table.

    foodID:8
    name: flour
    values_per:100
    unit_value: gram
    carbs: 81 
    fat: 1.1 
    protein: 9.1 
    salt: 0.01 
    sugar: 0.6 

    foodID is my primary key and name, values_per,unit_value, carbs,fat, protein,salt, sugar are my fields. 

    foodID has a field of int. Name, value_per,unit_valure have an input field of VARCHAR(50) and carbs,fat,protein,salt and sugar have and input field of DECIMAL(5, 2).

    userdata is where I store all user data. 
    This is an example of a record in my table.

    userID:test
    username:test
    firstname:test
    lastname:test
    email:test@gmail.com
    hashedPassword:'$2b$10$ZdelKOcxojOAe1fFhehl8OBZhSJid5F0xYW6bpWlnoRnCc/J6Wwae'

    userID is my primary key and username, firstname, lastname, email, hashedPassword are my fields.

    userID has a field of int. Username, firstname and lastname have an input field of VARCHAR(50) and email  and hashPassword has a VARCHAR(250). Hashpassword is also unique.



ER Diagram:
    My ER diagram is the ER diagram.png 
    


