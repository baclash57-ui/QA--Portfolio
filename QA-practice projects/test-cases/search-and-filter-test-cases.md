### Test Case ID

TC_SEARCH_001

### Test Case Title

Search returns relevant results for valid keyword

---

### Preconditions

- Website search functionality is available
- Products exist that match the search keyword
- User is on the homepage or any page with search access

---

### Test Steps

1. Locate the search input field
2. Enter a valid product-related keyword (e.g., Gummy bears)
3. Click on the search icon
4. Observe the search results page

---

### Expected Result

- Search results page is displayed
- Returned products are relevant to the entered keyword
- Product names or descriptions contain the keyword or closely related terms
- No unrelated products are shown
- Page loads without errors or broken layout

---

### Actual Result

- Search results page is displayed
- Returned products are relevant to the entered keyword
- Product names or descriptions contain the keyword or closely related terms
- No unrelated products are shown
- Page loads without errors or broken layout

---

### Status

 Pass



 ### Test Case ID

TC_FILTER_001

### Test Case Title

Filter updates search results correctly

---

### Preconditions

- Products listing page is displayed
- Multiple products are available in Products listing page
- Filter options (e.g., category, flavor, color, brand, price) are visible and selectable

---

### Test Steps

1. On the PLP, Perform a search using a valid keyword
2. Confirm multiple products are displayed in the results
3. Select more than one available filter option (e.g., Category or Flavor)
4. Observe the updated search results
5. Clear or reset the applied filter

---

### Expected Result

- Search results update according to the selected filter
- Only products matching the filter criteria are displayed
- Result count updates correctly (if shown)
- Filter state is clearly indicated in the UI
- Clearing the filter restores the original result set
- No page errors or layout issues occur

---

### Actual Result

- Search results update according to the selected filter
- The price filter changes after the user exceeds $299 when selecting filter options.
- Only products matching the filter criteria are displayed
- Result count updates correctly (if shown)
- Filter state is clearly indicated in the UI
- The user cannot clear the price filter

---

### Status

FAILED
