# Service Owner

## Část 1 – Běh aplikace

Zajistěte běh webové aplikace s databází. Aplikaci si zvolte sami – můžete použít existující open-source projekt, demo aplikaci, nebo cokoliv jiného. Aplikace musí být funkční a otestovatelná.

## Část 2 – CI pipeline

Pro aplikaci z Části 1 vytvořte CI pipeline, která zajistí build a publikaci deployovatelného artefaktu.

## Část 3 – Deployment pipeline a prostředí

Aplikace potřebuje dvě prostředí – staging a production. Navrhněte a implementujte způsob, jakým se nová verze dostane od git push přes staging do production, včetně mechanismu schválení před nasazením do production.

## Část 4 – Logging a monitoring

Zajistěte centrální sběr logů a monitoring aplikace. Musí existovat způsob, jak sledovat zdraví a výkon aplikace, a jak v logách identifikovat chybu.

## Část 5 – Alerting a vizualizace

Navažte na Část 4. Nastavte alerting, který na základě logů nebo metrik upozorní na chybu. Chyba musí být vizualizovaná tak, aby bylo zřejmé, co se děje a co je třeba řešit.
