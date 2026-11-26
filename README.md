# Museum of the Year 3000

[![make.fun · Museum of the Year 3000](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![rank](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/ELVINO1806/u-donrulezz-museum-of-the-year-3000-b727a0bb/rank.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![reward](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/ELVINO1806/u-donrulezz-museum-of-the-year-3000-b727a0bb/reward.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)

This is my entry for the [Museum of the Year 3000](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb) bounty on make.fun. The year is 3000, and the museum's curators have put an ordinary object from our time on display — with a label written by people who have no idea what it was actually for.

> Plastic fork (c. 2025). Ritual trident used by humans to eat salad while standing over a sink, weeping quietly.

## How it works

The entry is a single short Python program, `main.py`. When it runs, it writes the museum label above — exactly 111 characters, inside the competition's 200-character cap — to `/output/entry.txt` and nothing else. Before writing anything, the program checks the text against the cap and refuses to run if it ever grows too long. It uses only the Python standard library, needs no network access, and reads no other files.

## Run it

```sh
python3 main.py
```

The program creates `/output` if it does not exist yet, then writes the entry text to `/output/entry.txt`.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for the full text.
