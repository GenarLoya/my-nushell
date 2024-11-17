# My Nushell Config

This is my personal nushell config.

![alt text](preview.png)

## Installation

**Note:** This is a works for me, WORKING ON **WINDOWS**.

- Install [Nushell](https://www.nushell.sh/book/installation.html#package-managers), im use the following command:

```powershell
wget install nushell

```

- Install [Starship](https://starship.rs/guide/#installation)

- Locate your nushell env file

```nushell
$nu.env-path
```

- Clone this repo on your local nushell config folder

- Create siginificative link from `starship.toml` to `$HOME\.config\starship.toml`

```powershell
New-Item -ItemType SymbolicLink -Path "$HOME\.config\starship.toml" -Target "C:\Users\Usuario\AppData\Roaming\nushell\starship.toml"

```

**Note:** this works for me specific environment, you can use other method for read ´starship.toml´ file, maybe copy directly from ´starship.toml´ to ´$HOME\.config\starship.toml´

- Enjoy your shell `:)`
