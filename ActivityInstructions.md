# Running the expo booth
For the different exercises, see below descriptions for different age ranges.
## Setup
Idea is to have 5 stations, mapping somewhat the history and complexitiy of cryptography

1) Scytale
  A standing neon tube with a paper wrapped around half of the paper not wrapped showing gibberish. On the table several rods/tubes with different diameters. This is the teaser to get people interested. Show an encrypted image by rolling it onto a tube. Give people strips of paper to roll themselves around and then wrrite a message.

2) Pigpen/Masonic
  Worksheets on the table, poster on the wall. Explain how letters become symbols and how to reverse. Make them decode the word. Make them create a secret message to be decoded by the next person. Give them the previous person's message to decode.

3) Ceasar
  Tell about Julius Caeser, roman emperor (for Kids, mention Asterix) how he coordinates the troups. Explain the encryption and that decryption goes in the other direction. Make them decode the word. Stop them decoding second word, the code/key is not known. Introduction to the concept of key. SHow how to find the key (break the code) with the cryptodrum.

4) Vigenere
  The key becomes now a word. Make visitors write a small sentence and chose a keyword (password). Then encrypt with 2 rules to help find the letters on the matrix. If there are 2 people, make them exchange the messages. Then decrypt.

5) Asymmetric keys
  Explain that sharing a password overseas is impractical. Introduce to one way function and the one way lock. Make people lock/unlock the cylinders when demonstrating.

# Age Group 1 (7-9 years old)
## Substitution Ciphers Simplified
*(white board/ flipchart, stick-it notes, cipher ruler prototype, cipher wheel, cardboard / paper plates, scissors, rulers and protractors, pins)*

Show kids a written unencrypted word, for instance George (because this is the name of the festival mascot). Tell them we want to keep it secret and will write it in a secret alphabet, a code. 
Put a stick-it note with a symbol, say a circle, over 'g'-s (both) and then a stick-it note with another symbol, e.g. a square, over 'e' and so on until all letters are covered with symbols. The kids can suggest which letter to cover with which symbols. 

Show the kids the alphabet and under each letter, put a stick-it note with the symbol we will use instead of the letter, starting with those we have already covered: g, e, o, r. 
Alternatively, the substitution table for the alphabet can be prepared in advance except for the letters used in 'George', which the kids will match with the symbols available, in order to save time.

Explain the notion of 'plain text' and 'ciphertext'.
Let them use the code to “encrypt” their names and then check with friends if they've done it correctly.

