# 🎬 Redis Lab: Querying the Movies Dataset

## 📌 Objective

This lab demonstrates how to query and manipulate movie-related data using **Redis**. It is part of a practical exercise designed to help develop skills working with Redis key types, sorted sets, and secondary indexes.

## 🗃️ Dataset Overview

The dataset includes the following key types:

- **Movies** — stored as **hashes**, with keys like `movie:<id>`
- **Theaters** — stored as **hashes**, with keys like `theater:<id>`
- **Users** — stored as **hashes**, with keys like `user:<id>`
- **Ratings** — stored as **sorted sets**, to track movie ratings
- **Indexes** — secondary indexes to facilitate searching

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Redis is installed and running locally (`localhost:6379`)
- `redis-cli` available in terminal
- Python `redis` package (`pip install redis`)

### Project Structure
