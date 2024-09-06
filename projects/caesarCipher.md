---
layout: project
type: project
image: img/caesarCipherLogo.png
title: "Caesar Cypher"
date: 2021
published: true
labels:
  - Java
  - Caesar Cipher
  - Encryption
summary: "A program that encrypts a message using a Caesar cipher."
---

<img class="img-fluid" src="../img/caesarCipher.png">

## Assignment

This assignment was from my Computer Science 1 class at Hawai'i Pacific University. The Caesar cipher is an encryption technique where each letter is replaced by another letter that is a fixed number of positions away in the alphabet. The Caesar cipher can easily be decrypted and offers no secuirty, but it is incorporated in some more complex ciphers. When creating this program, I was able to gain a better understanding of encryption techniques and was introduced to encryption.

This was an independent assignment and we were asked to create a program that prompts the user to enter a message, along with a key. The program should then print the Caesar cipher encrypted message.

<hr>

## Caesar Cipher Program Sample

<pre>

<img class="img-fluid" src="../img/caesarCipherSample.png">
  
</pre>

<hr>

## Code Snippet


```
// creates a scanner
Scanner input = new Scanner(System.in);
        
// user input is assigned to the message variable
System.out.println("Enter a message to encrypt: ");
String message = input.nextLine();

// user input is assigned to the key variable
System.out.println("Enter a number to be your key: ");
int key = input.nextInt();
```
