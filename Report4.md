# Step 4

![image](https://github.com/Klein-Shen/LabReport4/assets/165833763/007c8081-5c5e-492d-ad35-7c4cf081ba39)

`<up><Enter>`

One `<up>` since `ssh<space><nishen@ieng6.ucsd.edu>` are already here, and then used `<Enter>` to get into the ieng6 account.

# Step 5

![image](https://github.com/Klein-Shen/LabReport4/assets/165833763/70078284-0300-4a5f-a8e1-72d57e5484a2)

`git<space>clone<space><Ctrl + Shift + V><Enter>`

I used `git clone` with the ssh url to clone my fork of the repository from my Github account by using the SSH URL.

# Step 6

![image](https://github.com/Klein-Shen/LabReport4/assets/165833763/50df8023-42eb-4872-8011-2b9a2320c29d)

`ls<Enter>`
`cd<space>lab7<Enter>`
`ls<Enter>`
`<Ctrl + Shift + V><Enter>`
`<Ctrl + Shift + V><Back><Back><Back><Back><Back><Back><Back><Back><Back><Back>ListExamplesTests<Enter>`

`ls` is to see do I have the lab7 folder, then `cd` the folder, then `ls` to see what I have there. `<Ctrl + Shift + V>` copy the `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`from the week4 lab;
the second copied the `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests` then use `<Back>` 10 times to delete `ArrayTests` and then add the `ListExamplesTests` to the last and then run the test.

# Step 7

![image](https://github.com/Klein-Shen/LabReport4/assets/165833763/4ed70655-6eb2-4ffe-99da-4ffc5c13eea5)


`vim<space>ListExamples.java<Enter>` 
`<down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><down><E><A><Back><2><ESC>:wq`

`vim`the `ListExamples.java` is to use vim to edit the code file in the ssh local terminal.
43 * `<down>` since the line we need to change is in the line 44, and I start at line 1.
`<E>` is to move the cursor to the next word's end.
`<A>` is to move the cursor to the next and change to the `--INSERT--` mode; then used `<Back>` to delete 1, and add `<2>`, then `<ESC>` to leave the `--INSERT--` mode, at last use `:wq` to save and exit.

# Step 8

![image](https://github.com/Klein-Shen/LabReport4/assets/165833763/06659170-2777-4242-87d3-c9f1ccd9aec0)

`<up><up><up><Enter>`
`<up><up><up><Enter>`

First three `<up>` and `<Enter>` is to find the command I used before to javac those file. The second is to find the old command to run the test.


# Step 9

![image](https://github.com/Klein-Shen/LabReport4/assets/165833763/55d31c7a-ee67-441d-8a83-a9575c24f1aa)

`git<space>add<space>.<Enter>`
`git<space>commit<space>-m<space>"Some<space>concise<space>message<space>describing<space>the<space>change"<Enter>`
`git<space>push<space>origin<space>main<Enter>`

I used the command from lab4 `git add .` to add them to the staging area.
`git<space>commit` to commit them to the repository.
`git<space>push` to push the files for the changes to actually appear on GitHubm.
