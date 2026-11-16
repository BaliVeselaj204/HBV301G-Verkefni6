# Staðsetning krafna í SRS

Sýnið staðsetningu allra gildandi krafna, einnig eftir uppskiptingu. Aðlagið
kaflaheiti að kerfinu og rökstyðjið skipulag út frá tilgangi skjalsins og þörfum
lesenda. Þetta er yfirlit; ekki þarf fullbúna SRS-skýrslu.

## Kröfur

| SRS-kafli eða undirkafli | Auðkenni og tenglar í kröfuskjöl | Rök fyrir staðsetningu og þörf lesenda |
| --- | --- | --- |
| 1.1 Skráning við komu | [FR-1.1.3](requirements/FR-1.1.3.md) | Krafan á heima undir „Skráning við komu“ því hún lýsir hvenær virk talning er stofnuð og hvaða upplýsingar eru skráðar við komu ökutækis. |
| 1.2 Skráning við brottför | [FR-1.2.2](requirements/FR-1.2.2.md), [FR-1.2.3](requirements/FR-1.2.3.md) | Kröfurnar lýsa því hvernig kerfið finnur virka talningu við brottför, skráir brottfarartímann og lýkur talningunni. |
| 1.3 Útreikningur stæðistíma | [FR-2.1.1](requirements/FR-2.1.1.md) | Krafan lýsir því hvernig lengd stæðistíma er reiknuð út frá komu- og brottfarartíma sömu talningar. |
| 2.2 ökutækjastjórnun| [FR-2.2.1](../HBV301G-Verkefni6/requirements/FR-2.2.1.md) | Krafan fjallar um tengingu ökutækja við notandareikninga og á því heima undir ökutækjastjórnun |
| 2.3 Greiðslustjórnun | [FR-2.1.2](requirements/FR-2.1.2.md), [FR-2.2.2](requirements/FR-2.2.2.md) | Krafan fjallar um stofnun greiðslubeiðna og tryggir að greiðslubeiðni sé stofnuð fyrir réttan notanda og rétta upphæð |
| 3.1 Tilkynningar | [FR-3.1.3](https://github.com/BaliVeselaj204/HBV301G-Verkefni6/blob/main/requirements/FR-3.1.3.md) | Safnar saman kröfum um tilkynningar til eigenda ökutækja, þar á meðal afhendingu tilkynninga og tímamörk |



## Tengdar upplýsingar

| Upplýsingar | Staðsetning / auðkenni / tengill | Tengsl við kröfur eða sýnileg eyða og eftirfylgni |
| --- | --- | --- |
| Samhengi kerfisins | [Verkefni 1 – SRS, 1.2 Umfang og mörk kerfisins](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/SRS.md#12-umfang-og-m%C3%B6rk-kerfisins) | Afmarkar sjálfvirka skráningu komu og brottfarar (FR-1.1.3, FR-1.2.2 og FR-1.2.3) og skýrir hvar ábyrgð kerfisins endar gagnvart greiðsluþjónustu (FR-2.2.2). |
| Notendahlutverk | [Verkefni 1 – SRS, 2.1 Notendahópar](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/SRS.md#21-notendah%C3%B3par) og [UR-3.1](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/user_requirement.md#ur-31) | SRS lýsir hlutverkum ökumanns og rekstraraðila. UR-3.1 skýrir þörf skráðs eiganda fyrir tilkynningu þegar ökutæki hans er lagt í gjaldskylt stæði (FR-3.1.3). |
| Orðasafn | [Verkefni 1 – SRS, 1.3 Skilgreiningar](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/SRS.md#13-skilgreiningar) | Skilgreinir hugtökin *stæðistími* og *gjaldsvæði*, sem eru notuð við útreikning stæðistíma (FR-2.1.1) og val á gjaldskrá (FR-2.1.2). |
| Viðskiptareglur | [BRG-1](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/business_rule.md#brg-1) og [BRG-2](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/business_rule.md#brg-2) | BRG-1 skýrir hvers vegna gjaldsvæði og stæðistími skipta máli við val á gjaldskrá (FR-2.1.1 og FR-2.1.2). BRG-2 lýsir ábyrgð notanda á að upplýsingar um ökutækið séu réttar (FR-2.2.1). |
| Gæðakröfur | [QA-1 Nákvæmni skráningar](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/quality_attribute.md#qa-1) og [QA-2 Áreiðanleiki sendingar greiðslubeiðna](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/quality_attribute.md#qa-2) | QA-1 setur mælikvarða á nákvæmni skráningar við komu og brottför (FR-1.1.3 og FR-1.2.3). QA-2 fjallar um hvenær greiðslubeiðni á að berast eftir brottför og tengist því FR-2.2.2 um stofnun beiðninnar. |
| Forsendur | [UI-2 Greiðslugátt/netbanki](https://github.com/BaliVeselaj204/HBV301G-Verkefni1/blob/main/SRS/external_interface.md#ui-2) og [issue #3](https://github.com/BaliVeselaj204/HBV301G-Verkefni6/issues/3) | **TBD (FR-2.2.2).** TBD (FR-2.2.2). Bali og Kristinn bera sameiginlega ábyrgð á að staðfesta hvernig kerfið sendir stofnaða greiðslubeiðni til greiðsluþjónustunnar. |
