# 🏝️ Maldives Travel Data

Open dataset of Maldives atolls, islands, resorts, and travel information in JSON & CSV formats.

> Data curated by [YEIN Maldives](https://yein.cn) — the Chinese-language Maldives travel guide with an [island selector tool](https://yein.cn/selector) to help you find your perfect resort.

## Contents

- `data/atolls.json` — All 26 atolls with geographic coordinates
- `data/resorts.json` — Resort islands with pricing tiers, star ratings, transfer types, and features
- `data/activities.json` — Popular activities (snorkeling, diving, fishing, spa, etc.)
- `data/budget-reference.csv` — Budget reference table by resort tier

## Data Schema

### resorts.json

```json
{
  "name": "Resort Name",
  "atoll": "North Malé Atoll",
  "stars": 5,
  "priceRange": "$$$$",
  "transferType": "speedboat|seaplane|domestic-flight",
  "transferTime": "25 min",
  "houseReef": true,
  "allInclusive": false,
  "waterVilla": true,
  "familyFriendly": true,
  "honeymooners": true,
  "snorkeling": "A",
  "diving": "A",
  "website": "https://example.com"
}
```

## Usage

This data is free to use for travel apps, research, and content creation. If you use it, a link back to [yein.cn](https://yein.cn) is appreciated.

## Tools

Looking for a Maldives island selector? Try the [YEIN Island Selector](https://yein.cn/selector) — filter by budget, transfer type, activities, and more.

## Contributing

PRs welcome! If you have updated resort data or want to add new fields, please open a pull request.

## License

[CC0 1.0 Universal](LICENSE) — Public Domain
