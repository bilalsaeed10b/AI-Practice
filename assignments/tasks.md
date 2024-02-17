#All Tasks



1) Install Node.js, TypeScript and VS Code on your computer.

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/57eeb691-579e-401a-b7ab-34a81ac25a4b)

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/9c5476ea-4a62-4923-b527-620b4dc12de3)

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/dea3e395-aa15-4582-996a-2c915d08c6a9)

2) Personal Message: Store a person’s name in a variable, and print a message to that person. Your message should be simple, such as, “Hello Eric, would you like to learn some Python today?”

CODE:
let Name = "eric";
console.log(`Hello ${Name}, would you like to learn some Python today?`);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/6d21d3e6-3a24-4966-a8ee-789fa4992484)

3) Name Cases: Store a person’s name in a variable, and then print that person’s name in lowercase, uppercase, and titlecase.

CODE:
let Name = "eric";
console.log(`Uppercase: ${Name.toUpperCase()}`);
console.log(`Lowercase: ${Name.toLowerCase()}`);
console.log(`Titlecase: ${Name.charAt(0).toUpperCase()}${Name.slice(1)}`);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/c0048d28-9b35-416e-8b84-ec926c4cb171)


4)Famous Quote: Find a quote from a famous person you admire. Print the quote and the name of its author. Your output should look something like the following, including the quotation marks:

CODE:
let authorName = "Mahatma Gandhi";
console.log(`${authorName} once said, \"Be the change that you wish to see in the world.\"`);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/75e77d49-3a68-4e70-a1ad-ac1f5a82cd23)

5) Famous Quote 2: Repeat Exercise 4, but this time store the famous person’s name in a variable called famous_person. Then compose your message and store it in a new variable called message. Print your message.

CODE:
let famous_person = "Mahatma Gandhi";
let message = `${famous_person} once said, \"Be the change that you wish to see in the world.\"`;

console.log(message);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/bc0d56b6-1997-4ce6-b1bc-343c46d78650)


6) Stripping Names: Store a person’s name, and include some whitespace characters at the beginning and end of the name. Make sure you use each character combination, "\t" and "\n", at least once. Print the name once, so the whitespace around the name is displayed. Then print the name after striping the white spaces.

Code:
let personName = "  \t \t \n \n \n  Mahatma Gandhi   \n ";
console.log("Before trim: " + personName );
console.log("After trim:  " +personName.trim()  );

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/52c85c9f-c32b-4421-b839-0898d1dd7015)

7) Number Eight: Write addition, subtraction, multiplication, and division operations that each result in the number 8. Be sure to enclose your operations in print statements to see the results.

CODE:
let resultAddition = 5 + 3;
console.log(`Addition: ${resultAddition}`);

let resultSubtraction = 10 - 2;
console.log(`Subtraction: ${resultSubtraction}`);

let resultMultiplication = 4 * 2;
console.log(`Multiplication: ${resultMultiplication}`);

let resultDivision = 16 / 2;
console.log(`Division: ${resultDivision}`);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/29d91851-57a8-4016-8893-fe1a09d7b185)

8) You should create four lines that look like this: console.log(5 + 3) Your output should simply be four lines with the number 8 appearing once on each line.

CODE:
console.log(5+3);
console.log(10-2);
console.log(4*2);
console.log(16/2);
  
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/95b2c99d-0c1b-4856-bdc4-82934e8e838a)

9) Favorite Number: Store your favorite number in a variable. Then, using that variable, create a message that reveals your favorite number. Print that message.

CODE:
let favoriteNumber = 2;
console.log(`My favorite number is: ${favoriteNumber}`);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/38f60454-511d-4e2b-8b02-70f9050959ac)

10) Adding Comments: Choose two of the programs you’ve written, and add at least one comment to each. If you don’t have anything specific to write because your programs are too simple at this point, just add your name and the current date at the top of each program file. Then write one sentence describing what the program does.

CODE:
//this program results in 8
console.log(5+3);
console.log(10-2);
console.log(4*2);
console.log(16/2);

//This program reveals my fav number
let favoriteNumber = 2;
console.log(`My favorite number is: ${favoriteNumber}`);

11) Names: Store the names of a few of your friends in a array called names. Print each person’s name by accessing each element in the list, one at a time.

