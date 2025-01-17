# Telegram Calculator Bot

This is a simple Telegram bot that acts as a calculator, allowing users to perform basic arithmetic operations.

## Requirements

- Python 3.12.3
- pyTelegramBotAPI 4.17.0
- IDE: PyCharm or VS Code (code written in PyCharm)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/NooruzbekT/Calculator_bot.git
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install pyTelegramBotAPI==4.17.0
    ```

4. Create a bot on Telegram:
    - Go to [BotFather](https://t.me/BotFather) and follow the instructions to create a new bot.
    - Watch a YouTube tutorial for more detailed instructions if needed.
    - Copy the API token provided by BotFather and replace `API_TOKEN` in the code with this token.

## Usage

1. Run the bot:
    ```sh
    python calculate_bot.py
    ```

2. Interact with the bot on Telegram using the following command:
    - `/start`: Initialize the bot and display the calculator interface.

## Code Overview

The bot performs the following tasks:
- Handles the `/start` command to initialize the calculator interface.
- Processes button presses to update the current calculation.
- Evaluates arithmetic expressions and displays the result.
- Handles errors gracefully, such as division by zero.

### File Structure

- `calculate_bot.py`: Main script containing the bot logic and command handlers.

### Detailed Description

- The bot uses an inline keyboard to display a calculator interface with buttons for digits, operators, and functions (clear, delete, evaluate).
- User interactions are managed using callback queries, updating the displayed value based on the button pressed.
- Arithmetic expressions are evaluated dynamically, and errors are caught and displayed to the user.

## Note

- To use this code, you should have a basic understanding of the `pyTelegramBotAPI` library. If you lack this knowledge, you can watch video tutorials on YouTube.

- Comments in the code were written by AI and edited by me.

- The calculator has bugs and is only suitable as a small mini project for practice


## Contact

For any inquiries or issues, please contact `nookentoktobaev@gmail.com`.

