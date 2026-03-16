# Nutri Valley Website - Design Specification

## Overview
Pixel-perfect recreation of an Adobe XD design for Nutri Valley, a Greek food/nutrition brand. The site is a single homepage with multiple sections.

## Design Dimensions
- Desktop width: 1920px
- Total page height: ~7600px
- Content area: 1820px (50px padding each side)

## Color Palette
- `--coconut`: #fdfffd (off-white/cream)
- `--gray-nurse`: #e8e8e8 (light gray background)
- `--tundora`: #474444 (dark brown/charcoal - primary text)
- `--white`: #ffffff
- Green accent: #859e66 (navbar ΠΡΟΪΟΝΤΑ button)
- Green accent 2: #90a86d (about section CTA button)
- Green accent 3: #7a8c5b (footer kids social links)
- Events bg: #c4b2a3 (warm beige/tan)

## Typography
Font family: "TikTokSans18pt" in three weights:
- Bold (700)
- Medium (500)  
- Regular (400)

Font sizes (from CSS variables):
- xxxl: 42.1px (hero titles)
- xxl: 32px (section headings)
- xl: 21px (sub-headings, bold statements)
- l: 18px (footer contact info)
- m: 17px (body text, nav links)
- s: 16px (button text, smaller bold text)
- xs: 15px (footer small text)

## Page Structure (Top to Bottom)

