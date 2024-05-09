# EmojiLogger 🪵.🐍

EmojiLogger is an educational keylogger written in Python, making use of the Pythonji module to incorporate emojis within the code base. This keylogger operates discreetly in the background, capturing keystrokes and transmitting them to an IRC server. Moreover, it terminates itself when the user presses the 'Esc' key, ensuring user control over its activity. Upon exit, EmojiLogger saves the complete history of captured keystrokes to the file system for further analysis.

## Features

- Runs in the background, capturing keystrokes.
- Utilizes the Pythonji module for emoji support in the code.
- Provides system information such as OS details, architecture, and hostname.
- Sends keystrokes to an IRC server.
- Saves keystroke history on the hard disk.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/stenocyb/EmojiLogger.git
    ```

2. Navigate to the directory where the repository is cloned:

    ```
    cd EmojiLogger/
    ```

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Modify the `🏢` (IRC server address), `🚪` (IRC server port), `🎚️` (IRC server channel), `👤` (IRC server username), and `📁` (output file) variables in the 🪵.🐍 file according to your IRC server and preferences.

## Usage

1. Run the keylogger:

```
sudo pythonji 🪵.🐍
```
or
```
sudo python -m pythonji 🪵.🐍
```

Once the keylogger is running, it will capture keystrokes in the background. Press the 'Esc' key to exit and save the keystroke history to the hard disk.  

__Note__: The tool starts sending the captured keystrokes when the maximum IRC message length has been reached which is in case of the default channel name 487.

![image](https://github.com/stenocyb/EmojiLogger/assets/7761846/92764cc8-0d24-4e72-aeff-cc4de9456c47)

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
