WhatsApp Group Management

A WhatsApp bot built with Baileys for managing WhatsApp groups. It provides common moderation and administration features such as adding, removing, promoting, and demoting participants, as well as sending and receiving messages.

Features

- Add and remove group members
- Promote and demote group admins
- Send text messages to groups
- Receive and process incoming messages
- Extensible command system for custom features

Prerequisites

- Node.js 14 or later
- npm
- A WhatsApp account for authentication

Installation

1. Clone this repository:
   
   git clone <repository-url>
cd whatsapp-group-management

2. Install dependencies:
   
   npm install

3. Start the application:
   
   npm start

4. Scan the QR code displayed in the terminal using WhatsApp to authenticate the session.

Usage

The bot listens for commands in groups where it is present and has the required permissions.

Examples:

- "!add 1234567890"
- "!remove 1234567890"
- "!promote 1234567890"
- "!demote 1234567890"
- "!send Hello, everyone!"

The bot account must be a group administrator to perform membership and role-management actions.

Project Structure

- "index.js" – Main application entry point
- "package.json" – Project metadata and dependencies

Troubleshooting

- If no QR code appears, ensure your internet connection is working and restart the application.
- If group actions fail, verify that the bot account is a group administrator.
- If authentication expires, delete the saved session data (if any) and log in again.
- Make sure the installed Baileys version matches the API used in your code.

Disclaimer

Use this software only for groups and accounts that you own or are authorized to manage. Comply with WhatsApp’s Terms of Service and applicable laws.
