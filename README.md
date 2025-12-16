cat <<EOL > README.md
# e2zi

**e2zi** is a safe, interactive CLI tool for compressing files using \`xz\` and optionally creating a \`tar\` archive. 

## Features
- Interactive file selection
- Skips directories automatically
- Custom xz compression level (1-9)
- Optional tar archive
- Auto-confirm mode for non-interactive usage
- Colorful and clear terminal messages

## Installation
Clone the repository and install system-wide:

\`\`\`bash
git clone https://github.com/alinm98/e2zi.git
cd e2zi
./install.sh
\`\`\`

## Usage

Interactive mode:

\`\`\`bash
e2zi
\`\`\`

Non-interactive (auto-confirm all files, tar archive, compression level 9):

\`\`\`bash
e2zi -p /path/to/folder -l 9 -t -y
\`\`\`

Show help:

\`\`\`bash
e2zi --help
\`\`\`

## License
This project is licensed under the MIT License.
EOL

