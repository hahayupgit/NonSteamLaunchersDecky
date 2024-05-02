<p align="center">
  <img src="https://github.com/cchrkk/NSLOSD-DL/raw/main/logo.svg" width=40% height=auto
</p>

<h1 align="center">
NonSteamLaunchers - Decky Plugin 🚀
</h1>

This script installs the latest GE-Proton, installs NonSteamLaunchers under one unique Proton prefix folder in your compatdata folder path called "NonSteamLaunchers" and adds them to your Steam Library. It will also add the games automatically in real time.
So you can use them on Desktop or in Game Mode. Now available directly in the Decky Loader!

<h1 align="center">
Features  ✅
</h1>

- Automatic installation of the most popular launchers in your Steam Deck 🎮
- Handle automatically the download and installation of your chosen launchers and the games ⌚️ 
- MicroSD Support 💾 This script supports moving the entire prefix to a microSD. The script will install launchers and games to your SD card, and the launchers in Steam will point to the SD card installation. This allows you to save internal storage space on your Steam Deck!

<h1 align="center">
Supported Stores 🛍
</h1>

- Amazon Games Launcher ✔️
- Battle.net ✔️
- EA App ✔️
- Epic Games ✔️
- GOG Galaxy ✔️
- Humble Games Collection ✔️
- IndieGala ✔️
- Itch.io ✔️
- Legacy Games ✔️
- Rockstar Games Launcher ✔️
- Ubisoft Connect ✔️
- Glyph ✔️
- Minecraft ✔️
- Playstation Plus ✔️
- VK Play ✔️

<h1 align="center">
Supported Streaming Sites for games and as well as any website. 🌐
</h1>

- Website Shortcut Creator ✔️
- Xbox Game Pass ✔️
- GeForce Now ✔️
- Amazon Luna ✔️
- Netflix ✔️
- Amazon Prime Video ✔️
- Disney+ ✔️
- Hulu ✔️
- Youtube ✔️
- Twitch ✔️
- movie-web ✔️

<h1 align="left">
Finds Games Automatically
</h1> 

"NSLGameScanner.service" is also live when you use this script and continues after the script is closed and even works after your Steam Deck has restarted. This works in the background as a service file to automatically add your games to your library on every Steam restart. Currently adds:
- Epic Games 🎮
- Ubisoft Connect 🎮
- EA App 🎮
- Gog Galaxy 🎮
- Battle.net 🎮
- Amazon games 🎮
- Itch.io 🎮

<h1 align="center">
How to Install 🔧
</h1>

<p align="center">
  <a name="download button" href="https://github.com/SteamDeckHomebrew/decky-loader/releases/"><img src="https://user-images.githubusercontent.com/98482469/242361563-33f31d3d-9a69-4fca-a928-207a5d17a98f.png"  alt="Download DeckyLoader" width="350px" style="padding-top: 15px;"></a>
</p>
<!--- Thanks https://github.com/Heus-Sueh -->

* Download and install DeckyLoader
* Enter Game mode, go to the Decky Loader Settings, and change your store to `Testing`.
* Search for `NonSteamLaunchers`

* Go to desktop mode, right click the download button above and save the .desktop file to your Steam Deck desktop. 
* Go to your desktop, click the NonSteamLaunchers icon, it will download and run the latest NonSteamLaunchers.sh from this repository and run it.
* You will simply have to choose which launcher to install and let the script handle the rest. 💻 No files are left in your "Downloads" they are deleted after installation.
* After installing the plugin, you'll find the new launchers in your library under the non-steam tab. Click a launcher to see your installed games from that store, and launch them directly from Steam! If you have downloaded a game inside of your launcher, restart your Deck or quit and reopen Steam and the NSLGameScanner.service should add it to your library, even in gamemode! 🥳

<!--- TODO: handful of broken icons (cf. 🡺🡺🡺 ); probably should remove or replace them with more common font to handle unicode-->

<p align="center">
▶️ YouTube Tutorial 🡺🡺🡺 https://www.youtube.com/watch?v=svOj4MTEAVc 🡸🡸🡸 ▶️
</p>
<p align="center">
📖 Step-by-step Article 🡺🡺🡺 <a href="https://steamdeckhq.com/news/nonsteamlaunchers-adds-scan-support-launchers">here</a> 🡸🡸🡸 📖
</p>

<h1 align="center">
How to Uninstall 🗑
</h1>

+ Just run the script, and hit "Uninstall". Alternatively, if you want to totally wipe evrything from NonSteamLaunchers click "Start Fresh".
+ That's it.

<h1 align="center">
Contributing 🤝
</h1>

If you have any suggestions or improvements for this script, feel free to open an issue or submit a pull request.

