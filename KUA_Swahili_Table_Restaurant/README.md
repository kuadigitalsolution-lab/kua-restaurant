# Swahili Table Restaurant — KUA Digital Solution

Mradi huu ni tovuti ya mfano ya mgahawa, iliyotengenezwa kwa HTML, CSS na JavaScript bila database wala backend. Brand credit: **Developed by KUA**.

## Kuanza kutumia
1. Pakua na fungua ZIP.
2. Weka picha ya logo yako inayoitwa **`kualogo.png`** kwenye folder kuu (root), sambamba na `index.html`.
3. Fungua `index.html` kwenye browser. Kwa matokeo bora, tumia VS Code na extension ya Live Server, au endesha local static server.
4. Fungua `admin.html` ili kuona dashboard ya demo.

## Dashboard bila database
Dashboard inapatikana kwenye `admin.html`. Inaonyesha takwimu za bidhaa, kuongeza bidhaa, kubadilisha jina/bei, kuwasha/kuzima upatikanaji na kuhariri baadhi ya mipangilio. Data huhifadhiwa kwenye `localStorage` ya browser hiyo tu. Hii si mfumo salama wa online admin: mabadiliko hayafiki kwa wateja wengine, hayashirikishwi kati ya vifaa, na yanaweza kufutika ukisafisha data ya browser. Kwa dashboard ya kweli ya online inayosawazisha menu kwa wateja wote, utahitaji backend/database au CMS.

## Sanidi biashara
Hariri `assets/js/config.js`:
- `whatsapp`: namba ya WhatsApp katika muundo wa kimataifa bila alama ya `+`, mfano `2557XXXXXXXX`.
- `phone`, `email`, `address`, `openingHours`.
- `deliveryFee`, `deliveryEnabled`, `pickupEnabled`.
- `logoPath` (logo inayotumika ni `kualogo.png`).

Badilisha bidhaa kwenye `assets/js/products.js`. Bei, picha, bidhaa, maoni, wapishi na hadithi kwenye mradi huu ni maudhui ya demo; thibitisha na ubadilishe kabla ya matumizi halisi.

## Oda na nafasi
Checkout na fomu ya nafasi huandaa ujumbe wa WhatsApp. Kufungua WhatsApp hakumaanishi ujumbe umetumwa, wala oda imepokelewa. Mteja anapaswa kukagua na kutuma ujumbe mwenyewe, kisha kusubiri uthibitisho wa mgahawa. Hakuna malipo ya online, uthibitishaji wa malipo, database, live tracking au upatikanaji wa meza wa wakati halisi.

## Kurasa
Mradi una kurasa za nyumbani, menu, makundi, bidhaa, kikapu, checkout, uthibitisho wa hatua za WhatsApp, ofa, combo, breakfast, lunch/dinner, drinks, desserts, gallery, about, chefs, reservations, delivery, pickup, find-us, FAQ, contact, order tracking, privacy, terms, 404 na admin.

## Kuchapisha online
### Cloudflare Pages
1. Upload project kwenye Git repository.
2. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
3. Build command iwe tupu kwa static HTML; output directory iwe root ya project (`/` au folder ya mradi kulingana na mpangilio wako).
4. Deploy.

### Vercel
1. Weka mradi kwenye Git repository.
2. Vercel → Add New Project → import repository.
3. Framework preset: Other; build command tupu; output directory root.
4. Deploy.

## Checklist kabla ya kuzindua
- [ ] Weka `kualogo.png` kwenye root.
- [ ] Badilisha namba ya WhatsApp na simu.
- [ ] Hakiki bei, bidhaa, maelezo, picha na upatikanaji.
- [ ] Sanidi anwani, saa za kazi na maeneo/gharama za delivery.
- [ ] Hakiki sera ya faragha na masharti.
- [ ] Hakiki taarifa za viungo na mzio.
- [ ] Jaribu cart, totals, checkout, mobile navigation na WhatsApp.
- [ ] Kumbuka admin ya localStorage haibadilishi menu kwa wateja wa online.

## Testing iliyofanywa
Muundo wa HTML, CSS na JavaScript umeandaliwa na faili zote za kurasa zimewekwa kwenye project. Uendeshaji wa kila ukurasa kwenye browser halisi, WhatsApp kwa namba ya biashara, na deployment ya Cloudflare/Vercel havijathibitishwa katika mazingira haya. Picha nyingi hupakiwa kutoka Unsplash na zinahitaji intaneti.
