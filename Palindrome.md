**Identifying palindromes** 

To identify a plaindrome, you check the first and last letter, and see if they are the same. Next you check the 2nd and 2nd last letter, and see if they are the same.
You repeat this until there are no letters left, or if there is just 1 letter left and none to compare it to.


The Python 3 code for this is as follows:

"""print ("Hi there")
print ()
print ("Please enter your word so that our PalindromeChecker 2000 can deduct whether it is a palindrome or not. (Hint: don't enter a number)")
word = input()
wordlist = list()
for char in word:
	wordlist.append(char)
j = len(word) -1

i = 0
for b in wordlist:
	if b != wordlist[j]:
		print()
		print("This is not a palindrome!")
		break
	else:
		while wordlist[i] == wordlist[j]:
			i = i +1
			j = j -1
			if i == len(word):
				print()
				print ("This is a palindrome!")
			break
				"""
				
    
    
  
  

