# How to Debug Code - An Overview

Every coder makes mistakes, and finding out why code isn't working (or not working as intended) can be time consuming. This course tries to introduce tools and methods to help users with debugging and potentially optimising their code. It introduces common pitfalls of different languages and provides practical exercises in which bugs have to be found and fixed. It is completely modular, each day a different language will be introduced and tools and specifics for that language presented. Due to the structure of the course, there might be overlapping information between the individual days as each day focuses on one particular language.
The course is designed for students and researchers who have a basic background in programming (i.e. they should be familiar with concepts like variables, loops, if/then/else and functions), but are either new to a language or are starting their first projects. More specific requirements (including required software) will be listed for each day. 

See the [course page](https://scicomp.aalto.fi/training/scip/debugging-2022/) for more information.

## Parts of the Course

### Day 1: Debugging in Python (Presenter: Simppa Äkäslompolo)

**Prerequesites**:  
Basic knowledge of the python language and a working python installation to try the tricks on.

**Content**:  
We first recapitulate a few key features of the python language. After that we take a look at the python specific tools to help analyse a python program. We conclude with a few words on how to avoid problems.

The course material is being written into the github page [python-debugging](https://aaltoscicomp.github.io/python-debugging/).


### Day 2: Debugging in Matlab (Presenter: Thomas Pfau)

**Prerequesites**:  
Software: Installed Matlab 2021b including the Mapping toolbox.  
Skills: Basic understanding of Matlab (Essentially what is taught in our Matlab Basics Course [here](https://version.aalto.fi/gitlab/eglerean/matlabcourse/-/tree/master/AY20212022/MatlabBasics2021))

**Content**:  
This module will give an overview of basic matlab concepts, common errors (and error-messages) how to read and interpret these error messages and provides a variety of exercises to allow you to use the tools introduced and get some experience with them. 

Materials: [Matlab-Debugging-Exercises](https://github.com/AaltoSciComp/Matlab-Debugging-Exercises)

### Day 3: Debugging in C/C++ (Presenter: Jarno Rantaharju)

**Prerequisites**

Skills: Basic knowledge of C, C++ or both.

Software:
 * A c compiler. If you can run your C or C++ code, you have one.
 * A debugger
    * If you have a preferred IDE, you can use it. Since the interface can be different, I recommend you install the below as well.
    * Windows: [Visual Studio Code](https://code.visualstudio.com/) with the `C/C++` extension. Consider trying this even if you have gdb.
    * Other systems: [gdb](https://www.sourceware.org/gdb/). You probably already have it. Try running `gdb --version` to verify.
* A memory analyser
    * Windows: [drMemory](https://drmemory.org/page_install.html)
    * Other systems: Valgrind.
        * Ubuntu/Debian: Run `sudo apt-get install valgrind`
        * You can also try [drMemory](https://drmemory.org/page_install.html)

**Content**
C and C++ allows very direct control over your computer, including directly allocating and accessing memory. The languages are very versatile, but also
enable a wide class of bugs, both obvious and subtle.
This module will cover common errors in C and common tools for identifying problems. 

**Material**: coming soon!

### Day 4: Debugging in Julia (Presenter: Luca Ferranti)

**Prerequisites**:
Software: Detailed installation instructions about Julia and required libraries in the materials repository (to appear)
Skills: Familiarity with debugging concepts and programming skills in some programming language is assumed, basic knowledge of Julia and Julia environments is beneficial, but will be briefly reviewed at the beginning.

**Content**:
This module will give an overview of how to apply traditional debugging techniques in Julia. It will also focus on typical Julia specific gotchas and how to detect and fix them. If time allows, more advanced "debugging for performance" aspects such as detecting and fixing type stability issues will also be presented. 

**Material**: coming soon!

### Day 5: Debugging in R (Presenter: Simo Tuomisto)

**Prerequisites**:

Software: Rstudio. Detailed instructions on installation and usage will be
in a r-debugging repository.

Skills: Familiarity with R as a language.

**Content**:
We'll look into how one can trace errors, use interactive debugger to view
function internals, use breakpoints to quickly check your code and how to
debug non-interactive codes.

**Material**: coming soon!
