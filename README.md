# Formula 1 2021 GRUB Themes
2021 Formula One World Championship teams GRUB themes

## What are these?

GNU GRUB (GNU GRand Unified Bootloader) themes.

GRUB is a bootloader commonly used in GNU/Linux operating systems. A bootloader is simply a program that finds and boots up your operating system. An operating system is a program that allows you to interact with your computer (For example: GNU/Linux, MacOS, Windows). A computer is... You know...

## How this is started?

In 30 October 2021, around 4 AM, I've released my first GRUB theme, [Mercedes-AMG Petronas Formula One Team GRUB Theme](https://github.com/alisezisli/MAPF1-GRUB-Theme).

Later on, a few people around the Internet, especially from Reddit, asked about other teams. So I decided to write GRUB themes for all 10 teams of 2021 Formula One World Championship.

## Disclaimer

This project is **not affiliated** with Formula 1 or any Formula 1 team in any way.

As a fan, I've wanted to create a GRUB theme for myself and then share it with the world for free (as in freedom).

## Demo

[2021 Formula One World Championship GRUB themes](https://youtu.be/NCatlMIxr40)

## Installation (For Ubuntu 20.04)

1. `git clone https://github.com/alisezisli/Formula1-GRUB-Themes` (or download the project as a zip)
2. `cd Formula1-GRUB-Themes`
3. `sudo cp -r {The Theme You Want} /boot/grub/themes/`
4. `sudo vi /etc/default/grub`
5. Change the corresponding lines. If the lines don't exist, add them into file:
    + `GRUB_TIMEOUT_STYLE=menu`
    + `GRUB_THEME="/boot/grub/themes/{The Theme You Want}/theme.txt"`
6. `sudo update-grub`

## Installation (For other distros)

It's pretty much the same. But you might have to use some something else instead of `sudo update-grub`, like `sudo grub2-mkconfig -o /boot/grub2/grub.cfg`.

## Notes

These are my first GRUB themes and I'm sure it needs a lot of improvement. I've tested this theme with Ubuntu 20.04 in 1920x1080 resolution. Feel free to create issues and PR's.

## Screenshots

### Mercedes-AMG Petronas F1 Theme

![Mercedes-AMG Petronas F1 Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Mercedes-AMG-F1.png?raw=true)

### Red Bull Racing Honda Theme

![Red Bull Racing Honda Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Red-Bull-Racing.png?raw=true)

### McLaren Mercedes Theme

![McLaren Mercedes Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/McLaren-Mercedes.png?raw=true)

### Scuderia Ferrari Theme

![Scuderia Ferrari Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Scuderia-Ferrari.png?raw=true)

### Alpine F1 Team Theme

![Alpine F1 Team Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Alpine-F1.png?raw=true)

### Scuderia AlphaTauri Theme

![Scuderia AlphaTauri Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/AlphaTauri.png?raw=true)

### Aston Martin F1 Team Theme

![Aston Martin F1 Team Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Aston-Martin.png?raw=true)

### Williams Racing Theme

![Williams Racing Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Williams.png?raw=true)

### Alfa Romeo Racing Theme

![Alfa Romeo Racing Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Alfa-Romeo.png?raw=true)

### Haas F1 Team Theme

![Alfa Romeo Racing Theme](https://github.com/alisezisli/Formula1-GRUB-Themes/blob/main/Screenshots/Haas.png?raw=true)