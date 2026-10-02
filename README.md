# Excellence Training Center (ETC) — Static Website

This folder is a complete static website for Excellence Training Center in Port Sudan, Sudan. It is designed to upload directly to GitHub Pages.

## 1. Open locally
No Node.js, PHP, database, npm, or build process is required.

- Open `index.html` directly in a browser for a basic local preview.
- For best local testing, use any simple static web server, but this is optional.

## 2. Replace images
All image assets are in `images/`.

The current files are clearly named placeholders. Replace a placeholder with a real photograph while keeping the same filename, for example:
- `images/hero-classroom.jpg`
- `images/english-class.jpg`
- `images/kids-class.jpg`

Keep descriptive filenames and update the `alt` text in the relevant HTML if the image content changes.

## 3. Replace the logo
Replace `images/logo.png` with the official ETC logo. Keep the filename `logo.png`, or update the `<img>` paths in the HTML files.

## 4. Change phone numbers
Phone numbers are written directly in the HTML files, especially `contact.html` and the footer sections. Search the project for:
- `0915749548`
- `0126918343`
- `0126973848`

Update both visible text and `tel:` links.

## 5. Change WhatsApp
The current WhatsApp number is `00249915749548`.
The WhatsApp links use:
`https://wa.me/249915749548`
and a pre-filled message.

If the number changes, update all `wa.me` links.

## 6. Add programs
Program cards are on `programs.html`. Add a new card by copying an existing `<article class="card">` block and changing:
- image
- alt text
- program name
- description
- audience
- skills
- link

## 7. Edit program descriptions
Each dedicated program page is a separate HTML file. Edit the heading, paragraph, and list items directly.

## 8. Add trainers
Trainer names supplied for this site are:
- Ekrema Ali
- Mohammed Ali
- Ahmed Abdelaziz
- Khalid Eissa Elnadeef
- Azza Mohammed Saralkhatim Mohammed
- Mandela Ezekiel Kondo Komer

No qualifications have been invented. If trainer profiles are added later, use only verified information.

## 9. Connect the registration form
`registration.html` contains a static form with the placeholder `FORM_ENDPOINT_HERE`.

GitHub Pages cannot store form submissions by itself.

To connect it:
1. Create a form endpoint using a service such as Formspree, Google Forms, or another suitable provider.
2. Replace `FORM_ENDPOINT_HERE` in the `<form action="...">`.
3. Follow the provider's instructions for field names and redirects.
4. Test the form before publishing it.
5. Do not place private API keys or passwords in JavaScript.

The current JavaScript intentionally prevents the form from pretending to submit when no service is connected.

## 10. Add the real Google Maps location
The site intentionally does not invent GPS coordinates.

In `index.html` and `contact.html`, replace:
`GOOGLE_MAPS_EMBED_CODE_HERE`

with the actual Google Maps embed iframe supplied by the center's verified location.

For the directions button, replace:
`GOOGLE_MAPS_LINK_HERE`

with the real verified Google Maps directions URL.

## 11. Add social media links
Search the project for:
`SOCIAL_MEDIA_LINK_HERE`

Replace each placeholder with the verified Facebook, Instagram, TikTok, or YouTube URL.

Do not invent social URLs.

## 12. Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload the contents of `ETC-Website`.
3. Make sure `index.html` is in the repository root.
4. In GitHub, open **Settings → Pages**.
5. Choose the branch containing the website and the root folder.
6. Save.
7. GitHub will provide the published Pages address.

The website uses relative internal links and does not require server-side routing.

## 13. Website structure
- `index.html` — Home
- `about.html` — About
- `programs.html` — Programs
- `english.html` — English
- `kids.html` — Kids English
- `jolly-phonics.html` — Jolly Phonics
- `ielts.html` — IELTS
- `computer.html` — Computer
- `international-curriculum.html` — International Curriculum
- `human-development.html` — Human Development
- `information-management.html` — Information Management
- `filming-editing.html` — Filming & Video Editing
- `gallery.html` — Gallery
- `registration.html` — Registration
- `contact.html` — Contact
- `css/style.css` — shared styling
- `js/script.js` — small vanilla JavaScript interactions
- `images/` — image assets/placeholders
- `robots.txt` — crawler instructions
- `sitemap.xml` — page sitemap

## 14. Editing tips for non-programmers
- Keep backups before editing.
- Make one change at a time.
- Keep quotation marks and HTML tags intact.
- If you replace an image, keep its filename to avoid changing HTML.
- If you change a page title or description, keep the HTML structure intact.
- After edits, open `index.html` and click through every navigation link.
- Test the website on a phone before publishing.

## 15. Important content rules
The website intentionally avoids invented:
- prices
- schedules
- teacher qualifications
- accreditation
- government recognition
- student numbers
- testimonials
- reviews
- certificates
- GPS coordinates
- social media URLs

Placeholders identify information that still needs to be supplied.

## 16. Responsive design
The CSS includes layouts for:
- 360px
- 390px
- 412px
- 768px
- 1024px
- 1366px

The mobile navigation becomes a hamburger menu, cards collapse to one column, forms become one column, and the WhatsApp button remains visible.

## 17. Accessibility
The site uses:
- semantic HTML headings
- skip navigation
- descriptive image alt text
- visible focus states
- labels for form fields
- keyboard-friendly controls
- readable contrast
- reduced-motion support
- ARIA attributes where useful

## 18. Final verification checklist
Before publishing:
- Check every HTML page.
- Check every internal link.
- Replace real photographs.
- Replace the logo.
- Verify phone numbers.
- Verify WhatsApp.
- Connect the registration form.
- Add the real Google Maps embed.
- Add verified social links.
- Test the hamburger menu.
- Test the form on mobile.
- Test phone and WhatsApp buttons.
- Check spelling and page titles.
- Check `robots.txt` and `sitemap.xml`.
- Confirm `index.html` opens correctly.
