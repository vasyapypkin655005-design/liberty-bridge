# Liberty settings bridge

A tiny page that the **Liberty** HUD mod for Deadlock opens invisibly inside the game's built-in browser.

Deadlock's interface can't write files, so Liberty keeps its settings in this browser's own storage
(`localStorage`) on the player's computer. The mod passes messages to the page through the address
(`#...`) and reads the answers from the page title.

The page sends nothing anywhere and stores only Liberty's settings.
