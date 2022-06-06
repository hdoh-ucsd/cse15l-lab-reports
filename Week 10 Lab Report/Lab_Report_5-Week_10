# Hyungjun Doh's Week 10 Lab Report
**Explain:**
* How you found the tests with different results (Did you use vimdiff on the results of running a bash for loop? Did you search through manually? Did you use some other programmatic idea?)  
    * At first, I have tried to use vimdiff on the results of running a bash for loop. However, my code ended up with having infinite loop with the given files. So I used the command below to find the file that worked properly from the given code from week 9. Then I found two files, 
    test-files/501.md and  test-files/579.md, that have different answers.
     > bash script.sh > results.txt  


* Provide a link to the test-file with different-results (in the provided repository or your repository , either is fine)  
For each test:   
    * For test-files/501.md  
    https://github.com/hdoh-ucsd/markdown-parser/blob/main/501.md
    * For test-files/579.md
    https://github.com/hdoh-ucsd/markdown-parser/blob/main/579.md

* Describe which implementation is correct, or neither if both give the wrong output  
For both test-files, my implementation was incorrect.
For test-files/501.md, the expected result should be "foo\bar", while my implementation resulted with the symptom that considered backslash into a differenet character.

For test-files/579.md, Both implementation was incorrect. The given file had an image link but each implementations ended up with different symptoms. My implementation ignored the opening bracket and closing bracket covered the url. On the other hand, given implementation resulted with ignoring the brackets. The expected output was not printing any of the link since it was an image link.

* Indicate both actual outputs (provide screenshots) and also what the expected output is (list the links that are expected in the output).  
    * Actual outputs for my implementation
![My Actual output for 501](My501.png)
![My Actual output for 501](My579.png)

    * Actual outputs for given implementation
![Given Actual output for 501](Given501.png)
![Given Actual output for 501](Given579.png)

    * Expected outputs
![expected output for 501](Expected501.png)
![expected output for 579](Expected579.png)
