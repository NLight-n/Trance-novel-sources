# Trance Novel Sources Repository

Official community repository for **Trance App** novel scraping profiles and locator recipes.

This repository allows Trance users to discover, install, and update novel scraping profiles with one click (similar to Mihon's extension repository system for manga).

## Repository URL
Add this repository to your Trance App under **Browse → Novels → Repository Catalog → Edit URL**:
```
https://raw.githubusercontent.com/NLight-n/Trance-novel-sources/main/index.json
```
*(You can also paste the GitHub repository URL `https://github.com/NLight-n/Trance-novel-sources` directly into the app; it will automatically resolve).*

## Available Novel Sources
| Source | Domain | Description | Version |
|---|---|---|---|
| **Royal Road** | `royalroad.com` | Web fiction platform with responsive chapter index | v1 |
| **Scribble Hub** | `scribblehub.com` | Community portal with structured TOC | v1 |
| **Novel Updates** | `novelupdates.com` | Asian web novel release directory & translator hub | v1 |
| **Wuxiaworld** | `wuxiaworld.com` | Fantasy martial arts translations | v1 |
| **Novel Bin** | `novelbin.me` | Aggregator with comprehensive chapter catalog | v1 |
| **Light Novel World** | `lightnovelworld.co` | Modern responsive layout with clean reader container | v1 |
| **Dreamy Translations** | `dreamy-translations.com` | Semantic article reader with repeat links support | v1 |
| **BoxNovel** | `boxnovel.com` | Standard web novel aggregator layout | v1 |

## Contributing a New Source Recipe
To add a new novel source recipe:
1. Use the **Visual Picker** in Trance App to generate and test your selectors against the website.
2. Create a new recipe JSON file under `recipes/<source_name>.json`.
3. Add the source entry to `index.json`.
4. Open a Pull Request!
