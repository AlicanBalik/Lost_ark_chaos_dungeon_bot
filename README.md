Lost ark bot to farm chaos dungeons.

Just run main.py and decide if you want configure or start. To configure you need to stay not in a big city (need to have available cast spells) to let bot get screens of your spells. After that, just run main.py and let the magic work! You need to have "Song of Escape" on your hotkeys to let the bot get out of the dungeon.

You have to stay near the column that let you enter to chaos dungeon, then just run the bot.

I used a lot of libraries like pyautogui to manage all actions, cv2 to manipulate the screen of the minimap to find the right way to ally, scale it to normal size, and move. OpenCV also allow to detect images on screen. Changed mss to win32 for faster results with capturing screen. Few more popular libraries like random, time, Image, etc. Bot use now threading that lets him get faster moves and doesn't look like a bot.

Bot work for every class in-game but first is needed to configure spells etc.

If you have any questions or ideas on how to improve the bot, just write to me on GitHub in the Issues tab!


I was inspired by @learncodebygaming (also took his screen capturing system for my bot) and his tutorial from YouTube 
https://www.youtube.com/watch?v=KecMlLUuiE4&t=3s
Highly recommend it for everyone!
