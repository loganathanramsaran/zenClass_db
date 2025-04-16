# 🧠 Zen Class MongoDB Data

This repository contains sample MongoDB collections for a Zen Class program. Useful for testing MongoDB queries, aggregations, and Compass operations.

## 📂 Collections (in `/mongoDB_task` folder)

- `users.json`
- `mentors.json`
- `topics.json`
- `tasks.json`
- `attendance.json`
- `codekata.json`
- `company_drives.json`

## 🚀 How to Import into MongoDB

Use the following command to import any collection:

```bash
mongoimport --db zenClass --collection users --file ./data/users.json --jsonArray
