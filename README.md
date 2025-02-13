# Andstation 3 - PS3 Emulator for Termux

This is a PS3 emulator called **Andstation 3** that runs on Termux, allowing you to play PS3 games on your Android device.

## Prerequisites

- Termux installed on your device. (Download from [Play Store](https://play.google.com/store/apps/details?id=com.termux) or [F-Droid](https://f-droid.org/packages/com.termux/)).
- A powerful Android device (Snapdragon 8 or higher recommended for good performance).

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Afk-unkown/Andstation-3.git
   cd Andstation-3
   ```

2. **Run the installation script**:
   ```bash
   bash install.sh
   ```

3. The script will install the required dependencies, and you can now proceed to build the emulator.

## Running a Game

1. Download a PS3 game in ISO format.
2. Run the game with this command:
   ```bash
   ./run_game.sh /path/to/game.iso
   ```

## Notes
- Performance will vary based on your device’s specifications.
- This emulator requires significant CPU and RAM resources. Lower-end devices may experience slow performance.
- Please ensure you have legal copies of the games you are running.

## Troubleshooting
- If you encounter issues during installation, make sure that your device is up-to-date with the latest version of Termux and all dependencies.
