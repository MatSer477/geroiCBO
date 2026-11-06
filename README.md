<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Герои СВО Саратовской области</title>
    <style>
        :root {
            --primary-color: #003366; /* Темно-синий */
            --accent-color: #B22234;  /* Красный акцент */
            --bg-color: #F5F5F5;
            --text-color: #333333;
            --card-bg: #FFFFFF;
        }

        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        header {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            position: relative;
        }

        header::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background-color: var(--accent-color);
        }

        h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .subtitle {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-top: 0.5rem;
        }

        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem 1rem;
        }

        .intro {
            text-align: center;
            max-width: 800px;
            margin: 0 auto 3rem;
            font-size: 1.1rem;
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        .heroes-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .hero-card {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-left: 5px solid var(--accent-color);
        }

        .hero-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.12);
        }

        .hero-name {
            margin: 0 0 0.5rem;
            color: var(--primary-color);
            font-size: 1.4rem;
        }

        .hero-rank {
            color: #666;
            font-style: italic;
            margin-bottom: 1rem;
        }

        .hero-desc {
            font-size: 0.95rem;
        }

        .badge {
            display: inline-block;
            background-color: var(--accent-color);
            color: white;
            padding: 0.2rem 0.6rem;
            border-radius: 4px;
            font-size: 0.8rem;
            font-weight: bold;
            margin-top: 1rem;
        }

        .program-section {
            background: linear-gradient(135deg, var(--primary-color), #00509e);
            color: white;
            padding: 3rem 1rem;
            text-align: center;
            border-radius: 10px;
            margin-top: 3rem;
        }

        .program-section h2 {
            margin-top: 0;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--primary-color);
            color: #cccccc;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Герои СВО</h1>
    <div class="subtitle">Саратовская область</div>
</header>

<main>
    <section class="intro">
        <p>Этот проект посвящен жителям Саратовской области, проявившим мужество и героизм в ходе специальной военной операции. Мы помним и гордимся подвигами наших земляков, которые защищают интересы России.</p>
    </section>

    <section class="heroes-grid">
        <!-- Карточка 1: Роман Моисеев -->
        <article class="hero-card">
            <h2 class="hero-name">Роман Моисеев</h2>
            <div class="hero-rank">Младший сержант, санитар-инструктор</div>
            <p class="hero-desc">Рискуя собой под минометным огнем и атаками беспилотников, добрался до раненого сослуживца, оказал ему первую помощь и организовал эвакуацию в полевой госпиталь.</p>
            <span class="badge">Представлен к награде</span>
        </article>

        <!-- Карточка 2: Руслан Бекмуратов -->
        <article class="hero-card">
            <h2 class="hero-name">Руслан Бекмуратов</h2>
            <div class="hero-rank">Гвардии младший сержант</div>
            <p class="hero-desc">Вез боеприпасы на передовую, когда заметил приближение вражеских FPV-дронов. Меткими выстрелами уничтожил коптеры, которые сдетонировали в воздухе. Доставив снаряды, эвакуировал трех раненых.</p>
            <span class="badge">Героический поступок</span>
        </article>

        <!-- Карточка 3: Алексей Ефремов -->
        <article class="hero-card">
            <h2 class="hero-name">Алексей Ефремов</h2>
            <div class="hero-rank">Гвардии лейтенант</div>
            <p class="hero-desc">С первых дней спецоперации принимал участие в активных боевых действиях. Своевременно оказывал медицинскую помощь раненым товарищам, чем спас жизни наших военнослужащих.</p>
            <span class="badge">Орден Мужества</span>
        </article>
    </section>

    <section class="program-section">
        <h2>Региональная программа «Наши герои»</h2>
        <p>В Саратовской области запущен проект для участников СВО. Бойцы с управленческим опытом и высшим образованием могут пройти обучение, стажировку в органах власти и войти в кадровый резерв региона.</p>
        <p><em>«С сегодняшнего дня стартует регистрация в региональном аналоге федерального проекта "Время героев"»</em>, — губернатор Роман Бусаргин.</p>
    </section>
</main>

<footer>
    <p>&copy; 2026 Герои Саратовской области. Вечная память и слава.</p>
</footer>

</body>
</html>
