# Product Card Material and Bundle Subtitles

## Approved display

Single product:

```text
X Brief
COTTON SPANDEX
```

Bundle:

```text
Bundle display name
X Brief · Y Brief · Z Brief
```

## Implementation

- Use `custom.product_content.display_name` for the first line, with the product title as fallback.
- Remove the current material name from the first line so `X TransDRY® Brief` displays as `X Brief`.
- For a single product, show only the uppercase value of `theme.cutline` on the second line.
- Preserve the registered material name as `TransDRY®` with its brand casing and symbol.
- For a bundle, show the display names of products in `theme.bundle` and `theme.bundle_list`.
- Separate multiple included design names with a middle dot (`·`), not a comma.
- Apply the format to collection cards and predictive-search cards.
- Preserve existing styling, layout, pricing, and badges.
