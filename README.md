# CommandCenter Plugin

CommandCenter is a BetterDiscord plugin that allows you to define custom commands and respond to them dynamically within your Discord server. Designed for flexibility and ease of use, it is perfect for managing server rules, creating fun responses, or customizing server interactions.

---

## Features
- **Customizable Commands**: Add, modify, or remove commands via the configuration file.
- **Dynamic Responses**: Supports formatted messages including bold, italics, and more.
- **Seamless Integration**: Works with BetterDiscord for smooth operation within your Discord client.
- **Quick Access**: Triggers responses with predefined commands.

---

## Installation
1. **Download the Plugin**: Save the `.plugin.js` file into your BetterDiscord plugin folder.  
   - On Windows: `%appdata%\BetterDiscord\plugins`
   - On macOS: `~/Library/Application Support/BetterDiscord/plugins`
2. **Enable the Plugin**: Open Discord, navigate to the BetterDiscord settings, and enable CommandCenter.

---

## Configuration
1. Locate the `CommandCenter.config.json` file.
2. Add or update commands in the JSON file. Example structure:
   - Keys represent the command keywords (e.g., `hello`).
   - Values represent the responses (e.g., `Hello, world!`).
3. Save the file and reload the plugin for changes to take effect.

---

## Usage
1. Type the defined command (e.g., `/hello`) in any channel.
2. The plugin will automatically post the configured response.
3. Commands are case-sensitive.

---

## Example Commands
- `/hello` → Responds with "Hello, world!"
- `/rules` → Displays your server rules.
- `/bye` → Responds with "Goodbye, cruel world!"

---

## Notes
- **Prefix**: Commands are triggered without a leading prefix (e.g., no `!` or `/` unless specified in the configuration).
- **Formatting**: Use Markdown syntax for bold, italics, lists, etc., in responses.

---

## Troubleshooting
- **Commands Not Responding**: Ensure the plugin is enabled in BetterDiscord settings and that the configuration file is correctly formatted.
- **Configuration Errors**: Use a JSON validator to check for syntax issues in `CommandCenter.config.json`.

---

## Contribution
Feel free to contribute by reporting issues or submitting pull requests on the GitHub repository.

---

## License
This plugin is released under the MIT License. See the LICENSE file for details.
