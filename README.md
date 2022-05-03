# How to use Dark Reader

### Top Section

![Top Section](/darkreader-top-section.png)

- Toggle site button adds the current site into the ignore list (or removes it from there)
- On/Off switch enables or disables the extension.
- Click on the links under the buttons to modify the hotkeys for the extension.
- Note: If the toggle button is greyed-out, it means that the browser restricts injecting scripts into the current page.

### Filter Settings

![Filter Section](/darkreader-filter-settings.png)

Adjusting the mode, brightness, contrast, sepia and saturation ("grayscale") settings. This can be used to better suit your screen parameters and the lighting in the room.

### Custom Site Settings

![Custom Site Section](/darkreader-custom-site-settings.png)

The Only for button determines whether the above filter settings should only be applied to the current website.

To use, first click the button (which will become highlighted), then adjust the settings as desired for the current website. Click the button again to cancel.

### Site List

![Site List Section](/darkreader-site-list.png)

- Use Invert listed only if you wish Dark Reader to work only on listed websites.
- Not invert listed will prevent the extension from working on listed websites.
- Possible patterns for values are google.com, mail.google.com, google.*, google.com/maps etc.
- Clicking the Toggle button (in Top section) adds the current site into this list.

### More Tab

![More Tab Section](/darkreader-more-tab.png)

- Pick a font from list (or enter font name on Firefox), click the checkbox.
- Adjust the text stroke.
- Select a theme generation mode.

### Theme Generation Modes

![Theme Generation Section](/darkreader-theme-modes.png)

- Filter is the initial Dark Reader mode based on CSS filters. It inverts the whole page and reverts some parts back. Requires GPU resources. It is fast and powerful, but has several issues: it disables text sub-pixel rendering, inverts already dark parts into light, causes lags on large pages, and fails to render some pages in Firefox.
- Filter+ is the same as Filter, but is based on custom SVG filters and handles colors better making images less dull. Works poorly in Firefox.
- Static rapidly generates a basic stylesheet.
- Dynamic deeply analyzes website stylesheets, background images, and vector graphics. Requires some resources on initial page load, but produces the best visual results. The work on this mode is in progress, but it already works well for many modern websites.

### Bottom Section

![Bottom Section](/darkreader-footer.png)

- Read our privacy policy, follow us on Twitter, view source and contribute on Github, read the Help documentation on this page.
- Donate – if you like the extension, please consider supporting the active development of Dark Reader. Crowdfunding is powered by Open Collective, which currently uses Stripe for handling payments.
- News – notifies about release notes and important events.
- Developer tools – opens a config editor for the current theme mode.
