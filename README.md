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
<!DOCTYPE html>
<html>
  <head>
  <div class="container">
  <div class="block">
    <h3>Bird1</h3>
    <img src="https://live.staticflickr.com/65535/51980751292_38b3d98b76_b.jpg">
    <p>Some text</p>
  </div>
  <div class="block">
    <h3>Bird2</h3>
    <img src="https://avatarfiles.alphacoders.com/121/121594.jpg">
    <p>Some text</p>
  </div>
  <div class="block">
   <h3>Bird3</h3>
    <img src="https://i.redd.it/o6f2qwf7ii1a1.jpg">
    <p>Some text</p>
  </div>
   <div class="block">
    <h3>Bird4</h3>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8-DIQByMTryoybuoHV-pz0HZb-_p6XbRogg&s">
    <p>Some text</p>
  </div>
</div>
  </body>
</html>
