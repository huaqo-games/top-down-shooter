# 2d-shooter

## Overview
This 2d Shooter game is developed using the [Pygame](https://www.pygame.org/) library and supports maps created with Tiled, utilizing the `pytmx` library for map loading.

## Prerequisites
To run the game, ensure you have the following installed on your system:

- **Python 3.13 or later**: Install the latest version of Python from the [official Python website](https://www.python.org/).
- **Pygame**: Provides graphics, input handling, and sound.
- **PyTMX**: Used for loading Tiled map files.

## Setting Up the Environment
Follow these steps to set up the game environment:

1. **Create a virtual environment:**
   ```bash
   python3 -m venv venv
   ```
   This will create a virtual environment in the `venv` directory.

2. **Activate the virtual environment:**
   On macOS or Linux:
   ```bash
   source venv/bin/activate
   ```
   On Windows:
   ```cmd
   venv\Scripts\activate
   ```

3. **Install dependencies:**
   With the virtual environment activated, install the required libraries:
   ```bash
   pip3 install pygame pytmx
   ```

### Running from the `code` Directory

```bash
cd code
python3 game.py
```

## Troubleshooting
- **Missing Modules:** If you encounter `ModuleNotFoundError`, ensure all dependencies are installed in the virtual environment.
- **Missing Assets:** Ensure all required files, such as `../graphics/other/bg.png`, are in the correct directories relative to the code.
- **FileNotFoundError:** Verify the game is being run from the correct working directory (`code` if assets are referenced with relative paths).

## License
This project is distributed under the MIT License. See the `LICENSE` file for details.

## Contributions
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## Credits
- **Developer:** Joaquin Gottlebe
- **Built With:** Pygame, PyTMX, and Python
