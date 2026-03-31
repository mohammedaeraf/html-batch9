# 🧩 HTML Assignment: Styled Box – Favourite Destination

## 🎯 Objective

Create a **simple styled content box** using:

* Bootstrap **Text Colors**
* Bootstrap **Background colors**
* Bootstrap **Spacing classes**
* Font Awesome Icons
* Google Fonts
* Image
* HTML tags (`h1`, `h2`, `p`)

---

## 🌍 Theme: Favourite Destination

![Image](https://visitmaldives.s3.amazonaws.com/yYjD0MoP/c/wzarde2i-large.jpg)

![Image](https://media.assettype.com/outlooktraveller/2024-11-26/nz1ggxa8/shutterstock2465464459-2.jpg?auto=format%2Ccompress\&enlarge=true\&fit=max\&h=675\&w=1200)

![Image](https://img.andrewprokos.com/BURJ-KHALIFA-DUBAI-CITY-VIEW-NIGHT-1991-1100PX.jpg)

![Image](https://www.visitdubai.com/-/media/images/app-card-images/sights-and-attractions/burj-khalifa-featured-card-600x910-opt.jpg?cx=0.5\&cy=0.5\&rev=c685db5f545446ddb85366e8e86139b1)

Create a box showing your **favourite place** (a place you love or want to visit).

---

## 📋 Task

Create **one styled box (`div`)** that looks like a card.

---

### 🔹 Inside the Box:

1. 🖼️ **Image of the destination**
2. 📝 **Title (`h2`)** → Name of the place
   *(Example: “Maldives”, “Dubai”, “Kashmir”)*
3. 📄 **Description (`p`)** →

   * Why you like this place
   * What makes it special
4. ⭐ **Font Awesome Icon**
   *(Example: plane, location, globe)*

---

## ⚙️ Requirements

### ✅ Must Use:

* Bootstrap classes:

  * Background: `bg-light`, `bg-info`, etc.
  * Text color: `text-primary`, `text-dark`, etc.
  * Spacing: `p-3`, `mt-4`, `mb-2`
* Google Font (any one)
* Font Awesome icon (at least one)
* One image

---

## 💻 Starter Code

```html id="favdest1"
<!DOCTYPE html>
<html>
<head>
    <title>Favourite Destination</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Montserrat', sans-serif;
        }
    </style>
</head>

<body>

    <div class="container">

        <!-- Styled Box -->
        <div class="bg-light p-3 mt-4">

            <!-- Image -->
            <img src="https://via.placeholder.com/300" class="img-fluid mb-3">

            <!-- Title -->
            <h2 class="text-primary">
                <i class="fa-solid fa-location-dot"></i> My Favourite Place
            </h2>

            <!-- Description -->
            <p class="text-secondary">
                This is my favourite destination because it is beautiful and peaceful.
            </p>

        </div>

    </div>

</body>
</html>
```

---

## 🎓 Bonus (Optional)

* Use `bg-info`, `bg-warning`, etc.
* Add more spacing (`p-4`, `mb-4`)
* Use a different icon (`fa-plane`, `fa-globe`)

If you want next, I can create:
✅ **Model answers for different destinations (Dubai, Kashmir, etc.)**
✅ **Common mistakes students make in this assignment**
✅ **Quick viva questions for evaluation**
