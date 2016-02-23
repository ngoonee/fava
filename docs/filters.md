---
title: Filters
---

# Filters

There are four filters available in `fava`:

- **Time**: Filter entries by their date. This filter does some free-text
  recognition, which means you can enter terms like "Last Month".
- **Tags**: Filter entries to the ones having the tags selected. This filter is
  inclusive, meaning that if you select multiple tags entries with any of those
  tags will be filtered.
- **Account**: Filter entries by account, matching any entry where this account is part of.
- **Payee**: Filter entries by payee. This filter is, like the *Tags*-filter, inclusive.

If you select multiple filters (like *Tags* and *Time*), the subset of entries
matching both filters will be selected.