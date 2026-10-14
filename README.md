
# R Basics: Puppy Budget Exercise

## Overview
This project demonstrates basic R programming using variables, calculations, and logical comparisons. It uses a simple puppy budget example to practice R syntax.

## Installation
- Install R.
- Use RStudio or another R environment.
- No additional R packages are required.

## Dataset
This exercise does not use an external dataset. It uses sample values defined in the R script.

## Example Usage
1. Open `exercise.R` in RStudio.
2. Run the script.
3. View the calculated values in the R console.

## Example Code
```r
puppies <- 8
puppy_price <- 250
total_cost <- puppies * puppy_price
too_expensive <- total_cost > 1000
max_puppies <- 1000 %/% puppy_price
```

## Results
- Total puppy cost: $2,000.
- The total exceeds $1,000: TRUE.
- Maximum puppies within a $1,000 budget: 4.

## License
This project is for educational use. The exercise is adapted from course practice material.

## AI Assistance Disclosure
- AI tool used: ChatGPT.
- Main prompts: Generate a professional README for a basic R exercise; add installation, example code, and license sections; review Markdown formatting and clarity.
- Changes made: Reviewed the content, organized the sections, and checked the calculations against the R script.
  