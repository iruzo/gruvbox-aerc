<h3 align="center">
    Gruvbox theme for <a href="https://git.sr.ht/~rjarry/aerc">aerc</a>
</h3>

<p align="center">
	<img src="https://raw.githubusercontent.com/iruzo/gruvbox-aerc/main/assets/preview.webp"/>
</p>

## Previews

<details>
  <summary>:black_circle: Dark</summary>
  <img src="https://raw.githubusercontent.com/iruzo/gruvbox-aerc/main/assets/aerc-dark.png"/>
</details>
<details>
  <summary>:white_circle: Light</summary>
  <img src="https://raw.githubusercontent.com/iruzo/gruvbox-aerc/main/assets/aerc-light.png"/>
</details>

## Usage

1. Download the corresponding theme into `~/.config/aerc/stylesets/`
- dark
```sh
curl https://raw.githubusercontent.com/iruzo/gruvbox-aerc/main/gruvbox-dark > ~/.config/aerc/stylesets/gruvbox-dark
```
- light
```sh
curl https://raw.githubusercontent.com/iruzo/gruvbox-aerc/main/gruvbox-light > ~/.config/aerc/stylesets/gruvbox-light
```
3. Add this snippet to `~/.config/aerc/aerc.conf`:
```ini
[ui]
border-char-vertical="│"
border-char-horizontal="─"
styleset-name=gruvbox-$FLAVOR
```
