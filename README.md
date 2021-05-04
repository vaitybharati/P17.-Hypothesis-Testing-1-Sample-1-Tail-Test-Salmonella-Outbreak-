# P17.-Hypothesis-Testing-1-Sample-1-Tail-Test-Salmonella-Outbreak-

![image](https://user-images.githubusercontent.com/71163471/116982391-57c64800-ace6-11eb-8da5-78db06a0a13a.png)

1-sample 1-tail ttest Assume Null Hypothesis Ho as Mean Salmonella <= 0.3 Thus Alternate Hypothesis Ha as Mean Salmonella > 0.3

As No direct code for 1-sample 1-tail ttest available with unknown SD and arrays of means. Hence we find probability using 1-sample 2-tail ttest and divide it by 2 to get 1-tail ttest

Inference: Since (p_1t = 0.029) < (α = 0.05); Reject Null Hypothesis i.e Mean Salmonella > 0.3 

Ice-cream factory responsible for people illness.

Note: This python code states both 1-sample 1-tail and 1-sample 2-tail codes
