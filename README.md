[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=11965179)
# File Streams Lab

### Objective

Write a program that can take allergen information and arrange it properly in memory before being printed out to the terminal.

### Get Allergen Data

1. Open and read the `allergens.csv` to obtain all allergens and their value
2. Store this data into an array such that the entries are ordered by increasing powers of 2
3. This array will be used to print allergens of each patient

### Get Patient Data

1. Now open and read whatever file the user asked to use as input
2. For each patient in the file create a patient struct and put it into an array
3. Sort the array
4. Display all patients with allergens listed below

### Bitfield

A simple way to store the data is using a "bitfield" where each bit in the binary pattern that is ON indicates that the patient has that allergy (and thus should be listed on output). Some patients may have allergies that we are not listing in output
