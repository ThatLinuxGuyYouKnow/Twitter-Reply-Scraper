# Twitter Replies Fetcher

This Python script fetches the replies to a specific tweet using the Twitter API from RapidAPI. It extracts and displays the usernames and account IDs of the users who replied to the tweet.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Error Handling](#error-handling)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/twitter-replies-fetcher.git
    cd twitter-replies-fetcher
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment:**

    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

4. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Replace `YOUR_RAPIDAPI_KEY` in the script with your actual RapidAPI key.**

2. **Run the script:**

    ```bash
    python twitter_replies_fetcher.py
    ```

3. **Enter the Tweet URL when prompted.**

    The script will print out the usernames and account IDs of the repliers.

## Configuration

- **RapidAPI Key:**
  - Sign up on [RapidAPI](https://rapidapi.com/) to get your API key.
  - Replace `YOUR_RAPIDAPI_KEY` in the script with your actual RapidAPI key.

## Error Handling

The script includes basic error handling to manage issues such as:
- Invalid tweet URLs.
- No replies found.
- HTTP errors during API calls.

If any errors occur, appropriate messages will be printed to help diagnose the issue.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch:**

    ```bash
    git checkout -b feature-branch-name
    ```

3. **Make your changes and commit them:**

    ```bash
    git commit -m 'Add some feature'
    ```

4. **Push to the branch:**

    ```bash
    git push origin feature-branch-name
    ```

5. **Open a pull request.**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
