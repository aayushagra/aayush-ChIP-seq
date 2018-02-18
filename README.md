# aayush-ChIP-seq
```
aayush@aayush-VirtualBox:~$ R -e 'source("https://raw.githubusercontent.com/tdhock/PeakSegPipeline/master/tests/testthat/test-pipeline-input.R")'

R version 3.2.3 (2015-12-10) -- "Wooden Christmas-Tree"
Copyright (C) 2015 The R Foundation for Statistical Computing
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

source("https://raw.githubusercontent.com/tdhock/PeakSegPipeline/master/tests/testthat/test-pipeline-input.R")

Loading required package: httr
chr10	33061000	33061017	0.3256
chr10	33061017	33061022	0.2442
chr10	33061022	33061029	0.1628
chr10	33061029	33061061	0.2442
chr10	33061061	33061079	0.3256
chr10	33061079	33061083	0.2442
chr10	33061083	33061100	0.3256
chr10	33061100	33061129	0.2442
chr10	33061129	33061130	0.1628
chr10	33061130	33061151	0.2442
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
head: cannot open '/home/aayush/PeakSegPipeline-test/non-integer/samples/Input/MS010302/problems/chr10:18024675-38818835/coverage.bedGraph' for reading: No such file or directory
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
chr10	33061000	33061017	4
chr10	33061017	33061022	3
chr10	33061022	33061029	2
chr10	33061029	33061061	3
chr10	33061061	33061079	4
chr10	33061079	33061083	3
chr10	33061083	33061100	4
chr10	33061100	33061129	3
chr10	33061129	33061130	2
chr10	33061130	33061151	3
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
Next = 0, Inf mc.cores= 2 
terminate called after throwing an instance of 'dbstl::InvalidArgumentException'
  what():  Db*: Db and DbEnv object must be constructed with DB_CXX_NO_EXCEPTIONS flag set.
   penalty peaks   status fp fn errors
1:     Inf     0 feasible  0  2      2
0.052822 minutes elapsed / 5.000000 limit
Target interval: -Inf Inf change: NaN NaN
Next = 0, Inf mc.cores= 2 
terminate called after throwing an instance of 'dbstl::InvalidArgumentException'
  what():  Db*: Db and DbEnv object must be constructed with DB_CXX_NO_EXCEPTIONS flag set.
   penalty peaks   status fp fn errors
1:     Inf     0 feasible  0 11     11
0.048131 minutes elapsed / 5.000000 limit
Target interval: -Inf Inf change: NaN NaN
Searching for /home/aayush/PeakSegPipeline-test/input/samples/*/*/problems/*/target.tsv files for training.
Found 2 target.tsv files for training.
Error in array(x, c(length(x), 1L), if (!is.null(names(x))) list(names(x),  : 
  'data' must be of a vector type, was 'NULL'
Calls: source ... as.matrix -> as.matrix -> as.matrix.default -> array
Execution halted
aayush@aayush-VirtualBox:~$ 
```
