## https://seirrab.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="styles.css">
<title>Image Filters</title>

<style>
.container {
display: grid;
grid-template-columns: repeat(2, 1fr);
gap: 10px;
}

.item img {
width: 100%;
height: auto;
}

.filter1 {
filter: grayscale(100%);
}

.filter2 {
filter: blur(5px);
}

.filter3 {
filter: sepia(100%);
}

.filter4 {
filter: brightness(1.5);
}
</head>
<body>
<div class="container">
<div class="item"><img src="image1.jpg" class="filter1"></div>
<div class="item"><img src="image2.jpg" class="filter2"></div>
<div class="item"><img src="image3.jpg" class="filter3"></div>
<div class="item"><img src="image4.jpg" class="filter4"></div>
</div>
</body>
</html>

