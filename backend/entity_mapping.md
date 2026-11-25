## Product
- id
- name
- description
- price
- count

## Bill
- id
- item_ids (temporary; normalize into a join/line-items table later)
- total (snapshot at purchase time so later price edits don't rewrite old bills)
- bill_date
