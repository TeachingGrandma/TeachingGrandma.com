# 👵 Teaching Grandma

The internet's coziest corner for understanding **AI, money, and technology** —
explained simply, warmly, and with a lot of bad jokes. A blog-style website where
every confusing topic gets the patient-grandkid treatment.

## What's here

| File | What it is |
|------|------------|
| `index.html` | Homepage — site personality, the three topic categories, and featured posts |
| `posts/ai-chatbots-explained.html` | **AI** — "What Is a Chatbot, and Why Is It So Chatty?" (the showcase post) |
| `posts/compound-interest.html` | **Money** — "Compound Interest: How Your Money Has Babies While You Nap" |
| `posts/strong-passwords.html` | **Tech** — "Why 'password123' Makes Hackers Cackle With Joy" |
| `styles.css` | All shared styling — warm cream palette, hand-drawn-ish cards, sticky notes |

## Tech stack

Plain **static HTML + CSS**. No framework, no build step, no dependencies.
All illustrations are **inline SVG**, so there are zero external image files to
load or break. The favicons are emoji embedded via data-URIs.

## How to view it

Just open `index.html` in any web browser. That's it.

Or, if you'd like to serve it locally over HTTP:

```bash
cd teachinggrandma.com
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Design notes

- **Tone:** Written as a kind grandchild patiently explaining things to Grandma —
  simple words, real-world metaphors (cookies, parrots, snowballs, sneaky raccoons),
  and a steady drizzle of humor.
- **Visuals:** Warm cream background with a soft polka-dot wallpaper, thick friendly
  outlines, drop-shadowed "paper" cards, and charming hand-drawn-style SVG characters
  (a tea-drinking grandma, a well-read parrot, a happy piggy bank, a foiled raccoon burglar).
- **Navigation:** A sticky top bar links Home ↔ each category/post, and every post has
  previous/next buttons plus a "back to home" link.
- **Responsive:** Layouts collapse gracefully on phones and tablets.
