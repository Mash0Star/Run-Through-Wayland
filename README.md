# Run-Through-Wayland
Run Proton games through GE-PROTON10-3 on your Steam Deck!
(Pretty botched bash script as its my first time doing something like this...)

# Before
![alt text](https://github.com/Mash0Star/Run-Through-Wayland/blob/main/x11.jpg "Without the Wayland Driver (x11)")

# After
![alt text](https://github.com/Mash0Star/Run-Through-Wayland/blob/main/wayland.jpg "with the Wayland driver! (cage)")

# Instructions
* 1: Download the ``Run-Through-Wayland`` from the releases section.
* 2: Extract ``Run-Through-Wayland`` into your Steam install (by default its ``~/.steam/steam/compatibilitytools.d/``).
* 3: Install GE-PROTON10-3 into the same directory as before.
* 4: Enable devmode on your Steam Deck (make sure you have a password) by inputting the command ``sudo steamos-devmode enable``.
* 5: Install ``wlroots-0.16.2-1-x86_64.pkg.tar.zst`` by doing ``sudo pacman -U ~.steam/steam/compatibilitytools.d/Run-Through-Wayland/wlroots-0.16.2-1-x86_64.pkg.tar.zst``.
* 6: Restart Steam.
* 7: Select any Proton game you wanna play and force it to use ``Run-Through-Wayland``.
* 8: Hit play and enjoy! ^w^

# Caviats
Some games might not work yet with the Wayland Driver or the script isn't good enough to handle a certian game.

# Credits and License
Check CREDITS and LICENSE.
