* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, Helvetica, sans-serif;
    color: #111;
    background: #f8f7f3;
}


/* HERO */

.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding: 80px 10%;
    gap: 60px;
}


.hero-text {
    flex: 1;
}


.hero h1 {
    font-size: 20px;
    letter-spacing: 4px;
    text-transform: uppercase;
    margin-bottom: 40px;
}


.hero h2 {
    font-size: 56px;
    line-height: 1.1;
    margin-bottom: 25px;
}


.hero p {
    font-size: 18px;
    line-height: 1.6;
    max-width: 450px;
}


.hero-image {
    flex: 1;
}


.hero-image img {
    width: 100%;
    border-radius: 8px;
}


/* PRODUCTS */

.products {
    padding: 100px 10%;
}


.products > h2 {
    font-size: 42px;
    margin-bottom: 60px;
}


.product-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 50px;
}


.card img {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    margin-bottom: 20px;
}


.card h3 {
    font-size: 24px;
    margin-bottom: 10px;
}


.card p {
    line-height: 1.5;
    color: #555;
}


/* CONTACT */

.contact {
    text-align: center;
    padding: 120px 10%;
}


.contact h2 {
    font-size: 42px;
    margin-bottom: 20px;
}


.contact p {
    margin-bottom: 40px;
}


.buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
}


.button {
    padding: 15px 35px;
    background: #111;
    color: white;
    text-decoration: none;
}


footer {
    margin-top: 80px;
    font-size: 14px;
    color: #666;
}


/* MOBILE */

@media(max-width:768px){

    .hero {
        flex-direction: column;
        padding: 50px 6%;
    }


    .hero h2 {
        font-size: 38px;
    }


    .product-grid {
        grid-template-columns: 1fr;
    }

}
