KORYO TOURS — BHUTAN FESTIVALS / BEST TIME TO VISIT NEWSLETTER
==============================================================

FILE: koryo-bhutan-festivals-newsletter.html

HOW TO USE IN MAILERLITE
------------------------
1. Campaigns > Create campaign > "Custom HTML" editor.
2. Open the .html file in a text editor, select all, copy, paste it in.
3. Fill in the placeholders below.
4. Send yourself a test in both light and dark mode before scheduling.

{$url} and {$unsubscribe} are already in the footer and resolve
automatically.


THE ONE YOU SAID YOU'D FILL IN LATER
------------------------------------
CLIENT FEEDBACK — search the file for "TESTIMONIALS" to find the section.

There are three quote blocks, each marked with a PLACEHOLDER comment. Each
one has two things to replace:

  - the quote itself: "[ CLIENT FEEDBACK GOES HERE ]"
  - the attribution:  "[ Name ] • [ Tour and month ]"

The blocks are independent — delete any you don't need, or copy one to add
a fourth. Their left rules are teal, orange and purple in that order; if
you drop one, the remaining colours still look deliberate.

Two or three sentences per quote reads best at this width. Anything much
longer starts to compete with the four stories above it.

The section heading currently reads "Don't take our word for it" with the
line "Here's what the travellers who were actually standing there had to
say." If your feedback turns out to be about the trip generally rather
than these specific moments, soften that line to something like "Here's
how our groups described travelling with us off-season."


OTHER PLACEHOLDERS
------------------
Search the file for PLACEHOLDER — there are 26 marks in total.

IMAGES — seven, all pointing at MailerLite's grey placeholder for now:

  IMAGE 1  Hero, 600 x 340px — mask dance, or monks against the Himalaya
  IMAGE 2  Trashi Yangtse tshechu rehearsal, 486 x 220px
  IMAGE 3  Chele La Pass / young monks, 486 x 220px
  IMAGE 4  Great Global Peace Prayer, Trashigang, 486 x 220px
  IMAGE 5  Kyichu Lhakhang, 486 x 220px
  IMAGE 6  "Best time to visit Bhutan" blog thumbnail, 486 x 260px
  IMAGE 7  Featured travel guide thumbnail, 486 x 260px

  Images 2–5 are the four story cards. If you don't have a photo for one
  of them, delete that card's <img> row entirely rather than leaving the
  placeholder in — the card still looks right without it.

BEST TIME TO VISIT BLOG — three things:
  - confirm the exact blog title (currently bracketed)
  - the standfirst underneath, if you want to change it
  - the href, in two places: the image link and the "Read the post" link.
    Both currently point at /blog as a safe fallback because the exact
    post URL wasn't reachable when this was built.

FEATURED TRAVEL GUIDE — title, standfirst, and href (currently
/travel-guides/bhutan).

SIGN-UP LINK — currently https://koryogroup.com/newsletter. Point it at
your actual MailerLite form or landing page.


DESIGN NOTES
------------
Matches the Bhutan pricing newsletter exactly — same palette, fonts,
stripe treatment, dark mode and breakpoint. The two can go out as a
series and will read as a pair.

Colour split is roughly 75% white / 20% teal / 5% other Koryo colours.

  Teal (Bhutan)  #45B5AA   season comparison panel, "why small groups"
                           panel, tours button, sign-up button, eyebrows,
                           first quote rule
  Red            #E8112D   stripe, March 2025 card, "From the blog"
  Orange         #F49B1B   stripe, December 2025 card, second quote rule
  Purple         #3D3A8C   stripe, March 2026 card, "Travel guide",
                           third quote rule
  Green          #2E9B4C   stripe, Kyichu Lhakhang card

Each of the four story cards carries its own accent colour as a left rule,
so the sequence reads as four distinct moments rather than one long block.

Fonts are Circular Standard for headings, Karla for body, with
Helvetica/Arial fallbacks.

Dark mode uses prefers-color-scheme plus Outlook.com's [data-ogsc] /
[data-ogsb] hooks, with red, purple and green brightened so they stay
legible on a dark background.

Mobile breakpoint is 640px. The two-column "Two ways to see Bhutan" panel
stacks into one column there; everything else is single-column already.

600px wide, ~37KB — well under Gmail's 102KB clipping limit.


A NOTE ON THE COPY
------------------
Your source text spelled the temple "Kyichu Lhakhang" and the eastern
dzongkhag "Trashi Yangtse" / "Trashigang" — I've kept those spellings
consistent throughout. The dzong in the March 2025 story appears as
"Trashi Yangtse Dzong".

The fourth story (the Royal Grandmother at Kyichu Lhakhang) had no date in
the source, so its card is labelled by place rather than by month. Add a
date to that line if you have one — it would match the other three.
