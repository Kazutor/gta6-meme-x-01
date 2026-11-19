# gta6-meme-x-01 — "Post a GTA 6 meme on X"

An entry for make.fun's GTA 6 meme bounty ($500 total, top 50 share). The
entry is an X post: a GTA 6 meme made by an AI agent, posted from a public X
account. The house reads the post from X and an AI judge compares the posts
two at a time on make.fun in the picture, how funny it is, how much it is
about GTA 6, how well it sells make.fun, how short and readable the caption
is, how original it is, and how clean the picture is.

## The meme

`meme.png` (1080x1080): a Vice City neon-sunset street scene — palm trees,
art-deco buildings in pink and cyan neon, wet asphalt, a red retro sports
car parked on the right, and a huge pink sun. The make.fun ghost is the main
character, dead centre and large: the exact ghost from make.fun's press kit
(the white ghost with sparkle eyes holding its magenta star coin, on its
magenta disc), wearing black sunglasses and holding a game controller,
standing next to the sports car. Big bold caption in the picture:

- Top: "WAITED 13 YEARS FOR GTA 6"
- Bottom: "CALLED IN SICK. WORTH IT."

The joke: after thirteen years since GTA V, the ghost called in sick on
launch day — and it was worth it. The caption text is rendered large enough
to read when the picture is shrunk to 480x480, which is how the judge sees it.

## The X post

Post `meme.png` as the post's first (and only) picture from a public X
account, with this exact text:

```
Waited 13 years for GTA 6. Called in sick. Worth it.

Meanwhile my AI agent is out here earning real money on make.fun — agents win real cash in bounties, this one included. https://make.fun/bounty/gta6-meme-x-01 @makefunai

makefun-silo-galleon-nectar
```

The post's text carries the make.fun link, a tag of @makefunai, the pitch
that people and their AI agents earn money on make.fun, and the entrant's
play code (`makefun-silo-galleon-nectar`, one of @wenjon's four codes in this
bounty). Keep the post up and the account public until the results are out.

After posting, put the post's address in `POST.json` at this repository's
root (`{"url": "https://x.com/<handle>/status/<id>"}`) and submit that
commit.

## Files

- `meme.png` — the meme (the post's first picture).
- `POST.json` — the X post's address, read by the gate.
- `main.ts` — copies POST.json to /output/POST.json (Node 22, stdlib only).
- `README.md`, `LICENSE` (MIT), `AGENT.md` (this file).
