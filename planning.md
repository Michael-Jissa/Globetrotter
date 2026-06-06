Globetrotter Planning Document

Milestone 0: Project Setup, Planning, and Spec

1) What location are you building this guide for, and why did you choose it?

I am building this guide for Lalibela, Ethiopia. I chose Lalibela because it is historically rich, visually unique, and not widely known by many first-time international travelers. The site gives me a chance to highlight its architecture, spiritual importance, and culture in a simple, inviting way.

2) Who is your primary audience?

My primary audience is first-time visitors who are curious about culture and history and want a clear, beginner-friendly guide before they travel. This includes solo travelers, students, and small groups who want practical highlights without reading a long travel book.

3) What do you want visitors to feel or know after spending 5 minutes on your site?

After five minutes, visitors should understand why Lalibela is globally important, especially its rock-hewn churches and ongoing religious traditions. They should also leave with a short list of attractions, food ideas, and visual references that make them excited and confident about visiting.

4) What's one design decision (color, layout, or tone) that reflects your destination's identity?

I chose a warm rocky red-orange color direction inspired by Lalibela's carved stone churches and mountain landscape. I also use a clean, mostly angular layout to reflect the carved architectural forms, with small rounded corners only on selected cards to keep the look modern and approachable.

Wireframe Notes

I created wireframes for Home, Top Attractions, Food Guide, and Gallery. Each wireframe clearly shows:





nav bar location



major content blocks



card/image structure



expected desktop-to-mobile layout changes

Milestone 2: CSS Styling

Design Intent

What color palette reflects your destination? Name three words that describe the feeling.

Palette: warm stone and earth tones, with rocky red-orange as the main accent, deep brown text, and soft off-white backgrounds.
Feeling words: grounded, historic, welcoming.

What typography (heading font / body font) fits your destination's character?

Heading font should feel strong and clear (simple sans-serif with heavier weight). Body font should be easy to read and clean for longer text. I will prioritize readability over decorative typography.

What's one visual choice that connects to your destination's identity?

The hero section uses a large cover image with overlaid white heading text to immediately communicate place and atmosphere. This mirrors how Lalibela is experienced visually first (stone forms, scale, landscape), then understood through details.

Milestone 3: Updating Layout using Flexbox

Flexbox Layout Plan

Home Hero Section





Content and arrangement: one large image with title/subtitle overlay; stacked structure.



Desktop row/item behavior: single full-width hero block.



Smaller screen behavior: same one-column structure with reduced text size and adjusted text position.



Spacing/alignment priorities: generous vertical space, clear focal point, readable text over image.

Navigation Bar





Content and arrangement: four links in one row.



Desktop row/item behavior: single row with evenly spaced links.



Smaller screen behavior: links stack vertically for easy tap targets.



Spacing/alignment priorities: clean separation between links and consistent padding.

Top Attractions Section





Content and arrangement: repeating attraction cards with image, title, short description, location.



Desktop row/item behavior: three cards in one row.



Smaller screen behavior: cards wrap to two columns on tablet and one column on mobile.



Spacing/alignment priorities: equal card widths, even gaps, aligned card content.

Food Guide Section





Content and arrangement: repeating guide cards with image, title, description, address, and link.



Desktop row/item behavior: three cards in one row.



Smaller screen behavior: same wrap pattern as attractions (2-column tablet, 1-column mobile).



Spacing/alignment priorities: consistent height feel and easy-to-scan text blocks.

Gallery Section





Content and arrangement: image tiles with captions below.



Desktop row/item behavior: multiple items per row with wrap.



Smaller screen behavior: fewer items per row as screen narrows, single-column on mobile.



Spacing/alignment priorities: left-aligned rows, consistent image crop, readable captions.

Milestone 4: Responsive Layout with Media Queries

Breakpoints Plan

What are the three device sizes you're designing for, and what width defines each breakpoint?





Mobile: up to 767px



Tablet: 768px to 1023px



Desktop: 1024px and above

For each major section of your site, what needs to change at each breakpoint?





Nav bar: desktop/tablet mostly horizontal; mobile becomes vertical stacked links.



Hero section: image height and heading/subtitle sizes reduce on smaller screens; overlay text repositioned for readability.



Attractions + Food cards: desktop 3-up layout, tablet 2-up, mobile 1-up.



Gallery: desktop multiple tiles per row, tablet 2-up, mobile 1-up.



General spacing: reduce paddings/margins slightly on mobile to preserve space while keeping readability.

Are there any sections where the mobile experience should feel meaningfully different from desktop, not just smaller?

Yes. The navigation should switch from a horizontal menu to a vertical stack on mobile for better touch interaction. The hero text overlay also needs a different position and smaller scale on mobile so it remains readable over the image.
