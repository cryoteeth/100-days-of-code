# 100 Days Of Code - Log

### Day 1: January 01, 2017

**Today's Progress:** Completed 'Where do I belong' challenge and started 'Caesars Cipher'.

**Thoughts:** 
 Where do I belong - I'm not so great at remembering that things like filter and sort exist, and accidentally overcomplicated the problem and so needed the wiki to help. 

Caesar's Cipher - .fromCharCode is fussy and a pain, also the wiki entry is incorrect which didn't help. Luckily, someone has added a new, more comprehendable solution in the comments. (Note: It wasn't clear that JavaScript uses UTC-16 for charcodes, and the algorithms could do with links to their wiki articles.)

**Link to work:** [Where do I Belong](https://www.freecodecamp.com/challenges/where-do-i-belong#?solution=%0Afunction%20getIndexToIns(arr%2C%20num)%20%7B%0A%20%20%2F%2F%20Find%20my%20place%20in%20this%20sorted%20array.%0A%20%20arr.sort(function(a%2C%20b)%20%7B%0A%20%20%20%20return%20a%20-%20b%3B%0A%20%20%7D)%3B%0A%20%20%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20arr.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20if%20(num%20%3C%3D%20arr%5Bi%5D)%20%7B%0A%20%20%20%20%20%20return%20i%3B%0A%20%20%20%20%7D%20%20%20%20%0A%20%20%7D%0A%20%20%0A%20%20return%20arr.length%3B%0A%7D%0A%0AgetIndexToIns(%5B2%2C%205%2C%2010%5D%2C%2015)%3B%0A)

### Day 2: January 01, 2017

**Today's Progress:** Continued 'Caesars Cipher', watched some of the 'Cryptography I' course and did some of SoloLearn's JS course.

**Thoughts:** 
Caesar's Cipher - Getting tempted to just paste in the answer and get going...

Cryptography I - Interesting so far, but I'm worried I'm too rusty in maths for it.

SoloLearn JS - This sometimes seems to skip steps when doing the DOM manipulation parts of the course...

**Link to work:** [JS Course](https://www.sololearn.com/Profile/372058/JavaScript)
