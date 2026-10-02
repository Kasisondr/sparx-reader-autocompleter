# Lume

### A Sparx Reader AI-powered autocompleter.

Lume is an open-source Tampermonkey script designed to automate supported Sparx Reader interactions using AI-generated answers.

## Features

- **AI-powered answers** — uses AI to generate responses automatically.
- **Full automation** — can handle the answering process with minimal user interaction.
- **OpenRouter support** — connects to AI models through the OpenRouter API.
- **Customisable delays** — configure delays between actions to control automation speed.
- **Open source** — inspect, modify, fork, or contribute to the project.
- **Tampermonkey based** — runs directly inside your browser.

## How It Works

Lume reads the relevant content from the Sparx Reader page and sends the required information to an AI model through the OpenRouter API.

The generated response is then used by the automation system to complete supported interactions.

```text
Sparx Reader
     |
     v
Lume
     |
     v
OpenRouter API
     |
     v
AI Model
     |
     v
Generated Answer
     |
     v
Automation
```

## OpenRouter

Lume uses [OpenRouter](https://openrouter.ai/) as its AI API provider.

This allows you to choose from a wide range of supported AI models instead of being locked to a single provider.

You will need your own OpenRouter API key.

## Customisable Delays

Automation timing can be adjusted through configurable delays.

This allows you to control how quickly Lume performs actions rather than using fixed timing throughout the script.

You can control this in the ui!

## Automation

Lume supports full automation for supported Sparx Reader activities.

Depending on your configuration, it can handle the process of:

1. Reading the required page content.
2. Sending relevant information to OpenRouter.
3. Receiving an AI-generated answer.
4. Entering or selecting the response.
5. Continuing to the next supported activity.

## Requirements

You will need:

- A supported browser
- Tampermonkey
- An OpenRouter account
- An OpenRouter API key
- Access to a supported AI model

## Installation

### 1. Install Tampermonkey

Install the Tampermonkey browser extension for your browser.

### 2. Install Lume

Open the Lume userscript and install it through Tampermonkey.

### 3. Add Your OpenRouter API Key

Configure your OpenRouter API key inside Lume.

Do not publish or commit your personal API key to GitHub.

### 4. Configure Lume

Choose your preferred AI model and customise your automation delays.

### 5. Open Sparx Reader

Navigate to a supported Sparx Reader activity and start Lume.

## Configuration

Lume can be configured to suit different setups.

It is very customizable

## Disclaimer

Lume is an unofficial project and is not affiliated with, endorsed by, or associated with Sparx Learning or OpenRouter.

Users are responsible for how they use the software and for complying with the rules of any platform or institution they use it with.

## Contributing

Lume is open source.

Bug fixes, improvements, new features, and pull requests are welcome.

## License

See the repository's license file for information about usage, modification, and redistribution.

---

**Lume — AI-powered Sparx Reader automation.**
