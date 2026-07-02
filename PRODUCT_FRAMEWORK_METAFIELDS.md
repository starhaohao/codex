TRIIIPLE Studio Product Content Model

Live theme: FABRIC V2

Product link

- `custom.product_content`
- Type: `metaobject_reference`
- Definition: `triiiple_product_content`
- Assigned to active non-bundle products

Product content metaobject

- `name`
- `display_name`
- `signature_quote`
- `design_philosophy`
- `full_description`
- `at_a_glance`
- `why_youll_love_it`
- `designed_for`
- `pairs_well_with`
- `bundle_recommendation`
- `size_fit`
- `material_care`
- `size_guide`
- `fabric_profile`
- `fit_guide`
- `care_instructions`

Product content entries

- `v-brief`
- `w-boxer-trunk`
- `y-brief`
- `h-boxer-trunk`
- `x-brief`
- `x-boxer-trunk`
- `ed-t-shirt`
- `ed-sleeveless-top`
- `l-socks`

Size guide model

- Definition: `triiiple_size_guide`
- Entries: `underwear-xs-2xl`, `tops-s-2xl`, `socks-one-size`
- Each guide stores its introduction, dynamic column labels, size-row references, measurement instructions and fit note.

Size row model

- Definition: `triiiple_size_row`
- Fields: `size`, `value_1`, `value_2`, `value_3`, `value_4`
- Generic measurement fields allow underwear and tops to use different table structures without duplicating theme code.

Theme readers

- `blocks/product-title.liquid`
- `blocks/product-details-top.liquid`
- `blocks/product-size-chart.liquid`
- `sections/product-information.liquid`
- `sections/product-detail-story.liquid`

Bundles intentionally remain unlinked and use their native Shopify descriptions.
