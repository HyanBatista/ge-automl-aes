# Grammatical Evaluation-Based AutoML for Automated Essay Scoring

This project aims to build an grammatical evolution-based AutoML for evaluating student essays. We'll be using the [The Hewlett Foundation: Automated Essay Scoring](https://www.kaggle.com/c/asap-aes) dataset for running the experiments on.

# Stack
- Python
- Pandas
- scikit-learn
- Hugging Face
- PonyGE2

# How to get up and running?
First of all you need to clone the PonyGE project using the command bellow:
```
git clone https://github.com/PonyGE/PonyGE2.git
```
Then you'll have to add ```./PonyGE2/src``` to the extra paths. This can be achieved on Visual Studio Code by creating the file ```.vscode/settings.json``` and inserting the following configuration:
```
{
    "python.analysis.extraPaths": [
        "./PonyGE2/src"
    ]
}
```
Finally you can run the experiments by using the CLI.

# References
[Genetic Programming-Based AutoML for EEG Signal Classification - A Comparative Study](https://repositorio.usp.br/directbitstream/0a2656f3-54e2-449d-ba1a-1db95ca007d3/3142491.pdf)