CODE:
let names = ["azaan","bilal","sufiyan"] 

for (let name of names) {
    console.log(name);
}

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/31c8adfe-dc8c-44f4-ba6a-9019ef581670)

12) Greetings: Start with the array you used in Exercise 11, but instead of just printing each person’s name, print a message to them. The text of each message should be the same, but each message should be personalized with the person’s name.

CODE:
let names = ["azaan","bilal","sufiyan"] 

for (let name of names) {
    console.log("He is my friend " + name);
  }

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/38a4b6ac-a225-4380-9863-aa59fda94926)

13) Your Own Array: Think of your favorite mode of transportation, such as a motorcycle or a car, and make a list that stores several examples. Use your list to print a series of statements about these items, such as “I would like to own a Honda motorcycle.”  

CODE:
let favoriteTransportation = ["Tesla", "Motorcycle", "Bicycle"];

favoriteTransportation.forEach(item => {
  console.log(`I would like to own a ${item}.`);
});

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/1b86e8d3-5b32-4702-befe-77c578f43302)

14) Guest List: If you could invite anyone, living or deceased, to dinner, who would you invite? Make a list that includes at least three people you’d like to invite to dinner. Then use your list to print a message to each person, inviting them to dinner

CODE:
let guestList: string[] = ["Azaan", "Bilal", "Sufiyan"];

guestList.forEach(person => {
  console.log(`Dear ${person}, you are invited to dinner. Hope to see you there!`);
});

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/c51a1865-17df-4d01-b526-181cb1a5ab14)

15) Changing Guest List: You just heard that one of your guests can’t make the dinner, so you need to send out a new set of invitations. You’ll have to think of someone else to invite.
• Start with your program from Exercise 14. Add a print statement at the end of your program stating the name of the guest who can’t make it.
• Modify your list, replacing the name of the guest who can’t make it with the name of the new person you are inviting.
• Print a second set of invitation messages, one for each person who is still in your list.

CODE:
let guestList: string[] = ["Azaan", "Bilal", "Sufiyan"];
console.log(`Unfortunately, ${guestList[1]} can't make it to the dinner.`);
guestList[1] = "Faraz";

guestList.forEach(person => {
  console.log(`Dear ${person}, you are invited to dinner. Hope to see you there!`);
});

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/1d3e1efc-e2ed-4c1e-be8c-1defade23162)


16) More Guests: You just found a bigger dinner table, so now more space is available. Think of three more guests to invite to dinner.
• Start with your program from Exercise 15. Add a print statement to the end of your program informing people that you found a bigger dinner table.
• Add one new guest to the beginning of your array.
• Add one new guest to the middle of your array. • Use append() to add one new guest to the end of your list. • Print a new set of invitation messages, one for each person in your list.

CODE:
let guestList: string[] = ["Aisha", "Rizwan", "Fatima"];

console.log("Good news! A bigger dinner table is available.");

guestList.unshift("Imran"); 
guestList.splice(Math.floor(guestList.length / 2), 0, "Zainab"); 
guestList.push("Sana");

guestList.forEach(person => {
  console.log(`Dear ${person}, you are invited to  dinner. Hope to see you there!`);
});

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/7bdb4946-fb7d-43d9-8187-b569384355f5)

17) Shrinking Guest List: You just found out that your new dinner table won’t arrive in time for the dinner, and you have space for only two guests.

CODE:
let guestList: string[] = ["Aisha", "Rizwan", "Fatima", "Imran", "Zainab", "Sana"];

console.log("Bad news! The new dinner table won't arrive in time, and we have space for only two guests.");

const removedGuests = guestList.splice(2);

removedGuests.forEach(person => {
  console.log(`Sorry, ${person}, there's not enough space for you at the dinner.`);
});

guestList.forEach(person => {
  console.log(`Dear ${person}, you are still invited to dinner. Hope to see you there!`);
});

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/337cca1e-44db-42d3-8268-0db9c45d2565)

18) Seeing the World: Think of at least five places in the world you’d like to visit.

