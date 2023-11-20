
4. press 
```
ssh cs15lfa23zz@ieng6.ucsd.edu <enter>
```
to log into ieng6
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/2c9504de-bbd5-47a4-9160-4bb3920754db)

5. press
```
git clone git@github.com:Quianey/lab7repo.git <enter>
```
to clone my fork of the repository from my Github account
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/ddc6323d-32d7-4e57-b2c2-af5cffd89ff4)

6. press
```
cd lab7repo <enter>
```
to change directory to the working directoru. Then press
```
bash test.sh <enter>
```
to run the test. And we got failures. 
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/80f38000-69e1-45ce-97de-83862e205dbb)

7. press
```
vim ListExamples.java <enter>
```
to inter the vim mode 
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/5a2bc95f-68c0-40cf-98fe-3309b148e30d)
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/6bccdc02-b7d9-4e6e-9da6-d7d704ce143a)

   press ```j``` 43 times to find the line ```index1 += 1```
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/104fd12f-e85a-482e-873f-7500c4404e1c)

   press ```l``` 12 times, stopping at the space right after index1
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/56b4046c-0e06-44cd-8fb0-869e66438d25)

   press ```i``` to enter the insert mode
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/2c421df7-1ef1-4ced-9a34-bbd66c587112)

   press ```<backspace>``` to delete 1
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/dbefb95f-f1a7-4c2f-9eec-4f6a5aea810f)

   press ```2``` to add 2 after index
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/ac33190d-0f34-4b8c-adc0-d311208d3fde)

   press ```<Esc>``` to exit the insert mode
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/e8309be7-8a2a-4f15-806b-5126a1cb82f0)

   press ```:wq``` and ```<enter>``` to quit vim
   ![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/4ff8ec03-91e2-400f-9dd7-7fd08a498f92)


8. press
```
bash test.sh <enter>
```
to run the test again. Now we secceed. 
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/e70bb673-43c8-4e41-b147-e3f0f0868023)


press 
```
git add ListExamples.java<enter>
git commit<enter>
```
to commit the change
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/54fc1c7e-f27a-42dd-8ebe-8a6dea73cd6c)

![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/6e3fc80a-ff08-4c3b-a720-3df635231c83)

press ```i``` to get into insert mode and type "changed from index1 to index2" directly
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/1ba3d55d-a47c-4845-8e51-c5836982f895)

press ```<Esc>``` to exit the insert mode
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/a03352ff-90de-4153-b329-804c61416cde)

press ```:wq <enter>``` to quit git commit
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/0bbd919f-66a1-4454-8b51-d1f3b327fd7e)

press ```git push <enter>``` to push the commit.
![image](https://github.com/Quianey/cse15l-lab-report4/assets/147276821/06a214db-53d0-4ddc-ab66-fc451e2cdff5)





