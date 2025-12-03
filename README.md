

---

🌌 Vnto777 – Arch Linux Minimal + Hyprland Desktop

Screenshots :

<img width="1920" height="1080" alt="screenshot" src="https://github.com/user-attachments/assets/1f0767d2-229c-43a9-b426-2223bd75939a" />

<img width="1920" height="1080" alt="screenshot" src="https://github.com/user-attachments/assets/cbff0c86-c28c-41af-b723-7d8542014fe8" />

<img width="1920" height="1080" alt="screenshot" src="https://github.com/user-attachments/assets/5540aa9c-b9cf-495e-a693-89af533e235c" />

<img width="1920" height="1080" alt="screenshot" src="https://github.com/user-attachments/assets/3ec972fe-ac1b-4915-ae12-2d797d8a5850" />

<img width="1920" height="1080" alt="screenshot" src="https://github.com/user-attachments/assets/1e437eaa-5ba7-4afc-a34c-3276cdcb969b" />



---

🛠 Requirements

Tofi – Application launcher

Pywal – Color scheme generator

Waybar – Taskbar

CopyQ – Clipboard manager

Mirage – Screenshot tool

LazyVim – Text editor

WhiteSur-gtk-theme – GTK theme



---

📥 Installation

1. Cloner le dépôt :



git clone https://github.com/vnto777/dotfiles.git
cd dotfiles

2. Lister les fichiers cachés :



ls -a  # Pour voir les fichiers cachés

3. Copier les configurations :



cd .config
sudo mv fastfetch hypr kitty tofi wal waybar ~/.config

4. Installer le script du wallpaper Tofi :



cd ..
sudo cp tofi-wallpaper ~/.local/bin/

5. Copier les wallpapers :



cd
cp -r $HOME/dotfiles/Wallpaper $HOME


---



