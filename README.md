# Fable get user book finished information

This project fetches book data from the https://fable.co API and stores it in a SQLite database.

## Setup

1. Install the required Python packages:

   ```sh
   pip install requests
   ```
2. Ensure you have SQLite installed on your system.

## Usage

1. Update the `API_ENDPOINT` variable in `fable.py` with the API endpoint.
2. Run the script:

   ```sh
   python fable.py
   ```
3. The script will create the necessary tables and insert the book data into the `db/book.db` SQLite database.

## Find userCode and bookListCode

Go to the `finished category` of the user

![Find userCode and bookListCode](./images/Sans%20titre.png)

## Database Schema

The database contains the following tables:

- `book`
- `author`
- `subject`
- `genre`
- `storygraph_tag`
- `review_summary`
- `users`

## License

This project is licensed under the MIT License.
