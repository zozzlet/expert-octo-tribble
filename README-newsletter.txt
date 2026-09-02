KORYO TOURS - NEW TRIPS & EXPANSION NEWSLETTER
================================================

File: koryo-new-trips-newsletter.html
Paste this directly into MailerLite's "Custom HTML" / "Paste HTML" import
option when creating a new campaign. Built as one 600px table-based email
with light mode, dark mode (prefers-color-scheme + Outlook.com overrides)
and a mobile-responsive layout, using the same Koryo stripe branding as
your other newsletters. Font stack is 'Circular Standard', 'Karla',
Helvetica, Arial, sans-serif throughout (email clients fall back to Karla
or the system font since custom fonts can't be embedded in email).

BEFORE YOU SEND, DO THREE THINGS
---------------------------------

1) REPLACE THE IMAGE PLACEHOLDERS
   Every photo in the email is a MailerLite placeholder image. In the
   MailerLite editor, click each placeholder and swap it for a real photo:
     - Hero image (top): a collage or wide shot representing the expansion
     - Iraq & Syria
     - Yemen Mainland
     - Socotra
     - Yemen Mainland & Socotra Combo
     - Libya: East & West
     - Libya Total Solar Eclipse
     - Nepal

2) REPLACE THE LINK PLACEHOLDERS
   Search the HTML for "PASTE-" and you'll find every link that needs a
   real URL, e.g. PASTE-YEMEN-MAINLAND-LEARN-MORE-URL-HERE and
   PASTE-YEMEN-MAINLAND-BOOK-URL-HERE. There are two per new trip (Learn
   More -> the tour page on koryogroup.com, Book Now -> the booking page)
   and one per wait list trip (see below). I didn't guess at real
   koryogroup.com URLs since I can't verify them, so they're left as
   clearly-marked placeholders rather than made-up links.

3) FILL IN "PLACES LEFT"
   Every trip card has a small pill badge reading "XX places left". Find
   and replace "XX" with the real live availability figure for each trip
   before sending, since I don't have access to your booking system.

SETTING UP THE WAIT LIST BUTTONS IN MAILERLITE
------------------------------------------------

I don't have API access to your MailerLite account from this session, so
I can't create the groups or wire up the automations directly. Here's how
to get the exact behaviour you asked for (click a trip's wait list button
-> subscriber gets added to that trip's group) in about ten minutes,
using MailerLite's built-in features. No custom code or landing pages
needed.

Step 1: Create five groups (Subscribers > Groups > Create group):
   - Algeria Wait List
   - Pakistan Wait List
   - Timor-Leste Wait List
   - Moldova & Transnistria Wait List
   - Pacific 12 Combo Wait List

Step 2: Give each wait list button its own unique URL. The simplest way
is to point each one at the matching page on your site with a distinct
query string, e.g.:
   https://koryogroup.com/wait-list?tour=algeria
   https://koryogroup.com/wait-list?tour=pakistan
   https://koryogroup.com/wait-list?tour=timor-leste
   https://koryogroup.com/wait-list?tour=moldova-transnistria
   https://koryogroup.com/wait-list?tour=pacific-12-combo
(These can all point to the same landing page since the query string is
only there to make each link unique for the next step. Or use five
distinct real pages if you'd rather. Either way, paste the final URLs
into the matching "PASTE-...-WAITLIST-URL-HERE" spots in the HTML.)

Step 3: In MailerLite, go to Automations > Create automation, and for
each of the five trips set:
   Trigger:  "Subscriber clicks a link" -> paste that trip's exact URL
   Action:   "Add to group" -> that trip's wait list group

Once that's set up, anyone who clicks "Add Me to the Algeria Wait List"
in this campaign (or any future campaign using the same link) is added
straight to the Algeria Wait List group automatically. Repeat for the
other four.

If you'd ever like me to do this setup for you directly, connect a
MailerLite integration/API key to this session and I can create the
groups and automations for you instead of writing out these steps.

TAGLINE & VOICE
-----------------
Footer tagline is "Experts in Travel to Rather Unusual Destinations" as
requested. Copy is written in friendly Koryo voice with no em dashes.

STATS USED IN THE "OUR EXPANSION" SECTION
--------------------------------------------
3 new countries this year (Yemen, Libya, Nepal)
6 new trips this year (Yemen Mainland, Socotra, Yemen Mainland & Socotra
Combo, Libya East & West, Libya Total Solar Eclipse, Nepal)
Iraq & Syria is called out separately as "where it started", since you
mentioned that one launched a while ago rather than this year, it's
framed as the origin of the expansion programme rather than a "new this
year" trip. Double check these numbers against your own records before
sending.
