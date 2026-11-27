Paste into Lovable:

```text
Add the booking confirmation email that is already in this GitHub repo: ignacionavarrorios/adculture-black-friday-lp, file public/emails/booking-confirmation.html.

WHAT IT IS
A standalone HTML email sent to everyone who books a call with AdCulture Media. It thanks them, shows the date and time of the call, asks them to save it to their calendar, and shows video and written testimonials. It is sent from GoHighLevel, so it uses GoHighLevel merge tags like {{contact.first_name}} and {{appointment.only_start_date}}.

WHAT TO DO
1. Keep public/emails/booking-confirmation.html exactly as it is, so it is served at /emails/booking-confirmation.html. Do NOT convert it to React or Tailwind: email clients need the table layout and the inline styles as they are.
2. Add a page at /email-preview that shows the email inside an iframe, with two buttons: "Desktop" (680px wide) and "Mobile" (390px wide). In the preview, replace the merge tags with sample values: first name Maria, date Tuesday, 2 December 2026, time 10:30 AM, timezone Europe/Malta, location Google Meet. Links that are merge tags can point to #.
3. On the same page add a "Copy HTML" button that copies the original file (with the merge tags, not the sample values) so I can paste it into GoHighLevel.
4. Do not link /email-preview from the landing page.

RULES
- Do not change the email copy, the testimonials or the image URLs. Testimonials stay word for word.
- Keep every {{...}} merge tag exactly as written.
- No em dashes.

When done, show me the preview in desktop and mobile.
```
