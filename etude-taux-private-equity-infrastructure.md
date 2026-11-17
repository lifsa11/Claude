# Hausse des taux et marchés privés : levées de fonds et valorisations (private equity et infrastructure)

*Revue des études empiriques et des statistiques de marché. État des sources au 17 novembre 2026.*

---

## 1. Synthèse

| Question | Ce que disent les données | Degré de confiance |
|---|---|---|
| La hausse des taux a-t-elle réduit les levées de fonds ? | Oui, avec 4 à 12 trimestres de décalage. Les levées buyout mondiales baissent pour la **4e année consécutive** en 2025 (395 Md$, −16 %). Une étude économétrique récente estime qu'un resserrement de 25 pb réduit les capitaux levés d'environ **40 %** au pic (environ 6 trimestres). | Élevé sur le sens de l'effet, moyen sur l'ampleur |
| Par quels canaux ? | Surtout **indirects** : moins de sorties, donc moins de distributions aux LP, donc moins de nouveaux engagements. S'y ajoutent l'effet dénominateur, un coût d'opportunité plus élevé (crédit privé, obligations) et le coût de la dette LBO. | Élevé |
| Quel effet sur les valorisations en private equity ? | Les multiples d'entrée ont baissé de 2022 à 2024, puis se sont repris en 2025. Les NAV ont été **lissées** : −4,3 % pour l'indice PE US en 2022, contre −18,1 % pour le S&P 500. | Élevé sur le lissage, moyen sur l'ampleur réelle |
| Quel effet sur l'infrastructure ? | Une sensibilité d'environ **−10 % de juste valeur pour +100 pb** de taux d'actualisation (EDHECinfra). Elle est en partie compensée par l'indexation des revenus sur l'inflation. Les levées ont baissé d'environ **50 % en 2023**, puis ont atteint un **record en 2025** (environ 200 Md$). | Moyen |

**À retenir :** les taux pèsent moins sur l'appétit des investisseurs pour la classe d'actifs que sur la **liquidité du cycle**, c'est-à-dire la chaîne sorties → distributions → réengagements. Le choc de 2022-2023 a surtout bloqué ce circuit. C'est pourquoi les levées de PE restent faibles en 2025, alors que les taux baissent et que le volume des transactions repart (+19 %). L'infrastructure, plus proche d'une obligation indexée sur l'inflation, s'est redressée plus tôt.

---

## 2. Mécanismes de transmission

```
Hausse des taux directeurs / taux longs
 ├─► (1) Coût de la dette LBO ↑ ──► levier ↓, prix payés ↓, volumes ↓         [canal du crédit]
 ├─► (2) Taux d'actualisation ↑ ──► valeur des actifs ↓ (multiples, DCF)      [canal de valorisation]
 ├─► (3) Écart acheteurs/vendeurs ──► sorties ↓ ──► distributions (DPI) ↓
 │                                         └──► LP sans liquidité ──► engagements ↓   [canal de liquidité]
 ├─► (4) Chute des actifs cotés + NAV privées lissées ──► surpondération ──► engagements ↓   [effet dénominateur]
 └─► (5) Rendements obligataires et de crédit privé ↑ ──► coût d'opportunité ↑ ──► réallocation   [canal d'allocation]
```

**Ordre de grandeur pour un actif « long » (illustration).** Dans un modèle de Gordon, V = CF / (r − g), une hausse Δr réduit la valeur d'environ Δr / (r − g). Avec r = 8 % et g = 2 %, +100 pb réduisent la valeur d'environ 14 %, à cash-flows et prime de risque inchangés. Les effets observés sont plus faibles, pour trois raisons : la prime de risque se comprime en partie, les revenus sont indexés sur l'inflation, et les valorisations des actifs non cotés sont lissées.

---

## 3. Études empiriques : taux, conditions financières et activité ou levées de fonds en PE

### 3.1 Études récentes centrées sur la politique monétaire

