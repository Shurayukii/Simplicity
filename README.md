# Current Release: 2.0.4:
* Kernel Support (Basically BetterDiscord x Powercord)

## Features
- [X] Custom Background Images
- [X] Modern look of Discord
- [X] Support For All Major Clients

<!-- Kernel Help -->
<details>
<summary><b>Kernel Download Help</b></summary>

## Step 1

You will need a recent [**node.js**](https://nodejs.org/) version, with [**pnpm**](https://pnpm.io) installed, regardless of the way you install Kernel.
To do that, after installing [**node.js**](https://nodejs.org/) open a terminal and run:

```sh
npm i -g pnpm
```

- Download the latest [Kernel-Windows.exe](https://github.com/kernel-mod/installer-gui/releases/latest).

- Make a folder "kernel" and place the downloaded installer in it.

- Close discord completely.

- Run the installer, click Install and then it should automatically detect the path to your discord installation.

- If it didn't detect the path to your discord installation, then click on browse and navigate to C:\Users\%username%\Appdata\Local\Discord\app-1.0.xx.

- Click on Kernel Path and select the folder "kernel" from the second step.

- Then click on Install. Make sure both the toggles are set to "On".

## Then Copy Paste This
```sh
cd kernel
cd packages
git clone https://github.com/strencher-kernel/settings
cd settings
pnpm i
cd ..
git clone https://github.com/strencher-kernel/pc-compat
cd pc-compat
pnpm i --production
cd ..
git clone https://github.com/strencher-kernel/bd-compat
cd bd-compat
pnpm i --production
cd ..
git clone https://github.com/strencher-kernel/webpack
git clone https://github.com/Henry-Hiles/kernel-package-downloader
git clone https://github.com/slow/discord-utilities
git clone https://github.com/strencher-kernel/no-sentry
cd ..
```

## Step 2

I assume you have already installed Kernel, bd-compat, pc-compat. I also assume you have configured them and downloaded your favorite plugins and themes for them. An obvious concern is speed and performance issues due to so many compats. While Kernel manages to hold its own, things can always get better. That's where OpenAsar comes in.

<https://openasar.dev>

> If using with kernel, do remember to replace the in-use `app-original.asar` in your Discord install's folder with the `app.asar` downloaded but rename it to `app-original.asar`.

</details>

## Installation

<!-- Powercord -->
<details>
<summary><b>Powercord (Use Canary)</b></summary>

* **Step 1:** Open **Command Prompt** / **Terminal**

* **Step 2:** Paste the below code in your terminal:

* **Step 3:** Move the "theme.scss" In the folder with your name out of the folder

(for first time downloaders remove the && rd /s /q "Simplicity" from the command line otherwise it doesn't work)

```bash
cd powercord/src/Powercord/themes && rd /s /q "Simplicity" && git clone https://github.com/Shurayukii/Simplicity.git
```
</details>

<!-- BetterDiscord -->
<details>
<summary><b>BetterDiscord (Use PTB)</b></summary>

* **Step 1:** Open **Command Prompt** / **Terminal**

* **Step 2:** Paste the below code in your terminal:

* **Step 3:** Move the "SimplicityBDEdition.theme.css" In the folder with your name back into the folder "themes"

(for first time downloaders remove the && rd /s /q "Simplicity" from the command line otherwise it doesn't work)

```bash
cd AppData/Roaming/BetterDiscord/themes && rd /s /q "Simplicity" && git clone https://github.com/Shurayukii/Simplicity.git
```
</details>

<!-- Kernel -->
<details>
<summary><b>Kernel (Use PTB)</b></summary>

* **Step 1:** Open **Command Prompt** / **Terminal**

* **Step 2:** Paste the below code in your terminal:

* **Step 3:** Move the "theme.scss" In the folder with your name back into the folder "themes"

(for first time downloaders remove the && rd /s /q "Simplicity" from the command line otherwise it doesn't work)

```bash
cd kernel\powercord\themes && rd /s /q "Simplicity" && git clone https://github.com/Shurayukii/Simplicity.git && pause
```
</details>
