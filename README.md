## 🤖 [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **Reed Expo**. Easily scrape company profiles including **company details, websites, social media links, product categories, brands, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Reed Expo** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Reed Expo Events (Exhibitor Lists)](#supported-reed-expo-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Reed Expo event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, email, phone, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Reed Expo exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Reed Expo Events (Exhibitor Lists)

> The following partial list includes Reed Expo exhibitor directory URLs that have been tested so far. Other Reed Expo events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [Aluminium Global Exhibition Exhibitor List – aluminium-exhibition.com](https://www.aluminium-exhibition.com/germany/en-gb/exhibitor-directory.html#/)

- [SITL Exhibitor List – sitl.eu](https://www.sitl.eu/en-gb/who-is-coming/exhibitors-list.html#/)

- [JCK LasVegas Exhibitor List – lasvegas.jckonline.com](https://lasvegas.jckonline.com/en-us/about/exhibitor-directory.html#/)

- [World Hydrogen Summit & Exhibition Exhibitor List – world-hydrogen-summit.com](https://www.world-hydrogen-summit.com/world/en-gb/exhibitor-directory.html#/)

- [Mostra Convegno Expocomfort (MCE) Exhibitor List – mcexpocomfort.it](https://www.mcexpocomfort.it/en-gb/exhibitor-directory.html#/)

- [ILTM Asia Pacific Exhibitor List – iltm.com/asia-pacific](https://www.iltm.com/asia-pacific/en-gb/exhibitor-directory.html#/)

- [Bex Asia Exhibitor List – bex-asia.com](https://bex-asia.com/en-gb/Visit/exhibitor-directory.html#/)

- [Cannes Yachting Festival Exhibitor List – cannesyachtingfestival.com](https://cannesyachtingfestival.com/en-gb/exhibitors/exhibitors-list.html#/)

- [Equipotel Exhibitor List – equipotel.com.br](https://equipotel.com.br/pt-br/Expositores.html#/)

- [Expo Nacional Ferretera Exhibitor List – expoferretera.com.mx](https://expoferretera.com.mx/en-gb/exhibitor-list.html#/)

- [Febrava Exhibitor List – febrava.com.br](https://febrava.com.br/pt-br/Expositores.html#/)

- [FIBO Exhibitor List – fibo.com](https://fibo.com/germany/en-gb/exhibitor-directory.html#/)

- [FIEE Exhibitor List – fiee.com.br](https://fiee.com.br/pt-br/expositores.html#/)

- [G2E (Global Gaming Expo) Exhibitor List – globalgamingexpo.com](https://globalgamingexpo.com/en-us/attend/exhibitor-list.html#/)

- [ibtm World Exhibitor List – ibtmworld.com](https://ibtmworld.com/en-gb/exhibitor-directory.html#/)

- [iftm Exhibitor List – iftm.fr](https://iftm.fr/en-gb/show/exhibitors.html#/)

- [IT Partners Exhibitor List – itpartners.fr](https://itpartners.fr/en-gb/exhibitors-list.html#/)

- [Nepcon Vietnam Exhibitor List – nepconvietnam.com](https://nepconvietnam.com/hanoi/en-us/exhibitors/exhibitor-directory.html#/)

- [Offshore Europe Exhibitor List – offshore-europe.co.uk](https://offshore-europe.co.uk/en-gb/exhibitor-directory.html#/)

- [PGA Show Exhibitor List – pgashow.com](https://pgashow.com/en-us/show-info/exhibitor-list.html#/)

- [PSI Exhibitor List – psi-messe.com](https://psi-messe.com/en-gb/for-visitors/exhibitorlist.html#/)

- [Smart Energy Week Exhibitor List – wsew.jp](https://wsew.jp/autumn/en-gb/search/2025/directory.html#/)

- [Vision Expo East Exhibitor List – east.visionexpo.com](https://east.visionexpo.com/en-us/expo-hall/exhibitor-list.html#/)

- [Vision Expo West Exhibitor List – west.visionexpo.com](https://west.visionexpo.com/en-us/expo-hall/exhibitor-list.html#/)

- [WAICF Exhibitor List – worldaicannes.com](https://worldaicannes.com/en-gb/exhibition/exhibitors.html#/)

- [wtm London Exhibitor List – wtm.com](https://wtm.com/london/en-gb/exhibitor-directory.html#/)

- [Top Flotillas Exhibitor List – topflotillas.com](https://topflotillas.com/es/directorio-proveedores.html#/)

- [Hydrogen Americas Exhibitor List – world-hydrogen-summit.com](https://world-hydrogen-summit.com/americas/en-gb/exhibitor-directory.html#/)

- [Nepcon Japan Tokyo Exhibitor List – nepconjapan.jp](https://nepconjapan.jp/autumn/en-gb/search/2025/directory.html#/)

- [IFEX Exhibitor List – ifexflowerexpo.com](https://ifexflowerexpo.com/en-gb/exhibitor-directory/directory.html#/)

- [in-cosmetics latin america Exhibitor List – in-cosmetics.com](https://in-cosmetics.com/latin-america/en-gb/exhibitor-directory.html#/)

- [viscom Italia Exhibitor List – viscomitalia.it](https://viscomitalia.it/en-gb/exhibitor-directory.html#/)

- [BCB (Bar Convent Berlin) Exhibitor List – barconvent.com](https://barconvent.com/en-gb/exhibitor-directory.html#/)

- [Renodays Exhibitor List – renodays.com](https://renodays.com/fr-fr/qui-participe/les-exposants.html#/)

- [APS Exhibitor List – salon-aps.com](https://salon-aps.com/en-gb/exhibitors/exhibitors-list.html#/)

- [Manufacturing World Osaka Exhibitor List – manufacturing-world.jp](https://manufacturing-world.jp/osaka/en-gb/search/2025/directory.html#/)

- [Manufacturing World Fukuoka Exhibitor List – manufacturing-world.jp](https://manufacturing-world.jp/kyushu/en-gb/search/2024/directory.html#/)

- [Manufacturing World Nagoya Exhibitor List – manufacturing-world.jp](https://manufacturing-world.jp/nagoya/en-gb/search/2025/directory.html#/)

- [Manufacturing World Tokyo Exhibitor List – manufacturing-world.jp](https://manufacturing-world.jp/tokyo/en-gb/search/2025/directory.html#/)

- [FIBO Arabia Exhibitor List – fibo.com](https://fibo.com/arabia/en-gb/exhibitor-directory.html#/)

- [Medical Japan Tokyo Exhibitor List – medical-jpn.jp](https://medical-jpn.jp/tokyo/en-gb/search/2025/directory.html#/)

- [J-AGRI Gardex Tool Japan Exhibitor List – jagri-global.jp](https://jagri-global.jp/tokyo/en-gb/search/2025/directory.html#/)

- [Infosecurity Mexico Exhibitor List – infosecuritymexico.com](https://infosecuritymexico.com/en/exhibitors-list.html#/)

- [Bigdata & Ai Paris Exhibitor List – bigdataparis.com](https://bigdataparis.com/en-gb/exhibition/exposants.html#/)

- [EXPO Ferroviaria Exhibitor List – expoferroviaria.com](https://expoferroviaria.com/en-gb/exhibitor-list.html#/)

- [inter airport europe Exhibitor List – interairporteurope.com](https://interairporteurope.com/en-gb/exhibitor-list.html#/)

- [ILTM North America Exhibitor List – iltm.com/north-america](https://iltm.com/north-america/en-gb/exhibitor-directory.html#/)

- [pollutec Exhibitor List – pollutec.com](https://pollutec.com/en-gb/who-is-coming/liste-exposants.html#/)

- [NexTech Week Exhibitor List – nextech-week.jp](https://nextech-week.jp/autumn/en-gb/search/25/directory.html#/)

- [Reeduca Exhibitor List – salonreeduca.com](https://salonreeduca.com/en-gb/exhibitors/exhibitors-list.html#/)

- [ASLS Exhibitor List – asls.co.kr](https://asls.co.kr/en-gb/sponsor-exhibitor/exhibitor-directory.html#/)

- [JIS FALL Exhibitor List – jisshow.com](https://jisshow.com/fall/en-us/attend/exhibitor-directory.html#/)

- [SCE Exhibitor List – supplychain-event.com](https://supplychain-event.com/en-gb/who-is-coming/exhibitors-list.html#/)

- [Expo Fac Farmacias Exhibitor List – expofac.mx](https://expofac.mx/en-gb/exhibitor-directory.html#/)

- [Bioplus Interphex Korea Exhibitor List – bioplusinterphex.co.kr](https://bioplusinterphex.co.kr/en-us/visitor/exhibitor_directory.html#/)

- [IGTM Exhibitor List – igtmarket.com](https://igtmarket.com/en-gb/exhibitor-directory.html#/)

- [Kormarine Exhibitor List – kormarine.com](https://kormarine.com/en-gb/visitor/exhibitor_directory.html#/)

- [All Energy Australia Exhibitor List – all-energy.com.au](https://all-energy.com.au/en-gb/exhibitor-directory.html#/)

- [C-TOUCH & DISPLAY SHENZHEN Exhibitor List – quanchu.com.cn](https://quanchu.com.cn/en-gb/exhibitors/exhibitior-directory.html#/)

- [FILM&TAPE EXPO Exhibitor List – film-expo.com](https://film-expo.com/en-gb/exhibitors/directory.html#/)

- [Nepcon Asia Exhibitor List – nepconasia.com](https://nepconasia.com/en-gb/zszx/exhibitor-directory.html.html#/)

- [Waste Expo Australia Exhibitor List – wasteexpoaustralia.com.au](https://wasteexpoaustralia.com.au/en-gb/exhibitor-directory.html#/)

- [EBS Mexico Exhibitor List – expobeautyshow.com](https://expobeautyshow.com/en-us/exhibitor-list.html#/)

- [COSMEX Exhibitor List – cosmexshow.com](https://cosmexshow.com/en-gb/visitor-info/search-for-exhibitors.html#/)

- [in-cosmetics Asia Exhibitor List – in-cosmetics.com](https://in-cosmetics.com/asia/en-gb/exhibitor-directory.html#/)

- [World Nuclear Exhibition Exhibitor List – world-nuclear-exhibition.com](https://world-nuclear-exhibition.com/en-gb/wne-exhibitors/liste-des-exposants.html#/)

- [GPCE Exhibitor List – gpce.com.au](https://gpce.com.au/perth/en-gb/exhibitor-directory.html#/)

- [JWS Exhibitor List – jws.ae](https://jws.ae/en/brand-directory.html#/)

- [ISC East Exhibitor List – discoverisc.com](https://discoverisc.com/east/en-us/for-attendees/exhibitor-list.html#/)

- [Metalex Exhibitor List – metalex.co.th](https://metalex.co.th/en-gb/visitor-info/search-for-exhibitors.html#/)

- [ILTM Cannes Exhibitor List – iltm.com/cannes](https://iltm.com/cannes/en-gb/exhibitor-directory.html#/)

- [World Future Energy Summit Exhibitor List – worldfutureenergysummit.com](https://worldfutureenergysummit.com/en-gb/exhibitor-directory.html#/)

- [ibtm Americas Exhibitor List – ibtmamericas.com](https://ibtmamericas.com/en-gb/exhibitors-directory.html#/)

- [Bar Convent Berlin Exhibitor List – barconvent.com](https://barconvent.com/en-gb/exhibitor-directory.html#/)

- [Big Data London Exhibitor List – bigdataldn.com](https://bigdataldn.com/en-gb/exhibitor-list.html#/)

- [Aircraft Interiors Expo Exhibitor List – aircraftinteriorsexpo.com](https://aircraftinteriorsexpo.com/en-gb/exhibitor-directory.html#/)

- [Beauty Expo Australia Exhibitor List – beautyexpoaustralia.com.au](https://beautyexpoaustralia.com.au/en-gb/brand-directory.html#/)

- [World Travel Catering & Onboard Services Expo Exhibitor List – worldtravelcateringexpo.com](https://worldtravelcateringexpo.com/en-gb/exhibitor-directory.html#/)

- [Euro Bleech Exhibitor List – euroblech.com](https://euroblech.com/en-gb/exhibitor-list.html#/)

- [Reed Gift Fairs Sydney Exhibitor List – reedgiftfairs.com.au](https://reedgiftfairs.com.au/sydney/en-gb/exhibitor-directory.html#/)

- [Reed Gift Fairs Melbourne Exhibitor List – reedgiftfairs.com.au](https://reedgiftfairs.com.au/melbourne/en-gb/exhibitor-directory.html#/)

- [EQUITANA Essen Exhibitor List – equitana.com/essen](https://www.equitana.com/essen/en-gb/for-visitors/exhibitor-directory.html#/)

- [NHS Concept To Commerce Exhibitor List – nhsconcepttocommerce.com](https://www.nhsconcepttocommerce.com/en-us/exhibit-hall/exhibitor-list.html#/)

- [in-cosmetics Global Exhibitor List – in-cosmetics.com/global](https://www.in-cosmetics.com/global/en-gb/exhibitor-directory.html#/)

- [in-cosmetics Korea Exhibitor List – in-cosmetics.com/korea](https://www.in-cosmetics.com/korea/en-gb/exhibitor-directory/exhibitor-directory.html#/)

- [ISC West Exhibitor List – discoverisc.com/west](https://www.discoverisc.com/west/en-us/exhibitors/exhibitor-directory.html#/)

- [WTM Arabian Travel Market Exhibitor List – wtm.com/atm](https://www.wtm.com/atm/en-gb/exhibitor-directory.html#/)

- [WTM Latin America Exhibitor List – wtm.com/latin-america](https://www.wtm.com/latin-america/en-gb/exhibitor-directory.html#/)

- [APM (Asia Pasific Maritime) Exhibitor List – apmaritime.com](https://www.apmaritime.com/en-gb/be-a-part/exhibitor-directory.html#/)

- [Chemspec Europe Exhibitor List – chemspeceurope.com](https://www.chemspeceurope.com/en-gb/exhibitor-directory.html#/)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Categories</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Brands</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td></td>
        </tr>
        <tr>
            <td>Email</td>
            <td>YouTube</td>
            <td></td>
        </tr>
        <tr>
            <td>Phone</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.fibo.com/germany/en-gb/exhibitor-directory/exhibitordetails.org-ac7d7ac2-ad30-47ad-a507-fe8f1a6adcd0.html",
  "__company_name": "ABC Fitness",
  "_company_address": "2600 N Dallas Pkwy, TX, Frisco, Vereinigte Staaten",
  "_company_country": "United States",
  "_company_email": "info@abcfitness.com",
  "_company_phone": "866-364-4596",
  "_company_website": "https://www.abcfitness.com",
  "_hall_stands": "COND08",
  "_social_url_linkedin": "https://www.linkedin.com/company/abc-fitness",
  "_social_url_facebook": "https://www.facebook.com/abcfitnesssolutions",
  "_social_url_instagram": "https://www.instagram.com/abcfitnesssolutions",
  "_social_url_youtube": "https://www.youtube.com/@ABC-Fitness",
  "represented_brands": "Xtreme Fitness | F45 | Crunch | Jazzercise",
  "product_groups": "Software and Apps"
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)