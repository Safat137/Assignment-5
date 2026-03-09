1️.What is the difference between var, let, and const?
Answer:
var, let এবং const JavaScript এ variable declare করার জন্য ব্যবহার করা হয়।
var আগে বেশি ব্যবহার করা হতো।
let দিয়ে variable বানালে পরে তার value change করা যায়।
const দিয়ে variable বানালে পরে তার value change করা যায় না।

2️.What is the spread operator (...)?
Answer:
Spread operator (...) ব্যবহার করা হয় array বা object এর ভ্যালুগুলো আলাদা করে বের করা বা copy করার জন্য।
let arr1 = [1,2,3];
let arr2 = [...arr1];


3️.What is the difference between map(), filter(), and forEach()?
Answer:
map() array এর প্রতিটি element এর উপর কাজ করে এবং নতুন array return করে।
filter() condition অনুযায়ী কিছু element নিয়ে নতুন array return করে।
forEach() array এর প্রতিটি element এর উপর কাজ করে কিন্তু নতুন array return করে না।

4️.What is an arrow function?
Answer:
Arrow function হলো JavaScript এ function লেখার একটি ছোট এবং সহজ উপায়।
const sum = (a, b) => a + b;


5️.What are template literals?
Answer:
Template literals ব্যবহার করা হয় string এর মধ্যে variable বসানোর জন্য।
এটা backtick ( ) দিয়ে লেখা হয়।
let name = "Safat";
console.log(`My name is ${name}`);
