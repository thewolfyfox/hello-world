**Cybersecurity** 

-Cybersecurity - protects the **secrecy, integrity and availability** of computer systems and data against threats
    
    -Integrity : Only authorized people should have ability to use or modify systems and data
      e.g. a hacker sending emails mascarading as you is an integrity attack
    -Availability : An availability attack means that authorized people should have access to theiy systems and data
      -e.g. A DoS (denial of service) attack overloads a website with fake requests to make it slow or unreachable for others
    -Secrecy/confidentiality : Only authorized people should be able to access/read specific computer systems or data
      -e.g. a breach in privacy when personal details are leaked is an attack on secrecy/confidentiality
     
-Computers **have no ethics** - will execute any valid instruction!

-Security experts start by profiling attackers with something called a **threat model**
    -Specifies their capabilities, goals and probabal means of attack.

-**Authentication** used to differentiate between "right" and "wrong" people:
    
    -There are 3 types:
        -"What you know" : Based off knowledgde that should only be known by the right user and the computer. e.g. username + password
            -Most common, as easiest to compliment. 
            -However can be compromised, if hacker gets access to your "secret".
            -e.g. computers can test all 4 digit numbers in a fraction of a second, called a **brute force attack**.
            -Way to overcome : block attempts after 3 wrong attempts, or making sure lower-case letters, upper-case letters, numbers and special symbols are used.
        -"What you have" : based on the possession of a secret token only the real user has.
            -e.g. physical key and lock. 
            -Way to overcome : can be compromised if there is a physical presence of the attacker, e.g. a key is stolen or copied.
        -"What you are" -  Authenticate by presenting yourself to the computer, e.g. biometrics.
            -Way to overcome : might recognise wrong person that looks like you, as it is a **probabalistic** method. Attackers could get your fingerprints, and you cannot change yours so very dangerous comprimise.
    -2-factor/multi-factor authentication - An attacker may be able to guess your password or steal your phone, but it's a lot harder to do both.

-After authentication comes **access control** - When computer determines what you should be able to access.

    -Done through Access Control Lists (ACL), which describe what access each user has for every file, folder and program on a computer.
        -Read permission - Allows a user to only see the contents of a file.
        -Write permission - Allows a user to modify the contents of the file.
        -Execute permission - Allows a user to run the file.
            
            
            
