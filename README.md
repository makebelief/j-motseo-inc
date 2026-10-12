# J Motseo Inc. Legal Practitioners — Website Demo

This is a complete static HTML/CSS/JS multi-page website developed as a concept using the **C.O. Were-style visual structure**. No npm build step or secrets required. Vercel preset: **Other**, output directory: **`.`** (the repository root). 

## Pages
Home, About, Practice Areas (nine practice groups), Our Attorney, Insights, Contact, Privacy and Terms.

## Branding and imagery
The logo is sourced from the uploaded J Motseo Inc. mark, enlarged as transparent PNGs. It is an upscaled raster file, not a vector original. The two photographs supplied in the chat have been provisionally labelled as Johannes Motseo *at the user's request*, not independently verified. They are separate source images, used on the Home and Our Attorney pages respectively. **Confirm identity before publication to the actual firm.**

Pexels image URLs are third-party illustrative stock photography, not staff or clients. They require internet access and should be reviewed for subject suitability and licensing. Each stock image is a distinct photo ID; stock images with people are selected from references featuring Black/African professionals.

## Contact accuracy
Firm-level contacts from Attorneys.co.za published firm profile: phone +27 65 809 5744, WhatsApp 27658095744, alternative mobile +27 79 563 0221, email info@jmotseoinc.com. Office address: Unit 1009, Management House, 38 Melle Street, Braamfontein, Johannesburg, South Africa, 2001. Confirm details before publishing as an official site. 

The enquiry form opens a **mailto draft**; it does NOT send email from the server. Test with an email client. No content-management system, analytics or form backend is configured.

## SEO and deployment
Sitemap and canonical URLs assume https://j-motseo-inc.vercel.app. If Vercel gives a different hostname, run a full replace of that URL in all HTML pages, robots.txt and sitemap.xml before submitting to search engines.

```bash
cd ~/Downloads
unzip -oq j-motseo-inc-production.zip
cd j-motseo-inc
python3 -m http.server 8000
```
Browse http://localhost:8000. To publish using the existing Vercel login: `npx vercel --prod` from the site directory, select **Other** framework with Output Directory `.` (not `public`).

## Content provenance
- https://www.attorneys.co.za/CompanyHomePage.asp?CompanyID=2305
- https://www.attorneys.co.za/AttorneyHomePage.asp?AttorneyID=10294&CompanyID=2305
- User-supplied logo, two pictures, LinkedIn, Facebook and Instagram links.

## Important review before public marketing
- Check both portraits' names/identities.
- Check the firm's approval of demo content, phone numbers, urgent-service wording, domain and privacy notice.
- Inspect final stock images online for appropriate representation and correct licenses.
- Get professional review for final POPIA and confidentiality statements.

## October 2026 Maps and navigation update
- Removed the red location-pin emoji from the top information bar on every page.
- Added an embedded, responsive Google Maps view of **Management House, 38 Melle Street, Braamfontein** on the Contact page, alongside a directions link.
- Map address identifies the building; the floor/unit is provided as text and is not a separately mapped Google Maps location.
- Map loads from Google as a third-party embed; it requires internet connectivity. Google may process visitors' data (see Privacy page).
- CSS was renamed to `assets/site-map-update.css` to prevent the old, long-cached CSS being shown after deployment.
