
4. press 
```
ssh cs15lfa23zz@ieng6.ucsd.edu <enter>
```
to log into ieng6
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/2c9504de-bbd5-47a4-9160-4bb3920754db)

5. press
```
git clone https://github.com/Quianey/lab7repo <enter>
```
to clone my fork of the repository from my Github account
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/790c095f-b446-417f-9f53-ed675e4c3c92)

6. press
```
cd lab7repo <enter>
```
to change directory to the working directoru. Then press
```
bash test.sh <enter>
```
to run the test. And we got failures. 
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/556421e1-a702-44d5-83fd-f88b96d241b6)

7. press
```
vim ListExamples.java <enter>
```
to inter the vim mode 
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/5a2bc95f-68c0-40cf-98fe-3309b148e30d)
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/6bccdc02-b7d9-4e6e-9da6-d7d704ce143a)

   press j 43 times to find the line ```index1 += 1```
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/104fd12f-e85a-482e-873f-7500c4404e1c)

   press l 12 times, stopping at the space right after index1
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/56b4046c-0e06-44cd-8fb0-869e66438d25)

   press i to enter the insert mode
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/2c421df7-1ef1-4ced-9a34-bbd66c587112)

   press <backspace> to delete 1
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/dbefb95f-f1a7-4c2f-9eec-4f6a5aea810f)

   press 2 to add 2 after index
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/ac33190d-0f34-4b8c-adc0-d311208d3fde)

   press <Esc> to exit the insert mode
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/e8309be7-8a2a-4f15-806b-5126a1cb82f0)

   press :wq and <enter> to quit vim
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/4ff8ec03-91e2-400f-9dd7-7fd08a498f92)
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/b534c83c-62e1-4a27-8d8b-f2e5ff115166)

8. press
```
bash test.sh <enter>
```
to run the test again. Now we secceed. 
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/12d1ac63-4b27-4e82-9a09-4cf3e25cab6f)

9. 
