# Personalized Tabbed Fork

This repository contains a personalized fork of Tabbed, a simple generic tabbed frontend to xembed-aware applications, with patches applied to enhance its functionality and appearance.

Feel free to explore and adapt this customized Tabbed fork to suit your own preferences and requirements.

## Applied Patches

- `alpha`: Allows tabbed to handle windows with transparency.
- `autohide`: Hides tab bar if only one tab is open.
- `basenames`: Shows only the basename of the tabbed title. Toggle with -b.
- `center`: Centers window titles in tabs.

## Installation

1. Clone the repository to your local machine.
   ```shell
   git clone https://github.com/AkamQadiri/tabbed
   ```

2. Compile and install Tabbed by running the following command within the cloned repository:
   ```shell
   sudo make clean install
   ```
