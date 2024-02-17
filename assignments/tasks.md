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























