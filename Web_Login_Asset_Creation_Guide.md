# MahitiBazaar Web Login — Asset Creation Guide

**Audience:** Graphic Design Team
**Product:** MahitiBazaar Web Login
**Date:** 27 October 2026
**Sources:** `docs/MBWebLogin_PRDv1.md` and `docs/26-Mahitibazaar-Multi-Services-Category-Title.md`
**Companion:** `docs/Web_Login_Content_Update_Guide.md`

This guide lists the images to create for the Web Login catalogue. Service titles are copied from the Multi-Services document. Categories follow the Web Login PRD.

The source albums (Multi Services, Government schemes, University links, Educational admission, and GSTMitra groups) are trace labels only. They are not Web Login categories.

## How a service was placed

| Module | PRD meaning | Poster |
| --- | --- | --- |
| e-Mahiti | Time-bound information with a start date and an end date: jobs, admissions, scholarships, schemes, exams | Produce |
| e-Seva | A standing service with a start date and no end date: Aadhaar, PAN, GST, Shop Act, driving licence, voter card, and the same kind of counter service | Produce |
| Uncertain | The purpose fits more than one PRD module, or it fits e-Link | Wait for Admin |

e-Link, in the PRD, is for results, admit cards, exam forms, and official websites. It has no poster, advertisement, or document folder. Rows that point at e-Link stay under Uncertain so this guide does not assign them to e-Mahiti or e-Seva.

A **PRD category** is one of the category examples in the PRD. A **PRD example** is named in the module description and is not in that category list (Income Tax Services, MSME Registration). A **Proposed** subcategory is a purpose group the PRD does not name. Admin confirms a proposed name before publish. Artwork for that purpose can still be produced.

The e-Mahiti description also names Recruitment Drives. The category list names Government Jobs. Recruitment services in this guide use Government Jobs.

## Image specifications

### Subcategory card and service card

The PRD image library stores reusable category images. On the detailed content card the image is a square shown at 110–130px, with a bold title of at most two lines beside it.

- Square PNG.
- Recommended master: 1200 × 1200 px, so the icon stays clear at 110–130px. The PRD does not fix a pixel size.
- The catalogue title is stored in Web Login. Keep text inside the image short. The subcategory table gives a suggested Marathi label for the library thumbnail.
- Services in a section share that subcategory card, except where a row names its own card file.

### Service poster

e-Mahiti and e-Seva support posters. Poster-thumbnail layout shows the poster and the title. A Center Owner can download the original poster and a branded copy. Branding is applied to a copy. The original file stays unchanged.

- One primary poster for each service row, unless the row names a shared poster file.
- PNG or JPEG. The PRD accepts portrait, landscape, and square posters. Use portrait for this delivery.
- Recommended master: 1080 × 1350 px. This is a production recommendation, not a PRD size.
- Keep the headline, dates, and logos out of the bottom band. The PRD places a full-width transparent PNG overlay on the bottom edge of the branded copy. The overlay height follows that PNG. A clear band of about 18% of the poster height is a recommendation.
- The service title painted on the poster matches the service name in this guide.

### Default card

| File | Use |
| --- | --- |
| `CAT-DEFAULT-card.png` | Fallback when a record has no library image. The PRD then keeps the poster thumbnail or this default image. |

### Shared posters

These files are produced once and attached to every service named in the design note.

| Poster file | Covers |
| --- | --- |
| `SHARED-FSSAI-REG-poster.png` | FSSAI registration durations. The year count stays in the title. |
| `SHARED-GST-FILE-poster.png` | GST filing that differs only by bill count or monthly/quarterly period. |
| `SHARED-SHOP-BAND-poster.png` | Shop Act intimation that differs only by employee band. |
| `SHARED-GAZETTE-poster.png` | Gazette notification. Open or reserved stays in the title. |

### Outside this delivery

- Page banners, Help Center art, and the Center Owner’s shop logo or branding overlay.
- Advertisement creatives. They are optional. The content guide covers them.
- Supportive PDFs. Those are a content deliverable.
- Extra poster sizes. One primary poster is the first delivery.

## File names

Use `{id}-card.png` and `{id}-poster.png`. Shared files keep the `SHARED-...` or `CAT-...` id shown in the row. The asset id is the same id in the content guide.

## Counts

| Group | Services |
| --- | ---: |
| e-Mahiti | 143 |
| e-Seva | 190 |
| Uncertain, artwork on hold | 56 |
| Distinct service names | 389 |
| Card files to export, including the default card | 52 |
| Poster files to export | 324 |

An exact repeated title in the source is listed once. The content guide records each source list it came from.

## Subcategory cards

Produce one card for each row. The suggested label is for the artwork. It is not a PRD field.

| Card file | Module | Subcategory | Basis | Suggested art label | Services |
| --- | --- | --- | --- | --- | ---: |
| `CAT-EM-SCH-card.png` | e-Mahiti | Government Schemes | PRD category | योजना | 89 |
| `CAT-EM-ADM-card.png` | e-Mahiti | Admissions | PRD category | प्रवेश | 46 |
| `CAT-EM-SHO-card.png` | e-Mahiti | Scholarships | PRD category | शिष्यवृत्ती | 2 |
| `CAT-EM-EXM-card.png` | e-Mahiti | Exams | PRD category | परीक्षा | 5 |
| `CAT-EM-JOB-card.png` | e-Mahiti | Government Jobs | PRD category | भरती | 1 |
| `CAT-ES-AAD-card.png` | e-Seva | Aadhaar | PRD category | आधार | 8 |
| `CAT-ES-PAN-card.png` | e-Seva | PAN | PRD category | पॅन | 3 |
| `CAT-ES-GST-card.png` | e-Seva | GST | PRD category | जीएसटी | 15 |
| `CAT-ES-SHP-card.png` | e-Seva | Shop Act | PRD category | शॉप अ‍ॅक्ट | 5 |
| `CAT-ES-DL-card.png` | e-Seva | Driving License | PRD category | ड्रायव्हिंग लायसन्स | 5 |
| `CAT-ES-VOT-card.png` | e-Seva | Voter ID | PRD category | मतदान कार्ड | 4 |
| `CAT-ES-TAX-card.png` | e-Seva | Income Tax | PRD example | आयकर | 11 |
| `CAT-ES-MSM-card.png` | e-Seva | MSME | PRD example | उद्योग आधार | 3 |
| `CAT-ES-CER-card.png` | e-Seva | Certificates | Proposed | प्रमाणपत्रे | 22 |
| `CAT-ES-RTO-card.png` | e-Seva | Vehicle and RTO | Proposed | आरटीओ | 7 |
| `CAT-ES-TRV-card.png` | e-Seva | Passport and travel | Proposed | पासपोर्ट | 5 |
| `CAT-ES-LAB-card.png` | e-Seva | Labour and social security | Proposed | श्रम | 15 |
| `CAT-ES-LND-card.png` | e-Seva | Land and property | Proposed | जमीन | 8 |
| `CAT-ES-LIC-card.png` | e-Seva | Licences and permissions | Proposed | परवाना | 14 |
| `CAT-ES-BIZ-card.png` | e-Seva | Business compliance | Proposed | व्यवसाय नोंदणी | 26 |
| `CAT-ES-BNK-card.png` | e-Seva | Banking | Proposed | बँक | 1 |
| `CAT-ES-UTL-card.png` | e-Seva | Utilities | Proposed | जोडणी | 3 |
| `CAT-ES-EDU-card.png` | e-Seva | Education documents | Proposed | शैक्षणिक कागदपत्रे | 6 |
| `CAT-ES-GRV-card.png` | e-Seva | Grievance and public information | Proposed | तक्रार | 5 |
| `CAT-ES-BOK-card.png` | e-Seva | Bookings | Proposed | बुकिंग | 7 |
| `CAT-ES-PRF-card.png` | e-Seva | Professional registration | Proposed | व्यावसायिक नोंदणी | 5 |
| `CAT-ES-EMP-card.png` | e-Seva | Employment services | Proposed | रोजगार | 1 |
| `CAT-ES-DSN-card.png` | e-Seva | Design and digital services | Proposed | डिझाइन | 6 |
| `CAT-ES-AST-card.png` | e-Seva | Astrology | Proposed | ज्योतिष | 3 |
| `CAT-ES-RAT-card.png` | e-Seva | Ration card | Proposed | रेशन | 1 |
| `CAT-ES-HLT-card.png` | e-Seva | Health cards | Proposed | आरोग्य कार्ड | 1 |

## Service posters and cards

The card file goes to the image library. The poster file is attached to that service. A repeated card file is one shared image.

### e-Mahiti — Government Schemes

