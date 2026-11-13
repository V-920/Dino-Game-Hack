# Chrome Dino Game Hack

A tiny JavaScript script that prevents the Chrome Dino game from ending when you hit an obstacle.

## How it works

The script replaces the game's `gameOver` function with an empty function:

```javascript
Runner.instance_.gameOver = () => {}
```

As a result, the normal game-over action is disabled.

## How to run it

1. Open Google Chrome.
2. Go to `chrome://dino`.
3. Start the Dino game.
4. Open Chrome DevTools by pressing `F12` (or `Ctrl + Shift + J` on Windows/Linux).
5. Select the **Console** tab.
6. Paste the code from `Dino Game Hack.js` into the Console and press `Enter`.
7. Play the game. The game-over action should now be disabled.

If Chrome displays a paste-protection warning, follow the instruction shown in the Console before pasting.

## Notes

- This is a browser-console script, not a Chrome extension.
- You need to run it again after reloading the page.
