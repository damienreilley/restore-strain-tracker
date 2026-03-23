# Restore Fishtown — Pain/Sleep Strain Tracker

Interactive medical marijuana strain finder for [Restore Dispensaries Fishtown](https://restoredispensaries.com/fishtown-menu/) (Philadelphia, PA).

## Features
- 650+ Flower & Vape products from live dispensary menu
- Personalized pain/sleep scoring based on terpene profiles
- Sort, filter, search across all products
- Track favorites, tried strains, ratings, and notes (localStorage)
- Visual terpene profile bars per strain
- Export to CSV

## Scoring Formula
```
Score = Caryophyllene × 3.0 (anti-inflammatory, pain relief)
      + Limonene     × 2.5 (anti-anxiety, mood elevation)
      + Linalool     × 1.5 (anxiolytic, calming)
      + Myrcene      × 0.5 (low weight — personalized)
```

## Data Source
Menu data from [Restore Dispensaries](https://restoredispensaries.com/) via Hytiva API.

Built with Claude AI.
