# Lab Report 4

* ### A link to your markdown-parse repository and a link to the one you reviewed in week 7
  [my repository](https://github.com/Eunggseo/markdown-parsenew/tree/main/markdown-parserWenyu)

  [reviewed one]( https://github.com/HantianLin/markdown-parser)

 ## **Snippet 1**
```
`[a link`](url.com)

[another link](`google.com)`

[`cod[e`](google.com)

[`code]`](ucsd.edu)
```
* ### Test & output of running the test(Mine):
![image](snippet1mtest.png)

![image](snippet1result.png)

* ### Test & output of running the test(Reviewed):
![image](snippet1test.png)

![image](snippet1f.png)




 ## Snippet 2
 ```
 [a [nested link](a.com)](b.com)

[a nested parenthesized url](a.com(()))

[some escaped \[ brackets \]](example.com)
```
* ### Test & output of running the test(Mine):
![image](snippet3mtest.png)

![image](snippet3result.png)

* ### Test & output of running the test(Reviewed):
![image](snippet2test.png)

![image](snippet2f.png)



 ## Snippet 3
 ```
 [this title text is really long and takes up more than 
one line

and has some line breaks](
    https://www.twitter.com
)

[this title text is really long and takes up more than 
one line](
https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule
)


[this link doesn't have a closing parenthesis](github.com

And there's still some more text after that.

[this link doesn't have a closing parenthesis for a while](https://cse.ucsd.edu/



)

And then there's more text
```
* ### Test & output of running the test(Mine):
![image](snippet1mtest.png)

![image](snippet1result.png)

* ### Test & output of running the test(Reviewed):
![image](snippet3test.png)

![image](snippet3f.png)

### For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

* ### Do you think there is a small (<10 lines) code change that will make your program work for **snippet 1** and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

* ### Do you think there is a small (<10 lines) code change that will make your program work for **snippet 2** and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

* ### Do you think there is a small (<10 lines) code change that will make your program work for **snippet 3** and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

* ### If your code already works on some/all test cases, include an explanation of what were the code changes that allowed the tests to pass.

* ### Give an extra argument to git clone that specifies which directory to clone into, for example:

`$ git clone https://github.com/ucsd-cse15l-sp22/markdown-parse markdown-parse-target-directory`

