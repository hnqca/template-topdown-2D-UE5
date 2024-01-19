<br />
<div align="center">
  <img src="readme/images/ue_custom_logo.png" width="230" />
  <h3 align="center">Top Down 2D</h3>

  <p align="center">
    Basic project template developed in Unreal Engine using PaperZD and Blueprints
    <br />
    <a href="#technologies">Technologies</a>
    •
    <a href="https://github.com/HenriqueCacerez/template-topdown-2D-UE5/archive/refs/heads/main.zip">Download</a>
    •
    <a href="#credits">Credits</a> 
  </p>
</div>

***

## Demonstration:

<details>
  <summary><b>Click here</b> to check the project demonstration video</summary><br>

  <!-- Player Movement --->
  <details>
  <summary>(01/12/24) <b>Player Movement.</b></summary><br>
    
  https://github.com/HenriqueCacerez/template-topdown-2D-UE5/assets/110671999/30c4b607-ce43-4d81-a2ef-b04ed48b4066

  #### **Details:**

  - Player movement in four directions: Right, Left, Up, and Down.
  - Player Animations: Idle, Run, and Sword Attack

  </details>

  <!-- Enemy and Player Attack -->
  <details>
  <summary>(01/14/24) <b>Implementing an enemy and the player's attack.</b></summary><br>
    
  https://github.com/hnqca/template-topdown-2D-UE5/assets/110671999/c8c0d9aa-8e0c-467e-9e50-49ff63140884

  #### **Details:**

  - Player Attack hitbox with the sword in four directions (right, left, up, and down).
  - A simple enemy that pursues the player within the navmesh.
  - The enemy now displays animations corresponding to its current state: (idle, moving, taking damage, and dead).
  - The color of the enemy sprite will change when it takes damage.
  - Life system for the enemy, including the ability to take damage and die.
  - A floating indicator shows the amount of damage the player has dealt to the enemy.
  - Upon dealing damage to the enemy, the player's camera will now shake.

  </details>

  <!-- Health Bar and Player Damage -->
  <details>
  <summary>(01/15/24) <b>Health Bar and Player Damage</b></summary><br>
    
  https://github.com/hnqca/template-topdown-2D-UE5/assets/110671999/d588f6b3-d250-4a9a-b06f-ad499759634a

  #### **Details:**

  - Implementation of a Health Bar widget that displays the player's health.
  - In the Health Bar, the current amount of health has been added alongside the player's maximum health.
  - Addition of an effect on the Health Bar that highlights in yellow the amount of damage received.
  - Inclusion of a blood effect in full screen and on the ground near the player, indicating that the player has taken some damage.

  </details>

  <!-- Coin System -->
  <details>
  <summary>(01/16/24) <b>Coin System</b></summary><br>
    
  https://github.com/hnqca/template-topdown-2D-UE5/assets/110671999/3556129b-1835-41f7-9bf3-a5dd21c2e1ef

  #### **Details:**

  - Creation of the coin blueprint class.
  - Coin "floating" effect on the ground.
  - Effect upon collecting the coin.
  - Creation of a widget that will display the amount of coins collected by the player.

  </details>

  <!-- Sign System and Player Interact -->
  <details>
  <summary>(01/19/24) <b>Sign System and Player Interact</b></summary><br>
    
  https://github.com/hnqca/template-topdown-2D-UE5/assets/110671999/dbac8f12-f84c-43f4-a5e7-28040c30d6ca

  #### **Details:**

  - Player Interact Input.
  - Implementation of a new interface that will handle player interactions.
  - Creation of a new actor "Sign" that will allow the inclusion of text information for players to read when approaching and interacting with the sign.
  - Creation of a blueprint widget to display the sign text on the player's screen.
  - Typewriter effect during text display. The [Typewriter effect](https://www.unrealengine.com/marketplace/en-US/product/typewriter-effect) plugin was used for this purpose.

  </details>

</details>
</details>


***

## Technologies:

- [Paper2D](https://docs.unrealengine.com/5.2/en-US/paper-2d-in-unreal-engine)
- [PaperZD](https://www.unrealengine.com/marketplace/en-US/product/paperzd)
- [Typewriter effect](https://www.unrealengine.com/marketplace/en-US/product/typewriter-effect)
- 100% [Blueprints](https://docs.unrealengine.com/5.2/en-US/introduction-to-blueprints-visual-scripting-in-unreal-engine)
- Unreal Engine [5.2](https://www.unrealengine.com/en-US/blog/unreal-engine-5-2-is-now-available)

***

## Download:

Download this project and open it by clicking on the "**BaseTopDown2D.uproject**" file.

***

> **Notice**: This project is not finished. I plan to add new features soon.

***

## Credits:

All the arts for this project were downloaded for free through the [itch.io](https://itch.io) website.

<table>
  <tr>
    <td align="center">
      <a href="https://cainos.itch.io">
        <img src="https://pbs.twimg.com/profile_images/1308319629744336896/Ka0XRHCa_400x400.png" style="border-radius: 100%;" width="100px;" /><br>
        <sub>
          <b>Cainos</b><br>
      </a>
          <b>Assets</b>
        </sub>
    </td>
    <td align="center">
      <a href="https://game-endeavor.itch.io">
        <img src="https://pbs.twimg.com/profile_images/1057581842759483393/fzlpYvfm_400x400.jpg" style="border-radius: 100%;" width="100px;" /><br>
        <sub>
          <b>Game Endeavor</b><br>
      </a>
          <b>Assets</b>
        </sub>
    </td>
  </tr>
</table>