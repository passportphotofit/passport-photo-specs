# Passport and ID photo specifications (open data)

Photo size, head height and background rules for **49 passport, visa and ID documents**: US, UK, Ireland, Schengen, Canada, Australia, New Zealand, India and more.

Every record links to the **official government source** it was taken from and says when it was last checked. Maintained by [PassportPhotoFit](https://passportphotofit.com), a free passport photo maker that runs in your browser.

## Files

| File | What it holds |
|---|---|
| `specs.json` | Full records: size, head height, background, notes, all official sources, last checked date |
| `specs.csv` | One row per document with the main numbers and the primary source, for spreadsheets |

## Fields (`specs.json`)

| Field | Meaning |
|---|---|
| `id` | Stable identifier, e.g. `us-passport-print` |
| `name` | Document name |
| `width`, `height`, `unit` | Photo size (millimetres) |
| `head_height_mm` | `[min, max]` chin to crown, in mm |
| `head_height_official` | `true` if the head size is stated by the authority; `false` if it is a recommended framing |
| `background` | Background rule, in words |
| `upload_original_unedited` | `true` when the authority wants the original, uncropped file uploaded (it crops it itself), e.g. UK and US online applications |
| `notes` | Other rules, in plain English |
| `official_sources` | Name and URL of each official page or form used |
| `last_checked` | Date the sources were last checked |
| `guide` | Page with the full rules and a free photo maker |

## Documents

| Document | Size | Head height | Source | Checked |
|---|---|---|---|---|
| US passport (printed 2 × 2 in) | 50.8 × 50.8 mm | 25.4–34.9 mm | [official](https://eforms.state.gov/Forms/ds82%5Fpdf.PDF) | 2026-11-11 |
| US passport, renewing online (check only, no crop) | 3 × 4 mm | — | [official](https://eforms.state.gov/Forms/ds82%5Fpdf.PDF) | 2026-11-11 |
| US visa (DS-160 / DS-260 upload) | 1 × 1 mm | — | [official](https://be.usembassy.gov/photos/) | 2026-11-11 |
| DV lottery entry (600 × 600 px) | 1 × 1 mm | — | [official](https://www.govinfo.gov/content/pkg/FR-2024-10-01/pdf/2024-22482.pdf) | 2026-11-11 |
| SAT registration photo | 3 × 4 mm | — | [official](https://satsuite.collegeboard.org/sat/registration/online-registration/photo-requirements) | 2026-11-11 |
| ACT registration photo | 3 × 4 mm | — | [official](https://www.act.org/content/act/en/products-and-services/the-act/registration/photo-submission-requirements.html) | 2026-11-11 |
| LSAT registration photo | 1 × 1 mm | — | [official](https://www.lsac.org/lsat/lsat-photo-requirements) | 2026-11-11 |
| UK passport (printed photo) | 35 × 45 mm | 29–34 mm | [official](https://www.gov.uk/photos-for-passports) | 2026-11-11 |
| UK passport, applying online (check only, no crop) | 3 × 4 mm | — | [official](https://www.gov.uk/photos-for-passports) | 2026-11-11 |
| UK Railcard photo | 35 × 45 mm | — | [official](https://www.railcard.co.uk/help/) | 2026-11-11 |
| UK ETA or UK visa (digital photo) | 4 × 5 mm | — | [official](https://www.gov.uk/guidance/how-to-take-a-photo-for-a-visa-application-or-permission) | 2026-11-11 |
| CitizenCard (UK proof of age) | 3 × 4 mm | — | [official](https://www.citizencard.com/photo-guidance) | 2026-11-11 |
| TfL Zip, 18+ Student and 60+ Oyster photocard (digital photo) | 35 × 45 mm | — | [official](https://tfl.gov.uk/fares/free-and-discounted-travel/11-15-zip-oyster-photocard) | 2026-11-11 |
| CSCS card (construction), uploaded photo | 35 × 45 mm | — | [official](https://www.cscs.uk.com/photo-requirements/) | 2026-11-11 |
| HM Armed Forces Veteran Card (digital photo) | 4 × 5 mm | — | [official](https://www.gov.uk/veteran-card/apply) | 2026-11-11 |
| UK driving licence, postal D1 application (printed photo) | 35 × 45 mm | 29–34 mm | [official](https://www.gov.uk/renew-photo-driving-licence) | 2026-11-12 |
| UK firearm or shotgun certificate (Form 201) | 35 × 45 mm | — | [official](https://assets.publishing.service.gov.uk/media/6aad367f2f29b388848186dc/HO_Firearms_Form_201__Sept_26_-_Final_.pdf) | 2026-11-12 |
| Irish passport (Passport Online) | 715 × 951 mm | — | [official](https://www.ireland.ie/en/dfa/passports/photo-guidelines/) | 2026-11-11 |
| Irish visa (printed photo) | 35 × 45 mm | — | [official](https://www.irishimmigration.ie/photograph-rules-for-visa-applications/) | 2026-11-11 |
| Irish passport (paper application, printed photo) | 35 × 45 mm | — | [official](https://www.ireland.ie/en/dfa/passports/photo-guidelines/) | 2026-11-11 |
| Student TFI Leap Card (selfie upload) | 3 × 4 mm | — | [official](https://student.leapcard.ie/New-Card) | 2026-11-11 |
| Ireland SPSV driver licence (printed, about 10 × 7 cm) | 70 × 100 mm | — | [official](https://www.nationaltransport.ie/taxi/driver-licensing/applying-for-an-spsv-driver-licence/) | 2026-11-12 |
| Schengen visa (35 × 45 mm) | 35 × 45 mm | 32–36 mm | [official](https://uk.diplo.de/uk-en/02/visa/visa-faq/2442852) | 2026-11-11 |
| Australian passport (printed) | 35 × 45 mm | 32–36 mm | [official](https://www.passports.gov.au/help/passport-photos) | 2026-11-11 |
| Working with Children Check (Victoria) | 406 × 521 mm | — | [official](https://www.vic.gov.au/requirements-acceptable-photo) | 2026-11-11 |
| Australia ImmiAccount (citizenship and visas) | 3 × 4 mm | — | [official](https://immi.homeaffairs.gov.au/help-text/evidence/Pages/et-h0369.aspx) | 2026-11-11 |
| New Zealand passport (online) | 3 × 4 mm | — | [official](https://www.passports.govt.nz/passport-photos/) | 2026-11-11 |
| New Zealand visa or NZeTA | 3 × 4 mm | — | [official](https://www.immigration.govt.nz/assets/inz/documents/apply-for-a-visa/Taking-acceptable-visa-photos.pdf) | 2026-11-11 |
| Kiwi Access Card (printed 35 × 45 mm) | 35 × 45 mm | — | [official](https://kiwiaccess.co.nz/photo-requirements/) | 2026-11-11 |
| New Zealand firearms licence (MyFirearms upload) | 3 × 4 mm | — | [official](https://www.firearmssafety.govt.nz/individual-licence/get-licensed/application-process) | 2026-11-12 |
| India e-Visa | 1 × 1 mm | — | [official](https://indianvisaonline.gov.in/evisa/tvoa.html) | 2026-11-11 |
| India visa (regular, via mission) | 1 × 1 mm | — | [official](https://indianvisaonline.gov.in/evisa/tvoa.html) | 2026-11-11 |
| OCI card | 1 × 1 mm | — | [official](https://ociservices.gov.in/onlineOCI/faq) | 2026-11-11 |
| Indian passport, applying abroad (630 × 810 px) | 630 × 810 mm | — | [official](https://mportal.passportindia.gov.in/pdf/Guidelines_for_ICAO_Compliant_Photographs_for_Passport_Applications.pdf) | 2026-11-11 |
| PAN card, Protean online with scanned images (max 20 KB) | 197 × 276 mm | — | [official](https://tinpan.proteantech.in/downloads/pan/download/Form%2093.pdf) | 2026-11-12 |
| PAN card (printed 4.5 × 3.5 cm, Form 93) | 35 × 45 mm | — | [official](https://tinpan.proteantech.in/downloads/pan/download/Form%2093.pdf) | 2026-11-12 |
| China visa (online form upload) | 354 × 472 mm | — | [official](https://www.visaforchina.cn/MAN4_EN/qianzhengyewu/jichuzhishi/changjianwenti/552365353674608655.html) | 2026-11-11 |
| China visa (printed 33 × 48 mm) | 33 × 48 mm | 28–33 mm | [official](https://www.visaforchina.cn/MAN4_EN/qianzhengyewu/jichuzhishi/changjianwenti/552365353674608655.html) | 2026-11-11 |
| Saudi Arabia eVisa | 1 × 1 mm | — | [official](https://visa.visitsaudi.com/Home/PhotoSpecifications) | 2026-11-11 |
| UAE passport or Emirates ID (ICP, 3.5 × 4.5 cm) | 35 × 45 mm | — | [official](https://icp.gov.ae/wp-content/themes/ica_v3/assets/images/servicesGuideEN2024.pdf) | 2026-11-12 |
| 35 × 45 mm (standard passport size) | 35 × 45 mm | 32–36 mm | — | 2026-11-11 |
| 2 × 2 inch (51 × 51 mm) | 50.8 × 50.8 mm | — | — | 2026-11-11 |
| Canada visitor visa (printed, 35 × 45 mm) | 35 × 45 mm | 31–36 mm | [official](https://www.canada.ca/en/immigration-refugees-citizenship/services/application/application-forms-guides/temporary-resident-visa-application-photograph-specifications.html) | 2026-11-11 |
| Canada PR card, online application (check only, no crop) | 5 × 7 mm | — | [official](https://www.canada.ca/en/immigration-refugees-citizenship/services/permanent-residents/card/photos.html) | 2026-11-12 |
| Canada firearms licence (PAL), 45 × 57 mm | 45 × 57 mm | 30–36 mm | [official](https://rcmp.ca/en/firearms/licensing/photo-requirements-firearms-licence) | 2026-11-12 |
| Japanese passport, applying online (JPG upload) | 35 × 45 mm | — | [official](https://www.mofa.go.jp/mofaj/toko/passport/pass_2.html) | 2026-11-12 |
| Japanese passport (printed 45 × 35 mm) | 35 × 45 mm | 32–36 mm | [official](https://www.mofa.go.jp/mofaj/toko/passport/pass_2.html) | 2026-11-12 |
| Singapore passport (printed 35 × 45 mm) | 35 × 45 mm | 25–35 mm | [official](https://www.ica.gov.sg/photo-guidelines) | 2026-11-12 |
| Singapore passport or IC, applying online (400 × 514 px) | 400 × 514 mm | — | [official](https://www.ica.gov.sg/photo-guidelines) | 2026-11-12 |

## Important

Rules change. **Always check the official source before you apply.** If you spot an outdated rule, please open an issue with a link to the official page.

## License

Data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can use it in apps, articles and research, including commercially. Please credit: **"Source: PassportPhotoFit (passportphotofit.com)"** with a link.