Basis: PRD category. Subcategory card: `CAT-EM-SCH-card.png`. Suggested art label: योजना.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| EM-SCH-001 | 10040 पीएम सुर्य घर योजना | `CAT-EM-SCH-card.png` | `EM-SCH-001-poster.png` |  |
| EM-SCH-002 | 1020 प्रधानमंत्री स्वनिधी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-002-poster.png` | Possible same service, different title: 929 प्रधानमंत्री स्वनिधी योजना; प्रधानमंत्री स्वनिधी योजना. Create one catalog record after Admin picks the title to keep. Related group: Svanidhi. |
| EM-SCH-003 | 10228 मौलाना आझाद शैक्षणिक कर्ज योजना | `CAT-EM-SCH-card.png` | `EM-SCH-003-poster.png` | Education loan scheme. Confirm it is not also created under Scholarships. |
| EM-SCH-004 | 10265 CMYKPY मुख्यमंत्री युवा कार्य प्रशिक्षण योजना | `CAT-EM-SCH-card.png` | `EM-SCH-004-poster.png` |  |
| EM-SCH-005 | 10296 मुख्यमंत्री वयोश्री योजना | `CAT-EM-SCH-card.png` | `EM-SCH-005-poster.png` |  |
| EM-SCH-006 | 10326 राजे यशवंतराव होळकर महामेष योजना (भज-क प्रवर्गा साठी) | `CAT-EM-SCH-card.png` | `EM-SCH-006-poster.png` | Related group: Holkar scheme. |
| EM-SCH-007 | 10330 मागेल त्याला सौर पंप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-007-poster.png` |  |
| EM-SCH-008 | 10357 PMSYM प्रधानमंत्री श्रमयोगी मानधन योजना | `CAT-EM-SCH-card.png` | `EM-SCH-008-poster.png` |  |
| EM-SCH-009 | 10381 प्रधानमंत्री इंटर्नशिप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-009-poster.png` |  |
| EM-SCH-010 | 10404 शेतकरी ओळखप्रमाणपत्र | `CAT-EM-SCH-card.png` | `EM-SCH-010-poster.png` | Possible same service, different title: 10404 शेतकरी ओळखप्रमाणपत्र (Farmer ID). Create one catalog record after Admin picks the title to keep. |
| EM-SCH-011 | 10404 शेतकरी ओळखप्रमाणपत्र (Farmer ID) | `CAT-EM-SCH-card.png` | `EM-SCH-011-poster.png` | Possible same service, different title: 10404 शेतकरी ओळखप्रमाणपत्र. Create one catalog record after Admin picks the title to keep. |
| EM-SCH-012 | 10410 हमीभावात पिक विक्रीसाठी नोंदणी | `CAT-EM-SCH-card.png` | `EM-SCH-012-poster.png` |  |
| EM-SCH-013 | 10429 आण्णासाहेब पाटील आर्थिक विकास महामंडळ | `CAT-EM-SCH-card.png` | `EM-SCH-013-poster.png` |  |
| EM-SCH-014 | 10457 आयुष्यमान वय वंदना योजना | `CAT-EM-SCH-card.png` | `EM-SCH-014-poster.png` |  |
| EM-SCH-015 | 10533 MAPS महाराष्ट्र अप्रेंटिसशिप प्रमोशन स्किम | `CAT-EM-SCH-card.png` | `EM-SCH-015-poster.png` |  |
| EM-SCH-016 | 10547 प्रधानमंत्री अवास योजना | `CAT-EM-SCH-card.png` | `EM-SCH-016-poster.png` | Related group: Housing scheme. |
| EM-SCH-017 | 10578 दिव्यांगजन रेल्वे कार्ड | `CAT-EM-SCH-card.png` | `EM-SCH-017-poster.png` |  |
| EM-SCH-018 | 10680 पशुवाटप योजना 2025-26 | `CAT-EM-SCH-card.png` | `EM-SCH-018-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. Related group: Livestock distribution. |
| EM-SCH-019 | 10742 फळ पिक विमा मृग बहार योजना | `CAT-EM-SCH-card.png` | `EM-SCH-019-poster.png` | Related group: Crop insurance. |
| EM-SCH-020 | 10759 प्रधानमंत्री पीक विमा योजना 2025-26 | `CAT-EM-SCH-card.png` | `EM-SCH-020-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. Related group: Crop insurance. |
| EM-SCH-021 | 10817 पुणे महानगरपालिका योजना | `CAT-EM-SCH-card.png` | `EM-SCH-021-poster.png` | Bundle title for Pune Municipal Corporation schemes. Confirm one record or a split. |
| EM-SCH-022 | 10981 रब्बी पिक विमा 2025 | `CAT-EM-SCH-card.png` | `EM-SCH-022-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. Related group: Crop insurance. |
| EM-SCH-023 | 10982 बांधकाम कामगार स्मार्ट कार्ड | `CAT-EM-SCH-card.png` | `EM-SCH-023-poster.png` |  |
| EM-SCH-024 | 10990 POCRA नानाजी देशमुख कृषी संजीवनी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-024-poster.png` |  |
| EM-SCH-025 | 11004 VMDDP दुग्ध व्यवसाय योजना | `CAT-EM-SCH-card.png` | `EM-SCH-025-poster.png` |  |
| EM-SCH-026 | 1111 वन्यजीव नुकसान भरपाई | `CAT-EM-SCH-card.png` | `EM-SCH-026-poster.png` |  |
| EM-SCH-027 | 11146 बांधकाम कामगार योजना | `CAT-EM-SCH-card.png` | `EM-SCH-027-poster.png` |  |
| EM-SCH-028 | 11183 दिव्यांग योजना (दिव्यांग सहाय्यक पोर्टल) | `CAT-EM-SCH-card.png` | `EM-SCH-028-poster.png` |  |
| EM-SCH-029 | 11312 फार्मासिस्ट सुरक्षा कवच योजना | `CAT-EM-SCH-card.png` | `EM-SCH-029-poster.png` |  |
| EM-SCH-030 | 11365 पिकविमा 2026 | `CAT-EM-SCH-card.png` | `EM-SCH-030-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. Related group: Crop insurance. |
| EM-SCH-031 | 11483 महिला शेतकरी प्रमाणपत्र | `CAT-EM-SCH-card.png` | `EM-SCH-031-poster.png` |  |
| EM-SCH-032 | 11513 फळपिक विमा योजना | `CAT-EM-SCH-card.png` | `EM-SCH-032-poster.png` | Possible same service, different title: 9497 फळपिक विमा योजना. Create one catalog record after Admin picks the title to keep. Related group: Crop insurance. |
| EM-SCH-033 | 11522 ओबीसी महामंडळ कर्ज योजना 2026 | `CAT-EM-SCH-card.png` | `EM-SCH-033-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-SCH-034 | 1908 प्रधानमंत्री उज्ज्वला योजना | `CAT-EM-SCH-card.png` | `EM-SCH-034-poster.png` |  |
| EM-SCH-035 | 2966 मागेल त्याला शेततळे योजना | `CAT-EM-SCH-card.png` | `EM-SCH-035-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. |
| EM-SCH-036 | 4000 प्रधानमंत्री किसान सन्मान निधी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-036-poster.png` | Possible same service, different title: प्रधानमंत्री किसान सन्मान निधी योजना. Create one catalog record after Admin picks the title to keep. Related group: PM-Kisan. |
| EM-SCH-037 | 4132 माझी कन्या भाग्यश्री योजना | `CAT-EM-SCH-card.png` | `EM-SCH-037-poster.png` |  |
| EM-SCH-038 | 4225 कृषि सुक्ष्म सिंचन योजना : ई-ठिबक | `CAT-EM-SCH-card.png` | `EM-SCH-038-poster.png` |  |
| EM-SCH-039 | 5589 भाऊसाहेब फुंडकर फळबाग लागवड योजना | `CAT-EM-SCH-card.png` | `EM-SCH-039-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. |
| EM-SCH-040 | 6284 महात्मा फुले कर्ज योजना | `CAT-EM-SCH-card.png` | `EM-SCH-040-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. |
| EM-SCH-041 | 6327 मुख्यमंत्री सौर कृषी पंंप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-041-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. |
| EM-SCH-042 | 6371 शैक्षणिक कर्ज योजना | `CAT-EM-SCH-card.png` | `EM-SCH-042-poster.png` | Education loan scheme. Confirm it is not also created under Scholarships. |
| EM-SCH-043 | 6396 अटल सौर कृषी पंप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-043-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. |
| EM-SCH-044 | 6793 उन्नत शेती - समृद्ध शेतकरी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-044-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. |
| EM-SCH-045 | 6943 डॉ. बाबासाहेब आंबेडकर कृषी स्वालंबन योजना | `CAT-EM-SCH-card.png` | `EM-SCH-045-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. |
| EM-SCH-046 | 7013 राजे यशवंतराव होळकर महामेष योजना | `CAT-EM-SCH-card.png` | `EM-SCH-046-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. Related group: Holkar scheme. |
| EM-SCH-047 | 7508 महात्मा जोतिराव फुले शेतकरी कर्जमुक्ती योजना | `CAT-EM-SCH-card.png` | `EM-SCH-047-poster.png` |  |
| EM-SCH-048 | 7625 कृषी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-048-poster.png` | Bundle title for agriculture schemes. Confirm one record or a split. |
| EM-SCH-049 | 7980 डॉ. बाबासाहेब आंबेडकर जीवन प्रकाश योजना | `CAT-EM-SCH-card.png` | `EM-SCH-049-poster.png` |  |
| EM-SCH-050 | 8052 भारतरत्न डॉ. बाबासाहेब आंबेडकर विशेष अनुदान योजना | `CAT-EM-SCH-card.png` | `EM-SCH-050-poster.png` |  |
| EM-SCH-051 | 8127 कुसुम कृषी सौर पंप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-051-poster.png` |  |
| EM-SCH-052 | 8294 कोव्हिड सानुग्रह सहाय्य 50000/- | `CAT-EM-SCH-card.png` | `EM-SCH-052-poster.png` |  |
| EM-SCH-053 | 8301 पशुवाटप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-053-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. Possible same service, different title: 9856 पशुवाटप योजना. Create one catalog record after Admin picks the title to keep. Related group: Livestock distribution. |
| EM-SCH-054 | 8696 ESM Scheme | `CAT-EM-SCH-card.png` | `EM-SCH-054-poster.png` |  |
| EM-SCH-055 | 8746 केंद्र सरकारची व्याज सबसिडी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-055-poster.png` |  |
| EM-SCH-056 | 8748 डॉ. आंबेडकर केंद्रीय सबसिडी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-056-poster.png` |  |
| EM-SCH-057 | 8749 कृषी दवाखाने / व्यवसाय योजना | `CAT-EM-SCH-card.png` | `EM-SCH-057-poster.png` |  |
| EM-SCH-058 | 8750 कृषी पायाभूत सुविधा निधी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-058-poster.png` |  |
| EM-SCH-059 | 8751 प्रधानमंत्री रोजगार निर्मिती कार्यक्रम | `CAT-EM-SCH-card.png` | `EM-SCH-059-poster.png` |  |
| EM-SCH-060 | 8752 विणकर मुद्रा योजना | `CAT-EM-SCH-card.png` | `EM-SCH-060-poster.png` |  |
| EM-SCH-061 | 8753 प्रधानमंत्री मुद्रा योजना | `CAT-EM-SCH-card.png` | `EM-SCH-061-poster.png` |  |
| EM-SCH-062 | 8754 पी एम स्वनिधी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-062-poster.png` | Related group: Svanidhi. |
| EM-SCH-063 | 8755 सफाई कामगार योजना | `CAT-EM-SCH-card.png` | `EM-SCH-063-poster.png` |  |
| EM-SCH-064 | 8756 स्टॅड अप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-064-poster.png` |  |
| EM-SCH-065 | 8908 छतावरील सौर पॅनल योजना | `CAT-EM-SCH-card.png` | `EM-SCH-065-poster.png` |  |
| EM-SCH-066 | 9039 शेतक-यांना रू. 50000/- अनुदान | `CAT-EM-SCH-card.png` | `EM-SCH-066-poster.png` |  |
| EM-SCH-067 | 9250 घरगुती शौचालय निर्माण योजना | `CAT-EM-SCH-card.png` | `EM-SCH-067-poster.png` | Possible same service, different title: घरगुती शौचालय निर्माण योजना. Create one catalog record after Admin picks the title to keep. |
| EM-SCH-068 | 929 प्रधानमंत्री स्वनिधी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-068-poster.png` | Possible same service, different title: 1020 प्रधानमंत्री स्वनिधी योजना; प्रधानमंत्री स्वनिधी योजना. Create one catalog record after Admin picks the title to keep. Related group: Svanidhi. |
| EM-SCH-069 | 9336 पिंपरी आकुर्डी : - प्रधानमंत्री आवास योजना | `CAT-EM-SCH-card.png` | `EM-SCH-069-poster.png` | Related group: Housing scheme. |
| EM-SCH-070 | 939 CMEGP मुख्यमंत्री रोजगार निर्मती कार्यक्रम | `CAT-EM-SCH-card.png` | `EM-SCH-070-poster.png` | Possible same service, different title: CMEGP मुख्यमंत्री रोजगार निर्मती कार्यक्रम. Create one catalog record after Admin picks the title to keep. |
| EM-SCH-071 | 9467 महाज्योती मोफत टॅब, इंटरनेट व JEE/NEET/MHT Cet प्रशिक्षण | `CAT-EM-SCH-card.png` | `EM-SCH-071-poster.png` | Student benefit. Confirm it is not also created under Scholarships. |
| EM-SCH-072 | 9497 फळपिक विमा योजना | `CAT-EM-SCH-card.png` | `EM-SCH-072-poster.png` | Possible same service, different title: 11513 फळपिक विमा योजना. Create one catalog record after Admin picks the title to keep. Related group: Crop insurance. |
| EM-SCH-073 | 9543 प्रधानमंत्री पीक विमा योजना | `CAT-EM-SCH-card.png` | `EM-SCH-073-poster.png` | Possible same service, different title: 9840 प्रधानमंत्री पीक विमा योजना. Create one catalog record after Admin picks the title to keep. Related group: Crop insurance. |
| EM-SCH-074 | 9560 PCMC कल्याणकारी योजना पिंपरी चिंंचवड महानगरपालिका | `CAT-EM-SCH-card.png` | `EM-SCH-074-poster.png` | Bundle title for PCMC welfare schemes. Confirm one record or a split. |
| EM-SCH-075 | 9707 पंतप्रधान विश्वकर्मा योजना | `CAT-EM-SCH-card.png` | `EM-SCH-075-poster.png` |  |
| EM-SCH-076 | 9714 आयुष्यमान भारत कार्ड | `CAT-EM-SCH-card.png` | `EM-SCH-076-poster.png` | Related group: Ayushman Bharat card. |
| EM-SCH-077 | 9840 प्रधानमंत्री पीक विमा योजना | `CAT-EM-SCH-card.png` | `EM-SCH-077-poster.png` | Possible same service, different title: 9543 प्रधानमंत्री पीक विमा योजना. Create one catalog record after Admin picks the title to keep. Related group: Crop insurance. |
| EM-SCH-078 | 9856 पशुवाटप योजना | `CAT-EM-SCH-card.png` | `EM-SCH-078-poster.png` | Possible same service, different title: 8301 पशुवाटप योजना. Create one catalog record after Admin picks the title to keep. Related group: Livestock distribution. |
| EM-SCH-079 | 9898 दिव्यांग व्यक्तींना मोफत फिरत्या वाहनावरील दुकान (मोबाईल शॉप ऑन ई-व्हेईकल) | `CAT-EM-SCH-card.png` | `EM-SCH-079-poster.png` |  |
| EM-SCH-080 | 9910 जनऔषधी केंद्र योजना | `CAT-EM-SCH-card.png` | `EM-SCH-080-poster.png` |  |
| EM-SCH-081 | 9915 प्रधानमंत्री मातृवंदना योजना | `CAT-EM-SCH-card.png` | `EM-SCH-081-poster.png` |  |
| EM-SCH-082 | Ayushman Bharat Card | `CAT-EM-SCH-card.png` | `EM-SCH-082-poster.png` | Possible same card as the Marathi Ayushman Bharat title. If the card has no campaign end date, confirm a move to e-Seva. Related group: Ayushman Bharat card. |
| EM-SCH-083 | CMEGP मुख्यमंत्री रोजगार निर्मती कार्यक्रम | `CAT-EM-SCH-card.png` | `EM-SCH-083-poster.png` | Possible same service, different title: 939 CMEGP मुख्यमंत्री रोजगार निर्मती कार्यक्रम. Create one catalog record after Admin picks the title to keep. |
| EM-SCH-084 | घरगुती शौचालय निर्माण योजना | `CAT-EM-SCH-card.png` | `EM-SCH-084-poster.png` | Possible same service, different title: 9250 घरगुती शौचालय निर्माण योजना. Create one catalog record after Admin picks the title to keep. |
| EM-SCH-085 | डॉ. बाबासाहेब आंबेडकर स्वाधार योजना | `CAT-EM-SCH-card.png` | `EM-SCH-085-poster.png` |  |
| EM-SCH-086 | प्रधानमंत्री आवास योजना : पुणे महानगर प्रदेश विकास प्राधिकरण | `CAT-EM-SCH-card.png` | `EM-SCH-086-poster.png` | Listed under old schemes. Confirm the scheme is still open. A closed scheme can stay in Draft, or be published with its real end date so e-Mahiti marks it Expired. Related group: Housing scheme. |
| EM-SCH-087 | प्रधानमंत्री किसान सन्मान निधी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-087-poster.png` | Possible same service, different title: 4000 प्रधानमंत्री किसान सन्मान निधी योजना. Create one catalog record after Admin picks the title to keep. Related group: PM-Kisan. |
| EM-SCH-088 | प्रधानमंत्री किसान सन्मान योजना शेतकरी नावनोंदणी | `CAT-EM-SCH-card.png` | `EM-SCH-088-poster.png` | Related group: PM-Kisan. |
| EM-SCH-089 | प्रधानमंत्री स्वनिधी योजना | `CAT-EM-SCH-card.png` | `EM-SCH-089-poster.png` | Possible same service, different title: 1020 प्रधानमंत्री स्वनिधी योजना; 929 प्रधानमंत्री स्वनिधी योजना. Create one catalog record after Admin picks the title to keep. Related group: Svanidhi. |

