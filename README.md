# cs6601-assignment-0-solved
**TO GET THIS SOLUTION VISIT:** [CS6601 Assignment 0 Solved](https://mantutor.com/product/cs6601-assignment-0-python-jupyter-gradescope-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top kksr-disabled" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112752&quot;,&quot;readonly&quot;:&quot;1&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6601 Assignment 0  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
This assignment is designed to help you prepare your local python environment, introduce you to jupyter notebooks and provide a refresher on python language. After following this README you will have a python environment ready and will be able to proceed with learning about jupyter notebooks in the notebook.ipynb (where you will make your first graded submission!). Let’s get started!

Table of Contents

Get repository

Conda

Environment

Packages Jupyter

Summary

Get repository

First things first, let’s pull this repository to your local machine:

git clone https://github.gatech.edu/omscs6601/assignment_0.git

Then come back to this README to continue with further setup.

Instructions to create a private forked repository for assignments

The assignments you would be working on throughout this semester will potentially require multiple revisions. A good way to track these revisions is by using your own private repo to backup your assignments at various stages of completion. Please remember that your assignment repository should be private and only accessible to yourself so that you do not accidentally violate the OSI policy.

You can use the following steps to create a private repository for assignment 0. Please replace the A0 url with the future assignments’ URL to repeat this for the future assignments.

Get the class repo

git clone –bare https://github.gatech.edu/omscs6601/assignment_0.git

Mirror this to your private repo

cd assignment_0.git git push –mirror https://github.gatech.edu/your_gatech_id/YOUR_REPO You can now delete the assignment_0.git directory cloned two steps ago if you wish.

Now clone your private repo on your local system

git clone https://github.gatech.edu/your_gatech_id/YOUR_REPO

Next cd YOUR_REPO git remote add upstream https://github.gatech.edu/omscs6601/assignment_0.git You check if the remote branch has been added using git remote -v

Now you can use it like this

it will default to the origin (your repo)

If you are scared of pushing to upstream you can disable pushing to upstream using

git remote set-url –push upstream PUSH_DISABLED

Conda

Conda is an open source package and environment management system. Conda quickly installs, runs and updates packages/libraries and easily creates, saves, loads, and switches between environments on your local computer.

Please download Miniconda and install it on your local machine. Although we require Python 3.7 for this course, you should install the version of Miniconda for any Python 3 version (e.g. Python 3.x). You can override this default by specifying the python version as 3.7 when creating the environment you will be working in for this course. You can access conda via the console to make sure it’s properly installed. For instance, you can run conda -V to display the version.

On Windows, to access conda via the console please use “Anaconda Prompt” or “Anaconda Powershell Prompt” instead of “Command Prompt”.

Environment

Environments are used to keep different python versions and packages isolated from each other, generally each project/application will have an independent python environment. For example, we will be using Python 3.7 and packages like numpy, networkx etc, and we want them to be isolated from any other python projects you might have.

To create a new environment simply run:

conda create –name ai_env python=3.7 -y

Once it’s created you can activate it by running:

conda activate ai_env

The environment is not attached to any specific folder, and you can freely navigate to different directories while it’s activated. If you want to change the environment you can deactivate it using conda deactivate and then activate another env. To see the list of all environments you have on your machine you can run conda env list.

Packages

We will be using multiple python packages throughout this class. Here are some of them:

jupyter – interactive notebook (you will learn more about them soon) numpy – a package for scientific computing (multi-dimensional array manipulation) matplotlib – a plotting library networkx – a package for manipulating networks/graphs pandas – a package for data analysis pgmpy – library for probabilistic graphical models

You can see the complete list of packages and required versions in ./requirements.txt.

We can install all these packages using command pip install -r requirements.txt. Please navigate to the assignment_0/ directory, activate your environment (conda activate ai_env), then run: pip install -r requirements.txt

Once installed, you can run pip freeze to see the list of all of the packages installed in your ai_env environment.

Jupyter

Now that you have set up the environment it’s time to learn more about the jupyter notebooks.

We have already installed jupyter. To open it up you can run:

jupyter notebook

It will start a python kernel which you can access via https://localhost:8888 in your browser. For the rest of the assignment proceed to notebook.ipynb.

Summary

You have now installed conda package and environment manager, created a python environment and installed all the necessary packages.

Please always remember to run: conda activate ai_env to activate your environment before you start working on your assignments.
