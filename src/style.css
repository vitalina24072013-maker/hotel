/* Общие стили с фоновым изображением */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Montserrat', sans-serif;
    background-image: url('placeholder-site-bg.jpg'); /* ЗДЕСЬ ВАША ФОНОВАЯ КАРТИНКА */
    background-size: cover;
    background-position: center;
    background-attachment: fixed; /* Эффект параллакса - фон остается на месте при прокрутке */
    background-repeat: no-repeat;
    color: #2c3e50;
    line-height: 1.6;
    position: relative;
    min-height: 100vh;
}

/* Полупрозрачный слой поверх фона для читаемости контента */
body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(250, 247, 242, 0.85); /* Светлый полупрозрачный слой */
    z-index: 0;
    pointer-events: none; /* Чтобы слой не мешал кликать по элементам */
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    position: relative;
    z-index: 1; /* Контент выше фонового слоя */
    background-color: rgba(255, 255, 255, 0.3); /* Легкая полупрозрачность для контейнера */
    backdrop-filter: blur(2px); /* Эффект легкого размытия фона за контентом */
    border-radius: 30px;
    box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
}

h1, h2, h3, h4 {
    font-family: 'Cormorant Garamond', serif;
    font-weight: 600;
    letter-spacing: 1px;
}

h1 {
    font-size: 3.5rem;
    color: #1e2b3a;
    margin-bottom: 10px;
    text-shadow: 0 2px 5px rgba(255, 255, 255, 0.5);
}

h2 {
    font-size: 2.5rem;
    text-align: center;
    margin: 50px 0 30px;
    position: relative;
    padding-bottom: 15px;
}

h2::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 2px;
    background-color: #b89b7b;
}

/* Шапка */
/* Hero Section с картинкой на фоне */
.hero-section {
    position: relative;
    width: 100%;
    min-height: 600px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    border-radius: 20px;
    margin-bottom: 20px;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

/* Затемнение для лучшей читаемости белого текста */
.hero-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.4); /* Легкое затемнение */
    z-index: 1;
}

/* Контент поверх затемнения */
.hero-content {
    position: relative;
    z-index: 2;
    max-width: 800px;
    padding: 40px 20px;
}

/* ВЕСЬ ТЕКСТ БЕЛЫЙ */
.hero-content h1 {
    font-size: 4rem;
    color: #FFFFFF; /* Белый */
    margin-bottom: 15px;
    text-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
    font-weight: 600;
}

.hero-content .location {
    font-size: 1.3rem;
    text-transform: uppercase;
    letter-spacing: 4px;
    color: #FFFFFF; /* Белый */
    margin-bottom: 20px;
    text-shadow: 0 2px 8px rgba(0, 0, 0, 0.5);
}

.hero-content .tagline {
    font-size: 2.2rem;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    color: #FFFFFF; /* Белый */
    margin-bottom: 10px;
    text-shadow: 0 2px 8px rgba(0, 0, 0, 0.5);
}

.hero-content .sub-tagline {
    font-size: 1.3rem;
    color: #FFFFFF; /* Белый */
    text-shadow: 0 2px 8px rgba(0, 0, 0, 0.5);
    opacity: 0.95;
}

/* Адаптивность для мобильных */
@media (max-width: 768px) {
    .hero-section {
        min-height: 450px;
    }
    
    .hero-content h1 {
        font-size: 2.8rem;
    }
    
    .hero-content .tagline {
        font-size: 1.8rem;
    }
    
    .hero-content .location {
        font-size: 1.1rem;
        letter-spacing: 3px;
    }
    
    .hero-content .sub-tagline {
        font-size: 1.1rem;
    }
}

.location {
    font-size: 1.2rem;
    text-transform: uppercase;
    letter-spacing: 3px;
    color: #b89b7b;
    margin-bottom: 20px;
}

.tagline {
    font-size: 1.8rem;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
}

