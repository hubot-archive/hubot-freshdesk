# Hubot: hubot-freshdesk


Integrate Freshdesk support tickets right into your chat room.

See [`src/freshdesk.coffee`](src/freshdesk.coffee) for full documentation.

## Installation

Add **hubot-freshdesk** to your `package.json` file:

```json
"dependencies": {
  "hubot": ">= 2.5.1",
  "hubot-scripts": ">= 2.4.2",
  "hubot-freshdesk": ">= 0.0.0"
}
```

Add **hubot-freshdesk** to your `external-scripts.json`:

```json
["hubot-freshdesk"]
```

Run `npm install hubot-freshdesk`

## Sample Interaction

```
user1> hubot get tickets
Hubot> Status : Open with subject "I need Spinach-flavoured Chips" , id #1234 and url http://chipslova.freshdesk.com/helpdesk/tickets/1234
```