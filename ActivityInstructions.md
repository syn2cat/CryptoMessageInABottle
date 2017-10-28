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

frequency analysis of “sciencefestival”, “neumuenster”. /*Other ideas? Ideas for French, German and Luxembourgish words, texts and most frequently used letters? I don't have much on frequency analysis*/

## Vigenere Cipher

Next, building on the Caesar cipher, we introduce Vigenère ciphers (two-alphabet proto-Vigenere cipher), which work like the Caesar cipher, except that an entire block of 2, 3, 4, or 5 letters is shifted by a key-word. 
The Vigenère cipher, was invented by a Frenchman, Blaise de Vigenère in the 16th century. It is a polyalphabetic cipher because it uses two or more cipher alphabets to encrypt the data. 
In other words, the letters in the Vigenère cipher are shifted by different amounts, normally done using a word or phrase as the encryption key. 
For example, if the key-word is ”dog,” consisting of the 4th, 15th, and 7th letters of the alphabet, then the first letter of the message is shifted by 4, the second letter is shifted by 15, the third by 7, the fourth by 4 (here we return to the beginning of the key-word), the fifth by 15, and so on. 
Unlike the monoalphabetic ciphers, polyalphabetic ciphers are not susceptible to frequency analysis, as more than one letter in the plaintext can be represented by a single letter in the encryption.
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

### Code word 
*(flipchart/whiteboard; paper for kids to write their own tables)*

You can make a code based on a special code word which only you know about. We've chosen the word "XYLOPHONE". 
So first of all we write down the normal alphabet (the plaintext alphabet), and below it we write the code alphabet, starting with the codeword, and following the codeword with the rest of the alphabet.
But there's a trick to this - remember that we don't want repeated letters! 
So kids have to leave out the second O in XYLOPHONE, and when you get to the normal alphabet you write down ABCDFGI... leaving out the E, the H, and any other letters in the codeword.
So here's what the alphabet looks like when you're finished:

|Plain text:|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z|
|-----------|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Code:      |X|Y|L|O|P|H|N|E|A|B|C|D|F|G|I|J|K|M|Q|R|S|T|U|V|W|Z|

### Public Key Cryptography (Highly recommended)
Explain the use of encryption for public-secret (private) key cryptography – with previously shown ciphers, we use the same key for encrypting and decrypting – symmetric encryption. 
It is more secure if each of us has different keys. Demonstrate Georges's box with 2 locks that illustrates the idea of asymmetric encryption. 
Bob and Alice case: Alice wants to send a message that only Bob can read. She takes a public key Bob has given her and locks the message in the box. She can't open the box any more using her public key. 
Bob takes his secret key and opens the box to retrieve the message. This is how encryption works with different keys for encryption and decryption – essentially modern encryption mechanisms.

