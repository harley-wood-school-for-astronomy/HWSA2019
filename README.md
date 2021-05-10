# good-code-etiquette

“Programs must be written for people to read, and only incidentally for machines to execute.”
― Harold Abelson, Structure and Interpretation of Computer Programs 


We will use peardeck for the presentation.

Go to [joinpd.com](https://app.peardeck.com/join) and type in the code given you.

You will likely need to sign in with you google account.

## Session 1: Interactive lecture, intro to coding style and practices
Examples explored:
- [Readability](Readbility.ipynb)
- [Structure](Structure.ipynb)
- [Documentation](Documentation.ipynb)
- [Exception](Excepttions.ipynb)
- [DRY examples](DRY%20examples.ipynb)
- [Testing](Testing.ipynb)
- [Vectorize](Vectorize.ipynb)

## Session 2: Hands on project work, applying skills to (intentionally) crappy code

After installing `conda`, please do `conda env create -f hwsa-environment.yml`

### Data

In this part of the workshop we will look at an example code to reproduce HR diagrams using Gaia data.
We can query the Gaia public database and download the required data.
However, the query run in the notebook takes a long time so the data is made available here:

Data can be found here:

[In votable formaat](https://www.dropbox.com/s/3hsijr0fsj6evjb/async_20190630210155.vot?dl=0)

[As a pkl file](https://www.dropbox.com/s/4jat5yjmb7okwi9/async_20190630210155.pkl?dl=0)

[vot table subset](https://www.dropbox.com/s/3hczxo7vtn7zia7/async_subset.vot?dl=0)

## Session 3: Revision and Benchmarking

- When and What to Optimise
- Timing Code Snippets
- Profiling Code
- Parallelising Code
- Advanced Track

