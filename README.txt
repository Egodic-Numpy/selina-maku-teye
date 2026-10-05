SELINA MAKU TEYE — DIGITAL ORDER OF SERVICE

PROJECT STRUCTURE
index.html
css/style.css
js/script.js
assets/images/selina.jpg
assets/docs/Selina_Maku_Teye_Order_of_Service.pdf

1. PHOTOGRAPH
Place Madam Selina's portrait here:
assets/images/selina.jpg

Recommended: JPG/WebP, portrait orientation, roughly 1200–1800 px high, compressed for web.

2. PDF
The supplied PDF has already been copied to:
assets/docs/Selina_Maku_Teye_Order_of_Service.pdf

If you replace it later, keep exactly that filename unless you also update the links in index.html.

3. LOCAL TEST
From the project folder:
python3 -m http.server 8000
Then open:
http://localhost:8000

4. CLOUDFLARE PAGES
Option A — Git:
- Put this project in a GitHub repository.
- In Cloudflare Dashboard go to Workers & Pages > Create > Pages > Connect to Git.
- Select the repository.
- Framework preset: None.
- Build command: leave blank.
- Build output directory: /
- Deploy.

Option B — Direct Upload:
- In Cloudflare Pages choose Direct Upload.
- Upload the project files (or the unzipped project directory).

5. /order-of-service URL
For a clean /order-of-service route, deploy this project inside an "order-of-service" folder at the site root:
order-of-service/index.html
order-of-service/css/...
order-of-service/js/...
order-of-service/assets/...

Then the public URL becomes:
https://YOUR-PROJECT.pages.dev/order-of-service/
or:
https://YOUR-DOMAIN.com/order-of-service/

6. CUSTOM DOMAIN
In Cloudflare Pages:
- Open your Pages project.
- Go to Custom domains.
- Choose Set up a custom domain.
- Enter the domain/subdomain you own.
- Follow the DNS verification prompts.
If the domain's DNS is already on Cloudflare, the required DNS record can usually be configured automatically.

7. QR CODE
Do NOT encode the PDF file URL.
Encode the memorial page URL:
https://selina-maku.pages.dev/order-of-service/
or, with your own domain:
https://selinamaku.com/order-of-service/

Test the final QR code on both iPhone and Android before printing it.
