# aayush-ChIP-seq

```
R version 3.4.3 (2017-11-30) -- "Kite-Eating Tree"
Copyright (C) 2017 The R Foundation for Statistical Computing
Platform: x86_64-pc-linux-gnu (64-bit)

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

  Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.

> source("https://raw.githubusercontent.com/tdhock/PeakSegPipeline/master/tests/testthat/test-pipeline-input.R")
chr10 33061000  33061017  0.3256
chr10 33061017  33061022  0.2442
chr10 33061022  33061029  0.1628
chr10 33061029  33061061  0.2442
chr10 33061061  33061079  0.3256
chr10 33061079  33061083  0.2442
chr10 33061083  33061100  0.3256
chr10 33061100  33061129  0.2442
chr10 33061129  33061130  0.1628
chr10 33061130  33061151  0.2442
Reading /home/aayush/PeakSegPipeline-test/non-integer/labels/some_labels.txt
5 chunks, 19 label lines
labeled sample groups: kidney, Input
Wrote 19 labels to /home/aayush/PeakSegPipeline-test/non-integer/samples/Input/MS010302/labels.bed
Wrote 19 labels to /home/aayush/PeakSegPipeline-test/non-integer/samples/kidney/MS002201/labels.bed
Read 1 problems from /home/aayush/PeakSegPipeline-test/non-integer/problems.bed
Writing    1 /    2 samples 19 labels 1 labeled problems /home/aayush/PeakSegPipeline-test/non-integer/samples/Input/MS010302/problems
Writing    2 /    2 samples 19 labels 1 labeled problems /home/aayush/PeakSegPipeline-test/non-integer/samples/kidney/MS002201/problems
Writing 1 jointProblems.bed.sh scripts.
Writing 5 chunks in /home/aayush/PeakSegPipeline-test/non-integer/problems/chr10:18024675-38818835
bigWigToBedGraph -chrom=chr10 -start=18024675 -end=38818835 /home/aayush/PeakSegPipeline-test/non-integer/samples/Input/MS010302/coverage.bigWig /home/aayush/PeakSegPipeline-test/non-integer/samples/Input/MS010302/problems/chr10:18024675-38818835/coverage.bedGraph 
        chrom chromStart chromEnd coverage count.num.str count.int
     1: chr10   33061063 33061100   0.1242        0.1242         0
     2: chr10   33061100 33061116   0.2484        0.2484         0
     3: chr10   33061116 33061144   0.3726        0.3726         0
     4: chr10   33061144 33061163   0.4968        0.4968         0
     5: chr10   33061163 33061200   0.3726        0.3726         0
    ---                                                           
277372: chr10   38818823 38818826   1.2420         1.242         1
277373: chr10   38818826 38818830   0.9936        0.9936         1
277374: chr10   38818830 38818833   0.8694        0.8694         1
277375: chr10   38818833 38818834   0.6210         0.621         1
277376: chr10   38818834 38818835   0.3726        0.3726         0
        count.int.str
     1:             0
     2:             0
     3:             0
     4:             0
     5:             0
    ---              
277372:             1
277373:             1
277374:             1
277375:             1
277376:             0
chr10 33061000  33061017  4
chr10 33061017  33061022  3
chr10 33061022  33061029  2
chr10 33061029  33061061  3
chr10 33061061  33061079  4
chr10 33061079  33061083  3
chr10 33061083  33061100  4
chr10 33061100  33061129  3
chr10 33061129  33061130  2
chr10 33061130  33061151  3
Reading /home/aayush/PeakSegPipeline-test/input/labels/some_labels.txt
5 chunks, 19 label lines
labeled sample groups: kidney, Input
Wrote 19 labels to /home/aayush/PeakSegPipeline-test/input/samples/Input/MS010302/labels.bed
Wrote 19 labels to /home/aayush/PeakSegPipeline-test/input/samples/kidney/MS002201/labels.bed
Read 1 problems from /home/aayush/PeakSegPipeline-test/input/problems.bed
Writing    1 /    2 samples 19 labels 1 labeled problems /home/aayush/PeakSegPipeline-test/input/samples/Input/MS010302/problems
Writing    2 /    2 samples 19 labels 1 labeled problems /home/aayush/PeakSegPipeline-test/input/samples/kidney/MS002201/problems
Writing 1 jointProblems.bed.sh scripts.
Writing 5 chunks in /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835
Next = 0, Inf mc.cores= 4 
   penalty peaks     status fp fn errors
1:       0 89411 infeasible 19  0     19
2:     Inf     0   feasible  0  2      2
0.039655 minutes elapsed / 5.000000 limit
Target interval: 5.531713 Inf change: Inf NaN
Next = 252.576236683382 mc.cores= 4 
    penalty peaks     status fp fn errors
1:   0.0000 89411 infeasible 19  0     19
2: 252.5762  4938 infeasible 18  0     18
3:      Inf     0   feasible  0  2      2
0.044898 minutes elapsed / 5.000000 limit
Target interval: 8.337237 Inf change: 2.805524 NaN
Next = 4176.53405795014 mc.cores= 4 
     penalty peaks     status fp fn errors
1:    0.0000 89411 infeasible 19  0     19
2:  252.5762  4938 infeasible 18  0     18
3: 4176.5341    10   feasible 12  0     12
4:       Inf     0   feasible  0  2      2
0.049764 minutes elapsed / 5.000000 limit
Target interval: 14.396637 Inf change: 6.059400 NaN
Next = 1788050.95083481 mc.cores= 4 
        penalty peaks     status fp fn errors
1:       0.0000 89411 infeasible 19  0     19
2:     252.5762  4938 infeasible 18  0     18
3:    4176.5341    10   feasible 12  0     12
4: 1788050.9508     1   feasible  1  2      3
5:          Inf     0   feasible  0  2      2
0.054405 minutes elapsed / 5.000000 limit
Target interval: 16.685831 Inf change: 2.289194 NaN
Next = 26426.9587447055 mc.cores= 4 
        penalty peaks     status fp fn errors
1:       0.0000 89411 infeasible 19  0     19
2:     252.5762  4938 infeasible 18  0     18
3:    4176.5341    10   feasible 12  0     12
4:   26426.9587     3   feasible  2  0      2
5: 1788050.9508     1   feasible  1  2      3
6:          Inf     0   feasible  0  2      2
0.058719 minutes elapsed / 5.000000 limit
Target interval: 16.685831 Inf change: 0.000000 NaN
Next = 91583.9843794089, 7810.66570621882 mc.cores= 4 
        penalty peaks     status fp fn errors
1:       0.0000 89411 infeasible 19  0     19
2:     252.5762  4938 infeasible 18  0     18
3:    4176.5341    10   feasible 12  0     12
4:    7810.6657     5   feasible  3  0      3
5:   26426.9587     3   feasible  2  0      2
6:   91583.9844     2   feasible  1  0      1
7: 1788050.9508     1   feasible  1  2      3
8:          Inf     0   feasible  0  2      2
0.063776 minutes elapsed / 5.000000 limit
Target interval: 10.324785 11.936160 change: -6.361046 -Inf
Next = 0, Inf mc.cores= 4 
   penalty  peaks     status fp fn errors
1:       0 188109 infeasible 19  0     19
2:     Inf      0   feasible  0 11     11
0.039827 minutes elapsed / 5.000000 limit
Target interval: 5.547819 Inf change: Inf NaN
Next = 256.677224108445 mc.cores= 4 
    penalty  peaks     status fp fn errors
1:   0.0000 188109 infeasible 19  0     19
2: 256.6772   5303 infeasible 17  0     17
3:      Inf      0   feasible  0 11     11
0.044447 minutes elapsed / 5.000000 limit
Target interval: 9.079821 Inf change: 3.532002 NaN
Next = 8776.39558337604 mc.cores= 4 
     penalty  peaks     status fp fn errors
1:    0.0000 188109 infeasible 19  0     19
2:  256.6772   5303 infeasible 17  0     17
3: 8776.3956     45 infeasible  8  2     10
4:       Inf      0   feasible  0 11     11
0.048837 minutes elapsed / 5.000000 limit
Target interval: 6.548532 13.767020 change: -2.531289 -Inf
Next = 698.218644190147, 952666.492166474 mc.cores= 4 
       penalty  peaks     status fp fn errors
1:      0.0000 188109 infeasible 19  0     19
2:    256.6772   5303 infeasible 17  0     17
3:    698.2186   1611 infeasible 17  0     17
4:   8776.3956     45 infeasible  8  2     10
5: 952666.4922      2   feasible  4 10     14
6:         Inf      0   feasible  0 11     11
0.053596 minutes elapsed / 5.000000 limit
Target interval: 7.210717 11.890233 change: 0.662185 -1.876787
Next = 1353.86288142195, 145835.285384431, 18299537.4379804 mc.cores= 4 
        penalty  peaks     status fp fn errors
1: 0.000000e+00 188109 infeasible 19  0     19
2: 2.566772e+02   5303 infeasible 17  0     17
3: 6.982186e+02   1611 infeasible 17  0     17
4: 1.353863e+03    482 infeasible 15  0     15
5: 8.776396e+03     45 infeasible  8  2     10
6: 1.458353e+05     13   feasible  2  2      4
7: 9.526665e+05      2   feasible  4 10     14
8: 1.829954e+07      1   feasible  3 11     14
9:          Inf      0   feasible  0 11     11
0.058474 minutes elapsed / 5.000000 limit
Target interval: 10.287548 13.091200 change: 3.076831 1.200967
Next = 29364.6916964203, 484658.830658644, 2458.83878260142 mc.cores= 4 
         penalty  peaks     status fp fn errors
 1: 0.000000e+00 188109 infeasible 19  0     19
 2: 2.566772e+02   5303 infeasible 17  0     17
 3: 6.982186e+02   1611 infeasible 17  0     17
 4: 1.353863e+03    482 infeasible 15  0     15
 5: 2.458839e+03    183 infeasible 13  0     13
 6: 8.776396e+03     45 infeasible  8  2     10
 7: 2.936469e+04     22   feasible  3  2      5
 8: 1.458353e+05     13   feasible  2  2      4
 9: 4.846588e+05      6   feasible  2  4      6
10: 9.526665e+05      2   feasible  4 10     14
11: 1.829954e+07      1   feasible  3 11     14
12:          Inf      0   feasible  0 11     11
1.478601 minutes elapsed / 5.000000 limit
Target interval: 11.060507 12.595133 change: 0.772959 -0.496068
Next = 63608.8092566224, 295118.695227933, 4029.44576906718 mc.cores= 4 
         penalty  peaks     status fp fn errors
 1: 0.000000e+00 188109 infeasible 19  0     19
 2: 2.566772e+02   5303 infeasible 17  0     17
 3: 6.982186e+02   1611 infeasible 17  0     17
 4: 1.353863e+03    482 infeasible 15  0     15
 5: 2.458839e+03    183 infeasible 13  0     13
 6: 4.029446e+03     95   feasible 11  0     11
 7: 8.776396e+03     45 infeasible  8  2     10
 8: 2.936469e+04     22   feasible  3  2      5
 9: 6.360881e+04     17   feasible  2  2      4
10: 1.458353e+05     13   feasible  2  2      4
11: 2.951187e+05      9   feasible  2  4      6
12: 4.846588e+05      6   feasible  2  4      6
13: 9.526665e+05      2   feasible  4 10     14
14: 1.829954e+07      1   feasible  3 11     14
15:          Inf      0   feasible  0 11     11
2.905870 minutes elapsed / 5.000000 limit
Target interval: 10.538178 12.271983 change: -0.522329 -0.323150
Next = 37728.7599369362, 213626.165975701, 5913.89122570805, 95958.8709062301 mc.cores= 4 
         penalty  peaks     status fp fn errors
 1: 0.000000e+00 188109 infeasible 19  0     19
 2: 2.566772e+02   5303 infeasible 17  0     17
 3: 6.982186e+02   1611 infeasible 17  0     17
 4: 1.353863e+03    482 infeasible 15  0     15
 5: 2.458839e+03    183 infeasible 13  0     13
 6: 4.029446e+03     95   feasible 11  0     11
 7: 5.913891e+03     68 infeasible 11  0     11
 8: 8.776396e+03     45 infeasible  8  2     10
 9: 2.936469e+04     22   feasible  3  2      5
10: 3.772876e+04     18   feasible  2  2      4
11: 6.360881e+04     17   feasible  2  2      4
12: 9.595887e+04     15   feasible  2  2      4
13: 1.458353e+05     13   feasible  2  2      4
14: 2.136262e+05     11   feasible  2  2      4
15: 2.951187e+05      9   feasible  2  4      6
16: 4.846588e+05      6   feasible  2  4      6
17: 9.526665e+05      2   feasible  4 10     14
18: 1.829954e+07      1   feasible  3 11     14
19:          Inf      0   feasible  0 11     11
5.052800 minutes elapsed / 5.000000 limit
Target interval: 10.468714 12.423571 change: -0.069464 0.151588
Searching for /home/aayush/PeakSegPipeline-test/input/samples/*/*/problems/*/target.tsv files for training.
Found 2 target.tsv files for training.
Feature matrix:
     log.quartile.100% log.data
[1,]          4.110874 12.21546
[2,]          4.189655 12.95923
Target matrix:
         [,1]     [,2]
[1,] 10.32479 11.93616
[2,] 10.46871 12.42357
Learned regularization parameter and weights:
                          0
(Intercept)       0.3063770
log.quartile.100% 2.0027201
log.data          0.2121324
Train errors:
    status targets
1: correct       2
Writing model to /home/aayush/PeakSegPipeline-test/input/model.RData 
bash /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems.bed.sh 
Predicting penalty=68227.4830369895 log(penalty)=11.1306027397401 based on 2 features.
Writing /home/aayush/PeakSegPipeline-test/input/samples/Input/MS010302/problems/chr10:18024675-38818835/peaks.bed with 1 peak.
Predicting penalty=93540.9733726254 log(penalty)=11.4461548371764 based on 2 features.
Writing /home/aayush/PeakSegPipeline-test/input/samples/kidney/MS002201/problems/chr10:18024675-38818835/peaks.bed with 11 peaks.
12 total peaks form 10 overlapping peak clusters.
Found 11 labeled regions with no peaks out of 19 total.
Creating 21 joint segmentation problems for chr10:18024675-38818835
   1 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:32896236-33345739
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:32896236-33345739/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       7.401439          2      0
2:       7.401439      13.059217          1      0
3:      13.059217            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       7.401439          2      0
2:       7.401439      13.059217          1      0
3:      13.059217            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf            Inf      0
2:  group           -Inf            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:32896236-33345739/target.tsv
   2 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33345739-33692954
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33345739-33692954/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       13.64118          1      0
2:       13.64118            Inf          0      2
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       13.64118          1      0
2:       13.64118            Inf          0      2
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf       13.64118      0
2:  group           -Inf       13.64118      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33345739-33692954/target.tsv
   3 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33692954-33974944
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33692954-33974944/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.452378          1      1
2:       8.452378            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.452378          1      1
2:       8.452378            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       8.452378            Inf      0
2:  group       8.452378            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33692954-33974944/target.tsv
   4 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35182819-35261002
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35182819-35261002/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.622748          1      1
2:       8.622748            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.622748          1      1
2:       8.622748            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       8.622748            Inf      0
2:  group       8.622748            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35182819-35261002/target.tsv
   5 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35263958-35398170
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35263958-35398170/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.003164          2      2
2:       8.003164      12.664169          1      0
3:      12.664169            Inf          0      2
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.003164          2      2
2:       8.003164      12.664169          1      0
3:      12.664169            Inf          0      2
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       8.003164       12.66417      0
2:  group       8.003164       12.66417      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35263958-35398170/target.tsv
   6 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35398170-35588077
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35398170-35588077/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.399588          2      0
2:       8.399588      11.674657          1      0
3:      11.674657            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       8.399588          2      0
2:       8.399588      11.674657          1      0
3:      11.674657            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf            Inf      0
2:  group           -Inf            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35398170-35588077/target.tsv
   7 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:37975634-38107573
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:37975634-38107573/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       11.06583          1      1
2:       11.06583            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       11.06583          1      1
2:       11.06583            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       11.06583            Inf      0
2:  group       11.06583            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:37975634-38107573/target.tsv
   8 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38282232-38368734
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38282232-38368734/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       7.019403          2      1
2:       7.019403      12.515679          1      0
3:      12.515679            Inf          0      1
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       7.019403          2      1
2:       7.019403      12.515679          1      0
3:      12.515679            Inf          0      1
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       7.019403       12.51568      0
2:  group       7.019403       12.51568      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38282232-38368734/target.tsv
   9 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38379044-38391968
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38379044-38391968/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       10.48252          1      0
2:       10.48252            Inf          0      1
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       10.48252          1      0
2:       10.48252            Inf          0      1
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf       10.48252      0
2:  group           -Inf       10.48252      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38379044-38391968/target.tsv
  10 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38404897-38412091
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38404897-38412091/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf        10.2379          1      0
2:        10.2379            Inf          0      1
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf        10.2379          1      0
2:        10.2379            Inf          0      1
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf        10.2379      0
2:  group           -Inf        10.2379      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38404897-38412091/target.tsv
  11 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38416559-38444134
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38416559-38444134/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       5.129501          2      2
2:       5.129501       9.634116          1      1
3:       9.634116            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       5.129501          2      2
2:       5.129501       9.634116          1      1
3:       9.634116            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       9.634116            Inf      0
2:  group       9.634116            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38416559-38444134/target.tsv
  12 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38585584-38634852
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38585584-38634852/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       6.418148          2      2
2:       6.418148       7.327744          1      1
3:       7.327744            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       6.418148          2      2
2:       6.418148       7.327744          1      1
3:       7.327744            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       7.327744            Inf      0
2:  group       7.327744            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38585584-38634852/target.tsv
  13 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38643191-38650766
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38643191-38650766/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       9.887502          1      0
2:       9.887502            Inf          0      1
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       9.887502          1      0
2:       9.887502            Inf          0      1
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf       9.887502      0
2:  group           -Inf       9.887502      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38643191-38650766/target.tsv
  14 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38672352-38751115
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38672352-38751115/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       11.49933          1      0
2:       11.49933            Inf          0      1
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       11.49933          1      0
2:       11.49933            Inf          0      1
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf       11.49933      0
2:  group           -Inf       11.49933      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38672352-38751115/target.tsv
  15 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38751115-38790664
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38751115-38790664/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       7.012347          2      2
2:       7.012347       7.730969          1      1
3:       7.730969            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       7.012347          2      2
2:       7.012347       7.730969          1      1
3:       7.730969            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample       7.730969            Inf      0
2:  group       7.730969            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38751115-38790664/target.tsv
  16 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38807475-38814105
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38807475-38814105/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       6.220042          2      2
2:       6.220042       6.385140          1      1
3:       6.385140            Inf          0      0
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       6.220042          2      2
2:       6.220042       6.385140          1      1
3:       6.385140            Inf          0      0
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample        6.38514            Inf      0
2:  group        6.38514            Inf      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38807475-38814105/target.tsv
  17 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38815199-38816357
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38815199-38816357/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       6.454707          2      0
2:       6.454707       7.583618          1      1
3:       7.583618            Inf          0      2
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       6.454707          2      0
2:       6.454707       7.583618          1      1
3:       7.583618            Inf          0      2
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf       6.454707      0
2:  group           -Inf       6.454707      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38815199-38816357/target.tsv
  18 /   18 labeled joint problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38818375-38818835
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38818375-38818835/segmentations.RData 
Train error for samples:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       5.314800          2      0
2:       5.314800       6.157343          1      1
3:       6.157343            Inf          0      2
Train error for groups:
   min.log.lambda max.log.lambda complexity errors
1:           -Inf       5.314800          2      0
2:       5.314800       6.157343          1      1
3:       6.157343            Inf          0      2
Target intervals of minimum error penalty values:
    model min.log.lambda max.log.lambda errors
1: sample           -Inf         5.3148      0
2:  group           -Inf         5.3148      0
Writing target intervals to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38818375-38818835/target.tsv
$sample.target
           [,1]      [,2]
 [1,]      -Inf       Inf
 [2,]      -Inf 13.641178
 [3,]  8.452378       Inf
 [4,]  8.622748       Inf
 [5,]  8.003164 12.664169
 [6,]      -Inf       Inf
 [7,] 11.065834       Inf
 [8,]  7.019403 12.515679
 [9,]      -Inf 10.482518
[10,]      -Inf 10.237900
[11,]  9.634116       Inf
[12,]  7.327744       Inf
[13,]      -Inf  9.887502
[14,]      -Inf 11.499334
[15,]  7.730969       Inf
[16,]  6.385140       Inf
[17,]      -Inf  6.454707
[18,]      -Inf  5.314800

$group.target
           [,1]      [,2]
 [1,]      -Inf       Inf
 [2,]      -Inf 13.641178
 [3,]  8.452378       Inf
 [4,]  8.622748       Inf
 [5,]  8.003164 12.664169
 [6,]      -Inf       Inf
 [7,] 11.065834       Inf
 [8,]  7.019403 12.515679
 [9,]      -Inf 10.482518
[10,]      -Inf 10.237900
[11,]  9.634116       Inf
[12,]  7.327744       Inf
[13,]      -Inf  9.887502
[14,]      -Inf 11.499334
[15,]  7.730969       Inf
[16,]  6.385140       Inf
[17,]      -Inf  6.454707
[18,]      -Inf  5.314800

$features
      quartile.0% quartile.25% quartile.50% quartile.75% quartile.100%
 [1,]           0            3            7           12            66
 [2,]           0            4            8           19            64
 [3,]           0            3            5            9            31
 [4,]           0            1            3            5            24
 [5,]           0            4           12           22            63
 [6,]           0            3            6           11            44
 [7,]           0            1            4            8            38
 [8,]           0            3           12           23            82
 [9,]           0            4           11           21            53
[10,]           0            3            8           19            61
[11,]           0            2            4            8            29
[12,]           0            1            3            6            24
[13,]           0            5           12           23            44
[14,]           0            5           10           16            53
[15,]           0            1            2            5            23
[16,]           0            2            2            5            16
[17,]           1            1            9           13            20
[18,]           1           12           16           24            32
           mean        sd     mad  bases     sum  loss.0peaks   loss.1peak
 [1,]  9.468812  9.013826  5.9304 569478 2696140  -5.36147861  -6.80699375
 [2,] 11.591541 10.479198  7.4130 694430 4024757  -9.85300971 -11.98928411
 [3,]  5.642051  4.304096  4.4478 563980 1591002  -0.29782239  -0.30210829
 [4,]  3.830679  3.506995  2.9652 156366  299494   1.25935982   1.25935982
 [5,] 13.834180 10.885517 11.8608 268424 1856713 -13.13368098 -15.09537872
 [6,]  7.682739  6.526830  4.4478 379814 1459006  -3.00620980  -3.63087762
 [7,]  4.680148  4.854007  4.4478 263878  617494   0.55906198   0.55906198
 [8,] 14.413713 12.478591 13.3434 173004 1246815 -14.97412489 -17.74983817
 [9,] 13.174559 10.695903 11.8608  25848  170268 -12.88685894 -15.37533561
[10,] 12.402558 12.462948  7.4130  14388   89224  -9.90004317 -13.33634352
[11,]  5.336609  4.748351  4.4478  55150  147157   0.05080678  -0.49575626
[12,]  3.521172  3.445376  2.9652  98478  173379   1.21934577   1.17881323
[13,] 13.680132  9.979392 13.3434  15150  103627 -13.73307278 -16.16910799
[14,] 11.357300  8.581074  8.8956 157526  894535 -10.32249335 -11.50852312
[15,]  3.536550  3.352743  1.4826  79098  139867   0.91892246   0.88633150
[16,]  3.560633  3.131928  1.4826  13260   23607   0.21718494   0.06752974
[17,]  7.806563  5.975353  7.4130   2316    9040  -4.22208919  -6.35415795
[18,] 17.891304  7.461776  5.9304    920    8230 -22.42491766 -23.73404631
        loss.diff log+1.quartile.0% log+1.quartile.25% log+1.quartile.50%
 [1,] 1.445515137         0.0000000          1.7917595           2.890372
 [2,] 2.136274406         0.0000000          2.0794415           3.044522
 [3,] 0.004285903         0.0000000          1.7917595           2.484907
 [4,] 0.000000000         0.0000000          0.6931472           1.791759
 [5,] 1.961697734         0.0000000          2.0794415           3.496508
 [6,] 0.624667823         0.0000000          1.7917595           2.708050
 [7,] 0.000000000         0.0000000          0.6931472           2.197225
 [8,] 2.775713280         0.0000000          1.7917595           3.496508
 [9,] 2.488476670         0.0000000          2.0794415           3.401197
[10,] 3.436300353         0.0000000          1.7917595           3.218876
[11,] 0.546563043         0.0000000          1.3862944           2.197225
[12,] 0.040532537         0.0000000          0.6931472           1.791759
[13,] 2.436035206         0.0000000          2.4849066           3.496508
[14,] 1.186029772         0.0000000          2.3025851           3.295837
[15,] 0.032590956         0.0000000          0.6931472           1.098612
[16,] 0.149655194         0.0000000          1.0986123           1.098612
[17,] 2.132068765         0.6931472          0.6931472           2.890372
[18,] 1.309128644         0.6931472          3.1780538           3.806662
      log+1.quartile.75% log+1.quartile.100% log+1.mean log+1.sd log+1.mad
 [1,]           3.806662            6.802395   3.356555 3.197501 2.6045183
 [2,]           4.382027            6.590301   3.507111 3.318661 2.8452239
 [3,]           3.401197            5.583496   2.654479 2.287845 2.2868627
 [4,]           2.484907            5.123964   2.135106 2.025163 1.8186128
 [5,]           4.553877            6.664409   3.757122 3.400221 3.3410056
 [6,]           3.688879            6.200509   3.079464 2.825819 2.2868627
 [7,]           3.218876            5.968708   2.410531 2.448159 2.2868627
 [8,]           4.605170            7.037906   3.865225 3.591266 3.4634903
 [9,]           4.499810            6.352629   3.723533 3.373831 3.3410056
[10,]           4.499810            6.530878   3.819161 3.659926 3.0727682
[11,]           3.218876            5.429346   2.594595 2.413211 2.2868627
[12,]           2.708050            5.030438   1.968588 1.980197 1.8186128
[13,]           4.736198            5.953243   3.851769 3.263980 3.8092555
[14,]           3.806662            6.352629   3.473218 3.111474 3.0390845
[15,]           2.302585            5.036953   1.905029 1.950152 0.9093064
[16,]           1.791759            4.276666   1.746096 1.781790 0.9093064
[17,]           3.583519            4.564348   2.858625 2.604943 2.8452239
[18,]           4.890349            5.480639   4.232032 3.079146 2.6045183
      log+1.bases log+1.sum log+1.loss.0peaks log+1.loss.1peak log+1.loss.diff
 [1,]    25.11866  28.02125               NaN              NaN     0.901848521
 [2,]    25.51540  28.54844               NaN              NaN     1.143035601
 [3,]    25.09926  27.12418       -0.85729736       -0.8715279     0.004276745
 [4,]    22.53364  23.82211        0.97080667        0.9708067     0.000000000
 [5,]    23.61437  26.94623               NaN              NaN     1.106203695
 [6,]    24.30859  26.87844               NaN              NaN     0.495937095
 [7,]    23.58021  25.27760        0.48833929        0.4883393     0.000000000
 [8,]    22.73587  26.21093               NaN              NaN     1.348310633
 [9,]    18.93384  22.23826               NaN              NaN     1.249465157
[10,]    17.76228  21.23289               NaN              NaN     1.509135347
[11,]    20.44940  22.40303       -0.01170343       -1.1420574     0.445360822
[12,]    21.60892  22.57946        0.89389339        0.8683355     0.040110875
[13,]    17.86548  21.34331               NaN              NaN     1.257368333
[14,]    22.54842  25.53827               NaN              NaN     0.782087009
[15,]    21.17064  21.95136        0.64152498        0.6076752     0.032071135
[16,]    17.59902  17.75750       -0.11998147       -0.4564865     0.139462066
[17,]    14.11063  16.26504               NaN              NaN     1.395949793
[18,]    12.26680  16.17457               NaN              NaN     0.984153238
      log.quartile.0% log.quartile.25% log.quartile.50% log.quartile.75%
 [1,]            -Inf        0.6931472        2.3025851         3.465736
 [2,]            -Inf        1.0986123        2.4849066         4.094345
 [3,]            -Inf        0.6931472        1.7917595         2.995732
 [4,]            -Inf             -Inf        0.6931472         1.791759
 [5,]            -Inf        1.0986123        2.9957323         4.276666
 [6,]            -Inf        0.6931472        2.0794415         3.332205
 [7,]            -Inf             -Inf        1.3862944         2.772589
 [8,]            -Inf        0.6931472        2.9957323         4.330733
 [9,]            -Inf        1.0986123        2.8903718         4.219508
[10,]            -Inf        0.6931472        2.7725887         4.248495
[11,]            -Inf        0.0000000        1.3862944         2.772589
[12,]            -Inf             -Inf        0.6931472         2.079442
[13,]            -Inf        1.7917595        2.9957323         4.499810
[14,]            -Inf        1.3862944        2.7725887         3.332205
[15,]            -Inf             -Inf             -Inf         1.386294
[16,]            -Inf             -Inf             -Inf             -Inf
[17,]            -Inf             -Inf        2.0794415         3.091042
[18,]            -Inf        2.3978953        3.3322045         4.682131
      log.quartile.100%  log.mean    log.sd   log.mad log.bases  log.sum
 [1,]          6.725034 2.9025949 2.6712114 1.8862069  25.11866 28.02125
 [2,]          6.496775 3.0330399 2.7815564 2.1738890  25.51540 28.54844
 [3,]          5.455321 2.0249225 1.5150354 1.4807418  25.09925 27.12418
 [4,]          4.962845 1.2884777 1.1217928 0.7875946  22.53362 23.82209
 [5,]          6.579251 3.3318762 2.8950941 2.7335048  23.61435 26.94623
 [6,]          6.104793 2.5698604 2.2351557 1.4807418  24.30858 26.87844
 [7,]          5.863631 1.6973994 1.7427487 1.4807418  23.58019 25.27759
 [8,]          6.962243 3.4750763 3.1268216 2.8670361  22.73585 26.21092
 [9,]          6.253829 3.3045353 2.8618715 2.7335048  18.93368 22.23822
[10,]          6.436150 3.4708289 3.2345732 2.5793541  17.76201 21.23283
[11,]          5.288267 1.9536727 1.6903575 1.4807418  20.44933 22.40300
[12,]          4.852030 0.9705472 1.0291882 0.7875946  21.60888 22.57943
[13,]          5.828946 3.4780388 2.7195857 3.4266519  17.86522 21.34326
[14,]          6.253829 2.9898672 2.5551355 2.3970325  22.54840 25.53826
[15,]          4.867534 0.7807230 0.9847022      -Inf  21.17059 21.95131
[16,]          4.007333 0.1583256 0.5925280      -Inf  17.59872 17.75705
[17,]          4.317488 2.1553572 1.8802431 2.1738890  14.10890 16.26426
[18,]          5.332719 3.9113367 2.5861121 1.8862069  12.26245 16.17379
      log.loss.0peaks log.loss.1peak log.loss.diff log.log.quartile.0%
 [1,]             NaN            NaN   -3.98250942                 NaN
 [2,]             NaN            NaN          -Inf                 NaN
 [3,]             NaN            NaN          -Inf                 NaN
 [4,]      -0.9657083     -0.9657083          -Inf                 NaN
 [5,]             NaN            NaN   -2.79421042                 NaN
 [6,]             NaN            NaN   -4.05310053                 NaN
 [7,]      -2.6514948     -2.6514948          -Inf                 NaN
 [8,]             NaN            NaN   -2.58758884                 NaN
 [9,]             NaN            NaN          -Inf                 NaN
[10,]             NaN            NaN   -2.44740186                 NaN
[11,]             NaN            NaN   -4.23427488                 NaN
[12,]      -1.4903966     -1.5890081   -7.84006559                 NaN
[13,]             NaN            NaN   -2.52422049                 NaN
[14,]             NaN            NaN          -Inf                 NaN
[15,]             NaN            NaN          -Inf                 NaN
[16,]             NaN            NaN          -Inf                 NaN
[17,]             NaN            NaN   -0.09789951                 NaN
[18,]             NaN            NaN   -1.00398399                 NaN
      log.log.quartile.25% log.log.quartile.50% log.log.quartile.75%
 [1,]                 -Inf           0.10937207           1.05873363
 [2,]                 -Inf           0.21668516           1.32286315
 [3,]                 -Inf          -0.27246509           0.80251926
 [4,]                  NaN                 -Inf          -0.27246509
 [5,]                 -Inf           0.46751952           1.38801939
 [6,]                 -Inf          -0.03987866           0.99236407
 [7,]                  NaN          -0.73302584           0.65326852
 [8,]                 -Inf           0.46751952           1.40655256
 [9,]                 -Inf           0.42068209           1.36804578
[10,]                 -Inf           0.65326852           1.44630678
[11,]                 -Inf          -0.73302584           0.65326852
[12,]                  NaN                 -Inf          -0.03987866
[13,]           -0.2724651           0.46751952           1.53727013
[14,]                 -Inf           0.36558645           0.60390886
[15,]                  NaN                  NaN                 -Inf
[16,]                  NaN                  NaN                  NaN
[17,]                  NaN                 -Inf           0.50807846
[18,]                 -Inf           0.60390886           1.64458321
      log.log.quartile.100% log.log.mean log.log.sd log.log.mad log.log.bases
 [1,]              2.400289   0.63758113  0.3535608 -0.53152697      5.060927
 [2,]              2.311043   0.57594231  0.3035951 -0.35525410      5.092270
 [3,]              2.003324  -0.02491459 -0.5870303 -0.84854843      5.059382
 [4,]              1.816530  -0.90705816 -1.1610014 -1.86383792      4.843722
 [5,]              2.349794   0.78374472  0.4446976 -0.08189306      4.937415
 [6,]              2.223416   0.42314488  0.1095084 -0.84854843      4.995364
 [7,]              2.148290  -0.33222748 -0.3166700 -0.84854843      4.934520
 [8,]              2.452400   0.91839978  0.6205695 -0.02639040      4.861591
 [9,]              2.247261   0.80064974  0.4150564 -0.08189306      4.495591
[10,]              2.295504   1.03942720  0.7701413  0.48376252      4.367829
[11,]              1.935977  -0.05659029 -0.3928485 -0.84854843      4.649606
[12,]              1.751881  -2.65368012 -1.5815820 -1.86383792      4.759915
[13,]              2.094299   0.96834119  0.2713125  0.93339644      4.379417
[14,]              2.247261   0.53711439  0.2252741 -0.23715548      4.845034
[15,]              1.775971          NaN -1.6427131         NaN      4.718932
[16,]              1.350476          NaN        NaN         NaN      4.349358
[17,]              1.472114  -0.62120489 -0.5818403 -0.35525410      3.907317
[18,]              1.929982   1.19861662  0.4851638 -0.53152697      3.626790
      log.log.sum log.log.loss.0peaks log.log.loss.1peak log.log.loss.diff
 [1,]    5.278539                 NaN                NaN               NaN
 [2,]    5.314350                 NaN                NaN               NaN
 [3,]    5.214286                 NaN                NaN               NaN
 [4,]    4.954853                 NaN                NaN               NaN
 [5,]    5.198161                 NaN                NaN               NaN
 [6,]    5.195666                 NaN                NaN               NaN
 [7,]    5.073523                 NaN                NaN               NaN
 [8,]    5.143062                 NaN                NaN               NaN
 [9,]    4.813254                 NaN                NaN               NaN
[10,]    4.723169                 NaN                NaN               NaN
[11,]    4.832022                 NaN                NaN               NaN
[12,]    4.846488                 NaN                NaN               NaN
[13,]    4.731741                 NaN                NaN               NaN
[14,]    5.090844                 NaN                NaN               NaN
[15,]    4.788189                 NaN                NaN               NaN
[16,]    4.352306                 NaN                NaN               NaN
[17,]    4.182163                 NaN                NaN               NaN
[18,]    4.172674                 NaN                NaN               NaN

   1 /    1 problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835
Skipping since jointTargets.rds exists.
Training sample model using 16 finite targets.
Train errors:
    status targets
1: correct      16
Training group model using 16 finite targets.
Train errors:
    status targets
1: correct      16
Saved /home/aayush/PeakSegPipeline-test/input/joint.model.RData
Saved 1 jobProblems.bed files to /home/aayush/PeakSegPipeline-test/input/jobs
bash /home/aayush/PeakSegPipeline-test/input/jobs/1/jobPeaks.sh 
   1 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:32896236-33345739
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:32896236-33345739/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:32896236-33345739/peakInfo.rds
   2 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33345739-33692954
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33345739-33692954/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33345739-33692954/peakInfo.rds
   3 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33692954-33974944
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33692954-33974944/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:33692954-33974944/peakInfo.rds
   4 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35182819-35261002
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35182819-35261002/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35182819-35261002/peakInfo.rds
   5 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35263958-35398170
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35263958-35398170/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35263958-35398170/peakInfo.rds
   6 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35398170-35588077
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35398170-35588077/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35398170-35588077/peakInfo.rds
   7 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35678933-35959343
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35678933-35959343/segmentations.RData 
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:35678933-35959343/peakInfo.rds
   8 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:37975634-38107573
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:37975634-38107573/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:37975634-38107573/peakInfo.rds
   9 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38107573-38175941
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38107573-38175941/segmentations.RData 
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38107573-38175941/peakInfo.rds
  10 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38203545-38282232
Found 2 samples to jointly segment.
Writing segmentation and features to /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38203545-38282232/segmentations.RData 
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38203545-38282232/peakInfo.rds
  11 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38282232-38368734
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38282232-38368734/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38282232-38368734/peakInfo.rds
  12 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38379044-38391968
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38379044-38391968/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38379044-38391968/peakInfo.rds
  13 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38404897-38412091
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38404897-38412091/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38404897-38412091/peakInfo.rds
  14 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38416559-38444134
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38416559-38444134/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38416559-38444134/peakInfo.rds
  15 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38585584-38634852
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38585584-38634852/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38585584-38634852/peakInfo.rds
  16 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38643191-38650766
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38643191-38650766/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38643191-38650766/peakInfo.rds
  17 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38672352-38751115
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38672352-38751115/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38672352-38751115/peakInfo.rds
  18 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38751115-38790664
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38751115-38790664/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38751115-38790664/peakInfo.rds
  19 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38807475-38814105
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38807475-38814105/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38807475-38814105/peakInfo.rds
  20 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38815199-38816357
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38815199-38816357/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38815199-38816357/peakInfo.rds
  21 /   21 joint prediction problems /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38818375-38818835
Loading model from /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38818375-38818835/segmentations.RData
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/jointProblems/chr10:38818375-38818835/peakInfo.rds
               problem.name              jprob.name chrom peakStart  peakEnd
 1: chr10:18024675-38818835 chr10:32896236-33345739 chr10  33184016 33225822
 2: chr10:18024675-38818835 chr10:33345739-33692954 chr10  33465652 33619573
 3: chr10:18024675-38818835 chr10:35263958-35398170 chr10  35292981 35378194
 4: chr10:18024675-38818835 chr10:35678933-35959343 chr10  35772403 35865870
 5: chr10:18024675-38818835 chr10:38107573-38175941 chr10  38113867 38144904
 6: chr10:18024675-38818835 chr10:38203545-38282232 chr10  38233526 38263507
 7: chr10:18024675-38818835 chr10:38282232-38368734 chr10  38300958 38354116
 8: chr10:18024675-38818835 chr10:38379044-38391968 chr10  38384460 38387399
 9: chr10:18024675-38818835 chr10:38404897-38412091 chr10  38405366 38407503
10: chr10:18024675-38818835 chr10:38643191-38650766 chr10  38646902 38648615
11: chr10:18024675-38818835 chr10:38672352-38751115 chr10  38696463 38737802
12: chr10:18024675-38818835 chr10:38815199-38816357 chr10  38815694 38816169
13: chr10:18024675-38818835 chr10:38818375-38818835 chr10  38818438 38818533
    peak.mean.vec sample.loss.diff.vec background.mean.vec sample.peaks.vec
 1:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 2:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 3:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 4:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 5:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 6:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 7:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 8:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
 9:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
10:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
11:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
12:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
13:   <dgeMatrix>          <dgeMatrix>         <dgeMatrix>      <lgCMatrix>
    group.peaks.vec sample.loss.diff group.loss.diff
 1:     <lgCMatrix>      469402.8408     469402.8408
 2:     <lgCMatrix>      840017.2769     840017.2769
 3:     <lgCMatrix>      316212.3633     316212.3633
 4:     <lgCMatrix>      431388.2415     431388.2415
 5:     <lgCMatrix>      116432.4069     116432.4069
 6:     <lgCMatrix>      159700.6204     159700.6204
 7:     <lgCMatrix>      272577.6594     272577.6594
 8:     <lgCMatrix>       35686.1668      35686.1668
 9:     <lgCMatrix>       27942.3831      27942.3831
10:     <lgCMatrix>       19682.8277      19682.8277
11:     <lgCMatrix>       98650.0767      98650.0767
12:     <lgCMatrix>        2601.4151       2601.4151
13:     <lgCMatrix>         675.4956        675.4956
bash /home/aayush/PeakSegPipeline-test/input/peaks_matrix.tsv.sh 
Reading predicted peaks in 1 jobPeaks.RData files.
Read 8 labels.
Read 21 joint problems, plotting 3 in chunk.
Read 2 samples of coverage.
Read 2 samples of separate peak predictions.
Read joint peak predictions: 2 peaks in 2 genomic regions, 3 peakInfo.RData files.
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/chunks/chr10:33061897-33974942/figure-predictions.png
Read 6 labels.
Read 21 joint problems, plotting 3 in chunk.
Read 2 samples of coverage.
Read 1 samples of separate peak predictions.
Read joint peak predictions: 1 peaks in 1 genomic regions, 3 peakInfo.RData files.
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/chunks/chr10:35182820-35398459/figure-predictions.png
Read 10 labels.
Read 21 joint problems, plotting 7 in chunk.
Read 2 samples of coverage.
Read 1 samples of separate peak predictions.
Read joint peak predictions: 5 peaks in 5 genomic regions, 7 peakInfo.RData files.
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/chunks/chr10:38041023-38444133/figure-predictions.png
Read 8 labels.
Read 21 joint problems, plotting 4 in chunk.
Read 2 samples of coverage.
Read 1 samples of separate peak predictions.
Read joint peak predictions: 2 peaks in 2 genomic regions, 4 peakInfo.RData files.
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/chunks/chr10:38585584-38790663/figure-predictions.png
Read 6 labels.
Read 21 joint problems, plotting 3 in chunk.
Read 2 samples of coverage.
Read 0 samples of separate peak predictions.
Read joint peak predictions: 4 peaks in 2 genomic regions, 3 peakInfo.RData files.
Writing /home/aayush/PeakSegPipeline-test/input/problems/chr10:18024675-38818835/chunks/chr10:38807475-38819342/figure-predictions.png
bedGraphToBigWig /home/aayush/PeakSegPipeline-test/input/samples/Input/MS010302/joint_peaks.bedGraph hg19_chromInfo.txt /home/aayush/PeakSegPipeline-test/input/samples/Input/MS010302/joint_peaks.bigWig 
bedGraphToBigWig /home/aayush/PeakSegPipeline-test/input/samples/kidney/MS002201/joint_peaks.bedGraph hg19_chromInfo.txt /home/aayush/PeakSegPipeline-test/input/samples/kidney/MS002201/joint_peaks.bigWig 
bedToBigBed  /home/aayush/PeakSegPipeline-test/input/all_labels-short.bed hg19_chromInfo.txt /home/aayush/PeakSegPipeline-test/input/all_labels.bigBed 
bedToBigBed  /home/aayush/PeakSegPipeline-test/input/problems-short.bed hg19_chromInfo.txt /home/aayush/PeakSegPipeline-test/input/problems.bigBed 
bedToBigBed  /home/aayush/PeakSegPipeline-test/input/jointProblems-short.bed hg19_chromInfo.txt /home/aayush/PeakSegPipeline-test/input/jointProblems.bigBed 
bedToBigBed  /home/aayush/PeakSegPipeline-test/input/peaks_summary-short.bed hg19_chromInfo.txt /home/aayush/PeakSegPipeline-test/input/peaks_summary.bigBed 
Created http://hubs.hpc.mcgill.ca/~thocking/PeakSegFPOP-/hub.txt
> 
> 
