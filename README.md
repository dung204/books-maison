<p align="center">
  <a href="http://api.books-maison.live/api-docs" target="blank"><img src="assets/images/books-maison-logo-dark.svg" width="400" alt="Books Maison logo" /></a>
</p>

<p align="center">Books Maison - the book library management system</p>

Live URL: [https://books-maison.live](https://books-maison.live)

## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Primary Features](#2-primary-features)
- [3. License](#3-license)

## 1. Introduction

This repository is the entrypoint for the source code of the Books Maison project. Books Maison is a book library management system that allows users to borrow and return books, calculate fines for late returns, and pay fines using Momo E-wallet.

This repository contains these following modules (each in its own Git repository):

- `books-maison-api`: The REST API for the Books Maison project
- `books-maison-frontend`: The frontend web application for the Books Maison project
- `books-maison-mobile`: The mobile application for the Books Maison project

And some other modules coming soon...

> ⚠️ **Note**: Please do not clone this repository directly. Instead, head over to the each above module's repository to get the source code.

## 2. Primary Features

- CRUD (Create, Read, Update, Delete) users, books, authors, checkouts, fines
- User authentication and authorization using JWT (JSON Web Token) & Google OAuth2
- Allowing users to borrow and return books
- Calculating fines for late returns
- Allowing users to pay fines using [Momo E-wallet](https://www.momo.vn/)

> **Note**:
>
> - Whenever a user borrows a book, a checkout record is created with a due date.
> - If the user returns the book after the due date, a fine is calculated based on the number of days the book is overdue.

## 3. License

This project is licensed under the Unlicense - see the [LICENSE](LICENSE) file for details.
