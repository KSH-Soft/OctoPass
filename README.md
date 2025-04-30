
# OctoPass - Password Generator and Manager

<img src="https://raw.githubusercontent.com/KSH-Soft/OctoPass/refs/heads/main/img/gui0.PNG" width="400"> <img src="https://raw.githubusercontent.com/KSH-Soft/OctoPass/refs/heads/main/img/guiBP0.PNG" width="400">


OctoPass is open source software written in Python, combining a comprehensive, secure and customizable password manager and generator.
Translated into English and French

🔐 Main features:

- 🔑 Secure access via a MasterPassword: without this master password, it's impossible to decrypt the database.

- 🧠 Encrypted password storage, with custom titles, icons, notes, and associated links.

- 🧬 Customizable password generation:

- Choice of character types (lowercase, uppercase, numbers, symbols).

- Definition of length and ratio between character types

- 3 password format styles (random, symbol at end, uppercase + symbol)

- 📊 Password complexity evaluation in percent (0% to 100%)

- 🕓 Configurable password change reminder system (from 3 months to 3 years)

- 🧩 Option to avoid visually ambiguous characters (e.g. O/0, I/l)

- Optional integration with a Windows account to semi-automate local user password change

- 📁 Operates entirely locally, on USB stick, external disk, server or remote machine

🖥️ The interface is available in two versions: retro and modern, to suit your preferred style.

🛡 An example database is available [HERE](https://github.com/KSH-Soft/OctoPass/raw/refs/heads/main/OctoBase.OP) (it contains 3 accounts and 1 image).

## Demo

![App Demo](https://github.com/KSH-Soft/OctoPass/blob/main/img/GUIBP.gif?raw=true)


## Screenshots GUI EN & FR
<img src="https://raw.githubusercontent.com/KSH-Soft/OctoPass/refs/heads/main/img/gui0.PNG" width="400"> <img src="https://raw.githubusercontent.com/KSH-Soft/OctoPass/refs/heads/main/img/gui0FR.PNG" width="400">

<img src="https://raw.githubusercontent.com/KSH-Soft/OctoPass/refs/heads/main/img/guiBP0.PNG" width="400"> <img src="https://raw.githubusercontent.com/KSH-Soft/OctoPass/refs/heads/main/img/guiBP0FR.PNG" width="400">

<img src="https://raw.githubusercontent.com/KSH-Soft/OctoPass/refs/heads/main/img/guiBPParam.PNG" width="400">



## Roadmap

- Add more styles

- Add other useful features

- Correct the complexity function

- Correct password generation function

- Simplify the interface as much as possible

- Reduce application weight (currently 63MB)
## FAQ

#### What happens if I forget my MasterPassword?

The MasterPassword is the only key needed to decrypt the database. Without it, it's impossible to retrieve stored data. However, if you still know it, you can change it at any time from the application.

#### Where is my data stored?

All data is stored locally in an encrypted file. No data is sent online. OctoPass can be used from a USB key, external disk or remote server, without an Internet connection.

#### Are my passwords really secure?

Yes, they are. The output file is fully encrypted, and no password is written to a temporary file. Data is only loaded into memory after decryption via MasterPassword, preventing any accidental leakage to disk.

#### How does Windows integration work?

If you mark an account as a “Windows account”, OctoPass can remind you when to change it, and assist you in automatically changing the user's password on the local workstation or Active-Directory (currently untested on AD).
## Collaborators

Special thanks to everyone who contributed to this project.

- KITSU (aka Serana)


## Authors

- [@KSH-Soft](https://github.com/KSH-Soft)

