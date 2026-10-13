# Liberty settings bridge

A tiny page that the **Liberty** HUD mod for Deadlock opens invisibly inside the game's built-in browser.

Deadlock's interface can't write files, so Liberty keeps its settings in this browser's own storage
(`localStorage`) on the player's computer. The mod passes messages to the page through the address
(`#...`) and reads the answers from the page title.

The page stores only Liberty's settings. It also counts game launches anonymously with GoatCounter
(at most once every 6 hours per player): only the fact that a launch happened is sent — no nickname,
Steam ID or settings. Nothing else is sent anywhere.
