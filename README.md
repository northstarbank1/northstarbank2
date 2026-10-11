# Northstar Bank Demo

A responsive, fictional banking dashboard prototype with illustrative account balances and sample transactions. This is a reconstructed, simplified package inspired by the Northstar Bank demo; it is **not** a byte-for-byte export of the original AppDeploy project.

## Project structure

```text
northstar-bank-demo/
├── index.html          # Vite entry page
├── package.json        # Project metadata and commands
├── vite.config.js      # Vite configuration
├── .gitignore          # Files excluded from Git
├── public/
│   └── favicon.svg     # Site icon copied to the build output
└── src/
    ├── main.js         # Demo login and dashboard interactions
    └── styles.css      # Desktop and mobile responsive styles
```

## Requirements

- Node.js 18 or newer
- npm (included with Node.js)

## Run locally

1. Extract the ZIP.
2. Open a terminal in the extracted `northstar-bank-demo` folder.
3. Install the development dependency:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL printed in the terminal, usually `http://localhost:5173/`.

## Create a production build

```bash
npm run build
npm run preview
```

The production files are written to `dist/`.

## Open on a phone

For a quick preview, open the live demo in your phone browser:

https://northstar-banking-demo-hlxmhy.v2.appdeploy.ai/

To test your local copy on a phone, connect the phone and computer to the same Wi-Fi, run `npm run dev -- --host 0.0.0.0`, and open the network URL Vite prints in the terminal on your phone. Depending on your network, firewall settings may need to allow the connection.

## Demo limitations and safety

- This is a fictional visual demo, not a real bank website.
- Never enter real banking credentials or personal financial information.
- Balances and transactions are made-up illustrative data.
- Sign-in is a local visual interaction only; no authentication or account storage exists.
- Money transfers are disabled. The check-file picker only displays a filename locally; it does not upload or deposit a check.
- No real bank connection or payment processing is provided.
