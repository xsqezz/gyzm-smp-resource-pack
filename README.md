# Gyzmo SMP — Gemy

Oficjalny resource pack serwera Gyzmo SMP, wydanie **1.5.0**.

Paczka `Gyzmo-SMP-Gemy-1.5.0.zip` dodaje trzynaście unikalnych tekstur Gemów, `Odłamek Gemu`, `Ulepszacz Gemu`, fioletowy `Reroll Gem` bez tła oraz kompletny zestaw Enderite. Tekstury itemów i noszonej zbroi pochodzą z dostarczonego wzoru Enderite i są przypisane tylko do oznaczonych itemów przez `custom_model_data`; zwykły Netherite zachowuje vanilla wygląd. Tekstury noszonej zbroi są zapisane w prawidłowych katalogach vanilla `textures/entity/equipment/humanoid` i `humanoid_leggings`, z poprawnym kanałem alfa, więc zbroja nie zamienia gracza w czarną bryłę. Zwykły Ancient Debris zachowuje vanilla teksturę; Enderite używa osobnego proxy Crying Obsidian.

## Konfiguracja serwera

Wpisz bezpośredni adres paczki z repozytorium do pola **Resource pack** w panelu serwera albo ustaw w `server.properties`:

```properties
resource-pack=https://raw.githubusercontent.com/xsqezz/gyzm-smp-resource-pack/v1.5.0/Gyzmo-SMP-Gemy-1.5.0.zip
resource-pack-sha1=8ebd2b7c55e6d8d74cae9f235809c8a2059a7474
resource-pack-prompt={"text":"Gyzmo SMP wymaga resource packa Gemow."}
require-resource-pack=true
```
