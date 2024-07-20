Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="assets/images/lemon.jpeg" alt="Little Lemon Logo">
            <h1>LITTLE LEMON</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="promo">
            <h2>30% Off This Weekend</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
        </section>
        <section class="info">
            <div class="info-box">
                <img src="assets/images/rc1.jpg" alt="New Menu">
                <h3>Our New Menu</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="#">See our new menu</a>
            </div>
            <div class="info-box">
                <img src="assets/images/rc2.jpg" alt="Book a Table">
                <h3>Book a table</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="#">Book your table now</a>
            </div>
            <div class="info-box">
                <img src="assets/images/rc3.jpg" alt="Opening Hours">
                <h3>Opening Hours</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultricies.</p>
                <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
            </div>
        </section>
    </main>
    <footer>
        <img src="assets/images/lemon.jpeg" alt="Little Lemon Logo">
        <p>Copyright Little Lemon</p>
    </footer>
</body>
</html>
```

Style.css
```

body {
    font-family: Helvetica, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #eef0f2;
}

header {
    background-color: #fdfdfd;
    padding: 25px;
    border-bottom: 2px solid #bbb;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    display: flex;
    align-items: center;
}

.logo img {
    height: 45px;
    margin-right: 15px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #222;
    font-weight: bold;
}

.promo {
    background: url('assets/images/bg.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 110px 25px;
}

.promo h2 {
    font-size: 3.2em;
    margin: 0 0 25px;
}

.promo p {
    font-size: 1.3em;
    margin: 0 auto;
    max-width: 650px;
}

.info {
    display: flex;
    justify-content: space-around;
    padding: 30px 20px;
}

.info-box {
    background-color: #fdfdfd;
    padding: 25px;
    margin: 15px;
    border-radius: 12px;
    box-shadow: 0 0 12px rgba(0, 0, 0, 0.1);
    width: 30%;
    text-align: center;
}

.info-box img {
    max-width: 100%;
    border-radius: 12px;
}

.info-box h3 {
    font-size: 1.6em;
    margin: 25px 0 12px;
}

.info-box p {
    font-size: 1.1em;
    color: #444;
}

.info-box a {
    text-decoration: none;
    color: #0056b3;
    font-weight: bold;
    display: inline-block;
    margin-top: 15px;
}

footer {
    background-color: #fdfdfd;
    text-align: center;
    padding: 25px;
    border-top: 2px solid #bbb;
    margin-top: 25px;
}

footer img {
    height: 35px;
    margin-bottom: 12px;
}

footer p {
    margin: 0;
    font-size: 1em;
    color: #666;
}


```

OUTPUT
![Screenshot 2024-07-20 084853](https://github.com/user-attachments/assets/3f26507f-8770-4376-8539-611edf49241c)![Screenshot 2024-07-20 084955](https://github.com/user-attachments/assets/35c4956a-8ffd-4fff-b33a-f6d34d94fb0f)
