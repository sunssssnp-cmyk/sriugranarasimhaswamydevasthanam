
# 🛕 Sri Ugra Narasimha Swamy Devasthanam – Website

Official website for **Sri Ugra Narasimha Swamy Devasthanam**, Sanginenipalli, Telangana.
This site is built using **HTML + CSS + JavaScript** and hosted **free on GitHub Pages** with a custom domain.

🌐 Live URL:
[https://sriugranarasimhaswamydevasthanam.com](https://sriugranarasimhaswamydevasthanam.com)

---

## 📁 Project Structure

```text
/
├── index.html              # Home page (background music enabled)
├── about.html              # Temple history & significance
├── events.html             # Events overview
├── event-details.html      # Detailed 3-day event schedule
├── gallery.html            # Photo gallery
├── youtube.html            # YouTube & Instagram embeds
├── donate.html             # UPI + Bank donation details
├── contact.html            # Contact, map, WhatsApp, call & email
│
├── css/
│   └── style.css           # Main site styling (colors, layout, fonts)
│
├── audio/
│   └── *.mp3               # Background devotional music (Home page only)
│
├── images/
│   ├── gallery/            # Gallery photos
│   ├── events/             # Event-related images/posters
│   └── upi-qr.jpg          # UPI QR code image
│
├── sitemap.xml             # Sitemap for Google indexing
├── google*.html            # Google Search Console verification file
└── README.md               # Project documentation (this file)
```

---

## 🎵 Background Music (Home Page Only)

* Music is enabled **only on `index.html`**
* File location:

  ```
  audio/
  ```
* Example:

  ```
  audio/narasimha-stotram.mp3
  ```

### Important:

* Music **starts muted** (browser rule)
* User must tap **🔊 icon** to enable sound
* Tooltip: *“Tap to enable music”*

To change the tune:

1. Upload a new `.mp3` file to `audio/`
2. Update the `<audio>` source in `index.html`
3. Commit changes

---

## 🌐 Language Support (Telugu / English)

* Telugu text uses class:

  ```html
  class="lang-te"
  ```
* English text uses:

  ```html
  class="lang-en"
  ```

### Language toggle:

* Present on all pages
* Uses simple JavaScript (no backend)

### Telugu Font:

* **Noto Serif Telugu** (Google Fonts)
* Font `<link>` is added inside `<head>` of **all HTML files**
* Styling handled via:

  ```css
  .lang-te { font-family: 'Noto Serif Telugu', serif; }
  ```

---

## 💰 Donations Page (`donate.html`)

Supported methods:

### 1️⃣ UPI Donation

* UPI QR image:

  ```
  images/upi-qr.jpg
  ```
* UPI ID with 📋 copy icon
* Works on all UPI apps

### 2️⃣ Bank Transfer (NEFT / RTGS / IMPS)

* Account Name
* Account Number (📋 copy enabled)
* IFSC & Branch details

### 3️⃣ WhatsApp Receipt

* “Send Receipt on WhatsApp” button
* Opens WhatsApp with pre-filled message

⚠️ No payment gateway is used (static site).

---

## 📞 Contact Page (`contact.html`)

Enabled actions:

* 📞 Phone number → opens **dial pad**
* 📧 Email → opens **email app with subject**
* 💬 WhatsApp chat button
* 🗺️ Google Maps embed
* Floating WhatsApp & Call icons

All links use:

* `tel:` for calls
* `mailto:` for email
* `wa.me` for WhatsApp

---

## 📷 Gallery (`gallery.html`)

* Images stored in:

  ```
  images/gallery/
  ```
* Recommended image size:

  * 100 KB – 400 KB
  * JPG format
* Responsive grid layout
* Easy to add/remove images

---

## 🎥 Media Page (`youtube.html`)

* One **fixed YouTube video embed** (stable)
* Channel link button
* Instagram profile embed
* Avoids “video unavailable” errors

To change the video:

1. Copy YouTube video ID
2. Replace the `src` in iframe

---

## 🌍 Hosting & Domain

* Hosted on **GitHub Pages**
* Custom domain from **GoDaddy**
* HTTPS enabled (Let’s Encrypt – free SSL)

---

## 🔍 SEO & Indexing

Completed:

* Google Search Console verification
* Sitemap submitted
* Indexing requested

Files involved:

* `sitemap.xml`
* `google*.html`

To check indexing:

```
site:sriugranarasimhaswamydevasthanam.com
```

---

## ✏️ How to Make Common Changes

### Update text content

* Edit respective `.html` file
* Commit changes

### Add new photos

* Upload to `images/gallery/`
* Update `gallery.html` if needed

### Change phone/email

* Update in:

  * `contact.html`
  * footer section (all pages)

### Change theme color

* Update colors in:

  ```
  css/style.css
  ```

---

## ⚠️ Important Notes

* Do NOT remove Google verification file
* Do NOT rename HTML files without updating links
* Do NOT delete `sitemap.xml`
* All pages are static (no backend)

---

## 🙏 Credits

Website designed and structured with best practices for:

* Devotional sites
* Elder-friendly usability
* Mobile-first access
* Zero hosting cost

🛕 **Sri Ugra Narasimha Swamy Devasthanam**
May the site serve devotees with ease and devotion 🙏