### e-Mahiti — Admissions

Basis: PRD category. Subcategory card: `CAT-EM-ADM-card.png`. Suggested art label: प्रवेश.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| EM-ADM-001 | 11223 11वी प्रवेश 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-001-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-002 | 11273 D.El.Ed Admission 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-002-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-003 | 11282 आयटीआय अ‍ॅडमिशन ITI Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-003-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-004 | 11284 डिप्लोमा प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-004-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-005 | 11317 PDKV डॉ. पंजाबराव देशमुख कृषि विद्यापीठ अकोला कृषी तंत्र पदविका (Agri. Diploma) प्रवेश | `CAT-EM-ADM-card.png` | `EM-ADM-005-poster.png` |  |
| EM-ADM-006 | 11325 LLB 3 Year Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-006-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-007 | 11326 B.Ed. Admissions 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-007-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-008 | 11327 B.P.Ed. Admissions 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-008-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-009 | 11328 MPED Admission 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-009-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-010 | 11335 MEd Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-010-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-011 | 11337 B.Ed.-M.Ed. (Integrated) Admissions 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-011-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-012 | 11342 LLB 5 Year Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-012-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-013 | 11348 थेट द्वितीय वर्ष डिप्लोमा प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-013-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-014 | 11357 डिप्लोमा फार्मसी (D Pharmacy) प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-014-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-015 | 11358 12वी नंतरचा डिप्लोमा प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-015-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-016 | 11362 BE / BTech इंजिनिअरिंग प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-016-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-017 | 11363 MBA MMS Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-017-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-018 | 11364 MCA Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-018-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-019 | 11366 BBA/BMS/BBM/MBA (Integrated) Admission | `CAT-EM-ADM-card.png` | `EM-ADM-019-poster.png` |  |
| EM-ADM-020 | 11367 BCA / MCA (Integrated) Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-020-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-021 | 11370 थेट द्वितीय वर्ष इंजिनिअरींग प्रवेश | `CAT-EM-ADM-card.png` | `EM-ADM-021-poster.png` |  |
| EM-ADM-022 | 11371 BFA : फाईन आर्ट्स पदवी प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-022-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-023 | 11375 थेट द्वितीय वर्ष फार्मसी पदवी प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-023-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-024 | 11377 हॉटेल मॅनेजमेंट अँण्ड केटरिंग टेक्नॉलॉजी प्रवेश | `CAT-EM-ADM-card.png` | `EM-ADM-024-poster.png` |  |
| EM-ADM-025 | 11379 कृषी पदवी प्रवेश 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-025-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-026 | 11381 M.HMCT ADMISSION 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-026-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-027 | 11385 डिझाईनिंग पदवी प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-027-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-028 | 11387 B.Planning Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-028-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-029 | 11388 B. ARCH. ADMISSION 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-029-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-030 | 11389 थेट द्वितीय वर्ष हॉटेल मॅनेजमेंट अँण्ड केटरिंग टेक्नॉलॉजी पदवी प्रवेश | `CAT-EM-ADM-card.png` | `EM-ADM-030-poster.png` |  |
| EM-ADM-031 | 11396 M. PHARMACY ADMISSION | `CAT-EM-ADM-card.png` | `EM-ADM-031-poster.png` |  |
| EM-ADM-032 | 11397 थेट द्वितीय वर्ष एमबीए प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-032-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-033 | 11399 थेट द्वितीय वर्ष एमसीए प्रवेश | `CAT-EM-ADM-card.png` | `EM-ADM-033-poster.png` |  |
| EM-ADM-034 | 11413 बी फार्मसी / फार्म डी प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-034-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-035 | 11425 MBBS / BDS ADMISSION 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-035-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-036 | 11435 B.F.Sc. Admission मत्स्यशास्त्र पदवी प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-036-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-037 | 11454 बीएससी नर्सिंग प्रवेश 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-037-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-038 | 11457 GNM Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-038-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-039 | 11458 DPN / PHN Admission 2026 | `CAT-EM-ADM-card.png` | `EM-ADM-039-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-040 | 11464 ऑल इंडिया कोटा आयुष प्रवेश | `CAT-EM-ADM-card.png` | `EM-ADM-040-poster.png` |  |
| EM-ADM-041 | 11466 नवोदय इयत्ता 9 वी प्रवेश 2027-28 | `CAT-EM-ADM-card.png` | `EM-ADM-041-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-042 | 11467 नवोदय विद्यालय 11वी प्रवेश 2027-28 | `CAT-EM-ADM-card.png` | `EM-ADM-042-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-043 | 11480 आयुष स्टेट कोटा | `CAT-EM-ADM-card.png` | `EM-ADM-043-poster.png` |  |
| EM-ADM-044 | 11487 ANM / GNM ADMISSION 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-044-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-045 | 11495 BVSc & AH Admission 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-045-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-ADM-046 | 11496 B. TECH. DAIRY TECHNOLOGY ADMISSION 2026-27 | `CAT-EM-ADM-card.png` | `EM-ADM-046-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |

### e-Mahiti — Scholarships

Basis: PRD category. Subcategory card: `CAT-EM-SHO-card.png`. Suggested art label: शिष्यवृत्ती.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| EM-SHO-001 | 10234 MAHADBT SCHOLARSHIP | `CAT-EM-SHO-card.png` | `EM-SHO-001-poster.png` |  |
| EM-SHO-002 | Scholarship Application | `CAT-EM-SHO-card.png` | `EM-SHO-002-poster.png` | Generic title. Confirm it does not repeat MAHADBT or another named scholarship. |

### e-Mahiti — Exams

Basis: PRD category. Subcategory card: `CAT-EM-EXM-card.png`. Suggested art label: परीक्षा.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| EM-EXM-001 | 11305 SET Exam 2026 | `EM-EXM-001-card.png` | `EM-EXM-001-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-EXM-002 | 11422 IIMs CAT 2026 | `EM-EXM-002-card.png` | `EM-EXM-002-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-EXM-003 | 11423 CLAT 2026 | `EM-EXM-003-card.png` | `EM-EXM-003-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-EXM-004 | 11456 GATE 2027 | `EM-EXM-004-card.png` | `EM-EXM-004-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |
| EM-EXM-005 | 11486 JAM 2027 | `EM-EXM-005-card.png` | `EM-EXM-005-poster.png` | The title carries a year or season. Use that cycle’s official start and end dates. The next cycle is an update of this record or a new record with a new title. |