let placesToVisit = ["Paris", "Tokyo", "New York", "Dubai", "UAE"];
console.log("Original Order:", placesToVisit);
console.log("Alphabetical Order:", [...placesToVisit].sort());
console.log("Original Order (still):", placesToVisit);
console.log("Reverse Alphabetical Order:", [...placesToVisit].sort().reverse());
console.log("Original Order (still):", placesToVisit);
placesToVisit.reverse();
console.log("Reversed Order:", placesToVisit);
placesToVisit.reverse();
console.log("Original Order (again):", placesToVisit);
placesToVisit.sort();
console.log("Sorted in Alphabetical Order:", placesToVisit);
placesToVisit.sort((a, b) => b.localeCompare(a));
console.log("Sorted in Reverse Alphabetical Order:", placesToVisit);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/87b03b43-ce95-4743-9b36-7e58d4edb8a5)

19)  Working with one of the programs from Exercises 14 through 18, print a message indicating the number of people you are inviting to dinner.

let guestList: string[] = ["Azaan", "Bilal", "Sufiyan", "Aisha", "Rizwan", "Fatima", "Imran", "Zainab", "Sana"];
console.log(`Number of people invited to dinner: ${guestList.length}`);

20)Think of something you could store in a array. For example, you could make a list of mountains, rivers, countries, cities, languages, or anything else you’d like. Write a program that creates a list containing these items.

let favoriteMovies: string[] = ["Inception", "The Matrix", "Fight Club", "Harry Potter", "Interstellar"];

favoriteMovies.forEach(movie => {
  console.log(movie);
});
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/5de42830-5ad9-4c9f-88c9-99efd4a5f062)

21) They think of something you could store in a TypeScript Object. Write a program that creates Objects containing these items.]
CODE:
let myCar: { make: string, model: string, year: number, color: string } = {
  make: "Toyota",
  model: "Camry",
  year: 2022,
  color: "Silver"
};

console.log("Make:", myCar.make);
console.log("Model:", myCar.model);
console.log("Year:", myCar.year);
console.log("Color:", myCar.color);
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/1f32adb7-d5cb-4127-b463-11dbc1466505)



22) Intentional Error: If you haven’t received an array index error in one of your programs yet, try to make one happen. Change an index in one of your programs to produce an index error. Make sure you correct the error before closing the program.
CODE:
let favoriteMovies: string[] = ["Inception", "The Matrix", "Fight Club", "Forrest Gump", "Interstellar"];

console.log(favoriteMovies[5]);
console.log(favoriteMovies[2]); 
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/c7f4a245-34e3-4447-b582-4d193d2e5fe5)

23) Conditional Tests: Write a series of conditional tests. Print a statement describing each test and your prediction for the results of each test. Your code should look something like this:let car = 'subaru';console.log("Is car == 'subaru'? I predict True.")console.log(car == 'subaru')• Look closely at your results, and make sure you understand why each line evaluates to True or False.• Create at least 10 tests. Have at least 5 tests evaluate to True and another 5 tests evaluate to False.

CODE:
let number1 = 5;
let number2 = 10;
let string1 = "apple";
let string2 = "orange";

console.log("Is 5 equal to 10? I predict False.");
console.log(number1 == number2);

console.log("Is 5 not equal to 10? I predict True.");
console.log(number1 != number2);

console.log("Is 'apple' equal to 'orange'? I predict False.");
console.log(string1 == string2);

console.log("Is 'apple' not equal to 'orange'? I predict True.");
console.log(string1 != string2);

console.log("Is 5 less than 10? I predict True.");
console.log(number1 < number2);

console.log("Is 5 greater than or equal to 10? I predict False.");
console.log(number1 >= number2);

console.log("Is 'apple' less than 'orange'? I predict True.");
console.log(string1 < string2);

console.log("Is 'apple' greater than or equal to 'orange'? I predict False.");
console.log(string1 >= string2);

console.log("Is 5 equal to '5'? I predict True.");
console.log(number1 == '5');

console.log("Is 5 greater than or equal to 10? I predict False.");
console.log(number1 >= number2);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/8e48b48a-9c2c-4ab7-a351-c73e9eed2075)

