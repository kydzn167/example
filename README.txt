STUDENTSBIZ WEBSITE STARTER
===========================

This is a static multi-page website built with HTML5 and CSS3 only.
There is no JavaScript in this project.

FILES
- index.html       Homepage
- explore.html     Product directory
- businesses.html Vendor directory
- vendor.html      Example vendor profile
- about.html       About the project
- contact.html     Contact / inquiry form demonstration
- style.css        Shared styles for all pages

HOW TO OPEN IN VS CODE
1. Extract StudentsBiz.zip.
2. Open VS Code.
3. Choose File > Open Folder and select the extracted StudentsBiz folder.
4. Open index.html.
5. Preview it in a browser. You may use Live Server if your class allows it.

REPLACING SAMPLE PRODUCT PHOTOS
1. Put the real product photo inside the assets folder.
2. In the relevant HTML file, find the element with class "photo-placeholder".
3. Replace that placeholder block with:
   <img src="assets/your-photo.jpg" alt="Clear description of the product">
4. Save and refresh the browser.
5. Add this CSS rule if needed:
   .card > img { width:100%; height:185px; object-fit:cover; }

IMPORTANT LIMITATIONS
- This is an informational directory, not an automated e-commerce system.
- The contact form is only a front-end demonstration and does not send/store data.
- Replace the demo form with a Google Forms link before real use.
- Replace sample vendor names, product names, prices, descriptions and contact details.
- Ask vendors for permission before publishing their photos or business information.
- Confirm prices and availability with vendors.
- Do not publish personal phone numbers or private information without permission.

TECHNOLOGY
HTML5 + CSS3 only. No JavaScript, no database, no payment processing.