### e-Mahiti — Government Jobs

Basis: PRD category. Subcategory card: `CAT-EM-JOB-card.png`. Suggested art label: भरती.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| EM-JOB-001 | 11398 इंडियन आर्मी NCC स्पेशल भरती | `CAT-EM-JOB-card.png` | `EM-JOB-001-poster.png` | The e-Mahiti description also names Recruitment Drives. That name is not in the category list. Use Government Jobs unless Admin adds that category. |

### e-Seva — Aadhaar

Basis: PRD category. Subcategory card: `CAT-ES-AAD-card.png`. Suggested art label: आधार.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-AAD-001 | 1912 आधार कार्ड पत्ता दुरूस्ती | `CAT-ES-AAD-card.png` | `ES-AAD-001-poster.png` | Related group: Aadhaar address. |
| ES-AAD-002 | 921 आधार PVC कार्ड | `CAT-ES-AAD-card.png` | `ES-AAD-002-poster.png` | Related group: Aadhaar PVC. |
| ES-AAD-003 | 922 आधार दुय्यम प्रत सेवा | `CAT-ES-AAD-card.png` | `ES-AAD-003-poster.png` | Related group: Aadhaar reprint. |
| ES-AAD-004 | Aadhaar Address / Mobile / Email Update | `CAT-ES-AAD-card.png` | `ES-AAD-004-poster.png` | Related group: Aadhaar address. |
| ES-AAD-005 | Aadhaar PVC Card Order | `CAT-ES-AAD-card.png` | `ES-AAD-005-poster.png` | Related group: Aadhaar PVC. |
| ES-AAD-006 | Aadhaar Reprint | `CAT-ES-AAD-card.png` | `ES-AAD-006-poster.png` | Related group: Aadhaar reprint. |
| ES-AAD-007 | Lost Aadhaar Recovery | `CAT-ES-AAD-card.png` | `ES-AAD-007-poster.png` |  |
| ES-AAD-008 | आधारकार्ड संबधित सेवा | `CAT-ES-AAD-card.png` | `ES-AAD-008-poster.png` | Umbrella title. Confirm whether address update, PVC, reprint, and linking stay inside this record. |

### e-Seva — PAN

Basis: PRD category. Subcategory card: `CAT-ES-PAN-card.png`. Suggested art label: पॅन.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-PAN-001 | Find PAN Number by Aadhaar | `CAT-ES-PAN-card.png` | `ES-PAN-001-poster.png` | The lookup uses Aadhaar. The service result is a PAN number. |
| ES-PAN-002 | PAN Card (Normal / Urgent) | `CAT-ES-PAN-card.png` | `ES-PAN-002-poster.png` | Describe normal and urgent in the same record, or ask Admin to split them. |
| ES-PAN-003 | PAN Reprint | `CAT-ES-PAN-card.png` | `ES-PAN-003-poster.png` |  |

### e-Seva — GST

Basis: PRD category. Subcategory card: `CAT-ES-GST-card.png`. Suggested art label: जीएसटी.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-GST-001 | GST Amendment | `CAT-ES-GST-card.png` | `ES-GST-001-poster.png` |  |
| ES-GST-002 | GST Filing up to 20 Bills – Monthly | `CAT-ES-GST-card.png` | `SHARED-GST-FILE-poster.png` | GST filing that differs only by bill count or monthly/quarterly period. |
| ES-GST-003 | GST Filing up to 20 Bills – Quarterly | `CAT-ES-GST-card.png` | `SHARED-GST-FILE-poster.png` | GST filing that differs only by bill count or monthly/quarterly period. |
| ES-GST-004 | GST Filing up to 50 Bills – Monthly | `CAT-ES-GST-card.png` | `SHARED-GST-FILE-poster.png` | GST filing that differs only by bill count or monthly/quarterly period. |
| ES-GST-005 | GST Filing up to 50 Bills – Quarterly | `CAT-ES-GST-card.png` | `SHARED-GST-FILE-poster.png` | GST filing that differs only by bill count or monthly/quarterly period. |
| ES-GST-006 | GST Refund | `CAT-ES-GST-card.png` | `ES-GST-006-poster.png` |  |
| ES-GST-007 | GST Registration | `CAT-ES-GST-card.png` | `ES-GST-007-poster.png` |  |
| ES-GST-008 | GST Revocation | `CAT-ES-GST-card.png` | `ES-GST-008-poster.png` |  |
| ES-GST-009 | GST Surrender / Cancellation | `CAT-ES-GST-card.png` | `ES-GST-009-poster.png` |  |
| ES-GST-010 | GST Zero Filing – Monthly | `CAT-ES-GST-card.png` | `SHARED-GST-FILE-poster.png` | GST filing that differs only by bill count or monthly/quarterly period. |
| ES-GST-011 | GST Zero Filing – Quarterly | `CAT-ES-GST-card.png` | `SHARED-GST-FILE-poster.png` | GST filing that differs only by bill count or monthly/quarterly period. |
| ES-GST-012 | GSTR-1 (Monthly / Quarterly) | `CAT-ES-GST-card.png` | `ES-GST-012-poster.png` |  |
| ES-GST-013 | GSTR-3B (Monthly) | `CAT-ES-GST-card.png` | `ES-GST-013-poster.png` |  |
| ES-GST-014 | GSTR-9 (Annual Return) | `CAT-ES-GST-card.png` | `ES-GST-014-poster.png` |  |
| ES-GST-015 | LUT Filing | `CAT-ES-GST-card.png` | `ES-GST-015-poster.png` |  |

### e-Seva — Shop Act

Basis: PRD category. Subcategory card: `CAT-ES-SHP-card.png`. Suggested art label: शॉप अ‍ॅक्ट.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-SHP-001 | 924 शॉपअ‍ॅक्ट लायसन्स | `CAT-ES-SHP-card.png` | `ES-SHP-001-poster.png` | Related group: Shop Act. |
| ES-SHP-002 | Gumasta License (New / Renewal) | `CAT-ES-SHP-card.png` | `ES-SHP-002-poster.png` | Gumasta is the Maharashtra shop-establishment licence. Confirm it does not repeat the Shop Act rows. Related group: Shop Act. |
| ES-SHP-003 | Shop Act Intimation (10 & Above Employees) | `CAT-ES-SHP-card.png` | `SHARED-SHOP-BAND-poster.png` | Shop Act intimation that differs only by employee band. Related group: Shop Act. |
| ES-SHP-004 | Shop Act Intimation (Up to 9 Employees) | `CAT-ES-SHP-card.png` | `SHARED-SHOP-BAND-poster.png` | Shop Act intimation that differs only by employee band. Related group: Shop Act. |
| ES-SHP-005 | Shop Act Renewal (Maharashtra) | `CAT-ES-SHP-card.png` | `ES-SHP-005-poster.png` | Related group: Shop Act. |

### e-Seva — Driving License

Basis: PRD category. Subcategory card: `CAT-ES-DL-card.png`. Suggested art label: ड्रायव्हिंग लायसन्स.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-DL-001 | 930 ड्रायव्हिंग लायसन्स | `CAT-ES-DL-card.png` | `ES-DL-001-poster.png` | Umbrella title. Confirm whether learner, permanent, renewal, and international permit stay inside this record. Related group: Driving licence. |
| ES-DL-002 | DL Renewal / Duplicate | `CAT-ES-DL-card.png` | `ES-DL-002-poster.png` | Related group: Driving licence. |
| ES-DL-003 | International Driving Permit | `CAT-ES-DL-card.png` | `ES-DL-003-poster.png` | Related group: Driving licence. |
| ES-DL-004 | Learner Driving License (2W / 4W) | `CAT-ES-DL-card.png` | `ES-DL-004-poster.png` | Related group: Driving licence. |
| ES-DL-005 | Permanent Driving License (2W / 4W) | `CAT-ES-DL-card.png` | `ES-DL-005-poster.png` | Related group: Driving licence. |

### e-Seva — Voter ID

Basis: PRD category. Subcategory card: `CAT-ES-VOT-card.png`. Suggested art label: मतदान कार्ड.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-VOT-001 | 1907 मतदान कार्ड संबधित सुविधा | `CAT-ES-VOT-card.png` | `ES-VOT-001-poster.png` |  |
| ES-VOT-002 | Voter ID Correction | `CAT-ES-VOT-card.png` | `ES-VOT-002-poster.png` |  |
| ES-VOT-003 | Voter ID Download | `CAT-ES-VOT-card.png` | `ES-VOT-003-poster.png` |  |
| ES-VOT-004 | Voter ID New Registration | `CAT-ES-VOT-card.png` | `ES-VOT-004-poster.png` |  |

### e-Seva — Income Tax

Basis: PRD example. Subcategory card: `CAT-ES-TAX-card.png`. Suggested art label: आयकर.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-TAX-001 | Capital Gain ITR | `CAT-ES-TAX-card.png` | `ES-TAX-001-poster.png` |  |
| ES-TAX-002 | Form-16 / 26AS Download | `CAT-ES-TAX-card.png` | `ES-TAX-002-poster.png` |  |
| ES-TAX-003 | ITR Filing – Business | `CAT-ES-TAX-card.png` | `ES-TAX-003-poster.png` |  |
| ES-TAX-004 | ITR Filing – Business with CA Certificate | `CAT-ES-TAX-card.png` | `ES-TAX-004-poster.png` |  |
| ES-TAX-005 | ITR Filing – Salaried | `CAT-ES-TAX-card.png` | `ES-TAX-005-poster.png` |  |
| ES-TAX-006 | Income Tax Refund Tracking | `CAT-ES-TAX-card.png` | `ES-TAX-006-poster.png` |  |
| ES-TAX-007 | PTEC (Professional Tax Enrolment Certificate) | `CAT-ES-TAX-card.png` | `ES-TAX-007-poster.png` | Professional tax is a state tax. Income Tax is the PRD example for tax services. Confirm the category name. |
| ES-TAX-008 | PTRC (Professional Tax Registration Certificate) | `CAT-ES-TAX-card.png` | `ES-TAX-008-poster.png` | Professional tax is a state tax. Income Tax is the PRD example for tax services. Confirm the category name. |
| ES-TAX-009 | Presumptive Tax (44AD / 44ADA) | `CAT-ES-TAX-card.png` | `ES-TAX-009-poster.png` |  |
| ES-TAX-010 | TAN Registration | `CAT-ES-TAX-card.png` | `ES-TAX-010-poster.png` |  |
| ES-TAX-011 | TDS Return Filing | `CAT-ES-TAX-card.png` | `ES-TAX-011-poster.png` |  |

### e-Seva — MSME

