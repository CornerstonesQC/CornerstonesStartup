ccc# Cornerstones of Quantum Computing Pre-reading

This document contains the information needed to get you ready for attending the Cornerstone Models of Quantum Computing Summer School.  The initial sections will provide references for the concepts you’ll need to know in advance of the lectures. We'll go over some logistics and finally we'll set up the python environment so that you can attack homework challenges.


# Group guidelines

We are very happy to have the opportunity to interact with such a diverse group of students
from a variety of countries, programs, and educational backgrounds.

We are dedicated to providing a supportive learning environment for all participants. Everyone
is here to learn. As you interact during the sessions, on Slack, or anywhere else with your
fellow classmates, we ask that you adhere to the following guidelines:

   - Ask and answer questions with patience
      - No two participants will have the same background knowledge. Please ask questions when you are not sure about something, and answer the questions of others in a constructive way that helps their understanding. Everyone benefits when people feel comfortable asking questions.
   - Ensure everyone gets heard
      - Especially when working in small groups, give everyone the opportunity to share their thoughts. Please don’t interrupt when others are talking, and don’t make derogatory comments about their ideas.
   - Treat all participants with respect
      - We pledge to make these seminars a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.

If you have concerns about the behaviour of another participant, please reach out to one of the organizers via Slack, or private email. All complaints will be reviewed and investigated promptly and fairly, and the organizers will respect the privacy and security of the reporter of any incident. A portions of these guidelines were adapted from the [Contributor Covenant](https://www.contributor-covenant.org/version/2/0/code_of_conduct/)

# Fundamental Concepts

## Linear algebra

Core concepts:
   - Vectors and vector spaces
   - Linear (in)dependence, and bases for a vector space
   - Inner products and orthogonality
   - Matrices and matrix operations
   - Determinants
   - Eigenvalues and eigenvectors
   - Functions of matrices (e.g., square root of a matrix, matrix exponentiation)
   - Dirac notation

Below is some suggested reading that covers these topics, and more. If the concepts above are not fresh in your memory, we recommend at least going through the first link, and perusing the others for topics you’d like more information, or a different perspective on.

   - [Qiskit textbook's appendix on linear algebra](https://qiskit.org/textbook/ch-appendix/linear_algebra.html). Qiskit is IBM’s quantum computing library;
while we won’t be using it during the school, they have a very nice overview of the linear algebra needed for quantum computing.
   - [Linear algebra for quantum computation](https://cds.cern.ch/record/1522001/files/978-1-4614-6336-8_BookBackMatter.pdf). Appendix A from the book *Quantum Walks and Search Algorithms* by Renato Portugal. Check out sections A.1-A.4, A.6, and A.11-A.14
   - [Interactive linear algebra](https://textbooks.math.gatech.edu/ila/index.html). This is a great online textbook for linear algebra basics, with
lots of visuals to play with. Suggested sections: 2.1-2.2, 2.5, 2.7, 3.3, 4.1, 5.1-5.5, 6.1.

## Calculus

Core concepts:

   - Derivatives and gradients
   - Optimization

If you need a quick refesher on these concepts:

   - Basics of derivatives from J.Stewart's book on [LibreText](https://bit.ly/3BFfKzk) sections 3.1-3.7
   - Discussion on gradients from [Khan Academy](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/partial-derivative-and-gradient-articles/a/the-gradient)
   - Optimization: some examples on [LibreText](https://bit.ly/3iNveZP) and a [Wikipedia article](https://en.wikipedia.org/wiki/Combinatorial_optimization) on combinatorial optimization would be worth browsing
  
## Statistics

Core concepts:

   - Probability
   - Gaussian distributions
   - Sampling

Like calculus, there are many tutorials available online. Here are a few examples:

   - [A complete tutorial on statistics and probability](https://www.edureka.co/blog/statistics-and-probability/) is a pretty concise tutorial that covers most of the above in sufficient detail.
   - The [Wikipedia article](https://en.wikipedia.org/wiki/Normal_distribution) for the Gaussian distribution contains plenty of information. See the introduction, and sections 1.1, 1.2, 1.5.1, and 2.1. 
   - [Khan academy](https://www.khanacademy.org/math/statistics-probability/sampling-distributions-library) has a section about sampling. [Wikipedia](https://en.wikipedia.org/wiki/Sampling_%28statistics%29#Sampling_methods) also has an extensive set of examples of sampling methods that you can peruse to your level of interest.

## Selected topics in quantum mechanics

Core concepts:

   - Dirac notation
   - Wavefunctions
   - Quantum harmonic oscillators
 
You can find information about these in an undergraduate quantum mechanics textbook if you
have one handy. A nice, modern online resource is [University Physics Volume 3](https://opentextbc.ca/universityphysicsv3openstax/) available on
the [BC Open Textbooks page](https://opentextbc.ca/).

- Wave functions are covered in [section 50](https://opentextbc.ca/universityphysicsv3openstax/chapter/wave-functions/) of the above
- The quantum harmonic oscillator is in [section 54](https://opentextbc.ca/universityphysicsv3openstax/chapter/the-quantum-harmonic-oscillator/) of the above
- Dirac notation was covered in the linear algebra materials linked in the previous section.
It is also summarized quite nicely in the [Wikipedia article](https://en.wikipedia.org/wiki/Bra%E2%80%93ket_notation#Bra-Ket_notation/) (see 2.2 and 2.3)


# Logistics
Please download, configure, and familiarize yourself with the following tools with ample time before start of the school
 If you have any trouble, reach out to us on Slack in the #tech-setup channel
before the sessions start, and we can provide help.

## Slack
All discussions and management will be done through [Slack](https://slack.com/intl/en-ca/). You should have received an
invitation to our Slack workspace, so please follow it to create an account. Please use your full
name as your display name.
The participants admitted for full participaton will be assigned to small groups expected to work together on the challenges
 and we will invite you to separate channels so you can discuss amongst yourselves between sessions.

## Zoom
The lectures themselves will be held on Zoom - links will be provided a few days before the
sessions. Please [download and install](https://zoom.us/download#client_4meeting) Zoom and create an account. Before the sessions,
please test your camera and microphone and familiarize yourself with the features.

# Technical setup

If you have been admitted to full school participation or if you wish to attack the challenge problems on your own please follow the instructions below.

## Python and Jupyter
 
Coding will be done in Python using Jupyter notebooks. Necessary setup has been done for you using Python 3.8 version of Anaconda. Please follow the steps below with enough advance before the school to allow for debugging of any issues that may arise. 

   - On Windows 10 we recommend installing [Windows Subsystem for Linux 2](https://docs.microsoft.com/en-us/windows/wsl/install-win10) with Ubuntu 20.04. Further instructions assume access to linux-like teminal (or Mac OS X terminal)
   - If you do not have Python 3.8 Anaconda set up please set it up using installer apropriate for your system from [here](https://www.anaconda.com/products/individual#Downloads). ON WSL2 use the linux installer.
   - Open the terminal. We recommend turning off the automatic entry into the `base` environment by running:  
   `conda config --set auto_activate_base false`
   - Next clone this repo.
      - If you have a github account [with loaded ssh key pair](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) this is preferable:  
      `git clone git@github.com:CornerstonesQC/CornerstonesStartup.git`
      - If you don't have a github account or no ssh key pair loaded, you can clone the repo using https instead:  
      `git clone https://github.com/CornerstonesQC/CornerstonesStartup.git`
      - Now go into new repo local directory:`cd CornerstonesStartup`
   - Create the conda environment using the following command:
      - `conda create python=3.8 -name cornerstones`
   - Activate the environment:
      - `conda activate cornerstones`
   - The first time you activate the environment, you will need to install the
     require packages. This can be done using `pip`:
      - `python -m pip install -r requirements.txt`
   - Now, according to preference, start up jupyter or jupyter lab:
      - For jupyter notebook: `jupyter notebook --no-browser`
      - For jupyter lab: `jupyter lab --no-browser`
   - Jupyter will print instructions on which webpage to load - paste the address in your favourite browser to gain accesss to the jupyter notebook or lab
   - When you stop working you can exit the environment by typing `conda deactivate`. Next time simply issue again the activate line and start jupyter as before.


## Setting up accounts to access the devices

### IBM Q
Please set up an account for yourself on [IBM Quantum](https://quantum-computing.ibm.com/) - you will need it to access gate model device to complete the challenges.

### D-Wave

For access to D-Wave's quantum processing unit (QPU) you will need an account on Leap - the cloud service from D-Wave. Sign yourself up [here](https://cloud.dwavesys.com/leap/signup). We strongly suggest linking your GitHub account (or creating one and linking it) to your Leap account in order to renew this minute every month. Instructions can be found [here](https://support.dwavesys.com/hc/en-us/articles/360003706773-How-Do-I-Get-More-Time-). 

For this course, we’ll be working in the [Leap Integrated Developer Environment (IDE)](https://ide.dwavesys.io/workspaces/). You need a Leap account to access the Leap IDE. Before the course try opening one of the code examples and running it! We suggest [antennas selection]( https://cloud.dwavesys.com/leap/example-details/222023401/) as a good beginner example. Should you wish to download and install D-Wave's Ocean software development kit (SDK) on your machine locally follow the instructions [here](https://docs.ocean.dwavesys.com/en/latest/getting_started.html) and Ocean installation instructions [here](https://docs.ocean.dwavesys.com/en/latest/overview/install.html). Note that the `dwave-ocean-sdk` has been installed in the conda environment but the tools have not been set up - you will need to follow the instruction from the ["Set Up Your Environment"](https://docs.ocean.dwavesys.com/en/latest/overview/install.html#set-up-your-environment). You can find a series of instructional videos [here](https://www.youtube.com/playlist?list=PLPvKnT7dgEsuhec_yW9oxcZ6gg9SfRFFV).

If you reside in a country not on the [list](https://support.dwavesys.com/hc/en-us/articles/360051869733-From-What-Countries-Can-I-Access-Leap-) of countries where Leap is accessible from please do install Ocean SDK - you will have to work locally with non-QPU solvers and work together with participants whose country is on the list.


### Xanadu

Information forthcoming.



