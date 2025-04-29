# Replication package for paper "Detecting Data Contamination with Data’s Naturalnes and Data Complete"

![Overview](Overview.PNG)



This repository contains the code, datasets, and resources for the research paper **"Has My Code Been Stolen for Model Training? A Naturalness-Based Approach to Code Contamination Detection"**. The proposed method, **Natural-DaCoDe**, uses naturalness scores of source code to detect whether a given piece of code has been used to train deep learning models, particularly code completion models.

## Project Overview
The objective of this project is to provide a novel approach to detecting data contamination in deep learning models. By leveraging the **naturalness** of source code and combining it with the model’s performance, this approach significantly outperforms traditional methods for detecting whether a piece of code has been used for model training.
## Features
- Detection of contaminated vs. cleaned datasets using naturalness and model performance.
- Works for code completion models and method name suggestion tasks.
- Code and dataset collection for constructing contaminated (𝐶𝑇𝑑𝑎𝑡𝑎) and cleaned (𝐶𝐿𝑑𝑎𝑡𝑎) datasets.

## Directory Structure

This section provides an overview of the repository structure, including datasets, and the source code of the Code Completion models: [Dataset](https://drive.google.com/file/d/1QheSAfupFNCq_V4q4a4Mt8uHNDl_gpC2/view?usp=sharing),[UniXcoder](https://github.com/naturalnessbasedappraoch/Natural-DaCode/tree/main/Source_code/UniXcoder), [CodeParrot](https://github.com/naturalnessbasedappraoch/Natural-DaCode/tree/main/Source_code/CodeParrot), and [Ngram Model](https://github.com/naturalnessbasedappraoch/Natural-DaCode/tree/main/Source_code/n-gram_cachelm).
![Overview](directories.PNG)

# Dataset for Code Completion and N-gram Models
<p align="center">
    <img src="DatasetGraph.PNG" alt="TestingDataset" width="600">
</p>