Basis: PRD example. Subcategory card: `CAT-ES-MSM-card.png`. Suggested art label: उद्योग आधार.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-MSM-001 | 923 उद्योग आधार | `CAT-ES-MSM-card.png` | `ES-MSM-001-poster.png` | Related group: Udyam. |
| ES-MSM-002 | Udyog Aadhaar (MSME) Registration | `CAT-ES-MSM-card.png` | `ES-MSM-002-poster.png` | Related group: Udyam. |
| ES-MSM-003 | Udyog Aadhaar (MSME) Update | `CAT-ES-MSM-card.png` | `ES-MSM-003-poster.png` | Related group: Udyam. |

### e-Seva — Certificates

Basis: Proposed. Subcategory card: `CAT-ES-CER-card.png`. Suggested art label: प्रमाणपत्रे.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-CER-001 | 10000 जीवन प्रमाण | `CAT-ES-CER-card.png` | `ES-CER-001-poster.png` |  |
| ES-CER-002 | 11509 विवाह नोंदणी प्रमाणपत्र (Marriage Certi) | `CAT-ES-CER-card.png` | `ES-CER-002-poster.png` |  |
| ES-CER-003 | 1911 राजपत्र (Gazette) फेरबदल | `CAT-ES-CER-card.png` | `ES-CER-003-poster.png` | Related group: Gazette. |
| ES-CER-004 | 1928 जात पडताळणी | `CAT-ES-CER-card.png` | `ES-CER-004-poster.png` |  |
| ES-CER-005 | 1932 UDID Card दिव्यांग (अपंगत्वाचे) यूडीआयडी कार्ड व प्रमाणपत्र | `CAT-ES-CER-card.png` | `ES-CER-005-poster.png` | Related group: UDID. |
| ES-CER-006 | 905 Sparsh PCDA Allahabad जीवन प्रमाण | `CAT-ES-CER-card.png` | `ES-CER-006-poster.png` |  |
| ES-CER-007 | 925 पोलिस क्लिअरन्स सर्टिफिकेट | `CAT-ES-CER-card.png` | `ES-CER-007-poster.png` | Related group: Police clearance. |
| ES-CER-008 | Caste Certificate (New) | `CAT-ES-CER-card.png` | `ES-CER-008-poster.png` |  |
| ES-CER-009 | Divyang Card | `CAT-ES-CER-card.png` | `ES-CER-009-poster.png` | Related group: UDID. |
| ES-CER-010 | Domicile Certificate | `CAT-ES-CER-card.png` | `ES-CER-010-poster.png` |  |
| ES-CER-011 | EWS Certificate | `CAT-ES-CER-card.png` | `ES-CER-011-poster.png` |  |
| ES-CER-012 | Gazette Notification – Open Category | `CAT-ES-CER-card.png` | `SHARED-GAZETTE-poster.png` | Gazette notification. Open or reserved stays in the title. Related group: Gazette. |
| ES-CER-013 | Gazette Notification – Reserved Category | `CAT-ES-CER-card.png` | `SHARED-GAZETTE-poster.png` | Gazette notification. Open or reserved stays in the title. Related group: Gazette. |
| ES-CER-014 | Income Certificate | `CAT-ES-CER-card.png` | `ES-CER-014-poster.png` |  |
| ES-CER-015 | Maratha Caste Certificate | `CAT-ES-CER-card.png` | `ES-CER-015-poster.png` |  |
| ES-CER-016 | Minority Certificate | `CAT-ES-CER-card.png` | `ES-CER-016-poster.png` |  |
| ES-CER-017 | Non-Creamy Layer Certificate | `CAT-ES-CER-card.png` | `ES-CER-017-poster.png` |  |
| ES-CER-018 | Police Clearance Certificate – Normal | `CAT-ES-CER-card.png` | `ES-CER-018-poster.png` | Related group: Police clearance. |
| ES-CER-019 | Police Clearance Certificate – Security | `CAT-ES-CER-card.png` | `ES-CER-019-poster.png` | Related group: Police clearance. |
| ES-CER-020 | SC / OBC Caste Validity | `CAT-ES-CER-card.png` | `ES-CER-020-poster.png` |  |
| ES-CER-021 | ST Caste Validity | `CAT-ES-CER-card.png` | `ES-CER-021-poster.png` |  |
| ES-CER-022 | Senior Citizen Certificate | `CAT-ES-CER-card.png` | `ES-CER-022-poster.png` |  |

### e-Seva — Vehicle and RTO

Basis: Proposed. Subcategory card: `CAT-ES-RTO-card.png`. Suggested art label: आरटीओ.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-RTO-001 | 10582 HSRP हाय सेक्युरिटी नंबर प्लेट | `CAT-ES-RTO-card.png` | `ES-RTO-001-poster.png` | Related group: HSRP. |
| ES-RTO-002 | 11338 ट्राफिक चलान व मोबाईल लिंक | `CAT-ES-RTO-card.png` | `ES-RTO-002-poster.png` |  |
| ES-RTO-003 | Address Change in RC | `CAT-ES-RTO-card.png` | `ES-RTO-003-poster.png` |  |
| ES-RTO-004 | FASTag New / Replacement | `CAT-ES-RTO-card.png` | `ES-RTO-004-poster.png` |  |
| ES-RTO-005 | HSRP Number Plate | `CAT-ES-RTO-card.png` | `ES-RTO-005-poster.png` | Related group: HSRP. |
| ES-RTO-006 | RC Duplicate | `CAT-ES-RTO-card.png` | `ES-RTO-006-poster.png` |  |
| ES-RTO-007 | RC Transfer | `CAT-ES-RTO-card.png` | `ES-RTO-007-poster.png` |  |

### e-Seva — Passport and travel

Basis: Proposed. Subcategory card: `CAT-ES-TRV-card.png`. Suggested art label: पासपोर्ट.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-TRV-001 | 1931 पासपोर्ट सेवा | `CAT-ES-TRV-card.png` | `ES-TRV-001-poster.png` | Umbrella title. Confirm whether new passport and renewal stay inside this record. Related group: Passport. |
| ES-TRV-002 | Bus Pass (Student / Senior Citizen) | `CAT-ES-TRV-card.png` | `ES-TRV-002-poster.png` | The title covers student and senior-citizen passes. Describe both, or ask Admin to split the record. |
| ES-TRV-003 | Passport New | `CAT-ES-TRV-card.png` | `ES-TRV-003-poster.png` | Related group: Passport. |
| ES-TRV-004 | Passport Renewal | `CAT-ES-TRV-card.png` | `ES-TRV-004-poster.png` | Related group: Passport. |
| ES-TRV-005 | Visa Assistance | `CAT-ES-TRV-card.png` | `ES-TRV-005-poster.png` |  |

### e-Seva — Labour and social security

Basis: Proposed. Subcategory card: `CAT-ES-LAB-card.png`. Suggested art label: श्रम.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-LAB-001 | 7391 बांधकाम कामगार नोंदणी | `CAT-ES-LAB-card.png` | `ES-LAB-001-poster.png` | Related group: Construction-worker registration. |
| ES-LAB-002 | 906 ई श्रम कार्ड | `CAT-ES-LAB-card.png` | `ES-LAB-002-poster.png` | Possible same service, different title: 9665 ई श्रम कार्ड. Create one catalog record after Admin picks the title to keep. Related group: e-SHRAM. |
| ES-LAB-003 | 926 EPF Services (कर्मचारी भविष्यनिर्वाह निधी सुविधा) | `CAT-ES-LAB-card.png` | `ES-LAB-003-poster.png` | Umbrella title for EPF. Confirm whether the separate EPF actions stay inside this record. Related group: EPF. |
| ES-LAB-004 | 9665 ई श्रम कार्ड | `CAT-ES-LAB-card.png` | `ES-LAB-004-poster.png` | Possible same service, different title: 906 ई श्रम कार्ड. Create one catalog record after Admin picks the title to keep. Related group: e-SHRAM. |
| ES-LAB-005 | Construction Worker Registration | `CAT-ES-LAB-card.png` | `ES-LAB-005-poster.png` | Related group: Construction-worker registration. |
| ES-LAB-006 | EPF Claim (e-KYC + Nominee + Claim) | `CAT-ES-LAB-card.png` | `ES-LAB-006-poster.png` | Related group: EPF. |
| ES-LAB-007 | ESI Registration | `CAT-ES-LAB-card.png` | `ES-LAB-007-poster.png` |  |
| ES-LAB-008 | ESI Return Filing | `CAT-ES-LAB-card.png` | `ES-LAB-008-poster.png` |  |
| ES-LAB-009 | Labour Card Registration | `CAT-ES-LAB-card.png` | `ES-LAB-009-poster.png` |  |
| ES-LAB-010 | PF Balance Check | `CAT-ES-LAB-card.png` | `ES-LAB-010-poster.png` | Related group: EPF. |
| ES-LAB-011 | PF Transfer | `CAT-ES-LAB-card.png` | `ES-LAB-011-poster.png` | Related group: EPF. |
| ES-LAB-012 | Pension Claim (Form-10D) | `CAT-ES-LAB-card.png` | `ES-LAB-012-poster.png` | Related group: EPF. |
| ES-LAB-013 | UAN Activation | `CAT-ES-LAB-card.png` | `ES-LAB-013-poster.png` | Related group: EPF. |
| ES-LAB-014 | UAN Generation | `CAT-ES-LAB-card.png` | `ES-LAB-014-poster.png` | Related group: EPF. |
| ES-LAB-015 | e-SHRAM Card | `CAT-ES-LAB-card.png` | `ES-LAB-015-poster.png` | Related group: e-SHRAM. |

### e-Seva — Land and property

Basis: Proposed. Subcategory card: `CAT-ES-LND-card.png`. Suggested art label: जमीन.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-LND-001 | 10671 सातबारा (7/12) म्युटेशन / वारसनोंदणी | `CAT-ES-LND-card.png` | `ES-LND-001-poster.png` | Related group: 7/12 extract. Related group: Land mutation. |
| ES-LND-002 | 1913 7/12 (सात बारा) डिजिटल स्वाक्षरीत व प्रॉपर्टी कार्ड | `CAT-ES-LND-card.png` | `ES-LND-002-poster.png` | Related group: 7/12 extract. |
| ES-LND-003 | 1929 भाडेकरार नोंंदणी (LEAVE AND LICENSE AGREEMENT) | `CAT-ES-LND-card.png` | `ES-LND-003-poster.png` | Related group: Rent agreement. |
| ES-LND-004 | 7/12 Extract / Property Card | `CAT-ES-LND-card.png` | `ES-LND-004-poster.png` | Related group: 7/12 extract. |
| ES-LND-005 | Encumbrance Certificate | `CAT-ES-LND-card.png` | `ES-LND-005-poster.png` |  |
| ES-LND-006 | Land Mutation | `CAT-ES-LND-card.png` | `ES-LND-006-poster.png` | Related group: Land mutation. |
| ES-LND-007 | Property Tax Payment | `CAT-ES-LND-card.png` | `ES-LND-007-poster.png` |  |
| ES-LND-008 | Rent / Lease Agreement Online | `CAT-ES-LND-card.png` | `ES-LND-008-poster.png` | Related group: Rent agreement. |

