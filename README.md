# API Testing using Postman

## Overview
This project demonstrates API Testing using Postman and Newman.

The project includes:
- API Requests
- Test Scripts
- Environment Variables
- Newman Execution
- HTML Report Generation
- Sample API Collections

---

## Tools Used

- Postman
- Newman
- Node.js
- JSON
- REST API
- htmlextra Reporter

---

## Postman Introduction

Postman is an API client used for developing, testing, documenting, and sharing APIs.

Features:
- Send HTTP requests
- Validate responses
- Organize requests into collections
- Use environments and variables
- Automate execution using Newman
- Generate execution reports

---

## Request

A request consists of:

- URL
- HTTP Method
- Headers
- Body/Payload
- Parameters

---

## Collection

A Collection is a folder that stores related API requests.

### Create Collection

1. Open Postman.
2. Click Collections.
3. Click + New Collection.
4. Enter collection name.
5. Save the collection.

### Add Request

1. Click the three dots (...)
2. Select Add Request.
3. Enter request name.
4. Select method (GET, POST, PUT, DELETE).
5. Enter endpoint URL.
6. Click Send.

---

## Environment

An Environment is a group of variables used across multiple requests.

### Create Environment

1. Open Environments.
2. Click +
3. Enter Environment Name.
4. Add Variables.
5. Save.

Example:

```text
{{base_url}}
