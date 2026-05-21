
# WhatsApp Sender

A simple web dashboard for bulk WhatsApp messaging and customer management.

## Quick Start

- Open `public/index.html` in your browser.
- Or run a lightweight static server from the project root:

```bash
# using Python 3
python -m http.server 8000

# or with npm (install `serve` if needed)
npx serve public
```

## Features

- Add and manage customers
- Create and manage message templates
- Schedule bulk messages
- Open multiple WhatsApp chats with pre-filled messages
- Export/Import customers via CSV
- Quick Send feature for individual messages

## Usage

1. Open the app in your browser (see Quick Start).
2. Add customers with their phone numbers (include country code).
3. Create or select a message template and set any variables.
4. Schedule or generate messages for the selected customers.
5. Open chats in WhatsApp Web to send messages or use the Quick Send option.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage for data persistence
- WhatsApp Web (uses URL-based chat links)

## Contributing

Contributions are welcome — open an issue or submit a pull request with changes.

## License

See the `LICENSE` file in the repository if present.

