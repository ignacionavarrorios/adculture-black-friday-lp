# AdCulture Black Friday landing

One page: `index.html`. Media lives in `public/assets/`.

```
npm install
npm run dev
```

## Settings (top of the script in index.html)
- `FORM_ENDPOINT`: paste a form webhook (GoHighLevel). While empty, the form opens the visitor's email app.
- `DEADLINES`: 30 November, then 10 December 2026, Malta time. Preview a date with `?now=2026-12-02T10:00:00%2B01:00`.
- `data-on="false"` on the `stats` section hides the counters and hero chips.

## Check before publishing
- Counter figures come from adculturemedia.com. Confirm them.
- Six testimonial videos load from adculturemedia.com and their posters from ad-culture-media-vsl.lovable.app. Copy them into `public/assets/` if those sites change.