### e-Seva — Licences and permissions

Basis: Proposed. Subcategory card: `CAT-ES-LIC-card.png`. Suggested art label: परवाना.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-LIC-001 | 1902 उत्सव मंडळासाठी परवानगी अर्ज | `CAT-ES-LIC-card.png` | `ES-LIC-001-poster.png` |  |
| ES-LIC-002 | 9113 PCMC पाळीव प्राणी परवाना | `CAT-ES-LIC-card.png` | `ES-LIC-002-poster.png` |  |
| ES-LIC-003 | 927 फूड लायसन्स / अन्न परवाना | `CAT-ES-LIC-card.png` | `ES-LIC-003-poster.png` | Umbrella title for food licence. Confirm whether the separate FSSAI actions stay inside this record. Related group: FSSAI. |
| ES-LIC-004 | 937 मद्यपान / दारू खरेदी / बाळगण्याचा परवाना व खरेदी इ टोकन | `CAT-ES-LIC-card.png` | `ES-LIC-004-poster.png` |  |
| ES-LIC-005 | FSSAI Annual Return | `CAT-ES-LIC-card.png` | `ES-LIC-005-poster.png` | Related group: FSSAI. |
| ES-LIC-006 | FSSAI Modification | `CAT-ES-LIC-card.png` | `ES-LIC-006-poster.png` | Related group: FSSAI. |
| ES-LIC-007 | FSSAI Registration – 1 Year | `CAT-ES-LIC-card.png` | `SHARED-FSSAI-REG-poster.png` | FSSAI registration durations. The year count stays in the title. Related group: FSSAI. |
| ES-LIC-008 | FSSAI Registration – 3 Years | `CAT-ES-LIC-card.png` | `SHARED-FSSAI-REG-poster.png` | FSSAI registration durations. The year count stays in the title. Related group: FSSAI. |
| ES-LIC-009 | FSSAI Registration – 5 Years | `CAT-ES-LIC-card.png` | `SHARED-FSSAI-REG-poster.png` | FSSAI registration durations. The year count stays in the title. Related group: FSSAI. |
| ES-LIC-010 | FSSAI Renewal | `CAT-ES-LIC-card.png` | `ES-LIC-010-poster.png` | Related group: FSSAI. |
| ES-LIC-011 | Factory License | `CAT-ES-LIC-card.png` | `ES-LIC-011-poster.png` |  |
| ES-LIC-012 | Fire NOC | `CAT-ES-LIC-card.png` | `ES-LIC-012-poster.png` |  |
| ES-LIC-013 | Pollution Control Consent (MPCB) | `CAT-ES-LIC-card.png` | `ES-LIC-013-poster.png` |  |
| ES-LIC-014 | Trade License | `CAT-ES-LIC-card.png` | `ES-LIC-014-poster.png` |  |

### e-Seva — Business compliance

Basis: Proposed. Subcategory card: `CAT-ES-BIZ-card.png`. Suggested art label: व्यवसाय नोंदणी.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-BIZ-001 | Company Name Change | `CAT-ES-BIZ-card.png` | `ES-BIZ-001-poster.png` |  |
| ES-BIZ-002 | Copyright Registration | `CAT-ES-BIZ-card.png` | `ES-BIZ-002-poster.png` |  |
| ES-BIZ-003 | DIN Activation | `CAT-ES-BIZ-card.png` | `ES-BIZ-003-poster.png` |  |
| ES-BIZ-004 | DSC Application / Renewal | `CAT-ES-BIZ-card.png` | `ES-BIZ-004-poster.png` |  |
| ES-BIZ-005 | Design Registration | `CAT-ES-BIZ-card.png` | `ES-BIZ-005-poster.png` | This is an intellectual-property design registration, separate from logo and website design. |
| ES-BIZ-006 | Director KYC (DIR-3) | `CAT-ES-BIZ-card.png` | `ES-BIZ-006-poster.png` |  |
| ES-BIZ-007 | Disqualification of Director | `CAT-ES-BIZ-card.png` | `ES-BIZ-007-poster.png` |  |
| ES-BIZ-008 | ISO Certification | `CAT-ES-BIZ-card.png` | `ES-BIZ-008-poster.png` |  |
| ES-BIZ-009 | Import Export Code (IEC) | `CAT-ES-BIZ-card.png` | `ES-BIZ-009-poster.png` |  |
| ES-BIZ-010 | Increase Authorised Capital | `CAT-ES-BIZ-card.png` | `ES-BIZ-010-poster.png` |  |
| ES-BIZ-011 | LLP Annual Filing | `CAT-ES-BIZ-card.png` | `ES-BIZ-011-poster.png` |  |
| ES-BIZ-012 | LLP Registration | `CAT-ES-BIZ-card.png` | `ES-BIZ-012-poster.png` |  |
| ES-BIZ-013 | Multinational Company Registration | `CAT-ES-BIZ-card.png` | `ES-BIZ-013-poster.png` |  |
| ES-BIZ-014 | Nidhi Company Registration | `CAT-ES-BIZ-card.png` | `ES-BIZ-014-poster.png` |  |
| ES-BIZ-015 | One Person Company (OPC) | `CAT-ES-BIZ-card.png` | `ES-BIZ-015-poster.png` |  |
| ES-BIZ-016 | Private Limited Company | `CAT-ES-BIZ-card.png` | `ES-BIZ-016-poster.png` |  |
| ES-BIZ-017 | Producer Company (FPO) | `CAT-ES-BIZ-card.png` | `ES-BIZ-017-poster.png` |  |
| ES-BIZ-018 | ROC Annual Filing | `CAT-ES-BIZ-card.png` | `ES-BIZ-018-poster.png` |  |
| ES-BIZ-019 | Removal of Director | `CAT-ES-BIZ-card.png` | `ES-BIZ-019-poster.png` |  |
| ES-BIZ-020 | Section-8 NGO Registration | `CAT-ES-BIZ-card.png` | `ES-BIZ-020-poster.png` |  |
| ES-BIZ-021 | Strike Off Company | `CAT-ES-BIZ-card.png` | `ES-BIZ-021-poster.png` |  |
| ES-BIZ-022 | Trademark Classes | `CAT-ES-BIZ-card.png` | `ES-BIZ-022-poster.png` |  |
| ES-BIZ-023 | Trademark Hearing | `CAT-ES-BIZ-card.png` | `ES-BIZ-023-poster.png` |  |
| ES-BIZ-024 | Trademark Objection | `CAT-ES-BIZ-card.png` | `ES-BIZ-024-poster.png` |  |
| ES-BIZ-025 | Trademark Registration | `CAT-ES-BIZ-card.png` | `ES-BIZ-025-poster.png` |  |
| ES-BIZ-026 | Trademark Renewal | `CAT-ES-BIZ-card.png` | `ES-BIZ-026-poster.png` |  |

### e-Seva — Banking

Basis: Proposed. Subcategory card: `CAT-ES-BNK-card.png`. Suggested art label: बँक.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-BNK-001 | 938 बॅंक अकाऊंट ओपनिंंग | `CAT-ES-BNK-card.png` | `ES-BNK-001-poster.png` |  |

### e-Seva — Utilities

Basis: Proposed. Subcategory card: `CAT-ES-UTL-card.png`. Suggested art label: जोडणी.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-UTL-001 | 9975 घरगुती गॅस सेवा | `CAT-ES-UTL-card.png` | `ES-UTL-001-poster.png` |  |
| ES-UTL-002 | Electricity New Connection / Name Change | `CAT-ES-UTL-card.png` | `ES-UTL-002-poster.png` |  |
| ES-UTL-003 | Water Connection Application | `CAT-ES-UTL-card.png` | `ES-UTL-003-poster.png` |  |

### e-Seva — Education documents

Basis: Proposed. Subcategory card: `CAT-ES-EDU-card.png`. Suggested art label: शैक्षणिक कागदपत्रे.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-EDU-001 | 1001 १०वी / १२ वी इ मार्कशीट | `CAT-ES-EDU-card.png` | `ES-EDU-001-poster.png` | Related group: 10th and 12th marksheet. |
| ES-EDU-002 | 11017 10वी 12वी दुय्यम गुणपत्रे व प्रमाणपत्रे | `CAT-ES-EDU-card.png` | `ES-EDU-002-poster.png` | Related group: 10th and 12th marksheet. |
| ES-EDU-003 | 1910 10वी / 12वी मायग्रेशन सर्टिफिकेट | `CAT-ES-EDU-card.png` | `ES-EDU-003-poster.png` |  |
| ES-EDU-004 | 1920 आयटीआय प्रमाणपत्र डाऊनलोड | `CAT-ES-EDU-card.png` | `ES-EDU-004-poster.png` |  |
| ES-EDU-005 | 9579 ABC iD ( Academic Bank of Credits) | `CAT-ES-EDU-card.png` | `ES-EDU-005-poster.png` |  |
| ES-EDU-006 | DigiLocker Setup | `CAT-ES-EDU-card.png` | `ES-EDU-006-poster.png` |  |

### e-Seva — Grievance and public information

Basis: Proposed. Subcategory card: `CAT-ES-GRV-card.png`. Suggested art label: तक्रार.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-GRV-001 | 11054 आर्थिक फसवणूक तक्रार | `CAT-ES-GRV-card.png` | `ES-GRV-001-poster.png` |  |
| ES-GRV-002 | 9122 सायबर क्राईम कंप्लेंट | `CAT-ES-GRV-card.png` | `ES-GRV-002-poster.png` |  |
| ES-GRV-003 | 934 ऑनलाईन शासकीय तक्रार | `CAT-ES-GRV-card.png` | `ES-GRV-003-poster.png` |  |
| ES-GRV-004 | 935 पुणे शहर पोलीस लॉस्ट अ‍ॅड फॉऊड तक्रार नोंदणी | `CAT-ES-GRV-card.png` | `ES-GRV-004-poster.png` |  |
| ES-GRV-005 | 940 ऑनलाईन माहिती अधिकार | `CAT-ES-GRV-card.png` | `ES-GRV-005-poster.png` |  |

### e-Seva — Bookings

Basis: Proposed. Subcategory card: `CAT-ES-BOK-card.png`. Suggested art label: बुकिंग.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-BOK-001 | 11514 एसटी आवडेल तिथे कोठेही प्रवास | `CAT-ES-BOK-card.png` | `ES-BOK-001-poster.png` | State-transport travel. The poster should read as bus travel. Confirm if Admin would rather group it with passport and bus pass. |
| ES-BOK-002 | 1914 श्री तुळजाभवानी (तुळजापूर) ई दर्शन पास | `ES-BOK-002-card.png` | `ES-BOK-002-poster.png` |  |
| ES-BOK-003 | 1915 तिरूपती बालाजी दर्शन ऑनलाईन बुकिंग | `ES-BOK-003-card.png` | `ES-BOK-003-poster.png` |  |
| ES-BOK-004 | 1916 विठ्ठल दर्शन ऑनलाईन बुकिंग | `ES-BOK-004-card.png` | `ES-BOK-004-poster.png` |  |
| ES-BOK-005 | 1917 शिर्डी साईबाबा ऑनलाईन दर्शन ई बुकिंग | `ES-BOK-005-card.png` | `ES-BOK-005-poster.png` |  |
| ES-BOK-006 | 9124 ताडोबा नॅशनल पार्क बुकिंग | `ES-BOK-006-card.png` | `ES-BOK-006-poster.png` |  |
| ES-BOK-007 | 9666 वाळू बुकिंग | `ES-BOK-007-card.png` | `ES-BOK-007-poster.png` |  |

