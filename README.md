# Gyzmo SMP — Gemy

Oficjalny resource pack serwera Gyzmo SMP, wydanie **1.5.1**.

Paczka `Gyzmo-SMP-Gemy-1.5.1.zip` dodaje trzynaście unikalnych tekstur Gemów, `Odłamek Gemu`, `Ulepszacz Gemu`, fioletowy `Reroll Gem` bez tła oraz kompletny zestaw Enderite. Tekstury itemów i noszonej zbroi pochodzą z dostarczonego wzoru Enderite i są przypisane tylko do oznaczonych itemów przez `custom_model_data`; zwykły Netherite zachowuje vanilla wygląd. Asset wyposażenia wskazuje wspólny klucz `enderite`, więc warstwa spodni trafia do `textures/entity/equipment/humanoid_leggings/enderite.png`. Zwykły Ancient Debris zachowuje vanilla teksturę; Enderite używa osobnego proxy Crying Obsidian.

## Konfiguracja serwera

Wpisz bezpośredni adres paczki z repozytorium do pola **Resource pack** w panelu serwera albo ustaw w `server.properties`:

```properties
resource-pack=https://raw.githubusercontent.com/xsqezz/gyzm-smp-resource-pack/v1.5.1/Gyzmo-SMP-Gemy-1.5.1.zip
resource-pack-sha1=e6b3c8ae7ae3339229b16acb7c83b58473c3e7c7
resource-pack-prompt={"text":"Gyzmo SMP wymaga resource packa Gemow."}
require-resource-pack=true
```