24) More Conditional Tests: You don’t have to limit the number of tests you create to 10. If you want to try more comparisons, write more tests. Have at least one True and one False result for each of the following:
• Tests for equality and inequality with strings
• Tests using the lower case function
• Numerical tests involving equality and inequality, greater than and less than, greater than or equal to, and less than or equal to
• Tests using "and" and "or" operators
• Test whether an item is in a array
• Test whether an item is not in a array

CODE:
let string1 = "apple";
let string2 = "orange";

console.log(string1 == string2);
console.log(string1 != string2);

let lowercaseString = "Hello";
let uppercaseString = "HELLO";

console.log(lowercaseString.toLowerCase() == uppercaseString.toLowerCase());

let num1 = 5;
let num2 = 10;

console.log(num1 < num2);
console.log(num1 >= num2);

let age = 25;

console.log(age >= 18 && age <= 30);
console.log(age < 18 || age > 30);

let fruits = ["apple", "orange", "banana"];

console.log(fruits.includes("kiwi"));
console.log(!fruits.includes("orange"));

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/9bc9ea04-01ec-48e1-83a4-bf3de74ceab4)


25)Alien Colors #1: Imagine an alien was just shot down in a game. Create a variable called alien_color and assign it a value of 'green', 'yellow', or 'red'.
• Write an if statement to test whether the alien’s color is green. If it is, print a message that the player just earned 5 points.
• Write one version of this program that passes the if test and another that fails. (The version that fails will have no output.)

CODE:
let alien_color = 'green';

if (alien_color === 'green') {
  console.log("Player just earned 5 points!");
}

if (alien_color !== 'green') {
  // No output
}

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/0480bea0-0273-41ad-95af-6b041efc88a6)


26)Alien Colors #2: Choose a color for an alien as you did in Exercise 25, and write an if-else chain.
• If the alien’s color is green, print a statement that the player just earned 5 points for shooting the alien.
• If the alien’s color isn’t green, print a statement that the player just earned 10 points.
• Write one version of this program that runs the if block and another that runs the else block.

CODE:
let alien_color = 'green';

if (alien_color == 'green') {
  console.log("Player just earned 5 points for shooting the alien.");
} else {
  // No output
}


if (alien_color == 'orange') {
  // No output
} else {
  console.log("Player just earned 10 points.");
}
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/98c74d44-01e1-4d6b-93ce-81b3d20d23f3)



27) Alien Colors #3: Turn your if-else chain from Exercise 5-4 into an if-else chain.
• If the alien is green, print a message that the player earned 5 points.
• If the alien is yellow, print a message that the player earned 10 points.
• If the alien is red, print a message that the player earned 15 points.
• Write three versions of this program, making sure each message is printed for the appropriate color alien.

CODE:
let alien_color = 'green';
if (alien_color === 'green') {
  console.log("Player earned 5 points.");
}

let alien_color = 'yellow';
if (alien_color === 'yellow') {
  console.log("Player earned 10 points.");
}

let alien_color = 'red';
if (alien_color === 'red') {
  console.log("Player earned 15 points.");
}

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/1e58f4ea-5a81-453e-aba7-3c2617ed30ce)

28) Stages of Life: Write an if-else chain that determines a person’s stage of life. Set a value for the variable age, and then:
• If the person is less than 2 years old, print a message that the person is a baby.
• If the person is at least 2 years old but less than 4, print a message that the person is a toddler.
• If the person is at least 4 years old but less than 13, print a message that the person is a kid.
• If the person is at least 13 years old but less than 20, print a message that the person is a teenager.
• If the person is at least 20 years old but less than 65, print a message that the person is an adult.
• If the person is age 65 or older, print a message that the person is an elder.

CODE:
let age = 30;

if (age < 2) {
  console.log("The person is a baby.");
} else if (age >= 2 && age < 4) {
  console.log("The person is a toddler.");
} else if (age >= 4 && age < 13) {
  console.log("The person is a kid.");
} else if (age >= 13 && age < 20) {
  console.log("The person is a teenager.");
} else if (age >= 20 && age < 65) {
  console.log("The person is an adult.");
} else {
  console.log("The person is an elder.");
}
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/3aee94ad-01ce-460f-8c12-8f00b758671b)

