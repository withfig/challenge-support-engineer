# Bash & Customer Support Mini Challenges

- Challenge 1: The Shell
- Challenge 2: Customer support
- Challenge 3: 1 minute typing test

## Challenge 1 - The Shell

Pretend you have just received the following emails from a user named "Jane" asking for help with Fig/shell related issues. Write an example response to each. Please submit in a markdown/word/textedit doc

### Questions

1. How do I change my default shell from bash to zsh?
2. How can I customise my prompt such that:
    1. It says my current working directory but only the folder name not the full path (e.g. if I'm on my desktop, make it just say `Desktop` not `~/desktop`. If I'm in my home directory, make it say `~` not your name (e.g. `brendan`)
    2. If I'm in a git repo, it should additionally say the current branch I am on, but if am not in a git repo, it should say nothing
    3. BONUS: How can I make the git branch be bold and coloured green?
    
    ![image](https://user-images.githubusercontent.com/4949076/155825156-3672ff7f-ef5e-41a6-8266-f5c92ba016d3.png)

    
3. How can I have my shell automatically alternate printing out either "First line" or "Second line" just before a new prompt loads.
    1. Hints: 1. you will want to look into zsh's `precmd` hook + storing state with environment variables. 2. Assume the user has already defined `precmd` somewhere
    
![image](https://user-images.githubusercontent.com/4949076/155825160-4b020a5b-d6bb-4d0f-bec5-ee029e7c591b.png)

    
4. I have a file on my desktop called `[test.sh](http://test.sh)` which contains just one line: `echo hello world`. But when I run `./test.sh` it says `zsh: permission denied: ./test.sh`. How do I get this working?
5. I just installed brew on my new Mac M1 and it asked me to put `/opt/homebrew/bin`
 in my path. What does this mean and how do I do it?


### Bonus Question

I have a LOT of files on my desktop. I want to find all the files on my desktop that contain the phrase "hello world"

1. What command can I run that just lists the files that contain "hello world"?
2. What command can I run that lists the files that contain "hello world" and for each file, the line that contains "hello world" AND the lines 5 lines before and 5 lines after that line

![image](https://user-images.githubusercontent.com/4949076/155825166-7deda356-edf2-4715-9ae8-a669e43c82b6.png)


(This last one may be a little harder but I want to see how you do. If you can’t do it, no worries. If you need help please email)

### Hints for structuring your response

1. Keep your email short and simple! **No one** wants to read a long email
2. Use single backticks when referencing a small code block e.g. \`cd desktop\`  
3. Use tripe backticks when referencing a longer code block e.g.

\```  
git add .  
\```  

4. Remember, you’re pretending to respond to a user asking these questions. Be nice and friendly!

### Hints for understanding the shell

- For colors, look up ANSI escape sequences
- Look up "zsh hooks"

### Evaluation Criteria
* Correct and working answers
* Clear and simple communication
* Empathy with user



## Challenge 2 - Customer Support

Could you please just answer these quick questions for us:

1. As a support engineer, you will help maintain our public issues repository on GitHub. What makes a well maintained issues repo?
2. Every time a user submits our uninstall feedback form, we receive an email. The feedback form usually tells us why they uninstalled. As part of being a support engineer, you will try and upsell users who have uninstalled into redownloading it. In what cases is it appropriate to do this?



## Challenge 3 - Typing Test

Could you please take this 1 min typing speed test: [https://www.typing.com/student/typing-test/1-minute](https://www.typing.com/student/typing-test/1-minute) and screenshot your results? 

Feel free to take it a couple of times. Don’t worry too much about accuracy (as long as it’s above 90% it’s probably fine).

We know typing speed doesn’t necessarily correlate with a successful customer support person. However, you will likely be interacting with a lot of users online so we are just interested in seeing how quickly you can type!


# Submission
When you are done, please put your answers for challenge 1, 2, and 3 in separate files in a folder, zip the folder, and upload to: https://airtable.com/shrFwTaQFMqvzKYLX
