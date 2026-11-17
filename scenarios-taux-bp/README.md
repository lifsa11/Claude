# Swen CP : levées prévues au BP selon trois scénarios de taux (2026-2030)

Fichier : `swen-bp-scenarios-taux.xlsx`. Le modèle recalcule tout dès que le BP, les taux ou les hypothèses changent.

> **Important : les résultats ci-dessous sont calculés sur un BP illustratif.** Le BP réel de Swen n'était disponible ni dans le dépôt ni dans le Drive. Seule l'année 2026 reprend des closings publics (SWIFT 3, Territoires Innovants 4, Swen Terra, Select Europa 7). Les montants 2027-2030 sont fictifs. Les **pourcentages d'écart** donnent déjà le sens et l'ordre de grandeur de l'effet ; les **montants en M€** n'auront de sens qu'avec le vrai BP.

## Scénarios de taux (niveaux de fin d'année)

| | 2026 | 2027 | 2028 | 2029 | 2030 |
|---|---|---|---|---|---|
| **Stable** : BCE / OAT 10 ans | 2,50 % / 4,70 % | 2,50 / 4,70 | 2,50 / 4,70 | 2,50 / 4,70 | 2,50 / 4,70 |
| **Hausse** : BCE / OAT | 2,50 / 4,70 | 3,00 / 5,20 | 3,50 / 5,60 | 3,75 / 5,80 | 3,75 / 5,80 |
| **Baisse** : BCE / OAT | 2,50 / 4,70 | 2,00 / 4,20 | 1,50 / 3,80 | 1,25 / 3,60 | 1,25 / 3,50 |

Point de départ : taux de dépôt de la BCE à 2,50 %, maintenu le 29/10/2026 après deux hausses en 2026 ; OAT 10 ans à environ 4,70 % le 10/11/2026. Par défaut, le BP est supposé construit avec les taux actuels. Le scénario Stable est alors égal au BP. Si le BP intégrait déjà une baisse des taux, il faut la saisir dans l'onglet Scenarios (lignes 7-8).

## Méthode

1. **Écart de taux composite** : combinaison de l'écart sur le taux BCE et de l'écart sur l'OAT, avec un poids propre à chaque classe d'actifs. Le taux court domine pour le PE et la gestion privée (BIS WP 1326), le taux long pour l'infrastructure et le capital naturel (taux d'actualisation).
2. **Décalage** : 30 % de l'effet porte sur l'année même, 50 % sur l'année suivante et 20 % deux ans après. Ce profil suit de Jager/APRA 2026 : pic sur les capitaux levés après environ 6 trimestres.
3. **Impact** : sensibilité de la classe × écart effectif, exprimé par tranche de 100 pb. Si les taux baissent, l'impact est réduit par un facteur d'asymétrie : une baisse aide moins qu'une hausse ne pénalise, car les distributions aux investisseurs doivent d'abord repartir. L'impact est borné entre −50 % et +30 %.
4. **Levées projetées** = BP × (1 + impact).

## Hypothèses par classe d'actifs

| Classe d'actifs | Sensibilité par +100 pb | Poids du taux court | Asymétrie en cas de baisse | Confiance |
|---|---|---|---|---|
| PE multi-gestion, fonds primaires (Select Europa) | −12 % | 60 % | 0,6 | Moyenne |
| PE secondaire et co-investissement | −6 % | 60 % | 0,6 | Faible |
| PE direct PME/ETI France (Territoires) | −7 % | 70 % | 0,5 | Moyenne |
| Infrastructure, transition énergétique (SWIFT) | −10 % | 30 % | 0,8 | Moyenne |
| Capital naturel et agriculture (Swen Terra) | −8 % | 30 % | 0,6 | Faible |
| Venture et innovation à impact (Blue Ocean) | −15 % | 50 % | 0,7 | Moyenne |
| Dette privée et mezzanine | **+3 %** | 80 % | 1,0 | Moyenne |
| Gestion privée (FPS, UC, evergreen) | −14 % | 70 % | 0,8 | Faible |

Chaque paramètre est justifié et sourcé dans l'onglet Hypotheses, à partir de l'étude `../etude-taux-private-equity-infrastructure.md`.

## Résultats sur le BP illustratif (cumul 2026-2030)

| Classe d'actifs | BP (M€) | Hausse vs BP | Baisse vs BP |
|---|---|---|---|
| PE multi-gestion, fonds primaires | 876 | **−6,7 %** | +4,0 % |
| PE secondaire et co-investissement | 590 | −3,8 % | +2,3 % |
| PE direct PME/ETI France | 643 | −3,9 % | +2,0 % |
| Infrastructure, transition énergétique | 1 540 | −5,4 % | +4,3 % |
| Capital naturel et agriculture | 555 | −5,4 % | +3,3 % |
| Venture et innovation à impact | 370 | **−10,3 %** | +7,2 % |
| Dette privée et mezzanine | 480 | **+2,2 %** | −2,2 % |
| Gestion privée | 400 | **−10,0 %** | **+8,0 %** |
| **Total** | **5 454** | **−5,3 % (−287 M€)** | **+3,6 % (+195 M€)** |

Écart total par année : en hausse, −1 % en 2027, −4 % en 2028 et environ −9 % en 2029-2030 ; en baisse, +1 %, +3 % puis environ +6 %.

## Lecture

- **Effet asymétrique.** Une hausse de taux coûte environ 1,5 fois plus qu'une baisse de même ampleur ne rapporte : −5,3 % contre +3,6 %. Cela reflète l'expérience 2022-2025 : quatre années de baisse des levées buyout malgré le retournement des taux, parce que le stock d'actifs non cédés freine les distributions.
- **Effet décalé.** L'impact est quasi nul en 2027 et se concentre sur **2029-2030**. Les fonds dont le closing est prévu en fin de BP sont donc les plus exposés.
- **Classes les plus exposées :** venture à impact, gestion privée et PE primaire multi-gestion.
- **Classe qui en bénéficie :** la dette privée et mezzanine profite d'une hausse des taux. C'est la seule couverture naturelle de la gamme.
- **Infrastructure :** l'effet est moyen sur la période, mais le repli serait brutal en cas de hausse, comme en 2023 (−50 % de levées mondiales), et le rebond rapide en cas de baisse.

## Limites

- **Paramètres à dire d'expert.** Les sensibilités sont des hypothèses, pas des estimations économétriques propres à Swen. Elles sont à recaler sur l'historique de collecte 2019-2026 de Swen si ces données sont disponibles.
- **Les taux ne font pas tout.** Le modèle ignore d'autres déterminants majeurs : performance et distributions des millésimes précédents, calendrier des fonds successeurs, concentration du marché, réglementation (Solvabilité II, ELTIF 2.0), actionnariat Ofi Invest.
- **Périmètre limité aux levées.** L'effet sur les valorisations (NAV), sur le carried interest et sur les commissions de gestion n'est pas modélisé.
