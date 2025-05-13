# compbio-walkthroughs
A collection of Python notebooks exploring machine learning techniques for biomolecular design

  **01_bigram – Bigram-Based Protein Sequence Generation**
  
  Can simple pairwise statistics create new protein sequences?
  In this quickstart tutorial, we build a generative model of proteins using nothing more than counts of amino acid pairs—a bigram model.
  
  We walk through three core stages:
  
    1. Data Extraction
  
      - Download biological sequence data
  
      - Parse amino acid sequences
  
    2. Bigram Model Learning
  
      - Map amino acids to integers (and back)
  
      - Count pairwise amino acid transitions
  
      - Normalize counts into probabilities
  
    3. Sequence Generation & Structure Prediction
  
      - Sample new amino acid chains using the bigram model
  
      - Visualize predicted 3D structures using AlphaFold3
  
  This tutorial is **beginner-friendly** and **code-first** - ideal for anyone exploring computational protein design for the first time.

  Click **Open in Colab** in **01_bigram.ipynb** to run the code in your browser.
