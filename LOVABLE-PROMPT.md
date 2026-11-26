Paste into Lovable:

```text
I'm continuing a landing page that already exists in this GitHub repo: ignacionavarrorios/adculture-black-friday-lp (private). It is a single static page, index.html, with its media in public/assets/. Read index.html first and rebuild it as a React + Tailwind page that looks and behaves exactly the same. Keep all copy, colours, fonts, section order and animations unless I say otherwise. Use the media files from public/assets/ with the same names.

CLIENT
AdCulture Media (Malta). Black Friday offer: the entire social media department for €1,250 instead of €2,500.

DESIGN (keep)
- Navy #060A1E and #0C1333, AdCulture blue #0069FE, yellow #FFD23F as the only accent, white. No red, no green.
- Headings in Bricolage Grotesque, body in Figtree. Both from Google Fonts.
- Top yellow marquee, sticky header with mini countdown, hero with offer video, counters, two pairs of crossed tilted marquees, problem section, three service cards with looping clips, 9 video testimonials, scrolling wall of written reviews, client name marquees, price box, founders, application form, footer, sticky mobile bar.

KEEP THESE BEHAVIOURS
- Countdown to 2026-11-30T23:59:59+01:00. When it passes, switch by itself to 2026-12-10T23:59:59+01:00 with the "Extended" label. After that show "The Black Friday offer has closed" and change the buttons to "Apply for the next intake". ?now=<ISO date> previews any date.
- Counters count up when they scroll into view. One setting hides the counter band and the two hero chips.
- Marquees move continuously; the review columns scroll up and pause on hover.
- Testimonial videos load only when pressed, and only one plays with sound at a time.
- Service card clips autoplay muted while visible.
- Hero video autoplays muted with a "Watch with sound" button that restarts it with sound.
- The sticky mobile bar hides while the form is on screen.
- Form: POST JSON to a webhook read from VITE_FORM_ENDPOINT, with offer: "Black Friday social media package". If the variable is empty, open an email to info@adculturemedia.com with the answers. Show a clear message on success and on failure.
- Respect prefers-reduced-motion. No horizontal scrolling on mobile.

RULES FOR COPY
- Do not change or add copy. Testimonials and quotes must stay word for word.
- Do not invent numbers, testimonials, spot counts or deliverables.
- No em dashes.

When done, show me desktop and mobile.
```
