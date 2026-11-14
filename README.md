# ALL-OM.in website

ALL ONLINE MANAGEMENT FOR YOUR BUSINESS
Powered by Eventoria Plus Pvt. Ltd.

Ye ek simple static website hai (sirf HTML, koi build step nahi).

## Files

| File | Kaam |
|---|---|
| `index.html` | Poori website (logo aur favicon andar embed hain) |
| `logo.png`, `favicon.png` | Logo ki copies (design ya share karne ke liye) |
| `vercel.json` | Vercel ki settings (security headers, cache) |
| `package.json` | Railway ke liye (site ko serve karta hai) |
| `robots.txt` | Search engines ke liye |

## Contact details badalna ho to

`index.html` ke neeche script mein ye 2 lines dhundhein:

```js
var WHATSAPP = "918820306718";   // country code ke saath, bina + ya space ke
var EMAIL = "allom.official@gmail.com";
```

Footer ke email link aur WhatsApp buttons ke `href` mein bhi wahi number/email hai, unhe bhi badal lein.

## GitHub par daalna

1. github.com par naya repository banayein (naam jaise `allom-website`).
2. "Add file" -> "Upload files" dabayein.
3. Is folder ki saari files drag karke daalein (`index.html`, `logo.png`, `favicon.png`, `vercel.json`, `package.json`, `robots.txt`, `.gitignore`, `README.md`) aur "Commit changes" dabayein.

## Vercel par live karna (free)

1. vercel.com par GitHub se login karein.
2. "Add New" -> "Project" -> apna repository "Import" karein.
3. Framework Preset: **Other**. Build Command aur Output Directory khaali rakhein.
4. "Deploy" dabayein. 1 minute mein link mil jayega (jaise `allom-website.vercel.app`).

Custom domain: Project -> Settings -> Domains mein apna domain jodein aur Vercel ke DNS records apne domain provider mein daalein.

## Railway par live karna

1. railway.app par GitHub se login karein.
2. "New Project" -> "Deploy from GitHub repo" -> apna repository chunein.
3. Deploy ke baad service ki Settings -> Networking mein "Generate Domain" dabayein.

Railway `package.json` ka `start` command chalata hai, aur site apne aap serve ho jati hai.

## Live hone ke baad check karein

- Logo header aur footer mein dikhe.
- Floating WhatsApp button dabane par sahi number par chat khule.
- Audit form bharkar "Send on WhatsApp" dabayein, message pehle se bhara hua aaye.
- Instagram, Facebook, LinkedIn icons sahi pages par jayein.
- Phone par site ek baar dekhein.
