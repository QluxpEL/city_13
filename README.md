<h1 align="middle">CITY-13</h1>

<p align="middle">
  <a href="https://www.roblox.com/games/14097198055/CITY-13-RP">
    <img src="https://img.shields.io/badge/Play_on_Roblox-red?style=for-the-badge&logo=roblox&logoColor=white">
  </a>
  <a href="[https://www.roblox.com/games/14097198055/CITY-13-RP](https://discord.gg/j89Xm39vY4)">
    <img src="https://img.shields.io/badge/Join_Community-royalblue?style=for-the-badge&logo=discord&logoColor=white">
  </a>
</p>
<br>
<br>

**11.8K+ visits — Half-Life 2-inspired role-play game**  
**Role:** Main scripting developer  

<p align="left">
City-13 is a highly interactive role-playing game inspired by Half-Life 2. Players navigate the city and interact with other players, taking on roles such as Civil Protection officers or members of the resistance. They complete tasks, participate in events, and engage in immersive role-play scenarios throughout the city.
</p>

---

<h2 align="left">Work-showcase</h2>

https://github.com/user-attachments/assets/6d5df592-f1ce-4ddc-b8ee-09b702009e19
> An inventory system that allows players to equip and unequip tools, swap their positions, and have their arrangement saved for the next respawn.
<br>

https://github.com/user-attachments/assets/eea9d75b-ea09-4b6a-b08e-e9cf696c9fac
> The video highlights a wide range of features, including interactive UI elements, server-authoritative handling of player purchases, a semi-advanced movement system, head-camera rotation, weapons displayed on the player’s back, and a hacking mini-game.
<br>

https://github.com/user-attachments/assets/1ffbe845-cada-4a6a-abcf-2d763e041a59
> The video shows an Console pannel that authorized players may interact with to toggle some game states.
> NOTE: The weather shown in the video was not scripted by me, everything else shown was fully scripted by me.
<br>

<p align="middle">
  <a href="https://github.com/QluxpEL/Code_snippets">
    <img src="https://img.shields.io/badge/GitHub-View_Some_Code-181717?style=for-the-badge&logo=github">
  </a>
</p>

---

<h2 align="left">Biggest dificulty & What I learned</h2>
<p align="left">
During development, the gun system was by far the most challenging part. At the time, I had no experience with raycasts, server-side hit validation, or moving bullets. The very first version was functional and highly responsive, but it handled damage client-side, which posed obvious issues.

As I improved the system, I learned about Server Authority and reworked the gun system to handle almost everything on the server. While this solved the security issues, it made the system feel less responsive.

The latest version strikes a balance between responsiveness and server authority. Animations, effects, and some client-side detection ensure players cannot shoot through walls. When a shot is fired, a “fake” bullet is created locally for immediate feedback. This ensures the player experiences near-instant results, while the server validates the shot.

Once validated, the server sends the bullet information (start and end CFrame, tween time) to all clients. Each client then animates the bullet using tweens. The server independently tracks time, and when the bullet’s duration ends, it applies damage if necessary.

This approach keeps the gun system feeling responsive while maintaining server authority over all gameplay-critical aspects.
</p>

<br>
<br>
<p align="middle">
  <a href="https://github.com/QluxpEL#-city-13">
    <img src="https://img.shields.io/badge/GitHub-return_to_main_page-181717?style=for-the-badge&logo=github">
  </a>
</p>
