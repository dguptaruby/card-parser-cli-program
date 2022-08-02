# Adzymic README
## Cli program to display and filter Magic The Gathering cards.

This is a cli program to fetch and filter magic the gathering cards
It will print the data fetch from the public API provided by https://magicthegathering.io
It will print below features as a part of challege program.

## Features

- Returns a list of **Cards** grouped by **`set`**.
-  Returns a list of **Cards** grouped by **`set`** and within each **`set`** grouped by **`rarity`**.
- Returns a list of cards from the **Tenth Edition (10E)** set that ONLY have the colours `red` **AND** `blue`

## Installation

Clone this repository and run this cli program through below commands.

```sh
git clone https://github.com/dguptaruby/portfolio.git
cd magic_cards
chmod +x bin/cards
```


## Running this CLI Program
Go to root directory of the cloned repository and run below command with options `set` as arguments
```sh
cd magic_cards
./bin/cards --set 10E
```

## License

MIT

**Free Software**
