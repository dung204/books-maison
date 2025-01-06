<p align="center">
  <a href="http://api.books-maison.live/api-docs" target="blank"><img src="assets/images/books-maison-logo-dark.svg" width="400" alt="Books Maison logo" /></a>
</p>

<p align="center">Books Maison - the book library management system</p>

## Table of Contents

- [1. Primary Features](#1-primary-features)
- [2. License](#2-license)

## 1. Primary Features

- CRUD (Create, Read, Update, Delete) users, books, authors, checkouts, fines
- User authentication and authorization using JWT (JSON Web Token) & Google OAuth2
- Allowing users to borrow and return books
- Calculating fines for late returns
- Allowing users to pay fines using [Momo E-wallet](https://www.momo.vn/)

> **Note**:
>
> - Whenever a user borrows a book, a checkout record is created with a due date.
> - If the user returns the book after the due date, a fine is calculated based on the number of days the book is overdue.

## 2. License

This project is licensed under the Unlicense - see the [LICENSE](LICENSE) file for details.
