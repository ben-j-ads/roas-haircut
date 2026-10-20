# ROAS Haircut

How much of your platform's reported ROAS has to be real for the ads to pay? Enter reported ROAS and your contribution margin, and get the share of reported sales that must be truly incremental to break even, with no assumption about what the real share is.

Open `index.html` in any browser. No build step and no dependencies.

- **Verdict:** `losing money`, `fragile`, `depends on incrementality` or `comfortable`, from the incremental share needed to break even (cut-offs at 100%, 75% and 40%, listed on the page).
- **Shows:** breakeven ROAS (1 / margin), the incremental share needed, and, at your own guess of the true share, incremental ROAS and profit per $100 and per month. A table runs the share from 100% down to 20%.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

This does not measure incrementality. It tells you how much you need, and a holdout or geo test tells you how much you have (see holdout-sizer). It deliberately uses no published "typical haircut", because none of the figures found for this were from a source that could be traced.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
