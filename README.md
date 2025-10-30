# Predicting_Protein_Function_Project

## Plan for Creating Dataset

- Extract 3D protein data
- Find out Uniprot Accession code
- Use PDB Reader for 3D spatial data
- Concatenate data and add as column

## Dataset Explanation

- Take all 23,000 confirmed human proteins
- Feed to the PDB Reader which will search through each protein and extract the 3D spatial data
- Loop through and take 3D spatial data from each protein
- Take Uniprot accession code, find function, and add as column
- Concatenation to form dataset

## Initial Test 1
<img width="273" height="250" alt="Screenshot 2025-10-30 at 11 35 23 AM" src="https://github.com/user-attachments/assets/b96497f3-65f0-42b9-b779-e9e5ebe68e9a" />


### What was done
- Create a fake dataset using real Uniprot accession numbers
- Use PDB reader to extract structure

### Current Problem
- So many Uniprot accession codes are not working
- Fix: Use snippet from the actual dataset

### What Should The Next Test Be?
- Take a small snippet from the Human genome
- Illustrate getting the structure from multiple sequences of DNA

## Test 2
<img width="596" height="230" alt="Screenshot 2025-10-30 at 11 36 11 AM" src="https://github.com/user-attachments/assets/970b501d-b50c-4771-a8c2-06a3c3a43292" />


This is from the first structure in the dataset, it demonstrates that the files were success put into a list

## Test 3

- Currently running code to create feature dataset
- Takes a really long time

## What I need to do next

- Get a cloud service for more computing power
- Test the preliminary dataset with a supervised ML model to set a baseline
- Figure out how to extract features within the features to create a more representative dataset
- Start figuring out how the neural network works to help this process

## Milestone

- Not yet achieved: need to finish the preliminary dataset and run on supervised ML model
