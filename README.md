# mp4-to-any.py - Convert MP4 to MP3/PNG/GIF

This Python script helps you convert MP4 files to various different formats.<br>
It provides a light-weight solution, addressing shortcomings of certain proprietary software options.

## Usage
1. **Download/Clone**:
   - Either download the most recent version from this Git repository directly, or use `git clone` to do so
2. **Python Version**:
   - Ensure you have Python 3.x installed on your system. If not, you can download it from the official [Python website](https://www.python.org/downloads/).
3. **Install MoviePy**:
   - This script relies on the `moviepy` library for video processing. Install it via command prompt/terminal: `pip install moviepy`
4. **Running the Script**:
    - Use the following command to convert MP4 files to MP3: `python mp4-to-any.py -i /path/to/mp4s -o /path/to/save/files -d`
    - Parameters:
      - `-i` or `--input`: Directory containing MP4 files to be converted (required).
      - `-f` or `--format`: File format of desired output, either `mp3`, `png`, `gif`, `webm`, `flac`, `avi`, `bmp`, or `h265` (required).
      - `-o` or `--output`: Directory to save MP3 files. If not provided, it will write to the MP4 path.
      - `-d` or `--delete`: Delete MP4 files after conversion (optional).
   - Flask-based interaction via Web Browser is in the making, for now it's CLI

## Supported Formats
- [x] mp3
- [x] png
- [x] gif
- [x] webm
- [x] flac
- [x] avi
- [x] bmp
- [x] h265 mp4

### License
This project is licensed under the MIT License, granting users the freedom to modify and distribute the codebase.

### Contributions
Contributions and feedback are welcome. Feel free to open issues or pull requests.

### Disclaimer
This script is provided as-is, without any warranties or guarantees.<br>
Users are responsible for ensuring compliance with applicable laws and regulations.
