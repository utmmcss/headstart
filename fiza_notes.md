# HeadStart Workshop: August 23, 2016
- Professor Larry Zhang

### What CS is about?
- The science of computers:
    - a computer is a tool humans invented for solving problems
    - learn how this tool is built and how to solve problems with it

- How is a computer built:
    - a computer is made up mostly of silicon and through some magic you get a computer

- Use computers to solve problems like:
    - solve Sudoku
    - encrypt/decrypt files

- What problems should be solved by computers:
    - computers are better at repeating tasks than humans
    - running algorithms solve these problems
    - *there are algorithms and good algorithms*

- Exmaple: Text Encryption
    - Enigma was used by germans in WWII to send encrypted messages

- Substitution Cipher:
    - replace each letter with another letter according to some **substitution table**
    - **Caesar Cipher**:
        - substitution table is defined by a shift amount (left shift of 3)


####Exercise!
- Decipher the text using Caeser Cipher:
- ELALO (Cipher Text)
- HODOR (plain text)

#### Exercise 2!
- Decipher text (right shift of 4):
- XLIVIW E JMVI WXEVXMRK MR QC LIEVX 
- THERES A FIRE STARTING IN MY HEART

#### Algorithms!
- What to do when the Cipher is too long and repetitive?
    - Make an algorithm!
    - Figure out the shift amount!

- Algorithm for figuring out the shift amount:
    - 25 or 26 possible shift amounts
    - Try all 26 shift amounts to see which amount makes sense
    - time spent (aka *time complexity*) is going throught the text 26 times
  - There's a better way!
    - Hint: go over the text once and count the occurence of each letter
    - In a large enough text, the most frequent letter is **"E"**
    - In the ciphertext the most frequent letter must be the substiution of **"E"**
    - Knowing E is substituted by G...
      - Shift must be right by 2!
  - We only went over the text once! This is a more efficient way of solving problems. (26x faster than previous method)
  

- 3 virtues of a great computer scientist:
  - Laziness: make computers work on whatever can be automated
  - Impatience: speed up algorithms
  - Hubris: produce good quality code
  

## The ideas behind the code are more important: algorithms, math, model, design, etc...
