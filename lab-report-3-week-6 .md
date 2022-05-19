# Lab Report 3

* ##  Streamlining `ssh` Configuration
  1. Show your `.ssh/config` file, and how you edited it (with VScode, another program, etc)
![Image](sshfile_screenshot.png)

  2. Show the `ssh` command logging you into your account using just the alias you chose.
![Image](report301.png)

  3. Show an scp command copying a file to your account using just the alias you chose.

   ![Image](scpBasket5.png)

   ![Image](scp_successful.png)

* ## Setup Github Access from ieng6

  1. Show where the public key you made is stored on Github and in your user account (screenshot).
  * Github:
  ![Image](remotepublickey.png)
  * user account:
  ![Image](remotepublicterminal.png)

  2. Show where the private key you made is stored on your user account (but not its contents) as a screenshot.
  ![Image](privatekey.png)

  3. Show running `git` commands to commit and push a change to Github while logged into your ieng6 account.
  ![Image](git.png)
  4. Show a link for the resulting commit.
  https://github.com/Eunggseo/markdown-parser/commit/6587948449cf69329f1cb35f919786bd8242587d


* ## Copy whole directories with `scp -r`

  1. Show copying your whole markdown-parse directory to your ieng6 account.

    Command 1:
  ```
  ⤇ scp -r *.java *.md lib/ cs15lsp22@ieng6.ucsd.edu:markdown-parse
  ```
  By doing this, we can 
  ![Image](scp1.png)
  This command helps us to log into the server with `ssh` and see all of our files there in `markdown-parse`

    Command 2 is to copy only md and java file:
  ```
  ⤇ scp -r *.java *.md lib/ ieng6:markdown-parse
  ```
  ![Image](scp2.png)
   Command 3 using a shorter name for `ieng6` in all of `ssh` and `scp` commands:
   ```
   ⤇ scp -r . ieng6:markdown-parse
   ```
  ![Image](scp3.png)
  ![Image](scp4.png)

  2. Show logging into your ieng6 account after doing this and compiling and running the tests for your repository.
   ![Image](ssh.png)

  3. Show (like in the last step of the first lab) combining `scp, ;,` and `ssh` to copy the whole directory and run the tests in one line.
 ![Image](lab3final.png)