### e-Seva — Professional registration

Basis: Proposed. Subcategory card: `CAT-ES-PRF-card.png`. Suggested art label: व्यावसायिक नोंदणी.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-PRF-001 | 1933 नर्सिंग रजिस्ट्रेशन व रिन्युअल | `CAT-ES-PRF-card.png` | `ES-PRF-001-poster.png` | Related group: Nursing. |
| ES-PRF-002 | 9123 फार्मासिस्ट रजिस्ट्रेशन फार्मासिस्ट कौंन्सिल नावनोंदणी | `CAT-ES-PRF-card.png` | `ES-PRF-002-poster.png` |  |
| ES-PRF-003 | Ayush Registration | `CAT-ES-PRF-card.png` | `ES-PRF-003-poster.png` |  |
| ES-PRF-004 | Nursing Certificate Apply | `CAT-ES-PRF-card.png` | `ES-PRF-004-poster.png` | Related group: Nursing. |
| ES-PRF-005 | Nursing Registration | `CAT-ES-PRF-card.png` | `ES-PRF-005-poster.png` | Related group: Nursing. |

### e-Seva — Employment services

Basis: Proposed. Subcategory card: `CAT-ES-EMP-card.png`. Suggested art label: रोजगार.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-EMP-001 | 1909 एम्प्लॉयमेंट एक्सचेंज सेवा | `CAT-ES-EMP-card.png` | `ES-EMP-001-poster.png` |  |

### e-Seva — Design and digital services

Basis: Proposed. Subcategory card: `CAT-ES-DSN-card.png`. Suggested art label: डिझाइन.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-DSN-001 | Basic Website Setup | `ES-DSN-001-card.png` | `ES-DSN-001-poster.png` |  |
| ES-DSN-002 | Business Email ID Creation | `ES-DSN-002-card.png` | `ES-DSN-002-poster.png` |  |
| ES-DSN-003 | Google Business Profile Setup | `ES-DSN-003-card.png` | `ES-DSN-003-poster.png` |  |
| ES-DSN-004 | Logo + Letterhead + Visiting Card | `ES-DSN-004-card.png` | `ES-DSN-004-poster.png` |  |
| ES-DSN-005 | Logo Designing | `ES-DSN-005-card.png` | `ES-DSN-005-poster.png` |  |
| ES-DSN-006 | Website Domain Registration | `ES-DSN-006-card.png` | `ES-DSN-006-poster.png` |  |

### e-Seva — Astrology

Basis: Proposed. Subcategory card: `CAT-ES-AST-card.png`. Suggested art label: ज्योतिष.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-AST-001 | 40+ Muhurt Finding (Panchang) | `ES-AST-001-card.png` | `ES-AST-001-poster.png` |  |
| ES-AST-002 | Janam Kundli | `ES-AST-002-card.png` | `ES-AST-002-poster.png` |  |
| ES-AST-003 | Match Making | `ES-AST-003-card.png` | `ES-AST-003-poster.png` |  |

### e-Seva — Ration card

Basis: Proposed. Subcategory card: `CAT-ES-RAT-card.png`. Suggested art label: रेशन.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-RAT-001 | 10596 रेशनकार्ड केवायसी | `CAT-ES-RAT-card.png` | `ES-RAT-001-poster.png` | One service uses this proposed category. Admin may keep Ration card or place the service under Certificates. |

### e-Seva — Health cards

Basis: Proposed. Subcategory card: `CAT-ES-HLT-card.png`. Suggested art label: आरोग्य कार्ड.

| Asset ID | Service name | Card file | Poster file | Design note |
| --- | --- | --- | --- | --- |
| ES-HLT-001 | डिजिटल आरोग्य कार्ड | `CAT-ES-HLT-card.png` | `ES-HLT-001-poster.png` | One service uses this proposed category. Admin may keep Health cards or place the service under Certificates. |

## Uncertain services — hold the service artwork

Produce no service card and no poster for these names until Admin confirms the module. If the confirmed module is e-Link, the PRD requires no poster.

| Asset ID | Service name | Suggested placement | Why it is open |
| --- | --- | --- | --- |
| UN-001 | 10130 ESM CEA माजी सैनिक पाल्य शैक्षणिक भत्ता | e-Mahiti / Scholarships, or e-Mahiti / Government Schemes | ESM children-education allowance is an education benefit and a defence welfare scheme. |
| UN-002 | 10156 आदिवासी विभाग शासकीय वस्तीगृह प्रवेश | e-Mahiti / Admissions, or e-Mahiti / Government Schemes | Tribal-department hostel admission fits both Admissions and Government Schemes. |
| UN-003 | 10354 कापूस व सोयाबीन e-kyc | e-Mahiti / Government Schemes, or e-Seva | Cotton and soybean e-KYC is a scheme task and may also be a standing KYC service. |
| UN-004 | 10433 ई मोजणी नोंदणी | e-Seva / Land and property, or e-Mahiti / Government Schemes | E-measurement registration is not clearly a scheme or a land-record service. |
| UN-005 | 10598 आधारकार्ड बॅंक लिंकिंग | e-Seva / Aadhaar, or e-Seva / Banking | The work links an Aadhaar card to a bank account. Both PRD-adjacent categories fit. |
| UN-006 | 10884 दिव्यांग E - KYC | e-Mahiti / Government Schemes, or e-Seva | Divyang e-KYC is a scheme task and may also be a standing KYC service. |
| UN-007 | 10915 लाडकी बहीण योजना ई केवायसी | e-Mahiti / Government Schemes, or e-Seva | Ladki Bahin e-KYC is a scheme task and may also be a standing KYC service. |
| UN-008 | 10952 पदवीधर मतदारसंघ निवडणूक मतदारनोंदणी | e-Seva / Voter ID, or a time-bound election record | Graduate-constituency voter registration is tied to an election. Voter ID is the closest PRD category, and it does not cover an election roll. |
| UN-009 | 10986 निवडणूक उमेदवारी अर्ज | A time-bound election record. Voter ID is the closest PRD category and does not cover candidature. | Candidate nomination is an election process. The PRD categories do not include elections. |
| UN-010 | 11009 सार्वत्रिक निवडणुका 2025 मतदार यादी | e-Seva / Voter ID, or a time-bound election record | The title names the 2025 general-election voter list. That is a dated roll, not a standing voter-card service. |
| UN-011 | 11217 पुणे विद्यापीठ परीक्षा अर्ज | e-Mahiti / Exams, or e-Link / Exam Forms | A university exam application matches e-Mahiti Exams and e-Link Exam Forms. |
| UN-012 | 11228 अमरनाथ यात्रा बुकिंग | e-Seva / Bookings, or a seasonal e-Mahiti item | Amarnath yatra booking is a booking. The yatra is seasonal, and the PRD has no pilgrimage category. |
| UN-013 | 11307 पी एम किसान e-KYC | e-Mahiti / Government Schemes, or e-Seva | PM-Kisan e-KYC is a scheme task and may also be a standing KYC service with no end date. |
| UN-014 | 11341 महाराष्ट्र अग्निशमन सेवा प्रवेश मुंबई | e-Mahiti / Government Jobs, or e-Mahiti / Admissions | Fire-service entry is titled as an admission and functions as recruitment. |
| UN-015 | 11354 महा आयडी / सारथी कार्ड | e-Seva / Certificates, or e-Mahiti / Government Schemes | MahaID / Sarathi is a standing identity card and is also listed among schemes. The PRD does not name this card. |
| UN-016 | 11355 शिवाजी विद्यापीठ कोल्हापूर दिक्षांत अर्ज | No PRD category is a clear fit. Closest: e-Link / Notifications, or e-Mahiti / Admissions. | A convocation application has the same open question as the Pune University convocation. |
| UN-017 | 11361 YCMOU: | Title is incomplete. | The source title is “YCMOU:” with nothing after the colon. Confirm the service before classifying it. |
| UN-018 | 11382 10वी / 12वी पुरवणी परीक्षा निकाल | e-Link / Results | A supplementary-exam result matches the e-Link Results category. e-Link has no poster. |
| UN-019 | 11415 फॉर्म 17 (Form 17) फेब्रुवारी / मार्च 2027 अर्ज सुरू | e-Mahiti / Exams, or e-Link / Exam Forms | Form 17 is a board-exam form. e-Mahiti Exams and e-Link Exam Forms both match the PRD. |
| UN-020 | 11518 SBI बॅंक पिक कर्ज | e-Seva / Banking, or e-Mahiti / Government Schemes | SBI crop loan can be read as a bank product or as an agriculture scheme. The PRD has no loan category. |
| UN-021 | 11524 दीक्षांत समारंभ पुणे विद्यापीठ | No PRD category is a clear fit. Closest: e-Link / Notifications, or e-Mahiti / Admissions. | A convocation is a dated university event. It is not an admission, an exam, or a scheme. |
| UN-022 | 1918 अप्रेटिसशिप ट्रेनिंंग | e-Seva / Employment services, or e-Mahiti / Government Jobs | Apprenticeship training can be a standing placement service or a recruitment drive. The PRD names Recruitment Drives in the e-Mahiti description and Government Jobs in the category list. |
| UN-023 | 7509 किसान क्रेडिट कार्ड : सीएससी केंद्रचालकांसाठी | e-Mahiti / Government Schemes, or e-Seva / Banking | Kisan Credit Card for CSC operators can be read as a scheme or as a banking product. |
| UN-024 | 8747 पढो परदेश योजना | e-Mahiti / Scholarships, or e-Mahiti / Government Schemes | Study-abroad support fits Scholarships and Government Schemes. The title says योजना. |
| UN-025 | 8876 आधार मतदानकार्ड लिंक | e-Seva / Aadhaar, or e-Seva / Voter ID | Same open question as the other Aadhaar–voter link title. |
| UN-026 | 8924 माझी योजना My Scheme | e-Link / Official Links, or e-Mahiti / Government Schemes | My Scheme is a scheme-discovery portal, not one scheme. |
| UN-027 | 903 आधार मतदानकार्ड लिंक | e-Seva / Aadhaar, or e-Seva / Voter ID | The service links Aadhaar and the voter card. Both are PRD categories. |
| UN-028 | 904 आधार पॅन लिंंकिंग (Adhaar -Pan Linking) | e-Seva / Aadhaar, or e-Seva / PAN | The service links Aadhaar and PAN. Both are PRD categories. |
| UN-029 | 919 अप्रेंटिस डिग्री डिप्लोमा | e-Seva / Employment services, or e-Mahiti / Government Jobs | Apprentice degree and diploma training has the same open question as apprenticeship training. |
| UN-030 | 936 महाराष्ट्र राज्य वर्गानुसार जातीची यादी | e-Seva / Certificates, as a reference list | This is a caste list, not an application. It may be a supportive document of caste certificate rather than its own service. |
| UN-031 | 9706 म्हाडा पुणे विभाग | e-Link / Official Links, or e-Mahiti / Government Schemes | MHADA Pune Division reads as an office link. The PRD places official websites with e-Link. |
| UN-032 | Aadhaar–PAN Linking | e-Seva / Aadhaar, or e-Seva / PAN | The service links Aadhaar and PAN. Both are PRD categories. |
| UN-033 | Admit Card Download | e-Link / Admit Cards | Admit cards are an e-Link category. e-Link has no poster, advertisement, or document folder. |
| UN-034 | CIBIL Report | e-Seva / Banking, or e-Seva / Income Tax | A credit report is a banking product. The source list placed it with finance services. |
| UN-035 | Conductor Batch Billa | No clear PRD category. | The title is not enough to tell whether this is a transport permit, a badge, or another service. |
| UN-036 | Diploma Number (Nursing / Paramedical) | e-Seva / Education documents, or e-Seva / Professional registration | A diploma number can be an education document or part of nursing registration. |
| UN-037 | Online Exam Form Filling | e-Link / Exam Forms, e-Mahiti / Exams, or e-Seva / Education documents | A generic exam-form service matches three PRD paths. |
| UN-038 | Railway Concession Certificate | e-Seva / Passport and travel, or e-Mahiti / Government Schemes | This may be the same benefit as the Divyang railway card, or a general travel concession. |
| UN-039 | Result Download / Print | e-Link / Results | Results are an e-Link category. e-Link has no poster, advertisement, or document folder. |
| UN-040 | उत्तर महाराष्ट्र विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-041 | गाडगे बाबा अमरावती विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-042 | डॉ आंबेडकर तंत्रशास्त्र विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-043 | डॉ आंबेडकर मराठवाडा विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-044 | डॉ. पंजाबराव कृषि विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-045 | डॉ.सावंत कोकण कृषि विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-046 | तुकडोजी नागपूर विघापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-047 | पुणे विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-048 | फुले कृषि विद्यापीठ, राहुरी | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-049 | मराठवाडा कृषि विद्यापीठ, परभणी | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-050 | महाराष्ट्र ऑनलाईन नागरी सेवा | e-Link / Official Links | This is a set of civic-service links. The PRD places official links in e-Link, which has no poster. |
| UN-051 | मुंबई विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-052 | यशवंतराव चव्हाण मुक्त विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-053 | रामानंद विद्यापीठ नांदेड | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-054 | शिवाजी विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |
| UN-055 | सर्व जिल्ह्याच्या प्रशासकीय पोर्टलच्या लिंक | e-Link / Official Links | This is a set of district-portal links. The PRD places official websites in e-Link. |
| UN-056 | सोलापूर विद्यापीठ | e-Link / Official Links | A university website matches the e-Link Official Links category. e-Link has no poster. |

