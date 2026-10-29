GA DONA — FULL WEBSITE FOR GITHUB PAGES

FILES
- index.html: Homepage, about, menu preview and contact/order call-to-action.
- place-order.html: Full menu, cart, customer details, delivery address/map location, R15 delivery fee and WhatsApp order.
- assets/ga-dona-menu.jpg: Ga Dona menu image used by both pages.

HOW TO PUBLISH
1. Extract this ZIP.
2. Upload index.html, place-order.html, and the entire assets folder to the ROOT of your GitHub repository.
3. In GitHub, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Choose branch main and folder /(root), then Save.

NOTES
- This is a standalone recreation based on the available Ga Dona ordering page and menu artwork. I could not automatically fetch every section of the Google Sites homepage, so it may not exactly match all original page text/design.
- WhatsApp ordering is wired into the Place Order button. The code currently uses 27634018638 (international format, no + sign). Confirm this is Ga Dona's correct business WhatsApp number before publishing; if it is wrong, replace that number in place-order.html.
- Delivery adds R15; collection adds no delivery fee.
- The map-location button asks customers for browser location permission and can include a Google Maps link in their WhatsApp order.
- Online card payments are not connected, so this website does not collect card details or confirm payment. Confirm delivery availability and payment arrangements directly with Ga Dona.
- Browser location access normally requires HTTPS; GitHub Pages provides HTTPS. Customers can also type their delivery address and paste a Google Maps link.