29) Favorite Fruit: Make a array of your favorite fruits, and then write a series of independent if statements that check for certain fruits in your array.
• Make a array of your three favorite fruits and call it favorite_fruits.
• Write five if statements. Each should check whether a certain kind of fruit is in your array. If the fruit is in your array, the if block should print a statement, such as You really like bananas!

CODE:
let favorite_fruits: string[] = ["apple", "banana", "kiwi"];

if (favorite_fruits.includes("banana")) {
  console.log("You really like bananas!");
}

if (favorite_fruits.includes("apple")) {
  console.log("You really like apples!");
}

if (favorite_fruits.includes("kiwi")) {
  console.log("You really like kiwis!");
}

if (favorite_fruits.includes("orange")) {
  console.log("You really like oranges!");
}

if (favorite_fruits.includes("grape")) {
  console.log("You really like grapes!");
}
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/12eaa85a-6c57-41a6-87cc-bab0031afed5)



30) Hello Admin: Make a array of five or more usernames, including the name 'admin'. Imagine you are writing code that will print a greeting to each user after they log in to a website. Loop through the array, and print a greeting to each user:
• If the username is 'admin', print a special greeting, such as Hello admin, would you like to see a status report?
• Otherwise, print a generic greeting, such as Hello Eric, thank you for logging in again.

CODE:
let usernames: string[] = ["admin", "Ali", "Fatima", "Imran", "Sana"];

for (let username of usernames) {
  if (username === 'admin') {
    console.log("Hello admin, would you like to see a status report?");
  } else {
    console.log(`Hello ${username}, thank you for logging in again.`);
  }
}
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/adc9361e-ba5f-494d-b930-02a44375d3b1)

31) No Users: Add an if test to Exercise 28 to make sure the list of users is not empty.
• If the list is empty, print the message We need to find some users!
• Remove all of the usernames from your array, and make sure the correct message is printed.

CODE:
let usernames: string[] = ["admin", "Ali", "Fatima", "Imran", "Sana"];

usernames.splice(0, usernames.length);

if (usernames.length === 0) {
  console.log("We need to find some users!");
} else {
  for (let username of usernames) {
    if (username === 'admin') {
      console.log("Hello admin, would you like to see a status report?");
    } else {
      console.log(`Hello ${username}, thank you for logging in again.`);
    }
  }
}
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/ef741264-cec0-41de-9e16-143e02a6b214)


32) Checking Usernames: Do the following to create a program that simulates how websites ensure that everyone has a unique username.
• Make a list of five or more usernames called current_users.
• Make another list of five usernames called new_users. Make sure one or two of the new usernames are also in the current_users list.
• Loop through the new_users list to see if each new username has already been used. If it has, print a message that the person will need to enter a new username. If a username has not been used, print a message saying that the username is available.
• Make sure your comparison is case insensitive. If 'John' has been used, 'JOHN' should not be accepted.

CODE:
let current_users: string[] = ["Aisha", "Ali", "Fatima", "Imran", "Sana"];
let new_users: string[] = ["Aisha", "Sana", "Omar", "Zainab", "Kamran"];

for (let new_username of new_users) {
  let usernameExists = current_users.some(existing_user => existing_user.toLowerCase() === new_username.toLowerCase());

  if (usernameExists) {
    console.log(`Sorry, ${new_username} is not available. Please enter a new username.`);
  } else {
    console.log(`Congratulations! ${new_username} is available.`);
  }
}
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/d0de353a-7acb-46de-a45d-7b97c4999baa)


33) Ordinal Numbers: Ordinal numbers indicate their position in a array, such as 1st or 2nd. Most ordinal numbers end in th, except 1, 2, and 3.
• Store the numbers 1 through 9 in a array.
• Loop through the array.
• Use an if-else chain inside the loop to print the proper ordinal ending for each number. Your output should read "1st 2nd 3rd 4th 5th 6th 7th 8th 9th", and each result should be on a separate line.

CODE:
for (let i = 1; i <= 9; i++) {
  if (i === 1) {
    console.log(`${i}st`);
  } else if (i === 2) {
    console.log(`${i}nd`);
  } else if (i === 3) {
    console.log(`${i}rd`);
  } else {
    console.log(`${i}th`);
  }
}

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/b422b407-2220-4c8c-a267-d57304109623)


