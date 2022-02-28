# Tokens
tswaps.com token registry

# How to add a icon to your token on T-Swaps

1. Create a fork to your account by clicking on the fork button on the top right of the page.
2. Upload your icon to the `icons` folder in your fork.
3. Add your token details object to the tokens array in `tokens.json`.
4. You can either change the logo field to point to your hosted icon url or reference to your uploaded icon with : "https://raw.githubusercontent.com/Telos-Swaps/Tokens/main/icons/<your-token-name>.png"
5. Propose the changes with a heading: "NT-{contract_address}-{token_symbol}". e.g. "NT:token.start-START"
6. Make a pull request with your changes from your fork to main on tokens.
