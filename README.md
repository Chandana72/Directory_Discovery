# Directory Discovery 🕵️‍♂️

![Directory Discovery](https://img.shields.io/badge/Version-1.0-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg) ![Python](https://img.shields.io/badge/Python-3.8%2B-yellow.svg)

Welcome to the **Directory Discovery** project! This repository hosts a Python-based Hidden Directory Scanner tailored for ethical hacking and cybersecurity learning. It scans target websites for hidden or unlisted directories using a wordlist and prints the discovered paths. This tool is particularly useful for penetration testers conducting reconnaissance during web application security assessments.

You can download the latest version of Directory Discovery from the [Releases section](https://github.com/Chandana72/Directory_Discovery/releases). 

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features 🌟

- **Directory Scanning**: Efficiently scans websites for hidden directories.
- **Custom Wordlists**: Use your own wordlists or the default ones provided.
- **Output Display**: Clearly displays found directories in the console.
- **Ethical Hacking Focus**: Designed for use in ethical hacking and cybersecurity training.

## Installation ⚙️

To get started with Directory Discovery, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Chandana72/Directory_Discovery.git
   cd Directory_Discovery
   ```

2. **Install Required Packages**:

   Make sure you have Python 3.8 or higher installed. You can install the required packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Latest Release**:

   Visit the [Releases section](https://github.com/Chandana72/Directory_Discovery/releases) to download the latest version. Follow the instructions provided there to execute the tool.

## Usage 📖

To use Directory Discovery, run the following command in your terminal:

```bash
python directory_discovery.py -u <target_url> -w <wordlist_file>
```

### Parameters:

- `-u`: Specify the target URL.
- `-w`: Provide the path to your wordlist file.

### Example:

```bash
python directory_discovery.py -u https://example.com -w wordlist.txt
```

This command will scan the specified website using the provided wordlist and display any hidden directories found.

## How It Works 🔍

Directory Discovery employs a straightforward approach to uncover hidden directories:

1. **Input URL**: The user provides a target URL.
2. **Wordlist Usage**: The tool iterates through each entry in the wordlist.
3. **HTTP Requests**: For each entry, it sends an HTTP request to the target URL.
4. **Response Check**: It checks the response status codes to identify valid directories.
5. **Output**: The tool outputs the discovered directories to the console.

This method is effective for identifying paths that may not be easily accessible through standard navigation.

## Contributing 🤝

We welcome contributions to enhance Directory Discovery. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Open a pull request.

Please ensure your code follows the existing style and includes relevant tests where applicable.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments 🙏

- Thanks to the open-source community for their continuous support and contributions.
- Special thanks to the creators of the libraries used in this project.

## Topics Covered

This project touches on various topics within cybersecurity, including:

- **Bug Bounty**
- **Cybersecurity**
- **Directory Scanner**
- **Ethical Hacking**
- **Hidden Directories**
- **Information Gathering**
- **Penetration Testing**
- **Python Security**
- **Recon Tool**
- **URL Enumeration**
- **Web Reconnaissance**
- **Web Scanner**
- **Web Security**
- **Wordlist Attack**

## Conclusion

Directory Discovery serves as a valuable tool for anyone interested in ethical hacking and cybersecurity. Its simplicity and effectiveness make it a must-have for penetration testers and security enthusiasts alike. 

For more information, visit the [Releases section](https://github.com/Chandana72/Directory_Discovery/releases) to download the latest version and get started with your scans today!