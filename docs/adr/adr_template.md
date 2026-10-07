# ADR-001: Använd modulär monolit
## Kontext
Systemet ska utvecklas av ett mindre team och behöver vara enkelt
att utveckla och driftsätta.
## Alternativ
- Traditionell monolit
- Modulär monolit
- Mikrotjänster
## Beslut
Vi använder en modulär monolit.
## Motivering
Lösningen ger tydliga gränser mellan systemets delar utan den
ökade komplexitet som mikrotjänster innebär.
## Konsekvenser / trade-offs
Enklare utveckling och deployment, men systemets delar kan inte
skalas och driftsättas oberoende på samma sätt som mikrotjänster.
