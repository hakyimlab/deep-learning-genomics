# deep-learning-genomics
Summer immersion syllabus in deep learning in genomics

- [ ] update using https://hakyimlab.notion.site/Syllabus-of-Deep-Learning-in-Genomics-d1c308f6fc2d4e54ae9e19e492671e2a?pvs=4

## Organizers/Instructors
- Hae Kyung Im
- Ravi Madduri

## Students
- Srusti Donapati - (Uchicago - rising second year College - Katen Scholar 2023)
- Rachel Rodriguez - (Uchicago - rising second year College - Metcalf fellowship 2023)
- Sabrina Mi - (UCSD - rising second year Math PhD - R01AA029688)
- Tiffany Huang - (UChicago - rising third year College - BSD Quantitative Biology Fellowship 2023)
- Laura Vairus (Harvey Mudd College, rising 2nd year)
- Dante Vairus (UChicago Lab School - rising 12th year)

## Learning Objectives

## Syllabus

[Draft Syllabus](https://hakyimlab.notion.site/Syllabus-of-Deep-Learning-in-Genomics-d1c308f6fc2d4e54ae9e19e492671e2a?pvs=4)

Welcome to our intensive 8-week course on deep learning in genomics. 

In the first 6 weeks, you will learn essential concepts and tools to conduct computational genomic experiments.

For the last 2 weeks, you will conduct a capstone project, where you will apply your newly acquired skills to a real-world project. This involves:

- Identifying a scientific question
- Collecting and preprocessing genomic data
- Conducting experiments and training deep learning models
- Answering the identified question
- Presenting the findings to the team
- Preparing a report following a research paper format

Get ready to explore the fascinating intersection of deep learning and genomics.

The syllabus will change as we will customize it to the needs of the team.

## Concepts
- Central dogma of molecular biology
- DNA, RNA, proteins
- transcription, splicing, translation
- gene regulation
- GWAS
- Transcription factors (TFs)
- Promoters, Enhancers
- Chromatin structure
- Histone modifications
- DNA methylation
- genetic variation, SNP, structural variation
- Selection
- Coalescence and DNA sequence conservation
- linking variation to function

- linux file system navigation
- environmental variables (PATH, SHELL)
- 

## Tool list
    
- Vscode
- Code
- Conda
- Pip
- Numpy
- GitHub 
- Jupyter notebook
- PyTorch 
- Linux
    

[Cheatsheets](https://www.notion.so/Cheatsheets-664ee29b94e5440b81305a9d7cfe6893?pvs=21)

## Week 1: Intro and Logistics

### Day 1

- Take the [chatgpt prompt engineering class](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
- Learn basics of Linux command line
    - Play this game to practice your new command line skills (1.5 hr)
    
    [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html)
    
- Learn basics of RStudio ([download R and RStudio](https://posit.co/download/rstudio-desktop/))
- Discuss what you learned
- What we did
    
    watched module
    

### Day 2

- Read “[LLM in Molecular Biology](https://towardsdatascience.com/large-language-models-in-molecular-biology-9eb6b65d8a30).” There is a lot of information packed in this survey. Don’t worry if you don’t understand much for now.
- Discuss how much you understood, make a list of concepts that you did not understand.
- Create a blog post summarizing what you learned from the article with Quarto and RStudio using this [tutorial](https://quarto.org/docs/websites/website-blog.html) (you can use ChatGPT) ([download Quarto](https://quarto.org/docs/download/))
- Publish blog to [Quarto Pub](https://quartopub.com)
- What we did
    
    Read article, made a blog summary of it using Quarto Blog on RStudio and published it with [Quarto Pub](https://quartopub.com) following [tutorials](https://quarto.org/docs/websites/website-blog.html) on quarto website
    

### Day 3 June 7, 2023

- Learn how to create and work with Git and GitHub repositories
- publish blog from Day 2 on GitHub using this [tutorial](https://quarto.org/docs/publishing/github-pages.html)
- create a pro user and use co-pilot in github
- if time:
    - Learn how to use VSCode
- What we did
    
    spent the whole time fixing errors on Github, didn’t get to VSCode, recommend having professor more available for questions
    

![git_2x.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bb89edb1-7eea-4c68-8684-4115228c27a8/git_2x.png)

### Day 4 June 8, 2023

- Install VSCode and watch [tutorial](https://www.youtube.com/watch?v=VqCgcpAypFQ)
- Learn basics of Python at https://groklearning.com/
- Install miniconda [here](https://docs.conda.io/en/latest/miniconda.html) (macOS installers)
    - start a blog post on what conda is
- Python - numpy https://www.w3schools.com/python/numpy/numpy_intro.asp
- Complete PyTorch tutorials on tensor, autograd, neural networks, and CIFAR10
    
    [basics of matrix algebra using numpy](https://www.notion.so/basics-of-matrix-algebra-using-numpy-b6712e33edd941ce80dd08c482e1b765?pvs=21)
    
    - watch the short video and follow the tutorial using the colab notebook https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html
- What we did
    
    Learned basics of using Visual Studio Code.
    
    Learned and teached each pther basics of python
    
    Installed conda and environment with much effort and confusion
    
    - Checkpoints: make a blog on how to use Conda, install conda
        
        find what path your python is in (which python)
        
        make env (conda create —name envname)
        
        activate env (conda activate envname)
        
        install python in new env (conda install python)
        
         (conda install pip)
        
        install python packages with pip (python -m pip install packagename)
        
        deactivate env (conda deactivate) → returns to default env
        
    
    Learned and taught each other basics of python
    
    split off and practiced python, made tutorial blogs, and started pytorch 
    
    Tiffanie: finished article, matrix algebra exercises
    

### Day 5

- Learn about OOP (classes, etc.) and dictionaries and files
- Complete PyTorch tutorials on tensor, autograd, neural networks, and CIFAR10
    - watch the short video and follow the tutorial using the colab notebook https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html
- Update Blog with New Page (Day 3/4 materials) & Publish to Github + Quarto
- Get GitHub Copilot
- Notes
    - what is PATH? PATH is en env variable in linux (most env var are all caps)
        - shows you path values; order in which it tries to find program
        - if you want to see the value of path write `echo $PATH`
    - add Code
    - cd / (goes to Macintosh HD all the way to root)
    - exercise: what’s the path to VSCode?
    - for fututre classes of this: make a learning objectives, a preclass quiz, final quiz everyday
- what we did
    
    how to install VSCode
    
    - download your version of vscode here https://code.visualstudio.com/download
    - move VSCode to applications folder MacintoshOS/Applications
    - open VSCode
    
    spent a lot of time and effort trying to understand how to download things right.
    
    Rachel: Classes lesson + exercises, NumPy exercises + NumPy Cheatsheet, VSCode installation and Files system, Files and Dictionaries exercises (VSCode), started PyTorch tutorial
    
    Laura: made file and dictionary tutorial, did matrix tutorial
    
    Tiffanie: files review, published LLM summary on github pages, finished matrix algebra exercises, tensor demo
    
    Srusti: Learned about classes + exercises, NumPy matrix exercises, VSCode installation + files system
    

## Week 2

### Day 6

- Learn what a GWAS is
    - GWAS instructions
        
        ## Instructions
        
        - [ ]  Read and summarize in a few sentences this GWAS tutorial paper https://onlinelibrary.wiley.com/doi/10.1002/mpr.1608
        - [ ]  Download plink from [LINK](https://www.cog-genomics.org/plink/1.9/) (choose the one corresponding to your operating system. If running on posit.cloud, you should choose the linux version even if you are accessing posit from a different operating system)
        - [ ]  Create a github user if you don’t already have one
        - [ ]  Git clone the tutorial from the command line (run `git clone <https://github.com/MareesAT/GWA_tutorial.git`> on the terminal). You will need to unzip files that look like *.zip
        - [ ]  run the QC and Association components of the tutorial
            - 1_Main_script_QC_GWAS.txt and 3_Main_script_association_GWAS.txt
                - you may want to download the hapmap data from here https://uchicago.box.com/s/hawatrohw6fthytguaww83njrf5i6ace
            - you may need to download plink (https://www.cog-genomics.org/plink/1.9/)
            - The tutorial is designed so that you need to run all the steps but since   2_Population_stratification.txt is quite computationally time consuming, you can skip it and just download the files you need to run associations here https://uchicago.box.com/s/ux2xkab6zhth0csazixqoj98xtjh7h0x
        
        <aside>
        ☝🏽 Some modifications to the code may be needed. Use them if you encounter errors.
        
        </aside>
        
        - Notes
        
        Relatedness.R needs to change lines 7 and 15 to
        
        ```
        legend(1,1, xjust=1, yjust=1, legend=levels(factor(relatedness$RT)), pch=16, col=c(4,3))
        legend(0.02,1, xjust=1, yjust=1, legend=levels(factor(relatedness$RT)), pch=16, col=c(4,3))
        
        ```
        
        line 31 of 2_Main_script_MDS.txt replace
        
        ```bash
        plink --bfile ALL.2of4intersection.20100804.genotypes --set-missing-var-ids @:#[b37]\$1,\$2 --make-bed --out ALL.2of4intersection.20100804.genotypes_no_missing_IDs
        ```
        
        with
        
        ```bash
        plink --bfile ALL.2of4intersection.20100804.genotypes --set-missing-var-ids '@:#[b37]$1,$2' --make-bed --out ALL.2of4intersection.20100804.genotypes_no_missing_IDs
        ```
        
        line 144 in 2_Main_script_MDS.txt replace 
        
        ```bash
        (base) haekyungim@Im-Lab-016 1_QC_GWAS % cat race_1kG14.txt racefile_own.txt | sed -e '1i\FID IID race' > racefile.txt
        sed: 1: "1i\FID IID race
        ": extra characters after \ at the end of i command
        (base) haekyungim@Im-Lab-016 1_QC_GWAS % cat race_1kG14.txt racefile_own.txt | sed -e '1i\
        FID IID race' > racefile.txt
        ```
        
        install qqman in R and comment out first line on Manhattan_plot.R and QQ_plot.R
        
        ```bash
        ##install.packages("qqman",repos="http://cran.cnr.berkeley.edu/",lib="~" ) # location of installation can be changed but has to correspond with the library location 
        ##library("qqman",lib.loc="~")  
        library("qqman")
        ```
        
        ## Questions
        
        Using the output from the tutorial or using the commands you learned from it, answer the following questions. Show the command you used to create the result.
        
        1. How many individuals are in the genotype file you downloaded? (5 pts)
        2. Explain the contents of ``.fam, ``.bim, ``.bed files (5 pts)
        3. Write the captions for the pdf's generated by the commands in 1_Main_script_QC_GWAS.txt and 3_Main_script_association_GWAS (5 pts per figure caption)
        4. Discuss what you did and the results you obtained. (20 pts)
        
    - Run a GWAS, use these instructions
    
    https://bios25328.hakyimlab.org/post/2021/04/09/lab-2-gwas-in-practice/
    
- Start Karpathy's "Zero to Hero" course
    
    [Syllabus zero to hero](https://www.notion.so/Syllabus-zero-to-hero-690fd0fb557b4fccae2c4aefac3e6c84?pvs=21)
    
- installing plink (use zsh for your terminal)
    - download plink online https://www.cog-genomics.org/plink/
    - move plink file (not folder, you can leave the rest of the stuff) to bin folder (make a folder called bin in your home directory)
    - stand in that bin in terminal
    - make plink executable: `chmod +x plink`
    - if it doesn’t let you open it just go to the plink in Finder
    - `nano ~/.zshrc'
    - `more`
    - `less`
    - `cat`
    - only put programs in bin
- Questions
    
    What does the tutorial (1_QC_GWAS) mean when it says “cases” in the following instruction: “This second HWE step only focusses on cases because in the controls all SNPs with a HWE p-value < hwe 1e-6 were already removed”?
    
- what we did
    
    Rachel: installed plink, worked on main script QC GWAS tutorial (genetic QC)
    

### Day 7

- 
- 

### Day 8

- Take quantatative genomic training class
- Learn how to login to the HPC cluster
- Learn how to run enformer usage and training notebooks
- Learn how to visualize data with Python's Matplotlib library

### Day 9

- Learn how to visualize data with R's ggplot library
- Learn basics of Quarto blogging
- Create a new blog post

### Day 10

- Complete "LLM in Molecular Biology" article
- Take Deep Learning for Genomics quiz
- Learn how to summarize research papers
- Learn how to create multiple choice questions from research papers

## Week 3

### Day 11

- Run Temi's pipeline (PrediXcan 1.7)
- Train predictors of new tracks (TF binding, single cell expression)
- Learn how to interpret enformer results, models, and attention

### Day 12

- 

### Day 13

- 

### Day 14

- Create post-lesson Google Forms

### Day 15

- Learn how to create and work with Jupyter Notebooks
- Learn how to use Pandas for data manipulation

## Week 4

### Day 16

- Learn how to use Seaborn for data visualization
- Complete Seaborn tutorial on Kaggle
- Learn the basics of statistical analysis

### Day 17

- Learn how to use Weights & Biases for experiment tracking

### Day 18

- 

### Day 19

- 

### Day 20

- 

## Week 5

### Day 21

- 

### Day 22

- 

### Day 23

- 

### Day 24

- 

### Day 25

## Week 6

### Day 26

- 

### Day 27

- 

### Day 28

- 

### Day 29

- 

### Day 30

- 

## Select capstone project

- predict methylation from DNA sequence
- 
- train personalized Enformer
- setup llamaindex to allow summarization and question answering with custom text or papers
- reproduce/implement scGPT
- train additional epigenetic features
- run https://github.com/kundajelab/bpnet and compare to TFPred
- analyze TF binding matrix predicted by Enformer, interpret, attention links?
- visualize Enformer output to facilitate interpretation

- (Dante) predict epigenome in Neanderthals
- (Sabrina) train predictors of rat transcriptome
- 

## Week 7 (Capstone Project)

### Day 31

- 

### Day 32

- 

### Day 33

- 

### Day 34

- 

### Day 35

## Week 8 (Capstone Project cont.)

### Day 36

- 

### Day 37

- 

### Day 38

- 

### Day 39

- 

### Day 40

- 

[https://hakyimlab.notion.site/Homework-3-run-a-GWAS-685b2d3b16e1485d913500739a99eb58?pvs=4](https://www.notion.so/685b2d3b16e1485d913500739a99eb58?pvs=21)
