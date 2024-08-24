# Module-10_Assignment-2
Ostad - PHP, Laravel &amp; Vue.js batch 4 - Module 10, Assignment 2.

1. Problem Statement:

Write a PHP program that takes an array of strings as input. Your program should iterate over each string in the array and perform the following operations:

    1. Count the number of vowels (a, e, i, o, u) in each string.
    2. Reverse each string.
    3. Print the original string and the modified strings along with their vowel counts.

You must use this array of strings:

    $strings = ["Hello", "World", "PHP", "Programming"];

Your Output must look like this:

    Original String: Hello, Vowel Count: 2, Reversed String: olleH
    Original String: World, Vowel Count: 1, Reversed String: dlroW
    Original String: PHP, Vowel Count: 0, Reversed String: PHP
    Original String: Programming, Vowel Count: 3, Reversed String: gnimmargorP

2. Problem Statement:

A. You are required to create a simple Library System in PHP using Object-Oriented Programming (OOP) principles. The system should have the following functionalities:

B. Create a Book class with private properties for title and availableCopies. Create a Member class with a private property for name.

C. Implement methods in the Book class to borrow and return books. This borrowBook method should decrease the available copies and returnBook method should increase the available copies.

D. Implement methods in the Member class to borrow and return books. Here the borrowBook method should take book as an argument and returnBook method should also take book as an argument.

E. Write a PHP program to demonstrate the usage of the library system, including adding books to the library, adding members, borrowing books, returning books, and displaying the available books.

F. You have to create  2 books and 2 members. Member One has to borrow  book 1 and Member Two has to borrow  book 2.

G. For your reference we have provided a template.

You must have to use this template:

    <?php


    class Book {

     // TODO: Add properties as Private

     public function __construct($title, $availableCopies) {

         // TODO: Initialize properties

         }

    // TODO: Add getTitle method

    // TODO: Add getAvailableCopies method

    // TODO: Add borrowBook method

    // TODO: Add returnBook method

    }

    class Member {

     // TODO: Add properties as Private


     public function __construct($name) {

          // TODO: Initialize properties

         }


     // TODO: Add getName method


     // TODO: Add borrowBook method

     // TODO: Add returnBook method


    }



// Usage

// You have to create  2 books and 2 members. Members One should borrow  book 1 and Member Two should borrow  book 2.


    // TODO: Create 2 books with the following properties


    Book 1 - Name: The Great Gatsby, Available Copies: 5.


    Book 2 - Name: To Kill a Mockingbird, Available Copies: 3.


    // TODO: Create 2 members with the following properties

    Member 1 - Name: John Doe

    Member 2 - Name: Jane Smith


    // TODO: Apply Borrow book method to each member


    // TODO: Print Available Copies with their names:


    ?>


Output must look like this:

    Available Copies of 'The Great Gatsby': 4
    Available Copies of 'To Kill a Mockingbird': 2

