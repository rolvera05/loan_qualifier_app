# Loan Qualifier App

Filtering through loan applications can be a difficult task. It requires countless hours to to review and determine whether the applicant qualifies for a loan or not. The work is repetitive and would be more efficiently excuted if the task could be automated. 

That is where this project comes in. We have created a loan qualifier application system that uses machine learning algorithms to analyze the loan applications for you. The system will account for varies factors such as the applicants credit score, income, DTI, and LTV, and provid recommendations based on these factors. Once the qualifying loans are accounted for, the loans can be saved to a CSV file. This file can be shared as a spreadsheet which saves you from having to manually copy and paste the data into a spreadsheet.

The projects main contribution is that it streamlines the loan qualificaion process making it more efficient. As previously stated, our project also saves qualifying loans to a CSV file which makes sharing the results as a spreadsheet faster. Thus, further uncreasing efficiency and collaboration. 

---


## Technologies

Programming langauages: The programing languages used in this project are python. Running python 3.9
Libraries: The specific libraries used for this project are fire, csv, sys, and questionary. 
Operating systems: This project can be ran through VS Code and Terminal or iTerm on Mac 

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs
---

## Installation Guide
Make sure to install csv, fire, and questionary to run the application
```python
  pip install fire
  pip install questionary
  pip install csv
```


## Usage

To use the program clone the repository and run the **app.py** with:
```python
python app.py
```
After you launch your first question this is what you should see:

![Loan Qualifier Prompts](images/image2.png)

---

## Contributors

This project was made possible by Rosalinda Olvera through the FinTech Bootcamp and instructor Firas Obeid.

---

## License

Available to anyone. 