34) Pizzas: Think of at least three kinds of your favorite pizza. Store these pizza names in a array, and then use a for loop to print the name of each pizza.
• Modify your for loop to print a sentence using the name of the pizza instead of printing just the name of the pizza. For each pizza you should have one line of output containing a simple statement like I like pepperoni pizza.
• Add a line at the end of your program, outside the for loop, that states how much you like pizza. The output should consist of three or more lines about the kinds of pizza you like and then an additional sentence, such as I really love pizza!

CODE:
let favorite_pizzas: string[] = ["Pepperoni", "Margherita", "BBQ Chicken"];

for (let pizza of favorite_pizzas) {
  console.log(`I like ${pizza} pizza.`);
}

console.log("I really love pizza!");
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/62484403-9686-4b6a-8ae6-75e24cd11829)


35) Animals: Think of at least three different animals that have a common characteristic. Store the names of these animals in a list, and then use a for loop to print out the name of each animal. • Modify your program to print a statement about each animal, such as A dog would make a great pet. • Add a line at the end of your program stating what these animals have in common. You could print a sentence such as Any of these animals would make a great pet!

CODE:
let animals: string[] = ["dog", "cat", "rabbit"];

for (let animal of animals) {
  console.log(`A ${animal} would make a great pet.`);
}

console.log("Any of these animals would make a great pet!");
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/2d6a25a8-a670-4355-b09f-cf0c9b592ebf)



36) T-Shirt: Write a function called make_shirt() that accepts a size and the text of a message that should be printed on the shirt. The function should print a sentence summarizing the size of the shirt and the message printed on it. Call the function.

CODE:
function make_shirt(size, message){
  console.log(`The shirt size is ${size} and the message on it is: "${message}"`);
}

make_shirt("Large", "The Boys");
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/fd2eecb5-1b8f-47ce-b2dd-0add5cffe10c)


37) Large Shirts: Modify the make_shirt() function so that shirts are large by default with a message that reads I love TypeScript. Make a large shirt and a medium shirt with the default message, and a shirt of any size with a different message.

CODE:
function make_shirt(size = "Large", message = "I love TypeScript") {
  console.log(`The shirt size is ${size} and the message on it is: "${message}"`);
}

make_shirt();
make_shirt("Medium");
make_shirt("Small", "JavaScript is fun!");
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/6171005a-f050-475b-aa3b-029713fd04b4)


38) Cities: Write a function called describe_city() that accepts the name of a city and its country. The function should print a simple sentence, such as Karachi is in Pakistan. Give the parameter for the country a default value. Call your function for three different cities, at least one of which is not in the default country.

CODE:
function describe_city(city, country = "Dubai") {
  console.log(`${city} is in ${country}.`);
}

describe_city("Karachi", "Pakistan");
describe_city("Tokyo", "Japan");
describe_city("Paris");
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/58b79e24-2be7-40c0-93b6-f5e643e9071c)


39) City Names: Write a function called city_country() that takes in the name of a city and its country. The function should return a string formatted like this:

"Lahore, Pakistan"

Call your function with at least three city-country pairs, and print the value that’s returned.

CODE:
function city_country(city: string, country: string): string {
  return `${city}, ${country}`;
}

console.log(city_country("Lahore", "Pakistan"));
console.log(city_country("Tokyo", "Japan"));
console.log(city_country("Paris", "France"));
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/b3dce48a-9dd9-4751-84b7-4377706150cc)


40) Album: Write a function called make_album() that builds a Object describing a music album. The function should take in an artist name and an album title, and it should return a Object containing these two pieces of information. Use the function to make three dictionaries representing different albums. Print each return value to show that Objects are storing the album information correctly. Add an optional parameter to make_album() that allows you to store the number of tracks on an album. If the calling line includes a value for the number of tracks, add that value to the album’s Object. Make at least one new function call that includes the number of tracks on an album.

CODE:
function make_album(artist: string, title: string, tracks?: number): object {
  let album = {
    artist: artist,
    title: title,
  };

  if (tracks !== undefined) {
    album['tracks'] = tracks;
  }

  return album;
}

console.log(make_album("Artist1", "Album1"));
console.log(make_album("Artist2", "Album2"));
console.log(make_album("Artist3", "Album3"));

