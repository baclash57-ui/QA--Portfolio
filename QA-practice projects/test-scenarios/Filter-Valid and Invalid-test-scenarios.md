**Valid Scenarios:**

- Apply a price filter and verify only products within the selected range are displayed.
- Filter by price, availability, colors, etc  and verify results match the criteria.
- Combine multiple filters and verify results are correct.
- Clear filters and verify all products are displayed again.

**Invalid Scenarios:**

- Apply conflicting filters (e.g., price below $50 and above $1,000) and verify proper messaging or empty results.
- Select invalid filter values (if possible via URL manipulation) and ensure the system doesn't crash.
