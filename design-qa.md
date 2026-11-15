# Design QA

Source: https://englishelm.com/ (desktop browser capture, 1470 × 737 CSS pixels)
Implementation: http://127.0.0.1:5174/ (desktop browser capture, 1470 × 737 CSS pixels)
State: home page, top of page. Both images were inspected at the same browser viewport; a combined comparison image was not captured.

## Findings
- [P1] The source has a large catalog, category menus, customer accounts, and live Shopify checkout; this local prototype contains four products and a preview-only checkout. A commerce backend, product catalog, payment provider and merchant configuration are required for a production equivalent.
- [P2] Navigation icons, typography, menu behavior, and some lower-page sections differ from the source. The requested company and shipping changes are intentional content differences.
- [P2] Mobile source and implementation have not been compared at the requested 390 × 844 viewport.
- Fonts and typography: approximate serif and Arial fallbacks; source font not confirmed.
- Spacing and layout: desktop hero grid proportions and imagery are similar, but not measured or fully compared.
- Colors: neutral background and header approximated.
- Image quality: source homepage and product images downloaded locally; source rights must be confirmed.
- Copy: shipping and company information intentionally changed; policies are provisional and require merchant-specific review.

## Checks
- Desktop product, cart quantity, guest checkout preview, and $15 flat shipping checked in browser.
- Production build and Sites worker tests passed.
- Browser console and combined visual comparison were not checked.

final result: blocked