console.log(make_album("Artist4", "Album4", 15));
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/b6eeb3c8-7638-410a-afe5-7e9afd85b9f7)



41) Magicians: Make a array of magician’s names. Pass the array to a function called show_magicians(), which prints the name of each magician in the array.

CODE:
function show_magicians(magicians: string[]): void {
  for (let magician of magicians) {
    console.log(magician);
  }
}

let magicians: string[] = ["Aamir Liaquat", "Zaheer Ahmed", "Ali Rizvi"];
show_magicians(magicians);
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/8dc9aa52-b64d-40df-9937-95e1c52055c6)


42) Great Magicians: Start with a copy of your program from Exercise 39. Write a function called make_great() that modifies the array of magicians by adding the phrase the Great to each magician’s name. Call show_magicians() to see that the list has actually been modified.

CODE:
function make_great(magicians: string[]): string[] {
  let great_magicians: string[] = [];

  for (let magician of magicians) {
    great_magicians.push(`${magician} the Great`);
  }

  return great_magicians;
}

function show_magicians(magicians: string[]): void {
  for (let magician of magicians) {
    console.log(magician);
  }
}

let magicians: string[] = ["Aamir Liaquat", "Zaheer Ahmed", "Ali Rizvi"];
let great_magicians: string[] = make_great(magicians);

console.log("Original Magicians:");
show_magicians(magicians);

console.log("\nGreat Magicians:");
show_magicians(great_magicians);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/ea5d5914-1e58-430f-892f-7f72a7bf15a1)


43) Unchanged Magicians: Start with your work from Exercise 40. Call the function make_great() with a copy of the array of magicians’ names. Because the original array will be unchanged, return the new array and store it in a separate array. Call show_magicians() with each array to show that you have one array of the original names and one array with the Great added to each magician’s name.

CODE:
function make_great(magicians: string[]): string[] {
  let great_magicians: string[] = [];

  for (let magician of magicians) {
    great_magicians.push(`${magician} the Great`);
  }

  return great_magicians;
}

function show_magicians(magicians: string[]): void {
  for (let magician of magicians) {
    console.log(magician);
  }
}

let magicians: string[] = ["Aamir Liaquat", "Zaheer Ahmed", "Ali Rizvi"];
let copy_of_magicians: string[] = [...magicians];
let great_magicians: string[] = make_great(copy_of_magicians);

console.log("Original Magicians:");
show_magicians(magicians);

console.log("\nGreat Magicians:");
show_magicians(great_magicians);

![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/84751113-f0be-4436-bb23-8c98542d2b10)

44) Sandwiches: Write a function that accepts a array of items a person wants on a sandwich. The function should have one parameter that collects as many items as the function call provides, and it should print a summary of the sandwich that is being ordered. Call the function three times, using a different number of arguments each time.

CODE:
function make_sandwich(...ingredients: string[]): void {
  console.log("Sandwich Summary:");
  for (let ingredient of ingredients) {
    console.log(`- ${ingredient}`);
  }
  console.log("Enjoy your sandwich!\n");
}

make_sandwich("Bread", "Cheese", "Tomato");
make_sandwich("Chicken", "Lettuce", "Mayonnaise", "Bread");
make_sandwich("Ham", "Swiss Cheese", "Mustard", "Pickles", "Bread");
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/624b77c9-f7b0-4725-89eb-ce1becca483f)



45) Cars: Write a function that stores information about a car in a Object. The function should always receive a manufacturer and a model name. It should then accept an arbitrary number of keyword arguments. Call the function with the required information and two other name-value pairs, such as a color or an optional feature. Print the Object that’s returned to make sure all the information was stored correctly.

CODE:
function create_car(manufacturer: string, model: string, ...options: any): object {
  let car_info: any = {
    manufacturer: manufacturer,
    model: model,
  };

  for (let option of options) {
    let key = Object.keys(option)[0];
    car_info[key] = option[key];
  }

  return car_info;
}

let car_info = create_car("Toyota", "Camry", { color: "Blue" }, { year: 2022 });
console.log(car_info);
![image](https://github.com/bilalsaeed10b/AI-Practice/assets/143334946/4291702d-f07e-416c-bac8-629e92862ef6)













































