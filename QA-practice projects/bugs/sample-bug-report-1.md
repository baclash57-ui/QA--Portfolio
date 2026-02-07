**BUG ID: BR_UI_001**

## Bug Report: User Cannot Close "Follow on Shop" Feature

**Severity:** High (Functional Blocker)

**Reproducibility:** Always (5/5)

**Environment:** Laptop / Windows 11

---

### **Description**

Once the **"Follow on Shop"** feature is triggered/opened, it cannot be closed or dismissed. The interface does not respond to "Close" buttons, "X" icons, or clicking outside the area, effectively blocking the rest of the application.

### **Steps to Reproduce**

1. Open the practice site
2. In the homepage, scroll down to the footer section 
3. Click on the “follow on shop” button
4. Attempt to close the feature using the "Close" button, "X" icon, or by clicking away.
5. Attempt to navigate to other parts of the page behind the feature.

### **Expected Results**

The "Follow on Shop" feature should close immediately upon user request, returning the user to the previous state of the page.

### **Actual Results**

The feature remains on screen and cannot be dismissed. All other page functionality is blocked or inaccessible behind the feature overlay.

### **Workaround**

The user must **manually refresh the page** (F5) to clear the feature from the screen and regain control of the application.

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


