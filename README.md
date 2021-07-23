# Cornerstones of Quantum Computing Pre-reading
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
   - Functions of matrices (e.g. square root of a matrix, matrix exponentiation)
-    Dirac notation
Below is some suggested reading that covers these topics, and more. If the concepts above are not fresh in your memory, we recommend at least going through the first link, and perusing the others for topics you’d like more information, or a different perspective on.
   - [Qiskit textbook's appendix on linear algebra](https://qiskit.org/textbook/ch-appendix/linear_algebra.html). Qiskit is IBM’s quantum computing library;
while we won’t be using it during the school, they have a very nice overview of the linear algebra needed for quantum computing. *You can ignore the parts about the Bloch sphere - this concept will be introduced in the  lectures*.
   - [Linear algebra for quantum computation](https://cds.cern.ch/record/1522001/files/978-1-4614-6336-8_BookBackMatter.pdf). Appendix A from the book *Quantum Walks and Search Algorithms* by Renato Portugal. Check out sections A.1-A.4, A.6, and A.11-A.14
   - [Interactive linear algebra](https://textbooks.math.gatech.edu/ila/index.html). This is a great online textbook for linear algebra basics, with
lots of visuals to play with. Suggested sections: 2.1-2.2, 2.5, 2.7, 3.3, 4.1, 5.1-5.5, 6.1.

## Calculus
Core concepts:
   - Derivatives and gradients
   - Optimization
If youneed a quick refesher on these concepts:
   - Basics of derivatives from J.Stewart's book on [LibreText](https://math.libretexts.org/Bookshelves/Calculus/Map%3A_Calculus_-_Early_Transcendentals_(Stewart)/03%3A_Differentiation_Rules) sections 3.1-3.7
   - Discussion on gradints can from [Khan Academy](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/partial-derivative-and-gradient-articles/a/the-gradient)
   - Optimization: some examples on [LibreText](https://math.libretexts.org/Bookshelves/Calculus/Map%3A_Calculus_-_Early_Transcendentals_(Stewart)/04%3A_Applications_of_Differentiation/4.07%3A_Optimization_Problems) and a [Wikipedia article](https://en.wikipedia.org/wiki/Combinatorial_optimization) on combinatorial optimization would be worth browsing
  
## Statistics
Core concepts:
   - Probability
   - Gaussian distributions
   - Sampling
Like calculus, there are many tutorials available online. Here are a few examples:
- [A complete tutorial on statistics and probability](https://www.edureka.co/blog/statistics-and-probability/) is a pretty concise tutorial that covers
most of the above in sufficient detail.
- The [Wikipedia article](https://en.wikipedia.org/wiki/Normal_distribution) for the Gaussian distribution contains plenty of information. See the
introduction, and sections 1.1, 1.2, 1.5.1, and 2.1. 
- [Khan academy](https://www.khanacademy.org/math/statistics-probability/sampling-distributions-library) has a section about sampling. [Wikipedia](https://en.wikipedia.org/wiki/Sampling_%28statistics%29#Sampling_methods) also has an extensive set of
examples of sampling methods that you can peruse to your level of interest.

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


## Logistics