**Avalos, Hofmann et Serena (BIS Working Paper n° 1326, janvier 2026), *Monetary policy and private equity acquisitions: tracing the links*.**
- Les chocs monétaires restrictifs sur la **partie courte** de la courbe des taux réduisent le **volume** des transactions de PE, le **recours au levier** et les **prix** des transactions.
- Deux canaux distincts sont identifiés. Le **canal du crédit** explique la baisse des volumes et du levier. Le **canal de valorisation** explique la baisse des prix.
- Les chocs sur la **partie longue** de la courbe ont des effets plus faibles.
- [BIS WP 1326](https://www.bis.org/publ/work1326.htm) · [SUERF Policy Brief 1421](https://www.suerf.org/wp-content/uploads/2026/04/SUERF-Policy-Brief-1421_Avalos-Hofmann-Serena.pdf)

**de Jager (2025, publié par l'APRA en mars 2026), *A Private Matter: Monetary Policy and the Rise of Private Capital in Australia*.**
- Données : Refinitiv Private Equity, 2005T1 à 2024T4. Méthode : projections locales et variables instrumentales, à partir de chocs monétaires haute fréquence (Beckers ; Bauer et Swanson).
- Effets d'un **resserrement domestique de 25 pb** :
  - **capitaux levés : environ −40 %** (pic après environ 6 trimestres) ;
  - nombre de levées : environ −10 % (creux après environ 11 trimestres) ;
  - nombre d'investissements : environ −12 % (environ 10 trimestres) ;
  - nombre de sorties : environ −9 % (10 à 11 trimestres) ;
  - LBO : réaction la plus forte et la plus tardive (−14 % après 9 trimestres).
- Les chocs monétaires américains ont des effets plus grands et plus persistants, mais estimés de façon imprécise.
- C'est l'une des rares estimations **causales** qui portent directement sur les **levées de fonds**. Il s'agit toutefois d'un mémoire, sur un marché de taille moyenne : à utiliser comme ordre de grandeur.
- [PDF APRA](https://www.apra.gov.au/sites/default/files/2026-03/A%20Private%20Matter%20Monetary%20Policy%20and%20the%20Rise%20of%20Private%20Capital%20in%20Australia.pdf)

### 3.2 Littérature académique de référence

*Ces références sont citées de mémoire, sauf mention d'un lien. Les résultats sont bien établis, mais il faut vérifier les chiffres exacts dans les articles avant de les citer.*

| Étude | Données | Résultat principal |
|---|---|---|
| **Haddad, Loualiche et Plosser (2017)**, *Buyout Activity: The Impact of Aggregate Discount Rates*, *Journal of Finance* ([NBER w22414](https://www.nber.org/papers/w22414.pdf)) | Opérations public-to-private, 1982-2011 | La **prime de risque actions agrégée** explique **plus de 30 %** de la variation de l'activité LBO. Les conditions de crédit seules en expliquent **au plus environ 10 %**. Une prime de risque basse augmente la valeur actuelle des gains opérationnels. |
| **Axelson, Jenkinson, Strömberg et Weisbach (2013)**, *Borrow Cheap, Buy High?*, *Journal of Finance* | Environ 1 100 LBO, 1980-2008 | Le levier dépend des **conditions du marché du crédit** (spreads high yield), pas des caractéristiques de l'entreprise. Plus de levier entraîne des **prix plus élevés** et des **rendements de fonds plus faibles**. |
| **Kaplan et Strömberg (2009)**, *Journal of Economic Perspectives* | Cycles LBO | Les vagues de LBO suivent les conditions de crédit. Les cohortes levées en période de crédit facile sous-performent. |
| **Kaplan et Schoar (2005)**, *Journal of Finance* | Fonds PE et VC | Les levées suivent la **performance passée**, ce qui rend les flux procycliques. Des valorisations d'entrée élevées (millésimes 2020-2021) pénalisent donc les réengagements. |
| **Gompers et Lerner (1998)**, *Brookings Papers* ; **Jeng et Wells (2000)**, *Journal of Corporate Finance* | Levées VC | Les levées dépendent des sorties (IPO), de la croissance et de la fiscalité. L'effet direct des taux est **faible ou instable**, ce qui confirme que les taux agissent surtout par des **canaux indirects**. |
| **Ljungqvist, Richardson et Wolfenzon (2020)**, *Review of Financial Studies* | Fonds buyout | Les fonds investissent plus vite quand les spreads de crédit sont bas et les opportunités nombreuses. |
| **Gupta et Van Nieuwerburgh (2021)**, *Journal of Finance* | Flux de trésorerie des fonds PE | Les fonds PE ont une exposition de type actions longues à la structure par terme des taux et des primes de risque, ce qui les rend sensibles au taux d'actualisation. |

### 3.3 Études et données sur l'effet dénominateur

- **Eaton Vance (2023), *Deconstructing the Denominator Effect*** : la baisse des marchés cotés en 2022, combinée au retard de valorisation du PE, a mécaniquement gonflé la part des actifs illiquides dans les portefeuilles. Couper les engagements ou vendre sur le secondaire peut coûter plus cher que de rester temporairement en surpondération. [PDF](https://eatonvance.com/content/dam/im/publication/insights/articles/article_deconstructingthedenominatordilemma.pdf)
- **Cambridge Associates, *Role Models*** : la modélisation conclut que réduire les engagements est rarement nécessaire si l'investisseur tolère temporairement une surpondération. [Lien](https://www.cambridgeassociates.com/?p=29065)
- **S&P Global (mai 2025)** : **plus de la moitié** des fonds de pension (publics, d'entreprise, syndicaux) dépassaient leur allocation cible en PE, ce qui limite les nouveaux engagements. [Lien](https://www.spglobal.com/market-intelligence/en/news-insights/articles/2025/5/more-than-half-of-pension-funds-exceed-private-equity-allocation-targets-89164143)
- **Thèse de Claremont (2025)**, 182 fonds de pension publics américains, 2005-2024 : une baisse de 10 points du rendement des actions cotées **augmente mécaniquement de 50,5 pb** l'allocation en PE. *C'est un travail de licence, à prendre avec prudence.* [Lien](https://scholarship.claremont.edu/cmc_theses/4264)
- **Coller Capital Barometer (hiver 2022-2023)** : 42 % des LP prévoyaient un ralentissement de leurs engagements à cause de l'effet dénominateur. *Chiffre lu dans une source secondaire, à vérifier.*

---

## 4. Statistiques de marché : levées de fonds

### 4.1 Monde, private equity

| Indicateur | Valeur | Source |
|---|---|---|
| Levées buyout 2025 | **395 Md$, −16 %**, 4e baisse annuelle consécutive | Bain, *Global PE Report 2026* ([CFO.com](https://www.cfo.com/news/bain-global-private-equity-report-finds-liquidity-pressure-rising-as-capital-cycles-grow/813053/), [Il Sole 24 Ore](https://en.ilsole24ore.com/art/private-equity-stands-still-third-year-box-awaits-recovery-AIYQEVXD)) |
| Levées PE fermées (closed-end) 2025 | **616 Md$, −17 %** ; Amérique du Nord **+8 %**, Europe **−41 %**, Asie-Pacifique **−49 %** | McKinsey, *Global Private Markets Report 2026* ([lien](https://www.mckinsey.com/industries/private-capital/our-insights/global-private-markets-report/private-equity)) |
| Pic de référence | Environ 1 800 Md$ en 2021 (périmètre plus large, selon une source secondaire) | [Angel Investors Network](https://angelinvestorsnetwork.com/market-analysis/pe-fundraising-data-2026-drought) |
| Distributions / NAV | **6 %** en 2025, contre **16 %** en moyenne sur 2015-2019 | McKinsey 2026 (via [PE Insights](https://pe-insights.com/record-scale-deals-shrinking-dpi-private-equitys-new-reality/)) |
| Portefeuilles non cédés | Environ **32 000 sociétés, 3 800 Md$** | Bain 2026 ([Enterprise AM](https://enterpriseam.com/mena-india/2026/02/25/private-equitys-liquidity-crunch-persists-with-usd-3-8-tn-in-assets-still-waiting-for-exit/)) |
| Valeur des transactions 2025 | **2 600 Md$, +19 %** ; buyout environ 1 800 Md$ | McKinsey 2026 |
| Intentions des LP | Environ **70 %** comptent maintenir ou augmenter leur allocation PE en 2026 | McKinsey 2026 |
| Perspectives 2026 | La reprise **cale de nouveau** au S1 2026, après trois chocs de marché successifs | [Bain, rapport de mi-année 2026](https://www.bain.com/zh/about/media-center/press-releases/2026/winning-firms-will-focus-on-what-they-can-control-weather-the-rest-as-triple-shock-brakes-private-equitys-latest-revival-bain--company-2026-midyear-pe-report/) |

**Lecture.** En 2025, l'activité de transaction repart alors que les levées continuent de baisser. Les taux agissent donc **avec retard** à travers le stock d'actifs non cédés. Tant que le ratio distributions/NAV reste à 6 %, les LP n'ont pas la liquidité nécessaire pour se réengager, même avec des taux en baisse. On retrouve la séquence estimée par l'étude APRA : d'abord les sorties, puis les levées, 6 à 11 trimestres plus tard.

### 4.2 France (France Invest et Grant Thornton, infrastructure comprise)

| Année | Capitaux levés | Variation | Commentaire |
|---|---|---|---|
| 2023 | Environ 35,7 Md€ (déduit de la hausse de +9 % en 2024) | En baisse | « Une année 2023 en retrait marquée par la **remontée des taux d'intérêt** » |
| 2024 | **38,9 Md€** | +9 % | Levées plus longues ; investissements 36,9 Md€ (+13 %) ; cessions 12,8 Md€ (+42 %) |
| 2025 | **42,9 Md€** | +10 % | Hausse **portée par les fonds de continuation** : **−2 %** hors ces fonds. Investissements 36,4 Md€ (−1 %), cessions 14,0 Md€ |

Sources : [France Invest, communiqué 2024](https://franceinvest.eu/wp-content/uploads/2025/03/CP-France-Invest-Etude-dactivite-du-capital-investissement-francais-en-2024.pdf) · [Grant Thornton, communiqué 2025](https://www.grantthornton.fr/globalassets/1.-member-firms/france/communiques-presses/2026/2026-03-25_cp_france-invest-activite-2025_grant-thornton.pdf) · [France Invest, S1 2025](https://www.franceinvest.eu/wp-content/uploads/2025/10/CP-France-Invest-Activite-S1-2025-VDEF.pdf)

**Lecture.** Le marché français a mieux résisté que l'Europe dans son ensemble (−41 % selon McKinsey). Deux facteurs l'expliquent : le poids de l'infrastructure et des engagements publics (Bpifrance), et le recours aux **fonds de continuation**, qui servent à créer de la liquidité quand les sorties classiques sont bloquées. Les levées « organiques » sont en fait stables ou en légère baisse.

### 4.3 Monde, infrastructure

| Année | Levées de fonds d'infrastructure non cotés | Source |
|---|---|---|
| 2022 | Environ **176 Md$** (record de l'époque) | Preqin |
| 2023 | Environ **88 à 95 Md$** (**environ −50 %**) | Preqin ([S&P Global](https://www.spglobal.com/market-intelligence/en/news-insights/articles/2024/2/infrastructure-fundraising-poised-for-recovery-after-slow-2023-80382339)) |
| 2024 | Environ 87 à 95 Md$ (stable ; BCG et Preqin divergent sur le sens de l'évolution) | [Preqin](https://www.preqin.com/news/infrastructure-in-2025-the-outlook-for-fundraising-deals-and-performance), [BCG 2025](https://bcg.com/publications/2025/investors-gain-advantage-asset-class-matures) |
| 2025 | **Environ 200 à 211 Md$, record** (+60 % selon BCG) | [BCG 2026](https://web-assets.bcg.com/51/f7/9aeca30542d0a9074f0bd0842108/infrastructure-strategy-2026-mar2026.pdf), [McKinsey](https://www.mckinsey.com/featured-insights/charts/private-capital-lays-the-groundwork) |

- UBS : la collecte en infrastructure non cotée a été **« atone pendant 10 trimestres depuis le début du cycle de hausse des taux à la mi-2022 »**, puis a rebondi au S1 2025. [Lien](https://www.ubs.com/ca/en/assetmanagement/insights/asset-class-perspectives/infrastructure/articles/infrastructure-inflows.html)
- Preqin : le nombre de fonds axés sur l'Amérique du Nord clôturés chaque année est passé de 63 en 2021 à 18 à fin T3 2024. La part du dry powder dans les encours (AUM) est à un **plus bas historique** ([communiqué](https://www.preqin.com/about/press-release/infrastructure-dry-powder-as-share-of-aum-falls-to-record-low-of-24-in-2024-preqin-reports)).

**Lecture.** L'infrastructure a mieux encaissé le choc que le PE. Elle a chuté plus brutalement en 2023 (−50 %), après une collecte 2022 qui avait déjà rempli les allocations, mais elle s'est **redressée plus vite**. Les LP l'utilisent comme couverture contre l'inflation et elle bénéficie de thèmes structurels (transition énergétique, centres de données). La collecte se concentre aussi sur les très grands gérants.

---

## 5. Impact des taux sur les valorisations en private equity

### 5.1 Multiples d'entrée

| Indicateur | Valeur | Source |
|---|---|---|
| Multiple EV/EBITDA médian des buyouts américains | 10,3x (2017), puis **14,3x (2021)** | [Preqin](https://www.preqin.com/insights/research/blogs/us-buyout-funds-are-paying-more-for-less) |
| Pic européen (EV/EBITDA médian) | **17,5x** au T3 2021 | [Mergermarket / ION](https://ionanalytics.com/insights/mergermarket/sponsors-rack-up-more-key-takings-than-ipos-among-2020-2021-european-buyouts-dealspeak-emea/) |
| États-Unis, 2025 | **13,2x**, soit **−18 %** par rapport à 2021 | [Gain, *State of US PE* S1 2026](https://marketing.gain.ai/hubfs/the-state-of-us-private-equity-h1-2026.pdf) |
| Europe | Trois années de baisse consécutives (2022-2024), premiers signes de reprise en 2025 | [Gain, S2 2025](https://gain.pro/insight-reports/the-state-of-european-private-equity-h2-2025) |
| Médiane des 12 derniers mois aux États-Unis (mi-2025) | 12,8x | [PitchBook, Q2 2025](https://files.pitchbook.com/website/files/pdf/Q2_2025_European_PE_Breakdown.pdf) |

Une baisse d'environ 15 à 20 % des multiples correspond au **canal de valorisation** identifié par la BIS. Elle est cohérente avec une hausse de 300 à 500 pb des taux sans risque (Fed funds de 0-0,25 % en mars 2022 à 5,25-5,50 % en juillet 2023 ; taux de dépôt de la BCE à 4 % en septembre 2023), en partie absorbée par la compression des primes de risque.

### 5.2 Lissage des NAV et décalage avec les marchés cotés

| Année | Indice Cambridge Associates US PE | S&P 500 |
|---|---|---|
| 2022 | **−4,3 %** | **−18,1 %** |
| 2023 | +9,3 % (buyout : +10,4 %) | +26,3 % |

Sources : [Cambridge Associates, CY2022](https://publishedresearch.cambridgeassociates.com/wp-content/uploads/2023/08/2023-08-US-PE-VC-Benchmark-Commentary-CY2022-Data.pdf) · [CY2023](https://publishedresearch.cambridgeassociates.com/wp-content/uploads/2024/07/2024-07-US-PE-VC-Benchmark-Commentary-CY2023-Data.pdf)

- **Interprétation.** En 2022, le PE n'a pas vraiment « résisté » : ses valorisations ont été **amorties dans le temps**. Le choc de taux a été étalé sur 2022-2024, ce qui a provoqué l'effet dénominateur et une sous-performance relative en 2023.
- **Études académiques.** Brown, Ghysels et Gredil, *Nowcasting Net Asset Values: The Case of Private Equity* (*Review of Financial Studies*, 2023 ; [version AEA 2020](https://aeaweb.org/conference/2020/preliminary/paper/edGsaR9Y)), reconstruisent des NAV hebdomadaires « non lissées ». Couts, Gonçalves et Rossi, *Unsmoothing Returns of Illiquid Funds* (*RFS*), montrent que la volatilité et le bêta réels du PE sont nettement supérieurs aux chiffres publiés. *(Cité de mémoire.)*
- **Signal du marché coté.** En 2022-2023, le PE coté s'échangeait autour de **70 cents par dollar de NAV**, contre environ 90 cents en 2021 ([IFA](https://www.ifa.com/articles/private_equity_volatility_true_risk_higher_than_you_think), source secondaire). Les décotes du secondaire LP en sont une autre mesure.
- **Régulateurs.** Dans son *Global Financial Stability Report* d'avril 2024, le FMI range les **« valorisations obsolètes et potentiellement subjectives »** parmi les principales vulnérabilités des marchés privés. Il note aussi qu'après la hausse des taux, plus d'un tiers des emprunteurs du crédit privé avaient des charges d'intérêt supérieures à leurs résultats. [GFSR avril 2024](https://www.imf.org/en/Publications/GFSR/Issues/2024/04/16/global-financial-stability-report-april-2024)

### 5.3 Effets sur la création de valeur

- **Levier et coût de la dette.** Les LBO financés en 2019-2021 à taux variable ont vu leur couverture des intérêts se dégrader. La BIS et Axelson et al. montrent que le levier dépend du crédit. Moins de levier implique des TRI attendus plus bas à prix égal, donc des prix offerts plus bas.
- **Écart acheteurs/vendeurs.** Les vendeurs ancrés sur les NAV de 2021 et les acheteurs qui actualisent à des taux plus élevés n'arrivent pas à conclure. Les sorties s'effondrent et les durées de détention s'allongent : c'est la principale explication des 3 800 Md$ d'actifs non cédés.
- **Rôle de la croissance.** Neuberger Berman ([*Private Equity and Rates, Part II*](https://www.nb.com/en/lu/insights/whitepaper-private-equity-and-rates-part-ii-do-rates-really-matter-for-private-equity)) soutient que la performance et les distributions du PE dépendent avant tout de la **croissance économique**, plus que du niveau des taux. *C'est une étude de gérant, donc juge et partie.*

---

## 6. Impact des taux sur les valorisations en infrastructure

### 6.1 Sensibilité théorique et mesurée

- **EDHECinfra** : la juste valeur des actions d'infrastructure non cotées varie en moyenne d'environ **10 % pour 100 pb** de variation du taux d'actualisation, soit une duration effective d'environ 10. Sur un échantillon de plus de 500 actifs en 2020, la baisse des taux avait ajouté **plus de 5 %** aux NAV. [Bloomberg / EDHECinfra](https://sponsored.bloomberg.com/article/edhec-infra/inflation-risk-how-exposed-are-investors-in-infrastructure) *(contenu sponsorisé)*
- **EY** : les taux d'actualisation ont **augmenté en 2022 et 2023** avec les taux sans risque, puis se sont **stabilisés à un niveau légèrement inférieur en 2024**. [EY](https://ey.com/en_lu/insights/infrastructure/the-resilience-of-infrastructure-understanding-valuation-considerations)
- **AMP** : la **duration des actifs** est le premier déterminant de la sensibilité aux taux. La régulation, le levier et la croissance viennent ensuite. Selon AMP, le marché coté **surréagit** aux hausses de taux. [IO&C](https://ioandc.com/amp-shows-why-rates-are-over-rated-for-listed-infrastructure)

### 6.2 Facteurs qui atténuent l'effet

- **Inflation.** Pour EDHECinfra, un portefeuille d'infrastructure bien construit tend à être **positivement** affecté par l'inflation, qui est la cause même de la hausse des taux. Les revenus indexés (concessions, actifs régulés) compensent en partie la hausse du taux d'actualisation. [Institutional Investor](https://www.institutionalinvestor.com/article/2bswqkxh9uoab0zhnah34/innovation/how-exposed-are-investors-in-infrastructure-to-inflation-risk)
- **Prime de risque tampon.** Selon Frontier Advisors, la prime de risque s'est comprimée et a **amorti** la hausse des taux d'actualisation globaux. Le taux sans risque ne se transmet donc pas entièrement à la valorisation. [IO&C](https://ioandc.com/as-rising-rates-worry-the-unlisted-market)
- **Méthode de valorisation.** Toujours selon EDHECinfra, les taux d'actualisation utilisés par les gérants sont « ad hoc et très lissés ». Elle propose de les remplacer par des taux tirés du marché secondaire, ce qui implique que les NAV publiées **sous-estiment** la sensibilité réelle.

### 6.3 Données de performance

| Indicateur | Valeur | Source |
|---|---|---|
| EDHECinfra infra300 (actions non cotées, plus de 200 Md$) | **−5,0 %** de janvier à fin T3 2022 | [IREI](https://irei.com/publications/article/third-quarter-2022-unlisted-infrastructure-performance-update-infrastructure-is-not-immune-to-market-volatility) |
| Dette d'infrastructure (InfraDebt300) | **−12 %** de rendement total en 2022 : effet prix sur les coupons fixes, avec un revenu courant d'environ 3,5 % | [GI Hub](https://admin.gihub.org/infrastructure-monitor/insights/infrastructure-debt-remained-attractive-despite-negative-total-returns-in-2022/) |
| infra300, 12 mois à fin T3 2024 | **+17,0 %**, soutenu par la baisse des taux d'actualisation | EY / EDHECinfra |
| Infrastructure cotée (S&P Global Infrastructure) en 2022 | **+3,8 %**, contre −15,4 % pour le MSCI World | [IPE](https://hub.ipe.com/download?ac=141324) |

**Lecture.** En 2022, l'infrastructure cotée a bien résisté : poids de l'énergie, des services aux collectivités indexés et des concessions. L'infrastructure non cotée a cédé quelques pourcents avec retard. La **dette** d'infrastructure à taux fixe a été la plus touchée (−12 %). Les **actifs « core » à longue duration et revenus peu indexés** (certains actifs régulés, énergies renouvelables sous contrats d'achat d'électricité (PPA) à prix fixe) sont les plus sensibles. Les actifs **« core+ » et « value-add »** à revenus indexés ou liés à la croissance (centres de données, fibre) le sont moins.

**Références académiques complémentaires (citées de mémoire).** Andonov, Kräussl et Rauh, *Institutional Investors and Infrastructure Investing* (*Review of Financial Studies*, 2021) : les fonds d'infrastructure ne surperforment pas significativement et leurs flux de trésorerie sont plus cycliques que ce que suggère leur réputation « obligataire ».

---

## 7. Limites et points de vigilance

1. **Causalité.** La hausse des taux de 2022 coïncide avec la normalisation après la bulle de 2021, la guerre en Ukraine et l'inflation. Seules les études utilisant des chocs monétaires identifiés (BIS, APRA) isolent l'effet des taux.
2. **Définitions.** Les montants de levées varient d'un fournisseur à l'autre (Preqin, PitchBook, Bain, McKinsey) selon le périmètre (buyout ou PE total, fonds fermés ou evergreen, date de clôture finale ou intermédiaire). Il faut comparer des séries homogènes.
3. **Survie et concentration.** Les gros gérants captent une part croissante des levées. Les moyennes masquent l'effondrement chez les primo-accédants et les fonds de taille moyenne.
4. **Lissage.** Toute mesure de performance fondée sur les NAV sous-estime la sensibilité réelle aux taux. Les prix du secondaire et du PE coté sont de meilleurs indicateurs.
5. **Sources secondaires.** Plusieurs chiffres de 2025-2026 proviennent de comptes rendus de presse des rapports Bain et McKinsey. Ils sont signalés comme tels ; il faut les vérifier dans les rapports originaux avant publication.

---

## 8. Pistes d'approfondissement

- Lire les PDF complets de Bain (*Global PE Report 2026* et rapport de mi-année 2026) et de McKinsey (*Global Private Markets Report 2026*) pour obtenir les séries annuelles 2019-2025 homogènes.
- Lire l'étude d'activité complète de France Invest 2025, avec la répartition des souscripteurs, du poids de l'infrastructure et des fonds de continuation.
- Consulter les séries EDHECinfra infra300 et les taux d'actualisation trimestriels 2021-2026 (accès abonné).
- Exploiter le tableau de bord de l'Invest Europe *Investing in Europe: Private Equity Activity* (levées européennes par type de LP).
- Consulter la Banque de France et l'AMF (rapports de stabilité financière et cartographie des risques) pour les publications sur les valorisations du non-coté en France.
