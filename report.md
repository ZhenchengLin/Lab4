# Lab Report 4
### 4. Log into ieng6
Input `ssh csl15sp23oa@ieng6.ucsd.edu`  then press `Enter`
And log in with my password.  
<img width="783" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/ec1a6abd-4364-4009-a649-b439e8c69c0b"> 

### 5. Clone your fork of the repository from your Github account  
Input `git clone git@github.com:ZhenchengLin/Lab7.git`
<img width="746" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/8b13522d-9ced-4c95-8e19-ab3d632ce0a1">
  
### 6. Run the tests, demonstrating that they fail
  
Here we want to run test in Lab7, therefore we need to `cd` in to Lab7; `cd Lab7`
  
When we where in Lab7 we want to see what is in this file, so we use `ls` to print out all files in Lab7
  
<img width="466" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/dc0eb769-b987-4fa5-9453-c168c983975d">
  
We see that we have a `test.sh`, which is a bash for testing. 
Then we run this bash by `bash test.sh`
  
Which it the testes fail.  
<img width="599" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/ba46bbdb-5436-491e-af61-09f20d882cd1">
  
### 7. Edit the code file to fix the failing test
We knwo that we need to fix file `ListExamples.java` inorder the stop the failling test in `ListExamplesTests.java`
  
We want to enter this java file with `vim` 
We enter `vim List<Tab>.j<Tab>` which give us `vim ListExamples.java` NOW hit `<Enter>`
Given us this page...  
<img width="599" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/1b83ac86-112d-460c-bcc4-909aa07f0b75">
  
"After reading this code.. we know that we need to change the `index1` in the last while loop" (Privided in the begging)
Steps to change this `index1` to `index2`
- `<Esc>`
- `:?index1`
- `<Enter>`
- `:?index1`
- `<Enter>`
- `v`
- `l` `l` `l` `l` `l` `l`
- `d`
- `i`
- `index2<Space>`
- `<Esc>`
- `:wq`
- `<Enter>`

Following these steps will give you this..  
<img width="599" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/db88c383-08d3-4905-a016-a6d5a7af9959">
  
### 8. Run the tests, demonstrating that they now succeed
Rerun the test by inputing `bash test.sh` and press `<Enter>`
  
  <img width="345" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/1b353a17-8ae9-4630-9b22-dda2ca145274">

### 9. Commit and push the resulting change to your Github account (you can pick any commit message!)

First we want to input `git init` `<Enter>`  

Then `git branch -m "main" `

Now we want to add the file to git by `git add List<Tab>.j<Tab>` = `git add ListExamples.java`, next `<Enter>`
  
It will not run anything...   
NEXT we will input `git commit -m "Commit! For Lab 4"`
We will resive a meesage:  
<img width="493" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/e84fb19e-2aa5-4ec9-99f3-841b74562cae">
  
We can change by inputing `git log` and `<Enter>`we can see that we commited to main
  
<img width="457" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/f3319f83-4c76-4a02-bd15-2f2b2292e0d9">
  
Next we Single click on `q` to quit form log

Then we want to push it by entering `git push` and `<Enter>`

<img width="629" alt="image" src="https://github.com/ZhenchengLin/Lab4/assets/130115215/adc99d6b-31ed-46e1-9be7-feafd487357b">

  
#### Common mistake
If we don't change the code in the file we clone in to ieng6 or local, we can't add it nor commit it.
  