### 1. NAVBAR (Fixed/Sticky)
- Gradient background: linear-gradient(180deg, #e8e8e8 0%, rgba(232,232,232,0) 100%)
- Height: 260px gradient area, navbar bar at ~70px height
- Left: Green pill button (#859e66) with hamburger icon + "ΠΡΟΪΟΝΤΑ" text
- Center: Off-white pill bar (#fdfffd, border-radius: 35px) containing:
  - Logo (Nutri Valley logo with leaf icon)
  - Nav links: ΣΥΝΤΑΓΕΣ, ΔΙΑΓΩΝΙΣΜΟΙ, EVENTS, BLOG, ΣΧΕΤΙΚΑ, ΕΠΙΚΟΙΝΩΝΙΑ
  - Letter-spacing: 1.70px on nav links
- Right: Two circular buttons (globe/language + search icons)
- All text: TikTokSans18pt Bold, 17px

### 2. HERO SLIDER (within gray background)
- Gray background (#e8e8e8) covers first ~960px
- Two slide panels side by side (carousel), each 1820px wide:
  - Slide 1 (left): Background image group-31-1 — "ΚΑΝΕ ΤΟ ΠΡΩΙΝΟ ΤΟΥΣ... ΤΗ ΣΤΙΓΜΗ ΤΗΣ ΗΜΕΡΑΣ!" (kids theme with granola product)
  - Slide 2 (right): Background image group-31 — "ΑΠΟΛΑΥΣΗ & ΙΣΟΡΡΟΠΙΑ ΣΕ ΚΑΘΕ ΕΠΙΛΟΓΗ" (adult products)
- Each slide has: Title (42.1px bold), subtitle (17px regular), CTA button
- CTA buttons: Dark (#474444) pill shape, border-radius 35px, 300px wide, 70px tall
- Navigation arrows on sides (path-66 and path-69 icons)

### 3. ΠΡΟΪΟΝΤΑ ΓΙΑ ΕΝΗΛΙΚΕΣ (Adult Products Section)
- Still on gray background
- Centered heading "ΠΡΟΪΟΝΤΑ ΓΙΑ ΕΝHΛΙΚΕΣ" (32px bold, letter-spacing 1.6px)
- Subtitle paragraph (lorem ipsum, 17px, centered, 777px wide)
- 6 product category cards in a horizontal row:
  - Each card: 362px wide, full height ~600px
  - Background images: group-40-1 (Premium Konserves x2), group-42 (Μπάρες Πρωτεΐνης), group-48 (Γκοφρέτες), group-44 (Ταχίνι), group-46 (Νιφάδες Βρώμης)
  - Text overlay at bottom: product name in 32px bold, white text
- CTA button: "ΟΛΑ ΤΑ ΠΡΟΙΟΝΤΑ" dark pill button below cards

### 4. ΠΑΙΔΙΚΑ ΠΡΟΪΟΝΤΑ (Kids Products Section)  
- White background
- Heading "ΠΑΙΔΙΚΑ ΠΡΟΪΟΝΤΑ" (32px bold, centered)
- Subtitle (lorem ipsum, centered)
- 4 product cards with kids characters:
  - Each card: 573px wide, 740px tall, border-radius 20px
  - Background images: group-52, group-54, group-56, group-99
  - Brand logos on cards: rectangle-52, rectangle-53, group-61, rectangle-79
  - Each has white pill button at bottom "ΟΛΑ ΤΑ ΠΡΟΙΟΝΤΑ" (border-radius 35px)

### 5. ΣΧΕΤΙΚΑ ΜΕ ΕΜΑΣ (About Section)
- Full-width background image: mask-group-1 (food/cooking scene)
- 805px height
- White card overlay (715px wide, 585px tall, border-radius 20px) at bottom-left
- Card content:
  - Bold statement (21px): "Η NUTRI VALLEY ΔΗΜΙΟΥΡΓΕΙ ΠΡΟΪΟΝΤΑ ΠΟΥ ΚΑΝΟΥΝ ΤΗΝ ΚΑΘΗΜΕΡΙΝΗ ΔΙΑΤΡΟΦΗ ΠΙΟ ΕΥΚΟΛΗ, ΠΙΟ ΥΓΙΕΙΝΗ ΚΑΙ ΠΙΟ ΑΠΟΛΑΥΣΤΙΚΗ ΓΙΑ ΜΙΚΡΟΥΣ ΚΑΙ ΜΕΓΑΛΟΥΣ."
  - 5 bullet points with checkmark icons (path-71)
  - Green CTA button (#90a86d): "ΣΧΕΤΙΚΑ ΜΕ ΕΜΑΣ" (300px wide, 70px tall, pill shape)

### 6. ΣΥΝΤΑΓΕΣ (Recipes Section)
- Gray background (#e8e8e8)
- Heading "ΣΥΝΤΑΓΕΣ ΜΕ ΤΑ ΠΡΟΪΟΝΤΑ ΜΑΣ" (32px bold)
- 4 recipe cards in a row:
  - Each: 363px wide, 480px tall
  - Image section with recipe photo background
  - White bottom bar with recipe name (17px medium) + arrow icon
  - Recipe names: "Τηγανητό ρύζι με κοτόπουλο", "Brownies with a twist", "Ρυζογκοφρέτα με Cottage Cheese, Μέλι και Κανέλα", "Πέστο κόκκινης πιπεριάς και κοτόπουλο"
  - Gap: 50px between cards
- CTA: "ΟΛΕΣ ΟΙ ΣΥΝΤΑΓΕΣ" dark pill button

### 7. EVENTS Section
- Background color: #c4b2a3 (warm beige)
- Background image overlay: group-66 with mix-blend-mode multiply, opacity 0.5
- 805px height
- Left side: Bold text "Η NUTRI VALLEY ΤΑΞΙΔΕΥΕΙ ΠΑΝΤΟΥ. ΕΛΑΤΕ ΝΑ ΓΝΩΡΙΣΤΟΥΜΕ ΣΕ ΚΑΠΟΙΟ EVENT ΜΑΣ!"
- Subtitle text + CTA "ΟΛΑ ΤΑ EVENTS" (coconut/white background pill button)
- Right side: 3 overlapping event images (group-70, group-72, group-74), stacked with offsets

### 8. BLOG Section (Two Cards)
- Two large cards side by side, 885px each, 50px gap
- Each card: Image area (740px tall) + white text bar (180px)
- Card 1: group-89 background — "ΓΙΑΤΙ ΝΑ ΕΠΙΛΕΞΕΤΕ ΤΟ ΦΙΛΕΤΟ ΚΟΤΟΠΟΥΛΟ ΤΗΣ NUTRI VALLEY"
- Card 2: group-91 background — "ΒΙΩΣΙΜΟΤΗΤΑ ΤΗΣ NUTRI VALLEY"
- Each has title (21px bold) + description (17px regular)

### 9. FOOTER
- White background, border-radius 30px on container
- 400px height, 1820px wide
- Left: Nutri Valley logo (path-38, group-27, path-50) + copyright "© Nutri Valley 2025. All Rights Reserved"
- Right column:
  - Social icons (path-82 phone, group-97 email, group-98 location)
  - Contact: +30 212 000 1022, info@nutrivalley.gr, Ικαρίας 16, Κηφισιά, ΤΚ 14562
  - Legal: Όροι Χρήσης, Πολιτική Απορρήτου, Πολιτική Cookies
  - Bottom row: "Powered by Thinktank" | Facebook | Instagram | Facebook Kids | Instagram Kids

## Mega Menu (Two States)
### State 1 (menu-desktop-1): Expanded subcategories
- Dark overlay on page (opacity 0.3)
- White mega menu dropdown (1820px wide, 450px tall, border-radius 42px)
- Left column: "ΠΡΟΪΟΝΤΑ ΓΙΑ ΕΝΗΛΙΚΕΣ" and "ΠΑΙΔΙΚΑ ΠΡΟΪΟΝΤΑ" with arrows
- Subcategories visible: "Premium Κονσέρβες, Μπάρες Πρωτεΐνης, Γκοφρέτες, Ταχίνι" and "Γκρανόλα, Νιφάδες Βρώμης, Νιφάδες Καλαμποκιού"
- Right side: Product showcase image (group-25)

### State 2 (menu-desktop-2): Product category view
- Similar layout with highlighted category
- Product cards with brand logos: group-8, group-10, group-12, group-14
- Brand logos: rectangle-12, rectangle-13, group-16, rectangle-15

## Button Styles
- Primary CTA: bg #474444, text #fdfffd, border-radius 35px, 300px x 70px, text 16px bold, letter-spacing 1.6px
- Green CTA: bg #90a86d or #859e66, same shape
- White CTA: bg #fff, text #474444, same shape
- Product card buttons: bg #fff, full-width minus 40px padding, border-radius 35px, 70px tall

## Image Assets Available
All images are in /home/user/workspace/nutri-build/src/assets/images/
Named as exported from Anima (group-XX@1x.png, path-XX@1x.png, etc.)

## Key asset mapping:
- Logo: path-51-1 (leaf icon), group-33-1 (text), path-50 (dot)
- Hero slide 1: group-31-1 (kids/granola bg)
- Hero slide 2: group-31 (adult products bg)
- About background: mask-group-1
- Events background: group-66
- Recipe images: group-79, group-81, group-85, group-83
- Blog images: group-89, group-91
- Footer logo: path-38, group-27
- Social icons: path-82, path-83, path-84
- Check marks: path-71
- Arrows: path-66, path-69, path-76, path-36
- Product categories: group-40-1, group-42, group-44, group-46, group-48
- Kids products: group-52, group-54, group-56, group-99
- Kids logos: rectangle-52, rectangle-53, group-61, rectangle-79
- Event photos: group-70, group-72, group-74
- Menu products: group-8, group-10, group-12, group-14
- Menu logos: rectangle-12, rectangle-13, group-16, rectangle-15
