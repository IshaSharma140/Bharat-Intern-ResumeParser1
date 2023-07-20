# Bharat-Intern-Resume-Parser

This is a Python script that matches job requirements with candidate profiles based on skills, experience, and communication skills. It provides the following functionality:

- Calculating the score of a candidate based on their skills and job requirements.
- Finding the best candidate for a job based on their score.
- Displaying the details of the best candidate.

## Requirements

To run this script, you need to have the following dependencies installed:

- `nltk`: You can install it using `pip install nltk`.

## Usage

1. Clone this repository or download the script file.
2. Install the required dependencies.
3. Run the script using Python.

The script will prompt you to enter the job requirements. Follow the prompts to input the requirements. The script will then match the requirements with the candidate profiles and display the details of the best candidate.

### Example

Enter the job requirements:

Enter a job requirement (or 'done' to finish): python

Enter a job requirement (or 'done' to finish): machine learning

Enter a job requirement (or 'done' to finish): communication skills

Enter a job requirement (or 'done' to finish): done


Best candidate for the job:

Name: John

Skills: python, data analysis, problem-solving

Experience: 7 years

Communication Skills: excellent


## Customization

You can customize the candidate profiles by modifying the `candidate_profiles` list in the script. Each candidate profile is a dictionary containing the following keys:

- `name`: The name of the candidate.
- `skills`: A list of skills possessed by the candidate.
- `experience`: The number of years of experience the candidate has.
- `communication_skills`: The communication skills of the candidate, which can be `'excellent'`, `'good'`, or any other value.

Feel free to modify the candidate profiles to match your specific scenario.

## Contributions

Contributions to this script are welcome. If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.



