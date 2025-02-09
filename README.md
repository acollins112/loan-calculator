# Loan Calculator
⭐️⭐️⭐️⭐️⭐️
![Python badge](https://img.shields.io/static/v1?message=python&logo=python&labelColor=5c5c5c&color=3776AB&logoColor=white&label=%20&style=for-the-badge) ![Flask badge](https://img.shields.io/static/v1?message=Flask&logo=Flask&labelColor=5c5c5c&color=000000&logoColor=white&label=%20&style=for-the-badge) ![Bootstrap 5 badge](https://img.shields.io/static/v1?message=Bootstrap5&logo=bootstrap&labelColor=7952B3&color=7952B3&logoColor=white&label=%20&style=for-the-badge) ![University of Iowa badge](https://img.shields.io/static/v1?message=Hawks!!&labelColor=000000&color=FFCD00&label=Go&style=for-the-badge)

[![test-package-deploy-pipeline](https://github.com/mikecolbert/loan-calculator/actions/workflows/pipeline.yaml/badge.svg)](https://github.com/mikecolbert/loan-calculator/actions/workflows/pipeline.yaml)

## Introduction

Hi, I'm Anthony! I created this Loan Calculator as a Flask application using Jinja templates. The user enters details of their loan, and it calculates the monthly payment and an amortization table. I've used this application to learn CI/CD, including automated testing and GitHub Actions workflow files (.yaml).

## Features

- Loan calculation
- Amortization table
- Bootstrap 5 formatting
- Sticky header on amortization table
- Bootstrap 5 tooltips for help
- Font Awesome icons for tooltips
- Pytest file for unit and functional testing
- Custom GitHub Action workflow file for CI/CD
- Client-side validation

## Planned Features

- Server-side validation
- Error checking and error handling
- Re-configure Pytest for validation and error testing

## Running the Application

1. Clone this repository to your local computer
2. Create a new virtual environment:
   - Windows: `python -m venv ./venv`
   - Mac: `python3 -m venv ./venv`
3. Activate the new virtual environment:
   - Windows: `.\venv\Scripts\activate`
   - Mac: `source ./venv/bin/activate`
4. Install the dependencies: `pip install -r requirements.txt`
5. Run the application with `python app.py` or `flask run`

![Screenshot of loan calculator.](./simple_calc.jpg)

