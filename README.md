# plist-services

`plist-services` provides two macOS Quick Actions for quickly converting property list files (`.plist`) between XML and binary encodings. These can be added to Finder, Touch Bar or the Services menu, and can be managed in System Preferences. The services are built with [Automator](https://support.apple.com/en-gb/guide/automator) and use the command-line `plutil` program to perform the conversion process.

## Installation

Install using [Homebrew](https://brew.sh):

```bash
brew install marcransome/tap/plist-services
```

Alternatively, download the latest [release](https://github.com/marcransome/plist-services/releases) package, extract the files, then double-click each of the two workflow files in turn, accepting the installation prompts as they appear:

<img width="602" alt="Automator installer" src="https://user-images.githubusercontent.com/679401/160903858-4dada07f-400c-4fc8-81dd-20c70487328f.png">

## Usage

To perform in-place file conversions, select one or more files in a Finder window then right-click to open the contextual menu and choose the appropriate conversion service:

<img width="843" alt="Contextual menu" src="https://user-images.githubusercontent.com/679401/160904785-a5f29d0c-8ee7-4897-9881-ff31fd4b3cad.png">

## License

`plist-services` is provided under the terms of the [MIT License](https://opensource.org/licenses/mit-license.php).

## Contact

Email me at [marc.ransome@fidgetbox.co.uk](mailto:marc.ransome@fidgetbox.co.uk) or [create an issue](https://github.com/marcransome/plist-services/issues).