## Names that are not services

These source items are folders, inner labels, or image files. They are not catalogue services and they do not get a service poster.

| Name | What it is |
| --- | --- |
| जुन्या योजना | Folder of older schemes. The scheme titles inside it are services in the Government Schemes section or the uncertain section. |
| जुन्या जाहिराती | Folder label on the educational-admission list. The source gives no titles inside it. |
| CEA | Repeated inner label of ESM CEA. The parent service carries the content. |
| सेंट्रल बॅंक ऑफ इंडिया and Central Bank of India | One bank, two labels, inside bank-account opening. One optional bank mark. |
| युनियन बॅंक; Bank of Maharashtra; Canara Bank; UCO Bank; Axis Bank | Inner labels of bank-account opening. Optional bank marks on that one service. |
| ग्रांम पंचायत निवडणूक | Inner title of the election-candidature service, which is on hold. |
| माहितीबझार कॅलेंडर | Inner title of the civic-service link set, which is on hold. |
| Extra Income 4.jpg | Image file in the source album, not a service title. |
| 5.jpg | Image file in the source album, not a service title. |
| 4.jpg | Image file in the source album, not a service title. |
| 77.jpg | Image file in the source album, not a service title. |
| 100.jpg | Image file in the source album, not a service title. |
| university Link.jpg | Image file in the source album, not a service title. |

## Possible same service

Each title is kept because the wording differs. Treat a group as one service until Admin says the titles are different seasons or different actions. Deliver one poster for the title that is kept.

| Titles |
| --- |
| 1020 प्रधानमंत्री स्वनिधी योजना · 929 प्रधानमंत्री स्वनिधी योजना · प्रधानमंत्री स्वनिधी योजना |
| 10404 शेतकरी ओळखप्रमाणपत्र · 10404 शेतकरी ओळखप्रमाणपत्र (Farmer ID) |
| 11513 फळपिक विमा योजना · 9497 फळपिक विमा योजना |
| 4000 प्रधानमंत्री किसान सन्मान निधी योजना · प्रधानमंत्री किसान सन्मान निधी योजना |
| 8301 पशुवाटप योजना · 9856 पशुवाटप योजना |
| 8876 आधार मतदानकार्ड लिंक · 903 आधार मतदानकार्ड लिंक |
| 906 ई श्रम कार्ड · 9665 ई श्रम कार्ड |
| 9250 घरगुती शौचालय निर्माण योजना · घरगुती शौचालय निर्माण योजना |
| 939 CMEGP मुख्यमंत्री रोजगार निर्मती कार्यक्रम · CMEGP मुख्यमंत्री रोजगार निर्मती कार्यक्रम |
| 9543 प्रधानमंत्री पीक विमा योजना · 9840 प्रधानमंत्री पीक विमा योजना |

## Related titles

These names can describe one programme or one counter service in two languages. Keep them as separate records when the action differs (new and renewal, or two seasons). Compare them before publishing a second record.

### Svanidhi

- 1020 प्रधानमंत्री स्वनिधी योजना
- 8754 पी एम स्वनिधी योजना
- 929 प्रधानमंत्री स्वनिधी योजना
- प्रधानमंत्री स्वनिधी योजना

### HSRP

- 10582 HSRP हाय सेक्युरिटी नंबर प्लेट
- HSRP Number Plate

### Ayushman Bharat card

- 9714 आयुष्यमान भारत कार्ड
- Ayushman Bharat Card

### e-SHRAM

- 906 ई श्रम कार्ड
- 9665 ई श्रम कार्ड
- e-SHRAM Card

### Udyam

- 923 उद्योग आधार
- Udyog Aadhaar (MSME) Registration
- Udyog Aadhaar (MSME) Update

### Shop Act

- 924 शॉपअ‍ॅक्ट लायसन्स
- Gumasta License (New / Renewal)
- Shop Act Intimation (10 & Above Employees)
- Shop Act Intimation (Up to 9 Employees)
- Shop Act Renewal (Maharashtra)

### FSSAI

- 927 फूड लायसन्स / अन्न परवाना
- FSSAI Annual Return
- FSSAI Modification
- FSSAI Registration – 1 Year
- FSSAI Registration – 3 Years
- FSSAI Registration – 5 Years
- FSSAI Renewal

### Police clearance

- 925 पोलिस क्लिअरन्स सर्टिफिकेट
- Police Clearance Certificate – Normal
- Police Clearance Certificate – Security

### Gazette

- 1911 राजपत्र (Gazette) फेरबदल
- Gazette Notification – Open Category
- Gazette Notification – Reserved Category

### Nursing

- 1933 नर्सिंग रजिस्ट्रेशन व रिन्युअल
- Nursing Certificate Apply
- Nursing Registration

### Passport

- 1931 पासपोर्ट सेवा
- Passport New
- Passport Renewal

### Driving licence

- 930 ड्रायव्हिंग लायसन्स
- DL Renewal / Duplicate
- International Driving Permit
- Learner Driving License (2W / 4W)
- Permanent Driving License (2W / 4W)

### EPF

- 926 EPF Services (कर्मचारी भविष्यनिर्वाह निधी सुविधा)
- EPF Claim (e-KYC + Nominee + Claim)
- PF Balance Check
- PF Transfer
- Pension Claim (Form-10D)
- UAN Activation
- UAN Generation

### Aadhaar PVC

- 921 आधार PVC कार्ड
- Aadhaar PVC Card Order

### Aadhaar reprint

- 922 आधार दुय्यम प्रत सेवा
- Aadhaar Reprint

### Aadhaar address

- 1912 आधार कार्ड पत्ता दुरूस्ती
- Aadhaar Address / Mobile / Email Update

### 7/12 extract

- 10671 सातबारा (7/12) म्युटेशन / वारसनोंदणी
- 1913 7/12 (सात बारा) डिजिटल स्वाक्षरीत व प्रॉपर्टी कार्ड
- 7/12 Extract / Property Card

### Land mutation

- 10671 सातबारा (7/12) म्युटेशन / वारसनोंदणी
- Land Mutation

### Rent agreement

- 1929 भाडेकरार नोंंदणी (LEAVE AND LICENSE AGREEMENT)
- Rent / Lease Agreement Online

### Construction-worker registration

- 7391 बांधकाम कामगार नोंदणी
- Construction Worker Registration

### UDID

- 1932 UDID Card दिव्यांग (अपंगत्वाचे) यूडीआयडी कार्ड व प्रमाणपत्र
- Divyang Card

### 10th and 12th marksheet

- 1001 १०वी / १२ वी इ मार्कशीट
- 11017 10वी 12वी दुय्यम गुणपत्रे व प्रमाणपत्रे

### Holkar scheme

- 10326 राजे यशवंतराव होळकर महामेष योजना (भज-क प्रवर्गा साठी)
- 7013 राजे यशवंतराव होळकर महामेष योजना

### PM-Kisan

- 11307 पी एम किसान e-KYC
- 4000 प्रधानमंत्री किसान सन्मान निधी योजना
- प्रधानमंत्री किसान सन्मान निधी योजना
- प्रधानमंत्री किसान सन्मान योजना शेतकरी नावनोंदणी

### Housing scheme

- 10547 प्रधानमंत्री अवास योजना
- 9336 पिंपरी आकुर्डी : - प्रधानमंत्री आवास योजना
- प्रधानमंत्री आवास योजना : पुणे महानगर प्रदेश विकास प्राधिकरण

### Livestock distribution

- 10680 पशुवाटप योजना 2025-26
- 8301 पशुवाटप योजना
- 9856 पशुवाटप योजना

### Crop insurance

- 10742 फळ पिक विमा मृग बहार योजना
- 10759 प्रधानमंत्री पीक विमा योजना 2025-26
- 10981 रब्बी पिक विमा 2025
- 11365 पिकविमा 2026
- 11513 फळपिक विमा योजना
- 9497 फळपिक विमा योजना
- 9543 प्रधानमंत्री पीक विमा योजना
- 9840 प्रधानमंत्री पीक विमा योजना
