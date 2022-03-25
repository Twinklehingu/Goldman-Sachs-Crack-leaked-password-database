# Goldman Sachs: Crack leaked password database
Controlling passwords and implementing security policies
# Overview
One of the responsibilities of a governance analyst is to gauge the effectiveness of controls implemented and minimize the probability of a successful breach. If you are a security professional, you will often need to know the methods that hackers use to defeat controls implemented within an organization, as well as suggest ways to improve security overall. Once the attackers acquire valid credentials they can access an organization's IT system, which allows them to avoid many of the perimeter security controls in place.

# Project's sample data
Here is a sample data file containing hashes dumped together: https://github.com/Twinklehingu/Goldman-Sachs-Crack-leaked-password-database/blob/main/Password_dump.txt



# Description
Using the password dump file's 19 hashcodes I was able to crack 9 passwords: https://crackstation.net/




# Project report
1) What type of hashing algorithm was used to protect passwords?
Ans: 
Message digests (MD5) are cryptographic protocols for identifying messages as well as verifying contents and signing digitally signed documents. The MD5 algorithm verifies that the file you send matches the one received by the recipient through a hash function.
Some of the most widely used algorithms include
•	MD5 which is not secure anymore
•	SHA-1 also not secure anymore
•	SHA-256 and SHA-512
•	Bcrypt
•	As well as being used to generate cryptographic keys from passwords, PBKDF2 can also hash passwords

2)	What level of protection does the mechanism offer for passwords?
Ans: 
There can be four level of password security:
Plain-text or face palms
Hashing and encrypting 
Salting and Seasoning 
The master of all the password
There is very little protection provided by MD5 and it is very insecure

3) What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?
Ans: 
Passwords should include some special characters, numbers, and upper- and lower-case alphabets. 
Utilizing a hashing algorithm that offers high security.
It is recommended to implement a minimum password length rule.
Salting and seasoning technique should be there.

4)	What can you tell about the organization’s password policy (e.g. password length, key space, etc).
Ans: 
There should be no rule for special character and length of password. 

5) What would you change in the password policy to make breaking the passwords harder?
Ans: 
A password strength checker tool which provides strongest password.
In addition, a minimum of three or more special characters should be used in the password.
Passwords should be at least ten characters long.


