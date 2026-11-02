# SyllabusPilot design

Reference:
https://styles.refero.design/style/cfd0fec1-f25a-4b9b-9bd0-d5b66960f2f2

Visual direction:
A friendly study notebook with a calm, readable layout.

Colors:
- Page background: cream #fdfbf9
- Secondary surfaces: warm cream #f7efe9
- Headings: cocoa #2b1a07
- Text and borders: charcoal #171717
- Decorative highlights: orange #ff6f1e

Typography and shapes:
- Soft, rounded display headings; use Fraunces as a substitute.
- Clear body text with a simple sans-serif font.
- Lowercase headings, generous spacing.
- Thin dark borders, subtle shadows.
- Cards rounded to 12px; buttons rounded to 20px.
- Buttons use dark text and outlines on cream.
- Keep decorative stickers away from important information.

App layout:
- Header: syllabus pilot
- Heading: your semester, sorted.
- Upload PDF or photo, or paste syllabus text.
- Assessment table with dates, weights, and uncertainty notes.
- Planning conversation with at most three questions.
- Week-by-week study plan.
- Download plan.ics button after successful calendar generation.

Behavior:
- Connect to the existing Python agent.
- Keep the Gemini API key on the Python side.
- Show clear loading and error messages.
- Label imported RTU information as a saved snapshot.
- Do not display fake connections or invented deadlines.
- Work on both phones and laptops.
