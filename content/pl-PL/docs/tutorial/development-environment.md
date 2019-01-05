# Środowisko developerski

Electron bazuje na środowisku uruchomieniowym Node.js. W celu przygotowania systemu operacyjnego do budowania aplikacji bazujących na Electronie, należy zainstalować Node.js, npm, wybrane IDE oraz znać wierszu poleceń twojego systemu operacyjnego.

## Konfigurowanie systemu macOS

> Electron supports macOS 10.10 (Yosemite) and up. Apple does not allow running macOS in virtual machines unless the host computer is already an Apple computer, so if you find yourself in need of a Mac, consider using a cloud service that rents access to Macs (like [MacInCloud](https://www.macincloud.com/) or [xcloud](https://xcloud.me)).

Najpierw należy zainstalować najnowszą wersję programu Node.js. We recommend that you install either the latest `LTS` or `Current` version available. Visit [the Node.js download page](https://nodejs.org/en/download/) and select the `macOS Installer`. While Homebrew is an offered option, but we recommend against it - many tools will be incompatible with the way Homebrew installs Node.js.

Po pobraniu należy uruchomić instalator i przejść proces instalacji.

Po instalacji należy sprawdzić czy wszystkie składniki oprogramowania działają tak jak powinny. Znajdź terminal znajdujący się w folderze `/Applications/Utilities` (lub poprzez wpisanie w Spotlight słowa `Terminal`). Otwórz terminal lub inny wiersz poleceń i sprawdź czy zarówno `node` jak i `npm` są dostępne.:

```sh
# Ta komenda powinna wypisać wersje Node.js
node -v

# Ta komenda powinna wypisać wersje npm
npm -v
```
Jeżeli obie komendy zwróciły wynik w postaci numeru wersji, wszystko jest przygotowane! Przed zacznięciem pracy, zalecamy zainstalowanie [edytora](#a-good-editor) przygotowanego dla języka JavaScript.

## Konfigurowanie systemu Windows

> Electron supports Windows 7 and later versions – attempting to develop Electron applications on earlier versions of Windows will not work. Microsoft provides free [virtual machine images with Windows 10](https://developer.microsoft.com/en-us/windows/downloads/virtual-machines) for developers.

Najpierw należy zainstalować najnowszą wersję programu Node.js. We recommend that you install either the latest `LTS` or `Current` version available. Visit [the Node.js download page](https://nodejs.org/en/download/) and select the `Windows Installer`. Once downloaded, execute the installer and let the installation wizard guide you through the installation.

On the screen that allows you to configure the installation, make sure to select the `Node.js runtime`, `npm package manager`, and `Add to PATH` options.

Once installed, confirm that everything works as expected. Find the Windows PowerShell by opening the Start Menu and typing `PowerShell`. Open up `PowerShell` or another command line client of your choice and confirm that both `node` and `npm` are available:

```powershell
# Ta komenda powinna wypisać wersje Node.js
node -v

# Ta komenda powinna wypisać wersje npm
npm -v
```

If both commands printed a version number, you are all set! Before you get started, you might want to install a [code editor](#a-good-editor) suited for JavaScript development.

## Konfigurowanie systemu Linux

> Ogólnie rzecz biorąc Electron obsługuje Ubuntu 12.04, Fedora 21, Debian 8 i nowsze.

Najpierw należy zainstalować najnowszą wersję programu Node.js. Depending on your Linux distribution, the installation steps might differ. Assuming that you normally install software using a package manager like `apt` or `pacman`, use the official [Node.js guidance on installing on Linux](https://nodejs.org/en/download/package-manager/).

You're running Linux, so you likely already know how to operate a command line client. Open up your favorite client and confirm that both `node` and `npm` are available globally:

```sh
# Ta komenda powinna wypisać wersje Node.js
node -v

# Ta komenda powinna wypisać wersje npm
npm -v
```

If both commands printed a version number, you are all set! Before you get started, you might want to install a [code editor](#a-good-editor) suited for JavaScript development.

## Dobry Edytor

Możemy zasugerować dwa darmowe i popularne edytory zbudowane na Electronie: [Atom](https://atom.io/) od GitHuba i [Visual Studio Code](https://code.visualstudio.com/) od Microsoftu. Oba świetnie obsługują JavaScript.

Jeśli jesteś jednym z wielu doświadczonych programistów wiesz, że praktycznie każdy IDE i edytor tekstu obsługuje dzisiaj JavaScript.
