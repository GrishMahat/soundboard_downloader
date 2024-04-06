

# Soundboard Downloader

This project provides two Python scripts to download MP3 files from soundboard websites: `101soundboards.py` for [101soundboards.com](https://www.101soundboards.com/) and `downloader.py` for [soundboard.com](https://www.soundboard.com/). These scripts enable users to download audio files from specific soundboard profiles with ease.

## Table of Contents

- [Usage](#usage)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Usage

The project consists of two Python scripts: `101soundboards.py` and `downloader.py`. Both scripts take a soundboard URL as input and download the associated audio files.

## Features

### `101soundboards.py`

- Downloads MP3 files from [101soundboards.com](https://www.101soundboards.com/).
- Utilizes threading for faster downloads.
- Accepts a soundboard URL as input.
- Saves downloaded files to a specified output directory.

### `downloader.py`

- Downloads MP3 files from [soundboard.com](https://www.soundboard.com/).
- Supports multi-threaded downloading for faster processing.
- Prompts the user for the soundboard URL.
- Saves downloaded files to a specified output directory.

## Prerequisites

- Python 3.x
- Required Python packages:
  - `requests`
  - `bs4` (Beautiful Soup)
  - `pathlib`
  - `argparse`
  - `multiprocessing`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/soundboard-downloader.git
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## How to Use

1. Navigate to the project directory containing the Python scripts.
2. Choose the appropriate script based on the soundboard website.
3. Execute the script and follow the prompts to provide the soundboard URL and output directory.
4. Wait for the download process to complete.

Example usage of `101soundboards.py`:

```bash
python 101soundboards.py -d /path/to/output/directory https://www.101soundboards.com/boards/board-url
```

Example usage of `downloader.py`:

```bash
python downloader.py
```

## Contributing

Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests via GitHub.

## License

This project is licensed under the [MIT License](LICENSE).

