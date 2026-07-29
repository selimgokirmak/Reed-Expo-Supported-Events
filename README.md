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

- [Aircraft Interiors Expo 2026 Exhibitor List – aircraftinteriorsexpo.com](https://www.aircraftinteriorsexpo.com/en-gb/exhibitor-directory.html#/)

- [All Energy Australia 2026 Exhibitor List – all-energy.com.au](https://www.all-energy.com.au/en-gb/exhibitor-directory.html#/)

- [Aluminium Global Exhibition 2026 Exhibitor List – aluminium-exhibition.com](https://www.aluminium-exhibition.com/germany/en-gb/exhibitor-directory.html#/)

- [APM (Asia Pasific Maritime) 2026 Exhibitor List – apmaritime.com](https://www.apmaritime.com/en-gb/be-a-part/exhibitor-directory.html#/)

- [ASLS Korea 2026 Exhibitor List – asls.co.kr](https://www.asls.co.kr/en-gb/show-info/exhibitor-directory.html#/)

- [Bar Convent Berlin 2026 Exhibitor List – barconvent.com/berlin](https://www.barconvent.com/berlin/en-gb/exhibitor-directory.html#/)

- [Bar Convent Brooklyn 2026 Exhibitor List – barconventbrooklyn.com](https://www.barconventbrooklyn.com/en-us/about/exhibitor-directory.html#/)

- [Bar Convent London 2026 Exhibitor List – barconvent.com/london](https://www.barconvent.com/london/en-gb/exhibitor-directory.html#/)

- [Beauty Expo Australia 2026 Exhibitor List – beautyexpoaustralia.com.au](https://www.beautyexpoaustralia.com.au/en-gb/brand-directory.html#/)

- [Bex Asia 2026 Exhibitor List – bex-asia.com](https://www.bex-asia.com/en-gb/Visit/exhibitor-directory.html#/)

- [Big Data London 2026 Exhibitor List – bigdataldn.com](https://www.bigdataldn.com/en-gb/exhibitor-list.html#/)

- [Bigdata & Ai Paris 2026 Exhibitor List – bigdataparis.com](https://www.bigdataparis.com/en-gb/exhibition/exposants.html#/)

- [Cannes Yachting Festival 2026 Exhibitor List – cannesyachtingfestival.com](https://www.cannesyachtingfestival.com/en-gb/attend/exhibitors-list.html#/)

- [Chemspec Europe 2026 Exhibitor List – chemspeceurope.com](https://www.chemspeceurope.com/en-gb/exhibitor-directory.html#/)

- [COSMEX 2026 Exhibitor List – cosmexshow.com](https://www.cosmexshow.com/en-gb/visitor-info/search-for-exhibitors.html#/)

- [ISC East 2026 Exhibitor List – discoverisc.com](https://www.discoverisc.com/east/en-us/for-attendees/exhibitor-list.html#/)

- [ISC West 2026 Exhibitor List – discoverisc.com/west](https://www.discoverisc.com/west/en-us/exhibitors/exhibitor-directory.html#/)

- [Vision Expo 2026 Exhibitor List – visionexpo.com](https://www.visionexpo.com/en-us/attend/exhibitor-list.html#/)

- [Equipotel 2026 Exhibitor List – equipotel.com.br](https://www.equipotel.com.br/pt-br/Expositores.html#/)

- [EQUITANA Essen 2026 Exhibitor List – equitana.com/essen](https://www.equitana.com/essen/en-gb/exhibitor-directory.html#/)

- [Euro Bleech 2026 Exhibitor List – euroblech.com](https://www.euroblech.com/en-gb/exhibitor-directory.html#/)

- [EBS Mexico 2026 Exhibitor List – expobeautyshow.com](https://www.expobeautyshow.com/en-us/exhibitor-list.html#/)

- [Expo Fac Farmacias 2026 Exhibitor List – expofac.mx](https://www.expofac.mx/en-gb/exhibitor-directory.html#/)

- [Expo Nacional Ferretera 2026 Exhibitor List – expoferretera.com.mx](https://www.expoferretera.com.mx/en-gb/exhibitor-list.html#/)

- [EXPO Ferroviaria 2026 Exhibitor List – expoferroviaria.com](https://www.expoferroviaria.com/en-gb/exhibitor-directory.html#/)

- [Febrava 2025 Exhibitor List – febrava.com.br](https://www.febrava.com.br/pt-br/Expositores.html#/)

- [FIBO Arabia 2026 Exhibitor List – fibo.com](https://www.fibo.com/arabia/en-gb/exhibitor-directory.html#/)

- [FIBO Germany 2026 Exhibitor List – fibo.com](https://www.fibo.com/germany/en-gb/exhibitor-directory.html#/)

- [FIEE 2025 Exhibitor List – fiee.com.br](https://www.fiee.com.br/pt-br/visitar/marcas-confirmadas.html#/)

- [FILM&TAPE EXPO 2026 Exhibitor List – film-expo.com](https://www.film-expo.com/en-gb/exhibitors/directory.html#/)

- [G2E (Global Gaming Expo) 2026 Exhibitor List – globalgamingexpo.com](https://www.globalgamingexpo.com/en-us/attend/exhibitor-list.html#/)

- [GPCE 2026 Exhibitor List – gpce.com.au](https://www.gpce.com.au/perth/en-gb/exhibitor-directory.html#/)

- [ibtm Americas 2026 Exhibitor List – ibtmamericas.com](https://www.ibtmamericas.com/en-gb/exhibitors-directory.html#/)

- [ibtm World 2025 Exhibitor List – ibtmworld.com](https://www.ibtmworld.com/en-gb/exhibitor-directory.html#/)

- [IFEX 2026 Exhibitor List – ifexflowerexpo.com](https://www.ifexflowerexpo.com/en-gb/exhibitor-directory/directory.html#/)

- [iftm 2026 Exhibitor List – iftm.fr](https://www.iftm.fr/en-gb/show/exhibitors.html#/)

- [IGTM 2025 Exhibitor List – igtmarket.com](https://www.igtmarket.com/en-gb/exhibitor-directory.html#/)

- [ILTM Asia Pacific 2026 Exhibitor List – iltm.com/asia-pacific](https://www.iltm.com/asia-pacific/en-gb/exhibitor-directory.html#/)

- [ILTM Cannes 2025 Exhibitor List – iltm.com/cannes](https://www.iltm.com/cannes/en-gb/exhibitor-directory.html#/)

- [ILTM North America 2026 Exhibitor List – iltm.com/north-america](https://www.iltm.com/north-america/en-gb/exhibitor-directory.html#/)

- [in-cosmetics Asia 2026 Exhibitor List – in-cosmetics.com](https://www.in-cosmetics.com/asia/en-gb/exhibitor-directory.html#/)

- [in-cosmetics Global 2026 Exhibitor List – in-cosmetics.com/global](https://www.in-cosmetics.com/global/en-gb/exhibitor-directory.html#/)

- [in-cosmetics Korea 2026 Exhibitor List – in-cosmetics.com/korea](https://www.in-cosmetics.com/korea/en-gb/exhibitor-directory/exhibitor-directory.html#/)

- [in-cosmetics latin america 2026 Exhibitor List – in-cosmetics.com](https://www.in-cosmetics.com/latin-america/en-gb/exhibitor-directory.html#/)

- [EXPO SEGURIDAD MÉXICO 2026 Exhibitor List – infosecuritymexico.com](https://www.exposeguridadmexico.com/en-gb/exhibitor-list.html#/)

- [inter airport Global 2025 Exhibitor List – interairporteurope.com](https://www.interairportglobal.com/en-gb/exhibitor-directory.html#/)

- [IT Partners 2026 Exhibitor List – itpartners.fr](https://www.itpartners.fr/en-gb/exhibitors-list.html#/)

- [J-AGRI Gardex Tool Japan 2025 Exhibitor List – jagri-global.jp](https://www.jagri-global.jp/tokyo/en-gb/search/2025/directory.html#/)

- [JIS FALL 2026 Exhibitor List – jisshow.com](https://www.jisshow.com/fall/en-us/attend/exhibitor-directory.html#/)

- [JIS SPRING 2027 Exhibitor List – jisshow.com](https://www.jisshow.com/spring/en-us/attend/exhibitor-directory.html#/)

- [JWS 2026 Exhibitor List – jws.ae](https://www.jws.ae/en/brand-directory.html#/)

- [Kormarine 2025 Exhibitor List – kormarine.com](https://www.kormarine.com/en-gb/visitor/exhibitor_directory.html#/)

- [JCK LasVegas 2026 Exhibitor List – lasvegas.jckonline.com](https://lasvegas.jckonline.com/en-us/about/exhibitor-directory.html#/)

- [JCK Luxury 2026 Exhibitor List – lasvegas.jckonline.com](https://luxury.jckonline.com/en-us/exhibit/exhibitor-directory.html#/)

- [Manufacturing World Fukuoka 2024 Exhibitor List – manufacturing-world.jp](https://www.manufacturing-world.jp/kyushu/en-gb/search/2024/directory.html#/)

- [Manufacturing World Nagoya 2025 Exhibitor List – manufacturing-world.jp](https://www.manufacturing-world.jp/nagoya/en-gb/search/2025/directory.html#/)

- [Manufacturing World Osaka 2025 Exhibitor List – manufacturing-world.jp](https://www.manufacturing-world.jp/osaka/en-gb/search/2025/directory.html#/)

- [Manufacturing World Tokyo 2025 Exhibitor List – manufacturing-world.jp](https://www.manufacturing-world.jp/tokyo/en-gb/search/2025/directory.html#/)

- [Mostra Convegno Expocomfort (MCE) 2026 Exhibitor List – mcexpocomfort.it](https://www.mcexpocomfort.it/en-gb/exhibitor-directory.html#/)

- [Medical Japan Tokyo 2025 Exhibitor List – medical-jpn.jp](https://www.medical-jpn.jp/tokyo/en-gb/search/2025/directory.html#/)

- [Metalex 2026 Exhibitor List – metalex.co.th](https://www.metalex.co.th/en-gb/visitor-info/search-for-exhibitors.html#/)

- [Nepcon Asia 2026 Exhibitor List – nepconasia.com](https://www.nepconasia.com/en-gb/zszx/exhibitor-directory.html.html#/)

- [Nepcon Japan Tokyo 2025 Exhibitor List – nepconjapan.jp](https://www.nepconjapan.jp/autumn/en-gb/search/2025/directory.html#/)

- [NexTech Week 2025 Exhibitor List – nextech-week.jp](https://www.nextech-week.jp/autumn/en-gb/search/25/directory.html#/)

- [NHS Concept To Commerce 2026 Exhibitor List – nhsconcepttocommerce.com](https://www.nhsconcepttocommerce.com/en-us/exhibit-hall/exhibitor-list.html#/)

- [Offshore Europe 2025 Exhibitor List – offshore-europe.co.uk](https://www.offshore-europe.co.uk/en-gb/exhibitor-directory.html#/)

- [PGA Show 2027 Exhibitor List – pgashow.com](https://www.pgashow.com/en-us/show-info/exhibitor-list.html#/)

- [pollutec 2025 Exhibitor List – pollutec.com](https://www.pollutec.com/en-gb/who-is-coming/liste-exposants.html#/)

- [PSI 2026 Exhibitor List – psi-messe.com](https://www.psi-messe.com/en-gb/exhibitor-directory.html#/)

- [C-TOUCH & DISPLAY SHENZHEN 2026 Exhibitor List – quanchu.com.cn](https://www.quanchu.com.cn/en-gb/exhibitors/exhibitior-directory.html#/)

- [Reed Gift Fairs Melbourne 2026 Exhibitor List – reedgiftfairs.com.au](https://www.reedgiftfairs.com.au/melbourne/en-gb/exhibitor-directory.html#/)

- [Reed Gift Fairs Sydney 2027 Exhibitor List – reedgiftfairs.com.au](https://www.reedgiftfairs.com.au/sydney/en-gb/exhibitor-directory.html#/)

- [Renodays 2026 Exhibitor List – renodays.com](https://www.renodays.com/fr-fr/qui-participe/les-exposants.html#/)

- [APS 2025 Exhibitor List – salon-aps.com](https://www.salon-aps.com/en-gb/exhibitors/exhibitors-list.html#/)

- [Reeduca 2026 Exhibitor List – salonreeduca.com](https://www.salonreeduca.com/en-gb/exhibitors/exhibitors-list.html#/)

- [SITL 2026 Exhibitor List – sitl.eu](https://www.sitl.eu/en-gb/who-is-coming/exhibitors-list.html#/)

- [SCE 2026 Exhibitor List – supplychain-event.com](https://www.supplychain-event.com/en-gb/who-is-coming/exhibitors-list.html#/)

- [Top Flotillas 2026 Exhibitor List – topflotillas.com](https://www.topflotillas.com/es/directorio-proveedores.html#/)

- [viscom Italia 2026 Exhibitor List – viscomitalia.it](https://www.viscomitalia.it/en-gb/exhibitor-directory.html#/)

- [Waste Expo Australia 2026 Exhibitor List – wasteexpoaustralia.com.au](https://www.wasteexpoaustralia.com.au/en-gb/exhibitor-directory.html#/)

- [World Future Energy Summit 2026 Exhibitor List – worldfutureenergysummit.com](https://www.worldfutureenergysummit.com/en-gb/exhibitor-directory.html#/)

- [Hydrogen Americas 2025 Exhibitor List – world-hydrogen-summit.com](https://www.world-hydrogen-summit.com/americas/en-gb/exhibitor-directory.html#/)

- [World Hydrogen Summit & Exhibition 2026 Exhibitor List – world-hydrogen-summit.com](https://www.world-hydrogen-summit.com/world/en-gb/exhibitor-directory.html#/)

- [World Nuclear Exhibition 2025 Exhibitor List – world-nuclear-exhibition.com](https://www.world-nuclear-exhibition.com/en-gb/wne-exhibitors/exhibitors-list-25.html#/)

- [World Travel Catering & Onboard Services Expo 2026 Exhibitor List – worldtravelcateringexpo.com](https://www.worldtravelcateringexpo.com/en-gb/exhibitor-directory.html#/)

- [Smart Energy Week 2025 Exhibitor List – wsew.jp](https://www.wsew.jp/autumn/en-gb/search/2025/directory.html#/)

- [WTM Arabian Travel Market 2026 Exhibitor List – wtm.com/atm](https://www.wtm.com/atm/en-gb/exhibitor-directory.html#/)

- [WTM Latin America 2026 Exhibitor List – wtm.com/latin-america](https://www.wtm.com/latin-america/en-gb/exhibitor-directory.html#/)

- [WTM London 2026 Exhibitor List – wtm.com/london](https://www.wtm.com/london/en-gb/exhibitor-directory.html#/)

- [WTM Spotlight Riyadh 2026 Exhibitor List – wtm.com/spotlight-riyadh](https://www.wtm.com/spotlight-riyadh/en-gb/exhibitor-directory.html#/)

- [Expoprotection 2026 Exhibitor List – expoprotection.com](https://www.expoprotection.com/en-gb/who-is-coming/exhibitors-list.html#/)

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