.sub-tagline {
    font-size: 1.2rem;
    color: #7f8c8d;
    margin-top: 10px;
}

/* Карточки номеров */
.room-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 20px;
}

.room-card {
    background: rgba(255, 255, 255, 0.9);
    backdrop-filter: blur(5px);
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
    padding-bottom: 20px;
    border: 1px solid rgba(255, 255, 255, 0.5);
}

.room-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.15);
    background: rgba(255, 255, 255, 0.95);
}

.room-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    display: block;
}

.room-card h3 {
    font-size: 1.8rem;
    margin: 20px 20px 10px;
    color: #1e2b3a;
}

.capacity {
    color: #7f8c8d;
    font-size: 0.95rem;
    margin: 0 20px 10px;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.price {
    font-size: 1.6rem;
    font-weight: 600;
    color: #b89b7b;
    margin: 10px 20px 0;
}

.price span {
    font-size: 1rem;
    font-weight: 300;
    color: #95a5a6;
}

/* Спецпредложения */
.offers {
    background: rgba(255, 255, 255, 0.8);
    backdrop-filter: blur(5px);
    border-radius: 20px;
    padding: 30px;
    margin: 50px 0;
    box-shadow: 0 10px 30px rgba(0,0,0,0.05);
    border: 1px solid rgba(255, 255, 255, 0.5);
}

.offers-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-top: 30px;
}

.offer-item {
    text-align: center;
    padding: 20px;
    background: rgba(255, 255, 255, 0.6);
    border-radius: 15px;
    transition: all 0.3s ease;
}

.offer-item:hover {
    background: rgba(255, 255, 255, 0.9);
    transform: scale(1.02);
}

.offer-item img {
    width: 80px;
    height: 80px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 20px;
    border: 3px solid #b89b7b;
    padding: 5px;
    background: white;
}

.offer-item h4 {
    font-size: 1.4rem;
    margin-bottom: 15px;
    color: #1e2b3a;
}

.offer-item p {
    color: #5d6d7e;
    font-size: 0.95rem;
}

/* Пресса */
.press {
    text-align: center;
    padding: 40px 20px;
    background: rgba(234, 227, 218, 0.8);
    backdrop-filter: blur(5px);
    border-radius: 20px;
    margin: 40px 0;
    border: 1px solid rgba(255, 255, 255, 0.5);
}

.quote-text {
    font-size: 1.8rem;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    max-width: 800px;
    margin: 0 auto 20px;
    color: #2c3e50;
    text-shadow: 0 1px 3px rgba(255,255,255,0.5);
}

.quote-source {
    font-size: 1.1rem;
    font-weight: 500;
    color: #b89b7b;
    letter-spacing: 1px;
}

/* Футер и расположение */
.location-info {
    text-align: center;
    padding: 40px 20px;
    border-top: 1px solid rgba(184, 155, 123, 0.3);
    background: rgba(255, 255, 255, 0.5);
    backdrop-filter: blur(5px);
    border-radius: 20px;
    margin-top: 30px;
}

.location-info h3 {
    font-size: 1.8rem;
    margin-bottom: 30px;
}

.magazine-logos {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    margin: 30px 0;
    font-size: 1rem;
    color: #7f8c8d;
}

.magazine-logos span {
    padding: 8px 15px;
    background: rgba(240, 235, 229, 0.8);
    border-radius: 30px;
    border: 1px solid rgba(184, 155, 123, 0.3);
}

.copyright {
    margin-top: 40px;
    color: #95a5a6;
    font-size: 0.9rem;
}

/* Адаптивность */
@media (max-width: 768px) {
    h1 {
        font-size: 2.5rem;
    }
    
    h2 {
        font-size: 2rem;
    }
    
    .room-grid {
        grid-template-columns: 1fr;
    }
    
    .quote-text {
        font-size: 1.4rem;
    }
    
    .container {
        padding: 10px;
    }
}