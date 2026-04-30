# 🧩 Assignment: Bootstrap Grid (MD Breakpoint)

## 🎯 Objective

Learn how to use Bootstrap Grid with the **`md` (medium devices)** breakpoint to control layout behavior.

---

## 📘 Task 1: Equal Columns (MD Breakpoint)

### 📝 Instructions:

1. Create a file named `grid-md.html`
2. Add Bootstrap CDN
3. Create a layout with **3 equal columns**

### 💡 Requirements:

* Use:

  * `.container`
  * `.row`
  * `.col-md`
* Add background colors and padding
* Add text inside each column (Column 1, Column 2, Column 3)

### 🎯 Expected Behavior:

* On **medium screens and above (≥768px)** → 3 equal columns
* On **small screens (less than 768px)** → columns stack vertically

---

## 📘 Task 2: Unequal Columns (MD Breakpoint)

### 📝 Instructions:

Create another row with **different column sizes**

### 💡 Requirements:

* Use:

  * `col-md-6`
  * `col-md-3`
  * `col-md-3`
* Add different background colors

### 🎯 Expected Behavior:

* On **medium screens and above**:

  * 1st column → 50% width
  * 2nd column → 25% width
  * 3rd column → 25% width
* On **small screens**:

  * All columns stack

---

## 📦 Starter Code

```html id="9f3k2p"
<!DOCTYPE html>
<html>
<head>
    <title>Bootstrap Grid MD Assignment</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<div class="container mt-4">

    <!-- Task 1 -->
    <h4>Task 1: Equal Columns</h4>
    <div class="row mb-3">
        <div class="col-md-x bg-primary text-white p-3">Column 1</div>
        <div class="col-md-x bg-success text-white p-3">Column 2</div>
        <div class="col-md-x bg-warning text-dark p-3">Column 3</div>
    </div>

    <!-- Task 2 -->
    <h4>Task 2: Unequal Columns</h4>
    <div class="row">
        <div class="col-md-x bg-info text-white p-3">Column 1</div>
        <div class="col-md-x bg-danger text-white p-3">Column 2</div>
        <div class="col-md-x bg-secondary text-white p-3">Column 3</div>
    </div>

    <div class="row">
        <h2>Note - Replace 'x' with appropriate column sizes</h2>
    </div>

</div>

</body>
</html>
```

---

## 📝 Submission Requirements

* Use only `col-md` classes (no `col-sm`, `col-lg`)
* Proper spacing and colors
* Clean structure using `.container` and `.row`