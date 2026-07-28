KORYO TOURS — BHUTAN PRICING NEWSLETTER
=======================================

FILE: koryo-bhutan-pricing-newsletter.html

HOW TO USE IN MAILERLITE
------------------------
1. In MailerLite: Campaigns > Create campaign > choose "Custom HTML" editor.
2. Open the .html file in a text editor, select all, copy, and paste it in.
3. Fill in the placeholders listed below.
4. Send yourself a test in both light and dark mode before scheduling.

The MailerLite merge tags {$url} (view in browser) and {$unsubscribe} are
already in the footer and will resolve automatically.


PLACEHOLDERS TO FILL
--------------------
Every placeholder is marked in the HTML with an uppercase comment
(search the file for the word PLACEHOLDER — there are 14 of them).

IMAGES — all four currently point at MailerLite's grey placeholder image.
Replace each src with your own uploaded image URL.

  IMAGE 1  Hero, 600 x 340px
           Suggested: Tiger's Nest (Paro Taktsang) or the Paro valley

  IMAGE 2  In-article, 488 x 300px
           Suggested: a dzong, prayer flags, or Punakha

  IMAGE 3  Featured blog thumbnail, 486 x 260px

  IMAGE 4  Featured travel guide thumbnail, 486 x 260px

  Logo     Currently reuses the Koryo logo already hosted on MailerLite's CDN.
           No change needed unless you want a different lockup.

FEATURED BHUTAN BLOG — three things to swap:
  - the [ FEATURED BHUTAN BLOG — TITLE GOES HERE ] heading
  - the one-to-two-line intro underneath it
  - the "Read the post" href (currently /blog as a safe fallback; the
    image above it links to the "One Year of Group Tours" post)

FEATURED BHUTAN TRAVEL GUIDE — same three:
  - the [ FEATURED BHUTAN TRAVEL GUIDE — TITLE GOES HERE ] heading
  - the one-to-two-line intro
  - the "Read the guide" href (currently /travel-guides/bhutan)

SIGN-UP LINK
  Currently https://koryogroup.com/newsletter — point this at your actual
  MailerLite signup form or landing page.


DESIGN NOTES
------------
Colour split is roughly 75% white / 20% teal / 5% other Koryo colours.

  Teal (Bhutan)  #45B5AA   headline stat panel, tours button, sign-up
                           button, table rule, section eyebrows
  Red            #E8112D   stripe, "From the blog" eyebrow, 1974 marker
  Orange         #F49B1B   stripe, 1991 marker
  Purple         #3D3A8C   stripe, "Travel guide" eyebrow, 2020 marker
  Green          #2E9B4C   stripe, 2022 marker

The Koryo stripe runs across the top and bottom, led with teal rather than
red so the email reads as Bhutan at a glance.

Fonts are Circular Standard for headings and Karla for body text, with
Helvetica/Arial fallbacks — email clients that can't load a webfont will
fall back gracefully and the layout holds.

Dark mode is handled with prefers-color-scheme plus the [data-ogsc] /
[data-ogsb] attribute hooks that Outlook.com uses. Accent colours are
brightened in dark mode so the red and purple stay legible.

Mobile breakpoint is 640px: padding tightens, headings scale down, body
text bumps to 16px, and the buttons go full width.

Width is 600px, total file size ~38KB — comfortably under Gmail's 102KB
clipping limit, so nothing will be truncated.


A NOTE ON THE NUMBERS
---------------------
The savings table is derived from the +100 USD per night figure in the
source copy:

  5 nights  = +$500      10 nights = +$1,000
  7 nights  = +$700      14 nights = +$1,400

If the SDF change is confirmed at a different amount, those four rows are
the only figures that need recalculating.

The "7 nights (our 8-day group tour)" line assumes the Essence of Bhutan
tour is 8 days / 7 nights. Worth double-checking against the live tour page
before sending — koryogroup.com was unreachable when this was built, so the
duration came from a search result rather than the page itself.
