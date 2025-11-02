# Glasscord

Glasscord is a clean, modern, and rounded Discord theme inspired by liquid glass aesthetics.

It combines soft blur effects, subtle brightness, and smooth animations to create an elegant and modern interface.

✨ Features

- Beautiful Liquid Glass look with adjustable blur and brightness
- Smooth transitions and motion effects
- Rounded corners for a modern UI feel
- Fully compatible with Vencord and BetterDiscord

⚙️ Customization

You can easily tweak the glass effect to match your personal style.
Open the CSS file and look for this section:

<img width="622" height="392" alt="image" src="https://github.com/user-attachments/assets/270d9bb5-c75e-40d8-b9b2-538c04a0e5be" />


You can experiment with these values until you find your preferred look.
For example:

:root {
  --blur-strength: 1.5rem;
  --brightness-level: 0.9;
}

🖼️ background customization

You can change the background image of the theme to match your own style.
Open the css file and find this line inside the settings section:

--background-image: url('https://i.imgur.com/beADHes.jpeg');

Replace the link with your own image url.
Only images hosted on imgur or other sources allowed by vencord and betterdiscord will work.
Local file paths (like C:\Users\...) are not supported for security reasons.

example:

--background-image: url('https://i.imgur.com/yourimage.png');

Once you save the file, reload discord or toggle the theme off and on again to apply the new background.

📦 Installation

1. Download the glasscord.theme.css file.

2. Move it into your Vencord or BetterDiscord themes folder.

3. Enable it in your client’s theme settings.

4. Restart Discord if changes don’t apply immediately.

Credits

Author: NMWplays

Version: 1.0.0

License: MIT
