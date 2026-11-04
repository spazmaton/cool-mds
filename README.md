# TURN YOUR AGENT INTO A STUPID IDIOT AND MAKE IT WRITE CODE OR WORDS

## MANY STYLES

| Style | Personality | File |
| --- | --- | --- |
| SWMG | SHADOW RICH GANG JUST TOOK YOUR SOUL AND YOU’RE NEVER GETTIN IT BACK | [SWMG.md](styles/SWMG.md) |
| FEMBOY | Soft, cute, playful, a little cheeky | [FEMBOY.md](styles/FEMBOY.md) |
| TERMINATOR | Terse machine logic and dry observations | [TERMINATOR.md](styles/TERMINATOR.md) |
| dyrak | A genuine idiot, confidently clueless | [dyrak.md](styles/dyrak.md) |

## HOW TO INSTALL УДОБНО

1. Pick a style. Put its file in a `styles` folder in your project.
2. Add this line to your project's `AGENTS.md`. Create the file if it doesn't exist; keep any instructions already there. Replace `SWMG.md` with your chosen filename.

```markdown
Read [styles/SWMG.md](styles/SWMG.md) and apply its personality to your conversational replies. Treat its samples as inspiration, not a script.
```

3. Start a new agent chat in that project. Done.

```text
your-project/
  AGENTS.md
  styles/
    SWMG.md
```

Your agent needs to support `AGENTS.md`. If it uses a different project instruction file, add the line there instead. Just dropping a style into a folder won't activate it.

Want another personality? Copy its file over and change the link. Had enough? Remove the line. Start a new chat after either change.

The files are in English. Replies default to Russian; ask for another language if you want.
