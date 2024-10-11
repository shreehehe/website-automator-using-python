# URL Opener Script

This Python script opens a set of predefined URLs in your default web browser, based on the category ("work" or "personal") passed as a command-line argument.

## How It Works

The script accepts a single argument that corresponds to either the `work` or `personal` set of URLs. Once you provide the correct argument, it will open each URL in a new browser tab.

### URL Sets

- **Work**: URLs related to work, such as productivity tools or work-related websites.
- **Personal**: URLs for personal use, like music, to-do lists, or video streaming sites.

## Prerequisites

- Python 3.x installed on your system.
- Access to a default web browser.

## How to Use

1. Clone the repository or download the script:

   ```bash
   git clone https://github.com/yourusername/repo-name.git
   cd repo-name
python script.py work
python script.py personal


Usage: python script.py <set_name>
Available sets:
- work
- personal

