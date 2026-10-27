# Cleaning page check and SERP read, 2026-10-26

Source: WebFetch of onestopkwc.ca and sitemap.xml on 2026-10-26. SERP results are approximate and unpersonalized-ish; label as such.

## Finding: NO dedicated cleaning page exists
- Sitemap has 7 URLs: /, /handyman-kitchener, /handyman-waterloo, /handyman-cambridge, plus privacy, terms, customer service agreement.
- Homepage Cleaning card only anchors to #services on the same page. No cleaning URL anywhere.
- Phone 519-722-9057: yes, in header "Call Us" button and in the hero under "Book a Pro". Good.
- Cities named: Kitchener, Waterloo, Cambridge, plus Baden, Elmira, New Hamburg, Breslau, Wellesley, Woolwich, Guelph (all link to #book).
- Title: the visible H1/first line reads "OneStop KWC - Handyman, Cleaning & Home Services in Kitchener, Waterloo & Cambridge". Could not confirm the actual <title> tag. Meta description: not returned by fetch; treat as unconfirmed, check page source.
- Other: sitemap lists legal pages as .html while site links use no extension. Check for duplicate URLs.

## Top 5 fixes (each under 1 hour)

1. Create /cleaning-kitchener (then waterloo, cambridge later). Even one page beats none. Drop-in:
 - Title: House Cleaning in Kitchener | Move-Out & Deep Cleans | OneStop KWC
 - Meta: Move-out and deep cleaning in Kitchener, Waterloo and Cambridge. Vetted local cleaners. Free quote by phone, 519-722-9057, answered 24/7.
 - H1: House and Move-Out Cleaning in Kitchener
 - Intro: Moving out by the end of the month, or hosting soon? OneStop KWC sends a vetted local cleaner to your place in Downtown Kitchener, Doon, Forest Heights, Victoria Hills or anywhere in Kitchener-Waterloo. Tell us the size and the date. Free quote by phone.
 - CTA button: Call 519-722-9057 (top and bottom).

2. Fix title and meta on the homepage. Drop-in title: Handyman, Cleaning, Plumbing & Electrical in Kitchener-Waterloo-Cambridge | OneStop KWC (under 60 chars is better: "Home Services in Kitchener-Waterloo | OneStop KWC"). Meta: Handyman, cleaning, plumbing and electrical pros in Kitchener, Waterloo and Cambridge. Call 519-722-9057 any hour.

3. Link the homepage Cleaning card to the new cleaning page, and add a "Move-out cleaning" line to the hero or services section: "Moving out? Get the place cleaned for the walkthrough. Call 519-722-9057."

4. Add a 4-question FAQ to the cleaning page (and FAQPage schema):
 - Do you do move-out cleaning? Yes, for homes and apartments in Kitchener, Waterloo and Cambridge.
 - How much does it cost? Price on request. Call 519-722-9057 for a free quote.
 - Can you clean on short notice? Call any hour and we'll tell you the earliest slot.
 - Which areas? Kitchener, Waterloo, Cambridge, including Galt, Hespeler and Preston.
 (Short-notice answer is a claim Mushroom must confirm.)

5. Add LocalBusiness schema (name OneStop KWC, 387B King St E Kitchener, 519-722-9057, areaServed Kitchener/Waterloo/Cambridge, openingHours 24/7) to the homepage, and fix sitemap/URL consistency (.html vs none). Add the new cleaning URL to the sitemap.

Price flag: a "from $X" on the cleaning page would help. Needs Mushroom's number.

## SERP read (WebSearch, approximate, not personalized-verified)

"house cleaning Kitchener": Hellamaid (KW house cleaning page and a Kitchener demand blog), KCS Kitchener Cleaning Services, job boards (Indeed, Job Bank). OneStop not observed.

"move out cleaning Waterloo": results mostly other Waterloos (UK, Iowa, Illinois); local ones: InspireClean Kitchener-Waterloo, UWaterloo housing checklist. Weak local competition, so an opening. OneStop not observed.

"cleaning Cambridge Ontario": Molly Maid Cambridge, Hellamaid Cambridge (Galt, Hespeler, Preston), KCS (Hardcastle Dr), HomeStars. OneStop not observed.
