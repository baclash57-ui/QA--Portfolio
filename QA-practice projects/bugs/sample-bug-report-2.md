**BUG ID: BR_FILTER_001**

## Bug Report: Item Count Decreases Incorrectly When Price Filter Exceeds $300

**Severity:** High (Data Integrity / Functional Bug)

**Reproducibility:** Always (5/5)

**Environment:** Laptop / Windows 11

---

### **Description**

There is a logic discrepancy in the price filter results. When a user sets the maximum price filter above **$300**, the item count (the number of products found) decreases or adjusts lower, even though a higher price cap should theoretically include more products (or at least the same amount).

### **Steps to Reproduce**

1. Open the Practice site
2. Click on any menu or submenu eg **Tootsie Candy**
3. On the products listing page, click on the filter option
4. scroll to the price section
5.  Adjust the max price range to (>$120)
6. Observe the filter behaviour

### **Expected Results**

Increasing the maximum price limit should either **increase** the price or remain the same.

### **Actual Results**

The price count adjusts to lower figures.
