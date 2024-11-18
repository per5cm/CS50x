# Computational Thinking and Problem Solving

At its core, computational thinking involves breaking down problems and finding systematic solutions, often using:

    Input → Process → Output: Identify what goes in (input), how it's transformed (processing), and what comes out (output).

# Representation of Numbers

Binary (Base-2)

    Binary is the language of computers, using 0 and 1 (bits).
    Each bit represents an "on" or "off" state, much like switches.
    For example: 01010101 is a sequence of 8 bits (1 byte), which translates to specific numbers.

Unary (Base-1)

    Unary counting involves a single symbol to represent values.
    Example: Counting with fingers (5 fingers can count to 31 by using combinations of "on/off" fingers, much like binary).

Decimal (Base-10)

    Humans commonly use the decimal system, with digits from 0-9.

# Bytes and Bits

A bit is a single binary digit (0 or 1).

And it happens to be a power of 2, 2 to the third 

11111111 = 255 = 1 bit

# Representing Letters 

ASCII (American Standard Code for Information Interchange)

    Assigns numbers to letters, e.g., A = 65 (01000001 in binary).
    Limited to 128 characters (7 bits).

# Unicode

Expands representation to accommodate all human languages and symbols.
Uses 16-bit, 24-bit, or 32-bit encodings.
Example: U+1F602 is the Unicode for 😂 (tears of joy emoji).
Mission: Represent and preserve all human languages and enable the use of pictograms like emojis.

sometimes it uses 16 bits or 24 bits or 32 bits per character and so on.

Because if the longest one is 32 bits, that's 2 to the 32, which, if you do out the math, trust me, is roughly 4 billion.
Unicode's mission really is to represent and to preserve all human languages digitally, both past, present, and future.
So it is really about capturing the entirety of human knowledge, as we've expressed it in language, but also giving this newfound ability that's been used centuries ago, too-- in writings, on walls, and the like-- pictograms via which we can still communicate, even independently of our own human language.

# Colors and Images

RGB (Red, Green, Blue)

    Colors are represented using three values (one for each primary color).
        Example: (255, 0, 0) = pure red.
    Digital images are sequences of pixels, each defined by an RGB value.

Motion in Pictures

    Illusion of motion is achieved by displaying a sequence of images (frames) rapidly.
    Example: 30 FPS (frames per second) = smooth motion.

# Algorithm

6. Algorithms

    Algorithm: A step-by-step set of instructions to solve a problem.
    Goal: Efficiency in terms of time (speed) and space (memory).

What is an Algorithm?

    A logical, structured method to achieve a result.
    Example: Recipe for baking a cake is an algorithm.

# Code

Code: The implementation of algorithms in a programming language.
It's the bridge between human ideas and machine execution.

# Pseudocode

So pseudocode has no formal meaning. Generally, you write it in English or whatever your own human language is.
But you write your thoughts down tersely, succinct, but precisely. You try to really convey your thoughts, not with a wave of the hand, metaphorically, but step by step, precisely. 

1. Pick up phone book
2. Open to middle of phone book
3. Look at page
4. If person is on page
5.      Call person
6. Else if person is earlier in book
7.      Open to middle of left half of book
8.      Go back to line 3
9. Else if person is letter in book
10.     Open to middle of right half of book
11.     Go back to line 3
12. Else
13.     Quit

This is just one way to write pseudocode.
Technicaly speaking this is functions.

# Conditionals

Conditionals are decision-making structures in programming.

    They ask True/False questions to determine which block of code to execute.
    Examples:
        If-else statements:

        If the phone is ringing:  
    Answer the call  
Else:  
    Continue reading  


# Loops

Loops are used to repeat steps until a condition is met.

Examples of Loops in Pseudocode:

    While loop: Repeats as long as a condition is True.

    While there are unread messages:  
    Read the next message  

    For loop: Repeats a set number of times.

    For each page in the book:  
    Check if the person is on the page  



# Artificial intelligence

AI requires more building blocks than just basic 8-bit logic because it deals with complex, often abstract problems, such as:

    Recognizing patterns (e.g., faces, voices).
    Learning from data (e.g., neural networks).
    Making predictions or decisions in uncertain environments.

To achieve this:

    AI relies on advanced algorithms, large datasets, and robust processing capabilities.
    Example: Using loops, conditionals, and mathematical functions to adjust a machine-learning model’s weights iteratively.