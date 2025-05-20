# [Finals-Lab-Task-6](https://github.com/user-attachments/files/20347973/Garcia.Austin.Karl.C.docx)
-This task involves carrying out basic MongoDB operations, including creating a database, adding documents, and performing actions like find, update, search, and delete within a collection.

## Step-by-Step Process:

## 1. Create a Database

* Start by creating or switching to a specific database.
* The selected database becomes the active workspace for all upcoming operations.

## 2. Insert Documents

* Within the database, a collection is created.
* Multiple documents are inserted into the collection, each containing structured data fields such as name, age, or address.
  
### Insert the following documents into a `movies` collection.
1. title : Fight Club
writer : Chuck Palahniuk
year : 1999
actors : [
  Brad Pitt
  Edward Norton
]
- ![image](https://github.com/user-attachments/assets/e0f4cd25-6b71-479a-aa10-fa7fad40b2bf)
2. title : Pulp Fiction
writer : Quentin Tarantino
year : 1994
actors : [
  John Travolta
  Uma Thurman
  ]
- ![image](https://github.com/user-attachments/assets/7ca93d25-d186-4be9-b683-abd66616d154)
3. title : Inglorious Basterds
writer : Quentin Tarantino
year : 2009
actors : [
  Brad Pitt
  Diane Kruger
  Eli Roth
]
- ![image](https://github.com/user-attachments/assets/f0187364-22b8-4b95-919e-a8f0610e9f09)
4. title : The Hobbit: An Unexpected Journey
writer : J.R.R. Tolkein
year : 2012
franchise : The Hobbit
- ![image](https://github.com/user-attachments/assets/335c36e3-9bed-456e-86a8-cfbc6b78daf5)
5. title : The Hobbit: The Desolation of Smaug
writer : J.R.R. Tolkein
year : 2013
franchise : The Hobbit
- ![image](https://github.com/user-attachments/assets/fe6e864b-19fd-49f8-af66-a29a2761962b)
6. title : The Hobbit: The Battle of the Five Armies
writer : J.R.R. Tolkein
year : 2012
franchise : The Hobbit
synopsis : Bilbo and Company are forced to engage in a war against an array of combatants and keep the Lonely Mountain from falling into the hands of a rising darkness.
- ![image](https://github.com/user-attachments/assets/6ad220eb-9b31-4487-8962-2b8791254e43)
7. title : Pee Wee Herman's Big Adventure
- ![image](https://github.com/user-attachments/assets/dc49f121-d362-4c17-b9c8-72753d4f84b1)
8. title : Avatar
- ![image](https://github.com/user-attachments/assets/44a02b91-e03c-4125-87f7-798e1756db1c)

## 3. FIND Documents

* Display all documents stored in the collection.
* Use filters to find specific documents based on certain values like name or ID.

### Find the following
1. get all documents
- ![image](https://github.com/user-attachments/assets/d87ac511-b033-4f10-ae9a-1efda2d15507)
- ![image](https://github.com/user-attachments/assets/b0ceffe4-2bd1-4ac7-bf9a-8e14b1e56b5d)
- ![image](https://github.com/user-attachments/assets/2fb556a8-f96a-4396-a8cc-c0ba45086804)
2. get all documents with `writer` set to "Quentin Tarantino"
- ![image](https://github.com/user-attachments/assets/ed5567a8-8674-4168-b9a8-fc3cfc9dac22)
3. get all documents where `actors` include "Brad Pitt"
- ![image](https://github.com/user-attachments/assets/6182e9c4-b133-4f41-8cef-3e7f05d0ac8b)
4. get all documents with `franchise` set to "The Hobbit"
- ![image](https://github.com/user-attachments/assets/1b209e5c-afea-4baa-9c95-34764b4bdc9b)
5. get all movies released in the 90s
- ![image](https://github.com/user-attachments/assets/7d3d6de3-93cb-47de-a9b6-cb02b4505748)
6. get all movies released before the year 2000 or after 2010
- ![image](https://github.com/user-attachments/assets/c08b95d2-f826-4999-bc9e-c0b2fd42d349)

## 4. UPDATE Documents

* Locate the document that needs modification using a condition (e.g., name or ID).
* Specify the field(s) to be changed and apply the update.
* Confirm the update by checking the document again.

### Update the following
1. add a synopsis to "The Hobbit: An Unexpected Journey" : "A reluctant hobbit, Bilbo Baggins, sets out to the Lonely Mountain with a spirited group of dwarves to reclaim their mountain home - and the gold within it - from the dragon Smaug."
- ![image](https://github.com/user-attachments/assets/50454a68-0d19-4759-8e51-ea83638bb2c4)
2. add a synopsis to "The Hobbit: The Desolation of Smaug" : "The dwarves, along with Bilbo Baggins and Gandalf the Grey, continue their quest to reclaim Erebor, their homeland, from Smaug. Bilbo Baggins is in possession of a mysterious and magical ring."
- ![image](https://github.com/user-attachments/assets/582d82b3-db06-46e8-b8a1-cc06c09df70a)
3. add an actor named "Samuel L. Jackson" to the movie "Pulp Fiction"
- ![image](https://github.com/user-attachments/assets/acd6c6ce-a6ab-443e-9a69-3df1633b6df9)

## 5. SEARCH Documents

* Use specific criteria to locate documents that match particular conditions (e.g., age greater than a value or status equals a specific string).
* Review the matched results for accuracy.
  
### Search the following text
1. find all movies that have a synopsis that contains the word "Bilbo"
- ![image](https://github.com/user-attachments/assets/d0fd6666-614d-4eb2-b30a-0ca378a047bf)
2. find all movies that have a synopsis that contains the word "Gandalf"
- ![image](https://github.com/user-attachments/assets/d0f46cd3-3ff8-46c1-8ae3-5c60ee0b4515)
3. find all movies that have a synopsis that contains the word "Bilbo" and not the word "Gandalf"
- ![image](https://github.com/user-attachments/assets/9cb5462a-99b4-49ba-8c96-3500959d02eb)
4. find all movies that have a synopsis that contains the word "dwarves" or "hobbit"
- ![image](https://github.com/user-attachments/assets/ce3da7dc-a9c4-4fe8-a333-215e4fb15836)
5. find all movies that have a synopsis that contains the word "gold" and "dragon"
- ![image](https://github.com/user-attachments/assets/6b8b8f5b-9005-4bca-87dc-7b59e4dc218e)

## 6. DELETE Documents

* Identify the document(s) to be removed using a condition.
* Remove the document(s) from the collection.
* Verify deletion by checking the collection contents.

### Delete the following
1. delete the movie "Pee Wee Herman's Big Adventure"
- ![image](https://github.com/user-attachments/assets/62500dd5-dc5a-4190-ad19-2d197c0e7274)
2. delete the movie "Avatar"
- ![image](https://github.com/user-attachments/assets/9d44c16c-ed13-442f-a7d3-b57cbd1c1280)



## Relationship
### Insert the following documents into a `users` collection
1. username : GoodGuyGreg
first_name : "Good Guy"
last_name : "Greg"
- ![image](https://github.com/user-attachments/assets/4ac4f4d2-e2fc-41a4-9430-311ae46ad3c8)
2. username : ScumbagSteve
full_name :
  first : "Scumbag"
  last : "Steve"
- ![image](https://github.com/user-attachments/assets/ae8e9f12-cdb5-4c06-a51d-e0688b19535f)
  
### Insert the following documents into a `posts` collection
1. username : GoodGuyGreg
title : Passes out at party
body : Wakes up early and cleans house
- ![image](https://github.com/user-attachments/assets/0d9e4870-140c-42ab-a976-e17ecc724c91)
2. username : GoodGuyGreg
title : Steals your identity
body : Raises your credit score
- ![image](https://github.com/user-attachments/assets/7e2d9ae3-902b-497d-8ce0-d1afe2ce8701)
3. username : GoodGuyGreg
title : Reports a bug in your code
body : Sends you a Pull Request
- ![image](https://github.com/user-attachments/assets/e76a5c01-0c3d-485a-94c1-7adaf2bdf69f)
4. username : ScumbagSteve
title : Borrows something
body : Sells it
- ![image](https://github.com/user-attachments/assets/aac7fbc7-283d-4507-ab25-31fefafa7ab4)
5. username : ScumbagSteve
title : Borrows everything
body : The end
- ![image](https://github.com/user-attachments/assets/a9ae17f8-8538-44b7-bc52-20bb34f28817)
6. username : ScumbagSteve
title : Forks your repo on github
body : Sets to private
- ![image](https://github.com/user-attachments/assets/5040158a-e6fa-40ff-a845-4dc2d3bf7d36)

### Insert the following documents into a `comments` collection
1. username : GoodGuyGreg
comment : Hope you got a good deal!
post : [post_obj_id]
where [post_obj_id] is the ObjectId of the `posts` document: "Borrows something"
- ![image](https://github.com/user-attachments/assets/0af710f5-208c-4b42-9b0e-4ba91e7569b0)
2. username : GoodGuyGreg
comment : What's mine is yours!
post : [post_obj_id]
where [post_obj_id] is the ObjectId of the `posts` document: "Borrows everything"
- ![image](https://github.com/user-attachments/assets/3ca6a19f-f93f-481f-b63a-e5811c748911)
3. username : GoodGuyGreg
comment : Don't violate the licensing agreement!
post : [post_obj_id]
where [post_obj_id] is the ObjectId of the `posts` document: "Forks your repo on github
- ![image](https://github.com/user-attachments/assets/f478141b-f8ce-4b52-8896-277b322fa1da)
4. username : ScumbagSteve
comment : It still isn't clean
post : [post_obj_id]
where [post_obj_id] is the ObjectId of the `posts` document: "Passes out at party"
- ![image](https://github.com/user-attachments/assets/0898dfd0-a093-4650-8592-126dbd206b98)
5. username : ScumbagSteve
comment : Denied your PR cause I found a hack
post : [post_obj_id]
where [post_obj_id] is the ObjectId of the `posts` document: "Reports a bug in your code"
- ![image](https://github.com/user-attachments/assets/3e20aa96-a2ae-4818-adc0-53e751517db0)

## Querying Related Collections
1. Find all users  
- ![image](https://github.com/user-attachments/assets/76df7786-e18e-4c05-88ff-ef31f0b743f3)
2. Find all posts  
- ![image](https://github.com/user-attachments/assets/65a90d66-46ee-4a76-be53-3acdb11927c7)
- ![image](https://github.com/user-attachments/assets/616c4bdd-88ac-4357-81d7-946da3f0fda3)
3. Find all posts that were authored by **GoodGuyGreg**  
- ![image](https://github.com/user-attachments/assets/c33ca38b-0449-422f-aad2-9c77475068dd)
4. Find all posts that were authored by **ScumbagSteve**  
- ![image](https://github.com/user-attachments/assets/b2bae686-defb-462a-8f66-b2c14cfc751f)
5. Find all comments  
- ![image](https://github.com/user-attachments/assets/59eea7f6-224b-4135-aba7-2875697659e5)
- ![image](https://github.com/user-attachments/assets/69d1aa7e-5464-472c-ba81-a486b514d632)
6. Find all comments that were authored by **GoodGuyGreg**  
- ![image](https://github.com/user-attachments/assets/ad2cd56d-fdbd-4b12-a609-bf1ddca4ea1c)
7. Find all comments that were authored by **ScumbagSteve**  
- ![image](https://github.com/user-attachments/assets/d53eb68e-0b68-47c4-824a-965165a04611)
8. Find all comments belonging to the post **"Reports a bug in your code"**
- ![image](https://github.com/user-attachments/assets/322c9669-498e-4c1a-b334-529c8d3505b8)


## Entity-Relationship (ER) Diagram
### Below is the ER diagram representing the relationships between the `movies`, `users`, `posts`, and `comments` collections:
- ![image](https://github.com/user-attachments/assets/dd450c6d-27df-499f-bfcf-3a5ab1ef55f1)
