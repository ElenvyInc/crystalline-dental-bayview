# Crystalline Dental — Bayview Village demo

A self-contained, responsive website concept for Crystalline Dental's planned second location in Bayview Village, North York.

[View the public website demo](https://crystalline-dental-bayview-demo.nushinmiv.chatgpt.site)

## Website files

- `dist/index.html` — responsive page with its styles and interactions.
- `dist/assets/` — clinic logo, doctor portrait, and concept interior images.
- `.openai/hosting.json` — existing Sites hosting identifier and static-site configuration; contains no credentials.

The site uses plain HTML, CSS, and JavaScript. Images are included locally. Google Fonts are optional external resources, with local fallback fonts when offline.

## Open locally

Open `dist/index.html` in any modern browser. No installation or build step is required.

For a local web-server preview, run this from the `crystalline-dental-demo` folder:

```sh
python3 -m http.server 4173 --directory dist
```

Then open `http://127.0.0.1:4173`.

## Demo behaviour

- Navigation, mobile menu, FAQ accordions, scroll reveals, and the appointment-request confirmation are interactive.
- The form does not transmit or store information.
- The smart visit guide uses predefined responses in the browser. It is a demonstration, not a connected AI service.
- All unknown operational facts are marked as TODO or "to be confirmed."

## Before a real launch

- Replace the downloaded web-resolution logo with the clinic's original vector/master logo file when available.
- Review the Vaughan-sourced portrait and Dr. Karamlou biography for final launch approval.
- Confirm the Bayview Village service list, address, phone, email, opening date, and hours.
- Replace concept clinic images with approved location photography if desired.
- Add only verified, consented patient reviews and their source.
- Connect the form to an approved, privacy-compliant appointment workflow.
- Add final privacy, accessibility, and terms pages.

## Reference source

The demo uses the logo, Dr. Milad Karamlou portrait/biography, service taxonomy, and core teal colour from the current Vaughan website at `https://crystallinedental.com/`. Vaughan-specific operational details are not presented as Bayview Village facts.
