# Gem Forging Test Cases Generator

This Node.js script generates test cases and summary data for a gem forging process based on different levels of gem rarity. The output is written to an Excel file.

## Prerequisites

- Node.js
- npm

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/gem-forging.git
   cd gem-forging
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

## Usage

1. Run the script:
   ```bash
   node generateTestCases.js
   ```

2. Run the script:
   The generated Excel file will be saved as gem_forging_test_cases.xlsx in the current directory.


	2.	The generated Excel file will be saved as gem_forging_test_cases.xlsx in the current directory.

File Structure

	•	generateTestCases.js: The main script that generates the test cases and summary data.
	•	5gem_forging_test_cases.xlsx: The output file containing the test cases and summary.

## Output

The Excel file contains two sheets:

	1.Test Cases: Lists all the generated test cases with the following columns:
	- Level
	- Input Gems
	- Forged Result

	2. Summary: Provides a summary of the counts of each forged result shape for each level of gems needed, with the following columns:
	- Level of Gems needed
	- Shape
	- Count
   
