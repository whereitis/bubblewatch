# bubblewatch

Which stage of a technology mania are we in? A daily reading of Edward Chancellor's bubble signals, grouped by the
stages of a mania, built by a script from public data (FRED, Yahoo Finance, SEC EDGAR, Cboe, FINRA, DefiLlama,
World Bank).

Page: https://whereitis.github.io/bubblewatch/

A gauge, not advice. It says where we stand, never what to do. Nothing here is investment advice.

This repository holds only the built page (`docs/index.html` and `docs/data.json`). A scheduled job publishes it
after each daily run whose page passes its checks. A run that fails leaves the last good page in place.
