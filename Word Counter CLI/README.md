# Word Counter CLI 📊

A cross-platform command-line utility for analyzing text files. Count words, characters, lines, and paragraphs in `.txt` and `.md` files with beautiful colorized output and informative visuals.

## Features ✨

- Count words, characters, lines, and paragraphs in text files
- Beautiful colorized output with emoji indicators
- Support for `.txt` and `.md` file formats
- Process multiple files at once with total statistics
- Interactive progress bars for large files
- Elegant animated loading effects
- Visual indicators for metric magnitudes with emoji scaling
- Cross-platform compatibility (Windows, Mac, and Linux)
- Fast performance even with large files (tested with works by Shakespeare!)

## Demo 🎬

<!-- Add a demo GIF once you've created your GitHub repository -->

## Installation 🚀

### From Source

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/word-counter-cli.git
   cd word-counter-cli
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Make the script executable (Linux/Mac):
   ```bash
   chmod +x wordcounter.py
   ```

### ### Using pip (Coming Soon)

```bash
pip install word-counter-cli
```

### Using pipx (Recommended for CLI Tools)

```bash
pipx install word-counter-cli
```

## Usage 💻

### Basic Usage

```bash
python wordcounter.py myfile.txt
```

### Using Absolute File Paths

You can analyze files anywhere on your system by providing the full path:

```bash
# Windows
python wordcounter.py C:\Users\YourName\Documents\myfile.txt

# Mac/Linux
python wordcounter.py /Users/YourName/Documents/myfile.txt
```

### Analyze Multiple Files

```bash
python wordcounter.py file1.txt file2.md file3.txt

# With absolute paths
python wordcounter.py /path/to/file1.txt /different/path/file2.md
```

### Using Wildcards

```bash
python wordcounter.py *.txt documents/*.md

# With absolute paths
python wordcounter.py /path/to/documents/*.txt /other/path/*.md
```

### Exclude Spaces from Character Count

```bash
python wordcounter.py --ignore-spaces myfile.txt
```

## Sample Output 📋

```
██╗    ██╗ ██████╗ ██████╗ ██████╗      ██████╗ ██████╗ ██╗   ██╗███╗   ██╗████████╗███████╗██████╗ 
██║    ██║██╔═══██╗██╔══██╗██╔══██╗    ██╔════╝██╔═══██╗██║   ██║████╗  ██║╚══██╔══╝██╔════╝██╔══██╗
██║ █╗ ██║██║   ██║██████╔╝██║  ██║    ██║     ██║   ██║██║   ██║██╔██╗ ██║   ██║   █████╗  ██████╔╝
██║███╗██║██║   ██║██╔══██╗██║  ██║    ██║     ██║   ██║██║   ██║██║╚██╗██║   ██║   ██╔══╝  ██╔══██╗
╚███╔███╔╝╚██████╔╝██║  ██║██████╔╝    ╚██████╗╚██████╔╝╚██████╔╝██║ ╚████║   ██║   ███████╗██║  ██║
 ╚══╝╚══╝  ╚═════╝ ╚═╝  ╚═╝╚═════╝      ╚═════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝   ╚═╝   ╚══════╝╚═╝  ╚═╝

File                   📝 Words 🔤 Chars 📊 Lines 📄 Paras
------------------------------------------------------------------------------------------
sample1.txt             57 🔸  273 🔸   13 🔹    4 🔹
sample2.md              70 🔸  461 🔸   24 🔸    7 🔸
               ★ ★ ★ ★ ★ ★ ★ ★                
TOTAL 🌟           127 🔶 734 🔶 37 🔸 11 🔶
```

## Contributing 🤝

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

### Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR-USERNAME/word-counter-cli.git
cd word-counter-cli

# Set up a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dev dependencies
pip install -r requirements-dev.txt

# Run tests
python -m unittest discover tests
```

## Roadmap 🗺️

- [ ] Add PDF file support
- [ ] Implement reading level estimation (Flesch-Kincaid)
- [ ] Add export options (JSON, CSV)
- [ ] Support for more languages and character sets
- [ ] Build web interface

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Built with Python's rich ecosystem
- Inspired by the need for quick text analysis

## Screenshots 📸

### Basic Analysis
<!-- Add screenshot once you've created your GitHub repository -->

### Multiple File Analysis
<!-- Add screenshot once you've created your GitHub repository -->

---

If you find this tool useful, please consider giving it a star ⭐ on GitHub!

## Example Output

```
File                           Words    Characters      Lines   Paragraphs
----------------------------------------------------------------------
myfile.txt                       120          743         24            5
```

## Contributing

Contributions are welcome! Feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Get Feedback

Share this project and get feedback from:
- Reddit: [r/commandline](https://www.reddit.com/r/commandline/)
- Hacker News: [Show HN](https://news.ycombinator.com/submit)
