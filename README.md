# Learning REST APIs

This is my personal practice repository based on the LinkedIn Learning course [Learning REST APIs](https://www.linkedin.com/learning/learning-rest-apis). It is not a fork of the original course repository; it was initialized from scratch with its own commit history.

## Course Description

Learn the basics of REST APIs. This course covers what REST APIs are, why they matter, and how using them helps build faster, more efficient applications. It reviews how HTTP and REST APIs relate, explores the six constraints of REST, and covers HTTP status messages, along with how to consume REST APIs in data-driven applications.

## Instructions

This repository serves as a practice environment for interacting with a database server through a REST API. When opened in GitHub Codespaces, it spins up and populates a private database server with dummy content for practicing create, retrieve, update, and delete operations through a typical REST API.

The Codespace can take a while to boot up on first run. It's ready when the terminal shows something like:

```
INFO:     Started server process [5183]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

## Branches

This repository has only one branch: `main`.

## Installing

Setup is automated in GitHub Codespaces. The only manual step is making the REST API port public:

1. Select the Ports tab in the bottom panel
2. Find the row for port `8000`
3. In the "Visibility" column, right-click on "Private"
4. Select "Port Visibility -> Public"

## Expanding the Database

The database is auto-populated from the contents of `init_db.py`. To start with a larger dataset, modify and expand this file and start a new Codespace.

## REST API Documentation

Full documentation of the REST API is available in `DOCUMENTATION.md`.

## Notes

This repository does not include a live `.env` file. Environment variables should be configured locally using `.env.devcontainer` as a template.