You can donate to me on [ko-fi](https://ko-fi.com/moraroy), [liberapay](https://liberapay.com/moraroy), or [sponsor me on github](https://github.com/sponsors/moraroy) or [patreon](https://patreon.com/moraroy)

## Development Environment

### Dev Container

Install [Docker](https://docs.docker.com/compose/install/). Once installed, a clean dev environment with a Docker container [native to VSCode](https://code.visualstudio.com/docs/devcontainers/create-dev-container#_dockerfile) is spun up automatically. 

* [Command palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) (⇧⌘P) > Dev Containers: Reopen in Container
* F5 for debug
    * May need to select interpreter (e.g., `/opt/venv/bin/python`) first

**VSCode Extensions (Dev Container)**

* [Atom Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings)
* [Bash IDE](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode)
* [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
* [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
* [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
* [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)
* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
* [MS Visual Studio Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* [Shellcheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)

### Manual Docker Instance

If VSCode isn't present or only the python portion (cf. `__init__.py`) is being worked on, it's possible to just run a Docker container on its own. The container installs the correct version of python and any dependencies (e.g., ipython, rich) in `requirements.txt`.

```bash
# navigate to directory with Dockerfile
cd .devcontainer/

# build image
docker build -t nonsteamlaunchers .

# run container
docker run -it --rm --name=mynonsteamlaunchers --workdir=/app -v $(pwd):/app nonsteamlaunchers bash

# exit container
exit
```

### Python virtual environment

Useful for the python module(s), but extra compared to the [dev container](#dev-container) portion that covers the core shell script.

```bash
# create virtual environment
python -m venv .venv

# activate virtual environment
source .venv/bin/activate

# install dependencies
python -m pip install -r requirements.txt 
```

### Pre-commit hooks

Pre-commit hooks are installed via `pre-commit` and are run automatically on `git commit`. 

Most importantly, `ruff` is used to lint all python code.

* Install [pre-commit](https://pre-commit.com/#install)
* Install pre-commit hooks
    ```bash
    pre-commit install
    ```
* Trigger pre-commit hooks automatically on `git commit`
    ```bash
    git add .
    git commit -m "commit message"
    ```
* Bypass pre-commit hooks
  * Sometimes, it's necessary to bypass pre-commit hooks. This can be done with the `--no-verify` flag.
    ```bash
    git commit -m "commit message" --no-verify
    ```

### Conventional Commits

While not currently enforced, by using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary), it's possible to automatically generate changelogs and version numbers via [release-please](https://github.com/googleapis/release-please).

To help with that, the [commitizen](https://commitizen-tools.github.io/commitizen/) tool can be installed.

#### Usage

```bash
# install cz
npm install -g commitizen cz-conventional-changelog

# make repo cz friendly
commitizen init cz-conventional-changelog --save-dev --save-exact
npm install

# add file to commit
git add .gitignore

# run cz
λ git cz
cz-cli@4.3.0, cz-conventional-changelog@3.3.0

? Select the type of change that you're committing: chore:    Other changes that don't modify src or test files
? What is the scope of this change (e.g. component or file name): (press enter to skip) .gitignore
? Write a short, imperative tense description of the change (max 81 chars):
 (17) update .gitignore
? Provide a longer description of the change: (press enter to skip)

? Are there any breaking changes? No
? Does this change affect any open issues? No
[main 0a9920d] chore(.gitignore): update .gitignore
 1 file changed, 131 insertions(+)

λ git push
```

### Formatting

> **TL;DR**: The [Ruff formatter](https://astral.sh/blog/the-ruff-formatter) is an extremely fast Python formatter, written in Rust. It’s over 30x faster than Black and 100x faster than YAPF, formatting large-scale Python projects in milliseconds — all while achieving >99.9% Black compatibility.

* While it runs automatically on commits, it can also be run manually
    ```bash
    # check for errors
    ruff check .

    # fix (some) errors automatically
    ruff check . --fix
    ```

### Additional tooling

#### TODO

* Add [devbox](https://www.jetpack.io/devbox/) 👌

#### asdf

* Install [asdf](https://asdf-vm.com/guide/getting-started.html#_2-download-asdf)
* Add plugins
    ```bash
    asdf plugin-add python
    asdf plugin-add poetry https://github.com/asdf-community/asdf-poetry.git
    asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
    ```
* Usage
  * Install local plugins in repo
    ```bash
    asdf install
    ```
  * Install specific plugins
    ```bash
    # install stable python
    asdf install python <latest|3.11.4>

    # set stable to system python
    asdf global python latest
    ```

#### shellcheck

`.shellcheckrc` excludes various [bash language rules](https://github.com/koalaman/shellcheck/wiki/Ignore#ignoring-one-or-more-types-of-errors-forever). Useful to control noise vs. legitimate warnings/errors when using the shellcheck extension.

<h1 align="center">
License 📝
</h1>

This project is licensed under the MIT License. See the `LICENSE` file for more information.
