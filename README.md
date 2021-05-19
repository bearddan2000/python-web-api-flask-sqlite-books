# python-web-api-flask-sqlite-books

## Description
Creates an api of books for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.

## Tech stack
- python
- flask

## Docker stack
- python:latest

## To run
`sudo ./install.sh -u`
- Get all books: http://localhost/books/all
  - Schema id, author, title, first_sentence, and published
- Query with params: http://localhost/book <params>

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
https://programminghistorian.org/en/lessons/creating-apis-with-python-and-flask#creating-the-api
