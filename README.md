# Snap Cleaner Script
```
░█▀▀░█▀█░█▀█░█▀█░░░█▀▀░█░░░█▀▀░█▀█░█▀█░█▀▀░█▀▄
░▀▀█░█░█░█▀█░█▀▀░░░█░░░█░░░█▀▀░█▀█░█░█░█▀▀░█▀▄
░▀▀▀░▀░▀░▀░▀░▀░░░░░▀▀▀░▀▀▀░▀▀▀░▀░▀░▀░▀░▀▀▀░▀░▀
                              @sakibulalikhan.
```
A simple Bash script to remove old revisions of Snap packages and clear the Snap cache. This script is designed for Ubuntu and other Linux distributions ( Arch, Fedora, Debian, etc) that use Snap packages, ensuring you free up disk space by deleting unnecessary Snap package  revisions and caches.

## Features

- **Clear Snap Cache:** Removes all files from the Snap cache directory.
- **Remove Old Snap Revisions:** Deletes old revisions of installed Snap packages that are no longer in use.
- **User Confirmation:** Prompts for user confirmation before performing any actions.

## Usage

1. **Close All Snap Applications:** Before running the script, make sure all Snap applications are closed.
2. **Run the Script:**

    ```bash
    ./snap-cleaner.sh
    ```

3. **Follow the Prompts:** The script will ask for your confirmation before clearing the Snap cache and removing old Snap revisions.

## Prerequisites

- **Snap Package Manager:** Ensure that Snap is installed on your system.
- **Root Privileges:** The script requires root privileges to remove cache files and old Snap revisions.
- **Linux Distribution:** The script is intended for Ubuntu and any other Linux distributions ( Arch, Fedora, Debian, etc) that use Snap packages.

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/sakibulalikhan/snap-cleaner.git
cd snap-cleaner
```

Make the script executable:

```bash
chmod +x snap-cleaner.sh
```

Run the script:

```bash
./snap-cleaner.sh
```

## License and Credits

This script is released under the [MIT License](https://github.com/sakibulalikhan/snap-cleaner/blob/main/LICENSE). Some parts of the code were inspired by a tutorial from [It's FOSS](https://itsfoss.com/clean-snap-packages/).

---

**Author:** Sakibul Ali Khan  
**Follow:** [@sakibulalikhan](https://github.com/sakibulalikhan)

## Support Me:

<a href="https://www.buymeacoffee.com/sakibulalikhan" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
