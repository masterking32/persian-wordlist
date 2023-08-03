# Persian Word SQL Database

Welcome to the Persian Word SQL Database repository! This open-source project provides a comprehensive collection of Persian words in a structured SQL database format. Whether you're a language enthusiast, researcher, or developer, this repository offers a valuable resource for exploring and analyzing the richness of the Persian language.

## Features

- **Extensive Vocabulary:** Explore a vast collection of 494,286 Persian words, spanning various topics and contexts.
- **Structured SQL Format:** The database is organized in a structured SQL format, making it easy to query and analyze the data.
- **Unicode Support:** Fully supports Persian characters, diacritics, and symbols using Unicode encoding.

## Getting Started

1. Clone this repository: `git clone https://github.com/your-username/persian-word-sql.git`
2. Import the SQL database file into your preferred database.
3. Start querying and exploring the Persian words!

## Usage Examples

Here are a few example queries you can try:

```sql
-- Retrieve all entries from the 'word_list' table where the word contains 'درود' anywhere in the word.
SELECT * FROM `word_list` WHERE `word` LIKE '%درود%';

-- Retrieve all entries from the 'word_list' table where the word starts with 'درود'.
SELECT * FROM `word_list` WHERE `word` LIKE 'درود%';

-- Retrieve all entries from the 'word_list' table where the word ends with 'درود'.
SELECT * FROM `word_list` WHERE `word` LIKE '%درود';
