# Project Overview
This repository contains multiple Python projects demonstrating key concepts in data storage, web APIs, text-to-speech conversion using AWS, and data processing. The projects include:

1.A simple NoSQL database implementation.

2.A basic Flask API for managing a bookstore.

3.A Flask API for handling a shopping cart.

4.AWS Polly integration for text-to-speech conversion.

5.Python scripts showcasing dictionary operations and user record retrieval.

# Project Descriptions
Bookstore API (SampleAPI.py)

A simple bookstore management API built using Flask. It allows you to add books with details like title, author, and genre, and retrieve books based on their ID.

Simple NoSQL Database (NoSQL.py)

A Python-based NoSQL-like key-value store with functions for inserting, retrieving, deleting, and displaying data. It includes scripts to manage user records stored in nested dictionaries.

Dictionary Operations (NoSQL.py - Code 2)

Demonstrates storing and retrieving user data using nested dictionaries and includes a function to search for records based on specified criteria.

AWS Polly Text-to-Speech (AWSpolly.py)

Integrates AWS Polly to convert text into speech using Python. The script uses Boto3 and handles audio streaming and saving the output as an MP3 file.

Shopping Cart API (APIcall.py)

A Flask-based API that allows adding and deleting products in a shopping cart. It provides routes for adding items via a form and deleting them through an API call.

# Project Structure

├── SampleAPI.py                  # Bookstore API implementation

├── NoSQL.py                  # Simple NoSQL database and dictionary operations

├── AWSpolly.py               # AWS Polly text-to-speech integration

├── APIcall.py                # Shopping cart management API

└── README.md                 # Project documentation

# Prerequisites
Python 3.x

Flask

Boto3 (for AWS Polly)

MySQL (for SampleAPI if used with database extension)