A lesson plan and feedback on [Teaching crypto to 5th graders] (http://avi-rubin.blogspot.lu/2010/03/teaching-cryptography-to-5th-graders.html)

# Age Group 3 (13-15)
## Caesar Cipher
Start in the same way with a brief explanation of Caesar cipher, stressing more on the key/shift value and the calculation of ciphertext. 
Discuss replacement of each letter with a numerical value (which essentially is necessary when using computers), adding the value of the key and the use of modulo operation 
Don't use the term, explain rather that it's dividing by the number of letters in an alphabet. Then, the remainder is used as the value of the ciphertext letter:

The encryption of a letter *x* is equal to a shift of *x + n*, where *n* is the number of letters shifted. 
The result of the process is taken under modulo division, essentially meaning that if a letter is shifted past the end of the alphabet, it wraps around to the beginning. 
Decryption of the encrypted text (*ciphertext*) would be defined similarly, with instead a subtraction of the shift amount.

While it will be too much to show youngsters formulas, stressing the importance of the remainder from a division will suffice. 
However, we need to explain that in computing, and hence in the number cipher (called Affine cipher), counting starts from 0 to m-1 or 26-1, which is 25. For example letter A will be 0 and the last letter, Z, will be 25.

Ask attendees to encrypt a simple phrase or sentence with a key of their choice and exchange with friends.

## Frequency Analysis
As unreadable as the resulting ciphertext may appear at first sight, the Caesar Cipher is one of the weakest forms of encryption.
Using a brute force method, one could easily try all possible combinations in order to decrypt the message without initially knowing the key. 
The structure of the original plaintext remains intact. This makes the encryption method vulnerable to frequency analysis - 
by looking at how often certain characters or sequences of characters appear, one can discover patterns and potentially discover the key without having to perform a full brute force search. 

Perhaps the youngsters can figure out a way to break the cipher on their own; otherwise, frequency analysis can be suggested to them. 
That is, we first ask them to guess which letter appears most frequently in English (most will say either 'e' or 'a'). 
Then we have them look at a paragraph, count the 'a's, 'e's, etc. and check their guess, as well as check the second and third most frequently occurring letters. 
Also, they might look at words in ciphertext – 1-, 2- and 3-letter words in English and guess what they might be, hence guessing the letters, as the alternatives are quite few.

frequency analysis of “sciencefestival”, “neumuenster”. /*Other ideas? Ideas for French, German and Luxembourgish words, texts and most frequently used letters? I don't have much on frequency analysis*/

## Vigenère cipher
And then, you can move on to Vigenère cipher, which is a good way to lead into talking about Enigma-style ciphers that use multiple alphabets, making decryption more difficult, and how that led to more complex systems. 
As we will put up a Vigenere square, youngsters can encode (as a group) a short message and see how very different it looks from the previous ciphers. 

/*I miss here the transition to asymmetric encryption and Public key cryptography*/

## Public Key Cryptography 
Explain the use of encryption in public-secret (private) key cryptography – with previously shown ciphers, we use the same key for encrypting and decrypting – symmetric encryption. It is more secure if sender and recipient of the encrypted message have different keys. 

Demonstrate Georges's box with 2 locks that illustrates the idea of asymmetric encryption. 

Bob and Alice case: Alice wants to send a message that only Bob can read. She takes a public key Bob has given her and locks the message in the box. She can't open the box any more using her public key. Bob takes his secret key and opens the box to retrieve the message. 
This is how encryption works with different keys for encryption and decryption – essentially modern encryption mechanisms.

You can go on to explain the opposite use – to sign a message with your secret (private) key when everybody having the public key can open it. But they know that only you could lock it in the box, as only the secret key could open it in that direction.

*No extra activities here – attendees may encrypt their messages and decrypt others' messages for as much time as they have left.*

#Age Group 4 (16-18 + Adults)
## Caesar Cipher
Start with a very brief explanation of Caesar cipher, key values, replacement of each letter with a numerical value and calculation of corresponding ciphertext values, using modulo operation and the remainder as the ciphertext value.
The encryption of a letter *x* is equal to a shift of *x + n*, where *n* is the number of letters shifted. 
The result of the process is taken under modulo division, essentially meaning that if a letter is shifted past the end of the alphabet, it wraps around to the beginning. 
Decryption of the encrypted text (*ciphertext*) would be defined similarly, with instead a subtraction of the shift amount.

Rather than showing formulas, an example with calculating the value of a letter will do a better job. 
Also, you will need to explain that in computing, and hence in the number cipher (called Affine cipher), counting starts from 0 to m-1 or 26-1, e.g. letter A will be 0 and the last letter, Z, will be 25.

Ask attendees to encrypt a simple phrase or sentence and swap them with a friend.

##Frequency Analysis
Perhaps they can figure out a way to break the cipher of their friend on their own; otherwise, frequency analysis can be suggested to them. 
That is, we first ask them to guess which letter appears most frequently in English (most will say either 'e' or 'a'). 
Then we have them look at a paragraph, count the 'a's, 'e's, etc. and check their guess, as well as check the second and third most frequently occurring letters. 
Also, they might look at words in ciphertext – 1-, 2- and 3-letter words in English and guess what they might be, hence guessing the letters, as the alternatives are quite few.

frequency analysis of “sciencefestival”, “neumuenster”. /*Other ideas? Ideas for French, German and Luxembourgish words, texts and most frequently used letters? I don't have much on frequency analysis*/

## Vigenère cipher
And then, you can move on to Vigenère cipher, which is a good way to lead into talking about Enigma-style ciphers that use multiple alphabets, making decryption more difficult, and how that led to more complex systems. 
As we will put up a Vigenere square, youngsters can encode (as a group) a short message and see how very different it looks from the previous ciphers. 

## Public Key Cryptography
Explain that previously shown ciphers use the same key for encrypting and decrypting – symmetric encryption. It is more secure if each of us has different keys. 

Demonstrate Georges's box with 2 locks that illustrates the idea of asymmetric encryption, which is the basis for public-secret (private) key cryptography.

Bob and Alice case: Alice wants to send a message that only Bob can read. She takes a public key Bob has given her and locks the message in the box. She can't open the box any more using her public key. Bob takes his secret key and opens the box to retrieve the message. 
This is how encryption works with different keys for encryption and decryption – essentially modern encryption mechanisms.

Go on to explain the opposite use – to sign a message with your secret (private) key when everybody having the public key can open it. But they know that only you could lock it in the box, as only the secret key could open it in that direction.

Mention asymmetric key algorithms uses: SSL (point out https), SSH, PGP and GPG, bitcoins depending on the level of understanding and interest.

Maybe talk about hash functions, MD-5, SHA-1 and SHA-256

*No extra activities here – attendees may encrypt their messages and decrypt others' messages for as much time as they have left.*

Resources 
(to be printed on small pieces of paper and handed out to those interested):
[Kids] (http://www.cryptoclub.org/)
[Kids-teens-adults in French] (http://www.dcode.fr)
[Teens- adults] (http://crypto.interactive-maths.com)
[Adults: Chocolate Key Cryptography: Delicious Way to Send…] (http://youtu.be/xPz8aqDIwd0 )
