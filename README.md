## General
____________

### Author
* Josh McIntyre

### Website
* jmcintyre.net

### Overview
* SSLInfo fetches and displays information about TLS certificates

## Development
________________

### Git Workflow
* master for releases (merge development)
* development for bugfixes and new features

### Building
* Build with Android Studio for mobile
* Use Python files for PC 

### Features
* Fetch certificate for a given hostname
* Parse out useful certificate information and display

### Requirements
* Requires at least Android 12.0 (Snow Cone) on mobile
* Requires Python on PC

### Platforms
* Android
* Windows
* Linux
* MacOSX

## Usage
____________

### GUI Usage
* Enter hostname in the text field
* Tap "Show SSL Info"
* Parsed TLS certificate info will be displayed in text

### PC GUI Usage
* Run via `sslinfoui.py`
* Enter hostname in the text field
* Click "Get certificate info"
* Parsed TLS certificate info will be displayed in text
