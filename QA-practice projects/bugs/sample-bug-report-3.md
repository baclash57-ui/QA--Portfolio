**BUG ID:BR_FILTER_002**

## Bug Report: Price Filter Selection Cannot Be Cleared

**Severity:** High (Functional Issue)

**Reproducibility:** Always (5/5)

**Environment:** Laptop / Windows 11

---

### **Description**

Once a price range is selected in the product filter sidebar, the user is unable to reset or clear the filter. Clicking the "Clear" button, deselecting the range, or manually deleting the input values does not refresh the product list or remove the filter constraints.

### **Steps to Reproduce**

1. Open the Practice site
2. Click on any menu or submenu eg **Tootsie Candy**
3. On the products listing page, click on the filter option
4. scroll to the price section
5.  Adjust the max price range manually by tapping on the upward arrow inside the max prices range field.
6. Check the items in the product listing page
7. Close the filter option

### **Expected Results**

The price filter should be removed, the input fields/checkboxes should reset to their default state, and the product list should refresh to show all items regardless of price.

### **Actual Results**

The price filter remains active. The "Clear" action is ignored by the system, and the product list remains restricted to the previously selected price range.

### Additional Info

The price option remains even after refreshing the page