Show kids a cipher ruler: the plaintext alphabet in one colour, e.g. blue, and the symbols for the encrypted text (ciphertext alphabet) in another colour, e.g. red, below. 
Explain we can still use normal letters, not symbols, using a ciphertext alphabet, which is shifted a number of places. 
Demonstrate by showing a second line of alphabet (the ciphertext one) and shifting it several places to the left (that's important in order to be consistent with later explanations of the mathematical value of the key). 
Cut the end of the ciphertext alphabet that sticks out and put it at the end so that every letter has its cipher letter below it. 
Explain that this is not convenient and show kids a cipher wheel/disc: first with 0 key and then with keys 1, 2, etc. 
Explain to kids they'll make their own cipher wheels. Hand them pieces of cardboard or paper plates and guide them through cutting two wheels (a bigger and a smaller one), 
drawing 26 spaces for the letters along the edge and writing them there, then fixing the two wheels together. 

Let kids use their new cipher wheels to write a word their friends should guess. If they want, they can leave those words in a bottle for the next class to guess. 

Offer encrypted messages to decrypt.

*(If time is short, kids can only be shown the “symbol” cipher alphabet and can make a cipher wheel with symbols, rather than letters.)*

## **Extra activities:**

### Number Alphabet 

*(number alphabet poster, ASCII table poster)*

This is a very easy code to solve! Each number stands for a letter.
1 stands for A
2 stands for B
3 stands for C and so on.
So if you tell kids the number is 10, they count ten letters into the alphabet: "A B C D E F G H I J", and get a J.
To help solve this code a bit quicker, we will have the whole alphabet printed out with the numbers from 1 to 26 next to each letter.

A=1

B=2

C=3, etc.

Now, whenever kids see a number, they can either count that many letters, or look up the number and write down the letter above it. 
Additionally, you may explain to kids that this is how computers read letters and introduce them in a very, very simplified way to ASCII codes: 
'Computers can only understand numbers, so an ASCII code is the numerical representation of a character such as 'a' or '@' or an action of some sort.' 
Tell them ASCII was designed a long time ago for telegraphs and at the beginning of the table there are characters, e.g. non-printing characters, that are there just for the machines to understand. 
That is why if we want a computer to show a number, the code for this number will differ from it's value – it has been 'encoded'.

### Braille 

*(Braille alphabet poster)*

Braille is another substitution cipher - but it's not intended to keep things secret!  Braille is specially designed to print letters using a grid of up to six raised dots, so that a blind person can read the letter by running their fingers over it. 
There will be a poster showing Braille alphabet with an easy phrase to decode.

### Greek Code 

*(long strips of paper and the cardboard tube from wrapping paper or something similar)*

To make a code on a code stick, you need a long strip of paper, and a pipe or cardboard tube from wrapping paper ( tell kids at home they can use a walking stick or a broomstick).
First kids wind the strip of paper tightly around the pipe/tube/stick. Then they write their message all the way down (they can write it on several lines). 
When kids unwind the message, no-one can read it unless they have the same pipe/tube/stick as the original one! But if they have the stick, they can read the message just by winding the strip of paper around it again.

### Block Cipher 

*(flipchart/whiteboard, paper for students to write)*

We write the message in a rectangular block, one row at a time, and then read off the columns.

Example:
To encode the message THIS IS VERY EASY!, write it in a block like this:

THISI

SVERY

EASY!

The coded message is read by looking at the columns, and writing them out like this: TSE HVA IES SRY IY!
To decode it, just write all the code words in a block again, as columns, and then read the message across the rows. 

Here's a code for kids to solve:

LKU OHR OIT KGH WHE IER DRA ELF ROI LOE OKL OFD

# Age Group 2 (10-12)
## Caesar Cipher 

*(cipher wheel, Vigenere table and a Vigenere example poster, paper for kids to write their own Vigenere cipher squares or code word tables)*

Describe the **Caesar** encryption by alphabet shifts and using the cipher wheel. Start by choosing a fixed integer, such as 5. 
To encipher a message, each letter is replaced by the letter 5 places down the alphabet (move the cipher alphabet of the cipher ruler 
5 places **_to the left_**. Or demonstrate it with the cipher wheel.) To encrypt V, W, X, Y, or Z, we return to the beginning of the alphabet. 
For instance, the message “YES” gets transformed to “DJX.” The mathematical concept here is addition in a cyclic group. 
Schematic wheels provide a good way to illustrate this simple but important idea. Historically, wheels with gears were used to for alphabet shifts including the Vigenère shift. 

## Frequency Analysis
Perhaps the children can figure out a way to break the cipher on their own; otherwise, frequency analysis can be suggested. 
That is, we first ask them to guess which letter appears most frequently in English (most will say either 'e' or 'a'). 
Then we have them look at a paragraph, count the 'a's, 'e's, etc. and check their guess, as well as check the second and third most frequently occurring letters. 
Also, they might look at words in ciphertext – 1-, 2- and 3-letter words in English and guess what they might be, hence guessing the letters, as the alternatives are quite few.

Possible steps or tips:

-Match a common letter in the message with a common letter in English or in your language (Letter Frequencies?)

-Find a one letter word – what could it be?

-Find a two-letter word – what could it be?

-Look for double letters – what could they be?

-Look at punctuation – what letter could come after an apostrophe?

frequency analysis of “sciencefestival”, “neumuenster”. /*Other ideas? Ideas for French, German and Luxembourgish words, texts and most frequently used letters? I don't have much on frequency analysis*/

## Vigenere Cipher

Next, building on the Caesar cipher, we introduce Vigenère ciphers (two-alphabet proto-Vigenere cipher), which work like the Caesar cipher, except that an entire block of 2, 3, 4, or 5 letters is shifted by a key-word. 
The Vigenère cipher, was invented by a Frenchman, Blaise de Vigenère in the 16th century. It is a polyalphabetic cipher because it uses two or more cipher alphabets to encrypt the data. 
In other words, the letters in the Vigenère cipher are shifted by different amounts, normally done using a word or phrase as the encryption key. 
For example, if the key-word is ”dog,” consisting of the 4th, 15th, and 7th letters of the alphabet, then the first letter of the message is shifted by 4, the second letter is shifted by 15, the third by 7, the fourth by 4 (here we return to the beginning of the key-word), the fifth by 15, and so on. 

How to explain encryption using a Vigenere square:

Kids choose a keyword, e.g. 'dog'. They write the keyword (repeating it as many times as necessary) above the words of the message they want to encrypt – D above the first letter, O above the second letter, G above the third letter, and again D above the fourth letter, etc. Then, they start encrypting with the first letter of the keyword, e.g. D. They look at the Vigenere square and find the row starting with that chosen keyletter, e.g. D. Then, they use this row as a ciphertext alphabet to encrypt all the plaintext letters in their message, that have the chosen keyletter above them by choosing the right column. The cipher text letter is where the keyword row crosses the plaintext letter column.

The same is repeated for the second, third and so on letter of the keyword. 

Decryption works reversing the process.

Unlike the monoalphabetic ciphers, polyalphabetic ciphers are not susceptible to frequency analysis, as more than one letter in the plaintext can be represented by a single letter in the encryption.

## Using Caesar bruteforcing drum for encryption
It is possible to use the cesar brutforcing drum to encrypt. Set all wheels to A. Then turn the second wheel of each pair to spell the message. Then turn all the pairs (always 1st and 2nd synchronized, stick a sticky note to fix them) so the 1st wheels spell the codeword. Now you can read the encoded message on the entry line.
Here is hello encrypted with DOG

First we encode HELLO on the second wheel pairs
~~~~
 v-- coding line
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|
| |
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|
| |
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|
| |
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|
| |
|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|
~~~~
Then we turn all pairs to spell DOG on the coding line
~~~~
 v-- coding line
|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|
|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|
| |
|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|
|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|
| |
|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|
|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|
| |
|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|
|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|
| |
|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|A|B|C|D|E|F|
|U|V|W|X|Y|Z|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|
~~~~
The crypted message is read on the second wheel of each pair

KSROU

To decode set all wheels to A
~~~~
AA AA AA AA AA
~~~~
then put the keyword on the 1st wheels
~~~~
DA OA GA DA OA
~~~~
put the coded message on 2nd wheels on the code line
~~~~
DK OS GR DO OU
~~~~
Then turn the 1st & 2nd wheels of each pair synchronised so that the 1st wheels are all set to A. Now you can read the message on the 2nd wheels
~~~~
AH AE AL AL AO
~~~~
=> HELLO

Ask kids to encrypt a message for the following group and put it in a bottle / jar dedicated for that age group. Remind them – no hate speech, no bullying 
/* Shall we audit those messages before the following group? Shall we ask BEE Secure for no-bullying posters and materials? */

Offer encrypted messages to decrypt.

## Extra activity:
### Block Cipher 
*Easy! (flipchart/whiteboard, paper for students to write)*

We write the message in a rectangular block, one row at a time, and then read off the columns.

Example:
To encode the message THIS IS VERY EASY!, write it in a block like this:

THISI

SVERY

EASY!

The coded message is read by looking at the columns, and writing them out like this: TSE HVA IES SRY IY!
To decode it, just write all the code words in a block again, as columns, and then read the message across the rows. 

Here's a code for kids to solve:

LKU OHR OIT KGH WHE IER DRA ELF ROI LOE OKL OFD

### Code word / Keyword
*(flipchart/whiteboard; paper for kids to write their own tables; there are printable ones)*

Kids can make a code based on a special code word (or keyword) which only they know about. We've chosen the word "XYLOPHONE". 
So first of all we write down the normal alphabet (the plaintext alphabet), and below it we write the code alphabet, starting with the codeword, and following the codeword with the rest of the alphabet.
But there's a trick to this - remember that we don't want repeated letters! 
So kids have to leave out the second O in XYLOPHONE, and when you get to the normal alphabet you write down ABCDFGI... leaving out the E, the H, and any other letters in the codeword.
So here's what the alphabet looks like when you're finished:
~~~~
|Plain text:|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|-----------|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Code:      |X|Y|L|O|P|H|N|E|A|B|C|D|F|G|I|J|K|M|Q|R|S|T|U|V|W|Z|
~~~~
The next step is to explain to kids that besides a code word/ keyword, we can have a keyletter - the code word should be written starting under the specified keyletter rather than at the beginning. And then, the rest of the alphabet is written omitting duplicate letters.

### Public Key Cryptography (Highly recommended)
Explain the use of encryption for public-secret (private) key cryptography – with previously shown ciphers, we use the same key for encrypting and decrypting – symmetric encryption. 
It is more secure if each of us has different keys. Demonstrate Georges's box with 2 locks that illustrates the idea of asymmetric encryption. 
Bob and Alice case: Alice wants to send a message that only Bob can read. She takes a public key Bob has given her and locks the message in the box. She can't open the box any more using her public key. 
Bob takes his secret key and opens the box to retrieve the message. This is how encryption works with different keys for encryption and decryption – essentially modern encryption mechanisms.

A lesson plan and feedback on [Teaching crypto to 5th graders] (http://avi-rubin.blogspot.lu/2010/03/teaching-cryptography-to-5th-graders.html)

# Age Group 3 (13-15)
## Caesar Cipher
Start in the same way with a brief explanation of Caesar cipher, stressing more on the key/shift value and the calculation of ciphertext. 
Discuss replacement of each letter with a numerical value (which essentially is necessary when using computers), adding the value of the key and the use of modulo operation. 
Don't use the term, explain rather that it's dividing by the number of letters in an alphabet. Then, the remainder is used as the value of the ciphertext letter.

Ask attendees to encrypt a simple phrase or sentence with a key of their choice. They can encrypt the same phrase or sentence later with additive, multiplicative or affine ciphers.

##Additive, Multiplicative and Affine ciphers
First, youngsters need to replace each letter with its numerical value, starting with A=0, B=1, C=2, etc. Then, an encryption key value is added to each letter's value and the result is divided by 26. The remainder of this division is actually the ciphernumber. This is called Additive cipher.

To decrypt this, from each number in the ciphertext, kids need to subtract the key value and then find the letter corresponding to the result value.

A similar cipher, Multiplicative, exists when we multiply the letter numerical value by a key rather than add it to it. 
To decrypt this, kids need to understand the modular inverse of an integer concept so it might be too much for them.

When we combine the Additive Cipher and the Multiplicative Cipher, we get Affine cipher.

While it will be too much to show youngsters formulas, stressing the importance of the remainder from a division will suffice. 
However, we need to explain that in computing, and hence in the number cipher, counting starts from 0 to m-1 or 26-1, which is 25. For example letter A will be 0 and the last letter, Z, will be 25.

Ask attendees to encrypt a simple phrase or sentence with a cipher and key of their choice and exchange with friends.

## Frequency Analysis
As unreadable as the resulting ciphertext may appear at first sight, the Caesar Cipher is one of the weakest forms of encryption.
Using a brute force method, one could easily try all possible combinations in order to decrypt the message without initially knowing the key. 
The structure of the original plaintext remains intact. This makes the encryption method vulnerable to frequency analysis - 
by looking at how often certain characters or sequences of characters appear, one can discover patterns and potentially discover the key without having to perform a full brute force search. 

Perhaps the youngsters can figure out a way to break the cipher on their own; otherwise, frequency analysis can be suggested to them. 
That is, we first ask them to guess which letter appears most frequently in English (most will say either 'e' or 'a'). 
Then we have them look at a paragraph, count the 'a's, 'e's, etc. and check their guess, as well as check the second and third most frequently occurring letters. 
Also, they might look at words in ciphertext – 1-, 2- and 3-letter words in English and guess what they might be, hence guessing the letters, as the alternatives are quite few.

Possible steps or tips:

-Match a common letter in the message with a common letter in English or in your language (Letter Frequencies?)

-Find a one letter word – what could it be?

-Find a two-letter word – what could it be?

-Look for double letters – what could they be?

-Look at punctuation – what letter could come after an apostrophe?

frequency analysis of “sciencefestival”, “neumuenster”. /*Other ideas? Ideas for French, German and Luxembourgish words, texts and most frequently used letters? I don't have much on frequency analysis*/

## Vigenère cipher
And then, you can move on to Vigenère cipher, which is a good way to lead into talking about Enigma-style ciphers that use multiple alphabets, making decryption more difficult, and how that led to more complex systems. 
As we will put up a Vigenere square, youngsters can encode (as a group) a short message and see how very different it looks from the previous ciphers. 

How to explain encryption using a Vigenere square:

Kids choose a keyword, e.g. 'dog'. They write the keyword (repeating it as many times as necessary) above the words of the message they want to encrypt – D above the first letter, O above the second letter, G above the third letter, and again D above the fourth letter, etc. Then, they start encrypting with the first letter of the keyword, e.g. D. They look at the Vigenere square and find the row starting with that chosen keyletter, e.g. D. Then, they use this row as a ciphertext alphabet to encrypt all the plaintext letters in their message, that have the chosen keyletter above them by choosing the right column. The cipher text letter is where the keyword row crosses the plaintext letter column.

The same is repeated for the second, third and so on letter of the keyword. 

Decryption works reversing the process.

Transition to assymetric key systems: how do we trasmit the encryption key so that nobody can intercept it on the way?

## Public Key Cryptography 
Explain the use of encryption in public-secret (private) key cryptography – with previously shown ciphers, we use the same key for encrypting and decrypting – symmetric encryption. It is more secure if sender and recipient of the encrypted message have different keys. 

Demonstrate Georges's box with 2 locks that illustrates the idea of asymmetric encryption. 

Bob and Alice case: Alice wants to send a message that only Bob can read. She takes a public key Bob has given her and locks the message in the box. She can't open the box any more using her public key. Bob takes his secret key and opens the box to retrieve the message. 
This is how encryption works with different keys for encryption and decryption – essentially modern encryption mechanisms.

You can go on to explain the opposite use – to sign a message with your secret (private) key when everybody having the public key can open it. But they know that only you could lock it in the box, as only the secret key could open it in that direction.

See the detailed operating of this workshop in [PublicSecretCrypto/README.md](PublicSecretCrypto/README.md)

*No extra activities here – attendees may encrypt their messages and decrypt others' messages for as much time as they have left.*

# Age Group 4 (16-18 + Adults)
## Caesar Cipher
Start with a very brief explanation of Caesar cipher, key values, replacement of each letter with a numerical value and calculation of corresponding ciphertext values, using modulo operation and the remainder as the ciphertext value.
The encryption of a letter *x* is equal to a shift of *x + n*, where *n* is the number of letters shifted. 
The result of the process is taken under modulo division, essentially meaning that if a letter is shifted past the end of the alphabet, it wraps around to the beginning. 
Decryption of the encrypted text (*ciphertext*) would be defined similarly, with instead a subtraction of the shift amount.

Rather than showing formulas, an example with calculating the value of a letter will do a better job. 
Also, you will need to explain that in computing, and hence in the number cipher (called Affine cipher), counting starts from 0 to m-1 or 26-1, e.g. letter A will be 0 and the last letter, Z, will be 25.

Ask attendees to encrypt a simple phrase or sentence and swap them with a friend.

## Frequency Analysis
Perhaps they can figure out a way to break the cipher of their friend on their own; otherwise, frequency analysis can be suggested to them. 
That is, we first ask them to guess which letter appears most frequently in English (most will say either 'e' or 'a'). 
Then we have them look at a paragraph, count the 'a's, 'e's, etc. and check their guess, as well as check the second and third most frequently occurring letters. 
Also, they might look at words in ciphertext – 1-, 2- and 3-letter words in English and guess what they might be, hence guessing the letters, as the alternatives are quite few.

frequency analysis of “sciencefestival”, “neumuenster”. /*Other ideas? Ideas for French, German and Luxembourgish words, texts and most frequently used letters? I don't have much on frequency analysis*/

## Vigenère cipher
And then, you can move on to Vigenère cipher, which is a good way to lead into talking about Enigma-style ciphers that use multiple alphabets, making decryption more difficult, and how that led to more complex systems. 
As we will put up a Vigenere square, youngsters can encode (as a group) a short message and see how very different it looks from the previous ciphers. 

How to explain encryption using a Vigenere square:

Kids choose a keyword, e.g. 'dog'. They write the keyword (repeating it as many times as necessary) above the words of the message they want to encrypt – D above the first letter, O above the second letter, G above the third letter, and again D above the fourth letter, etc. Then, they start encrypting with the first letter of the keyword, e.g. D. They look at the Vigenere square and find the row starting with that chosen keyletter, e.g. D. Then, they use this row as a ciphertext alphabet to encrypt all the plaintext letters in their message, that have the chosen keyletter above them by choosing the right column. The cipher text letter is where the keyword row crosses the plaintext letter column.

The same is repeated for the second, third and so on letter of the keyword. 


## Public Key Cryptography
Explain that previously shown ciphers use the same key for encrypting and decrypting – symmetric encryption. It is more secure if each of us has different keys. 

Demonstrate Georges's box with 2 locks that illustrates the idea of asymmetric encryption, which is the basis for public-secret (private) key cryptography.

Bob and Alice case: Alice wants to send a message that only Bob can read. She takes a public key Bob has given her and locks the message in the box. She can't open the box any more using her public key. Bob takes his secret key and opens the box to retrieve the message. 
This is how encryption works with different keys for encryption and decryption – essentially modern encryption mechanisms.

Go on to explain the opposite use – to sign a message with your secret (private) key when everybody having the public key can open it. But they know that only you could lock it in the box, as only the secret key could open it in that direction.

Mention asymmetric key algorithms uses: SSL (point out https), SSH, PGP and GPG, bitcoins depending on the level of understanding and interest.

Maybe talk about hash functions, MD-5, SHA-1 and SHA-256

See the detailed operating of this workshop in [PublicSecretCrypto/README.md](PublicSecretCrypto/README.md)

*No extra activities here – attendees may encrypt their messages and decrypt others' messages for as much time as they have left.*

Resources 
(to be printed on small pieces of paper and handed out to those interested):
[Kids] (http://www.cryptoclub.org/)
[Kids-teens-adults in French] (http://www.dcode.fr)
[Teens- adults] (http://crypto.interactive-maths.com)
[Adults: Chocolate Key Cryptography: Delicious Way to Send…] (http://youtu.be/xPz8aqDIwd0 )
