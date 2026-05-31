
<h1 align="center">earone's themes</h1>

<p>This is what I use to make my experience a bit cooler. This repo is work-in-progress, for now it is only my Discord theme in pure CSS, but later I will add plugin configuration. Windhawk mods and their settings coming soon.</p>

<h2 align="center">
  <strong>Discord theme</strong>
</h2>

![Screenshot](https://media.pje.ovh/unlisted/discord-aero-theme-showcase1.png)

---

<h4><strong>Prerequisites</strong></h4>

> [!WARNING]
> The following Discord themes are not guaranteed to work. <strong>Make sure you have the latest version of [Equicord](https://equicord.org/) installed. I'm not planning to make it compatible with other clients.</strong><br/>You can fork or copy all you want, but if the issue exists only outside Equicord, expect that it will be marked as wontfix.

> [!IMPORTANT]
> <img width="254" height="122" alt="image" src="https://github.com/user-attachments/assets/a75e5401-51eb-4c66-a9a8-0a1da1e1ad30" align="right" />
> Discord Neumorphic is made for the Onyx theme.<br/><br/>
> Set it in your Discord settings:<br/>
> `User Settings → Appearance → Themes → Default Themes → select Onyx`

> [!NOTE]
> <img width="270" height="92" alt="image" src="https://github.com/user-attachments/assets/d14c4c0d-00c0-41dd-ae8d-19de33746af8" align="right"/>
> In order for transparency to work, you need to set the Background Material.<br/>
> `User Settings → Equicord → Background Material → select something`

---

- **Discord Neumorphic**
  > Discord with shading and subtle glass effects. Compatible with [Equicord](https://equicord.org/).

  ```uri
  https://raw.githubusercontent.com/ear1blue/EarOnes-Themes/refs/heads/main/theme.css
  
  ```

- **Mica for Discord Neumorphic**

  > Addon for transparency compatibility, modified version of [PL7963/Discord-Mica](https://github.com/PL7963/Discord-Mica) suited for my purposes.  

  <details>
    <summary>Variables customisable in QuickCSS</summary>
    
    ```css
    :root {
      --mica-tint-background-color: #0001; /* determines the tint of the layer overlays */
    }
    
    ```
  </details>
  
  ```uri
  https://raw.githubusercontent.com/ear1blue/EarOnes-Themes/refs/heads/main/mica-support.css
  
  ```

- **Blur Stuff for Privacy**

  > Blurs other server icons until hovered, to protect you from accidentally leaking where you're lurking.
  
  <details>
    <summary>Variables customisable in QuickCSS</summary>
    
  ```css
  :root {
    --privacy-blur-amount: 10px;
    --privacy-blur-saturate: 1.2;
    --privacy-blur-contrast: 1.4;
    --privacy-blur-opacity: 0.9;
    --privacy-blur-bg-color: #777;
  
    --privacy-duration-blur-enter: 60s;
    --privacy-duration-blur-leave: 0.2s;
    --privacy-delay-blur-leave: 0.05s;
    --privacy-duration-bg-enter: 10s;
  }
  
  .stack_dbd263[aria-label='Servers'] .listItem__650eb:is(
    /* Never reveal following servers on hover */
    [data-dnd-name="SERVER NAME"], 
    [data-dnd-name="ANOTHER SERVER"],
    [data-dnd-name="..."]
  ) {
    --privacy-is-hidden: true;
  }
  
  ```
  </details>
  
  ```uri
  https://raw.githubusercontent.com/ear1blue/EarOnes-Themes/refs/heads/main/privacy.css
  
  ```

---

More coming soon!
