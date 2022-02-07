# Poodle [![Rust](https://github.com/poyea/poodle/actions/workflows/rust.yml/badge.svg)](https://github.com/poyea/poodle/actions/workflows/rust.yml)
Not a 🐩 (Poodle), but a word-guessing game from your terminal 🟩⬛🟩🟨🟩

## Features
* ✅ In Rust 🦀
* ✅ Attempt logs
* ✅ Rules of the [original game](https://www.powerlanguage.co.uk/wordle/)
* ✅ Customizable, extendable, localizable
* ✅ More to come

## How to use it

#### Guess today's riddle
```bash
$ poodle start
```
<details>
    <summary>An example (SPOILER!!!)</summary>

    $ poodle start
    [Feb 02, 2022] Hello poodler!
    Your guess (6) → delta
                    🟩🟨🟨⬛⬛
    Your guess (5) → dwile
                    🟩🟨⬛🟨🟨
    Your guess (4) → dowel 
                    🟩🟩🟩🟩🟩

    <>==========<>
    Poodle Feb 02, 2022 3/6
    🟩🟨🟨⬛⬛
    🟩🟨⬛🟨🟨
    🟩🟩🟩🟩🟩
    <>==========<>

</details>

#### Display full logs
```bash
$ poodle log
```

#### Get help message
```bash
$ poodle -h
poodle 0.3.0
John Law <poyea@pm.me>
Not a 🐩 (Poodle), but a word-guessing game from your terminal 🟩⬛🟩🟨🟩

USAGE:
    poodle <CMD>

ARGS:
    <CMD>    Instruction [possible values: start, log]

OPTIONS:
    -h, --help       Print help information
    -V, --version    Print version information
```

## Building Poodle
```sh
$ cargo -V
cargo 1.56.0 (4ed5d137b 2021-10-04)
$ cargo run                   # run
$ cargo build --all --release # build
$ cargo test --all --release  # test
$ cargo doc --all --release   # documentation
```

## If you like this, please
* Star
* Fork
* Contribute

## License
This repository is licensed under MIT. See also [LICENSE](LICENSE) for details. Poodle is inspired by **Wordle**. **Wordle** is developed by Josh Wardle. The original game can be accessed [here](https://www.powerlanguage.co.uk/wordle/).
