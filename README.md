# Omarchy Greenhouse Theme

A houseplant dark theme for [Omarchy](https://omarchy.org/): mossy backgrounds, pale linen text, a spread of plant greens (monstera, pothos, new growth, snake plant), Pink Princess pink, terracotta and sun-gold. Includes a matching VS Code theme and a monstera boot screen logo.

![Preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/BBIEPavkov/omarchy-greenhouse-theme
omarchy theme set greenhouse
```

Requires Omarchy 4 (Quattro) and the `Yaru-sage-dark` icon theme.

## Colors

| Role | Color |
|------|-------|
| Background | `#2A3427` (moss) |
| Foreground | `#D6D8C4` (pale linen) |
| Accent | `#7FA86A` (monstera) |
| Green | `#8FB262` (pothos) |
| Bright green | `#B5CC7A` (new growth) |
| Cyan | `#6FA893` (snake plant) |
| Red | `#C9714F` (terracotta) |
| Yellow | `#D4B062` (sun-gold) |
| Magenta | `#D98FA8` (Pink Princess) |

## VS Code Theme

A matching VS Code theme is in the `vscode/` folder.

```bash
ln -s ~/.config/omarchy/themes/greenhouse/vscode ~/.vscode/extensions/omarchy-greenhouse-theme
```

Then reload VS Code and pick **Omarchy Greenhouse** from the theme picker (`Ctrl + Shift + P` → Preferences: Color Theme).

| Element | Color |
|---------|-------|
| Keywords | Terracotta |
| Functions | Pink Princess pink |
| Strings | New-growth green |
| Types | Sun-gold |
| Properties | Snake-plant teal |
| Comments | Sage, italic |

## Obsidian

Omarchy themes Obsidian automatically. This theme adds leaf bullet points, a sprout before each top-level heading, green highlights, and dividers made of leaves.

## Discord

For [Vencord](https://vencord.dev) or Vesktop: copy `vencord.theme.css` into Vencord's themes folder, then turn it on under Settings → Themes.

```bash
cp ~/.config/omarchy/themes/greenhouse/vencord.theme.css ~/.config/Vencord/themes/greenhouse.theme.css
```

## Boot Screen

The theme ships a monstera logo for the boot and login screens. Turn it on from the Omarchy menu under Style → Unlock, or run:

```bash
omarchy-plymouth-set-by-theme greenhouse
```

## Extras

A houseplant lock screen with hanging pothos vines, a leaf on the current workspace, leaf volume and brightness popups, a green cursor, and a monstera screensaver are in the separate [Omarchy Greenhouse Extras](https://github.com/BBIEPavkov/omarchy-greenhouse-extras) repo.

![Greenhouse lock screen from the extras](lock-preview.png)

## Wallpapers

Cycle through them with `Super + Ctrl + Space` or `omarchy theme bg next`. Add your own to `~/.config/omarchy/backgrounds/greenhouse/`; that folder survives theme updates.

Photos from [Wikimedia Commons](https://commons.wikimedia.org), cropped and resized:

| File | Photographer | License |
|------|--------------|---------|
| `alocasia-dew.jpg` | [Isiwal](https://commons.wikimedia.org/wiki/File:Alocasia_clypeolata_Green_shield_Hybride_Botanischer_Garten_Linz_-0135.jpg) | CC BY-SA 3.0 AT |
| `anthurium-in-leaves.jpg` | [Sankar 1995](https://commons.wikimedia.org/wiki/File:Pink_Flamingo_Lily_Flower-_Shola_Gardens_-_Kotagiri.jpg) | CC BY-SA 4.0 |
| `begonia-blooms.jpg` | [Fjvelsen](https://commons.wikimedia.org/wiki/File:Begonia_maculata_2016.jpg) | CC BY-SA 4.0 |
| `blush-orchids.jpg` | [Dinkum](https://commons.wikimedia.org/wiki/File:Exposition_mille_et_une_orchid%C3%A9es_3.jpg) | CC0 |
| `caladium-hearts.jpg` | [Forest & Kim Starr](https://commons.wikimedia.org/wiki/File:Starr_071024-9740_Caladium_bicolor.jpg) | CC BY 3.0 |
| `caladium-pink-blush.jpg` | [Yercaud-elango](https://commons.wikimedia.org/wiki/File:Caladium_hortulanum_pink_blush-1-yercaud-salem-India.jpg) | CC BY-SA 4.0 |
| `calathea-lace-curtain.jpg` | [Горбунова М.С.](https://commons.wikimedia.org/wiki/File:Листья_на_солнце.jpg) | CC BY-SA 4.0 |
| `conservatory-of-flowers.jpg` | [Daderot](https://commons.wikimedia.org/wiki/File:Interior_view_-_Conservatory_of_Flowers_-_San_Francisco,_CA_-_DSC03127.JPG) | CC0 |
| `fern-frond-dark.jpg` | [Wingchi Poon](https://commons.wikimedia.org/wiki/File:Perpendicular_Fern_Leaves.JPG) | CC BY-SA 3.0 |
| `fern-in-shade.jpg` | [Mar Mkrtchyan](https://commons.wikimedia.org/wiki/File:Green_fern_leaf_in_Syunik.jpg) | CC0 |
| `fern-on-moss.jpg` | [Kieran Roy Powell](https://commons.wikimedia.org/wiki/File:Struthiopteris_spicant_Craig_Rhosyfelin_Frond.jpg) | CC BY 4.0 |
| `fiddlehead-unfurling.jpg` | [Wingchi Poon](https://commons.wikimedia.org/wiki/File:Unfurling_Spiral_Fiddlehead_Fern_Frond.JPG) | CC BY-SA 3.0 |
| `glasshouse-orchids.jpg` | [Ljiljana Nešić](https://commons.wikimedia.org/wiki/File:Jun`15._178_Orhideja.jpg) | CC BY-SA 4.0 |
| `hoya-blossoms.jpg` | [Marcus Cyron](https://commons.wikimedia.org/wiki/File:Hoya_carnosa_flowers_4.jpg) | CC BY-SA 3.0 |
| `hoya-stars.jpg` | [Muldoonsamuel](https://commons.wikimedia.org/wiki/File:Inflorescence_of_Hoya_Carnosa.jpg) | CC0 |
| `kew-green-leaves.jpg` | [Dinkum](https://commons.wikimedia.org/wiki/File:Green_leaves_-_Kew_Gardens.JPG) | CC0 |
| `kew-palm-house-dome.jpg` | [Daderot](https://commons.wikimedia.org/wiki/File:Palm_House_interior_-_Kew_Gardens,_London_-_DSC03493.jpg) | CC0 |
| `kew-palm-house-path.jpg` | [Daderot](https://commons.wikimedia.org/wiki/File:Interior,_Palm_House_-_Kew_Gardens,_London_-_DSC03555.jpg) | CC0 |
| `monstera-canopy.jpg` | [David J. Stang](https://commons.wikimedia.org/wiki/File:Monstera_deliciosa_25zz.jpg) | CC BY-SA 4.0 |
| `monstera-leaf.jpg` | [David J. Stang](https://commons.wikimedia.org/wiki/File:Monstera_deliciosa_27zz.jpg) | CC BY-SA 4.0 |
| `monstera-window.jpg` | [Smatu](https://commons.wikimedia.org/wiki/File:Monstera_deliciosa_DSC02605.jpg) | CC BY-SA 4.0 |
| `orchid-among-palms.jpg` | [brewbooks](https://commons.wikimedia.org/wiki/File:Flickr_-_brewbooks_-_Pink_phalaenopsis_Orchid_-_Hawaii_Tropical_Botanical_Garden_(1).jpg) | CC BY-SA 2.0 |
| `orchid-spray.jpg` | [domdomegg](https://commons.wikimedia.org/wiki/File:White_and_pink_orchid_on_black_background.JPG) | CC BY 4.0 |
| `pink-anthurium.jpg` | [Rameshng](https://commons.wikimedia.org/wiki/File:Pink_Anthurium_from_Kanthalloor_5953.JPG) | CC BY-SA 3.0 |
| `pink-calathea.jpg` | [Daderot](https://commons.wikimedia.org/wiki/File:Calathea_roseopicta_-_Begonia_House_-_Wellington_Botanic_Garden_-_Wellington,_NZ_-_DSC09404.jpg) | CC0 |
| `polka-dot-begonia.jpg` | [Krzysztof Ziarnek, Kenraiz](https://commons.wikimedia.org/wiki/File:Begonia_maculata_kz01.jpg) | CC BY-SA 4.0 |
| `rose-painted-calathea.jpg` | [Mokkie](https://commons.wikimedia.org/wiki/File:Rose_Painted_Calathea_(Calathea_roseopicta)_1.jpg) | CC BY-SA 3.0 |
| `schonbrunn-spiral-stair.jpg` | [Flocci Nivis](https://commons.wikimedia.org/wiki/File:20250501_Palm_House_Schönbrunn_02.jpg) | CC BY-SA 4.0 |
| `tree-fern-backlit.jpg` | [LBM1948](https://commons.wikimedia.org/wiki/File:Flora_Mount_Field_4.jpg) | CC BY-SA 4.0 |
| `tree-fern-night.jpg` | [LBM1948](https://commons.wikimedia.org/wiki/File:Flora_Mount_Field_2.jpg) | CC BY-SA 4.0 |
| `wave-hill-conservatory.jpg` | [Andre Carrotflower](https://commons.wikimedia.org/wiki/File:Wave_Hill_-_20220616_-_41_-_Marco_Polo_Stufano_Conservatory_(interior).jpg) | CC BY-SA 4.0 |
| `windowsill-houseplants.jpg` | [Tangopaso](https://commons.wikimedia.org/wiki/File:Shelf_at_the_bottom_of_a_window_for_growing_houseplants.jpg) | Public domain |

The boot logo is a recolor of [Monstera leaf](https://game-icons.net) by Delapouite, CC BY 3.0.
