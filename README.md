<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Герои России — Саратовская область</title>
<style>
    :root {
        --primary-color: #0a2a52;
        --accent-color: #c8102e;
        --gold: #d9b45b;
        --card-bg: #ffffff;
        --text-color: #222222;
    }

    * { box-sizing: border-box; }

    body {
        font-family: 'Arial', sans-serif;
        margin: 0;
        color: var(--text-color);
        line-height: 1.6;
        min-height: 100vh;
        background-color: #0a1f3d;
        background-image:
            radial-gradient(ellipse 60% 40% at 15% 0%, rgba(217,180,91,0.22), transparent 70%),
            radial-gradient(ellipse 50% 35% at 90% 20%, rgba(200,16,46,0.18), transparent 70%),
            radial-gradient(ellipse 70% 50% at 50% 100%, rgba(70,130,210,0.25), transparent 70%),
            linear-gradient(160deg, #07172e 0%, #0f3260 50%, #123f78 100%);
        background-attachment: fixed;
        position: relative;
    }

    /* Сетка из точек поверх фона */
    body::before {
        content: '';
        position: fixed;
        inset: 0;
        background-image: radial-gradient(rgba(255,255,255,0.14) 1px, transparent 1.5px);
        background-size: 28px 28px;
        pointer-events: none;
        z-index: 0;
    }

    header, main, footer { position: relative; z-index: 1; }

    header {
        color: white;
        text-align: center;
        padding: 3rem 1rem 2.5rem;
    }

    header::after {
        content: '';
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
        width: min(420px, 70%);
        height: 4px;
        background: linear-gradient(90deg, #ffffff 0 33.3%, #1c57a5 33.3% 66.6%, var(--accent-color) 66.6% 100%);
        border-radius: 2px;
    }

    .star { width: 64px; height: 64px; margin-bottom: 0.75rem; filter: drop-shadow(0 0 12px rgba(217,180,91,0.6)); }

    h1 { margin: 0; font-size: 2.5rem; text-shadow: 0 2px 12px rgba(0,0,0,0.4); }

    .subtitle { font-size: 1.1rem; opacity: 0.9; margin-top: 0.5rem; }

    main { max-width: 1200px; margin: 0 auto; padding: 2.5rem 1rem; }

    .intro {
        text-align: center;
        max-width: 800px;
        margin: 0 auto 3rem;
        font-size: 1.1rem;
        background: rgba(255,255,255,0.96);
        padding: 2rem;
        border-radius: 10px;
        border-top: 4px solid var(--gold);
        box-shadow: 0 10px 30px rgba(0,0,0,0.25);
    }

    .heroes-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(min(350px, 100%), 1fr));
        gap: 2rem;
    }

    .hero-card {
        background: var(--card-bg);
        border-radius: 10px;
        padding: 1.5rem;
        box-shadow: 0 8px 24px rgba(0,0,0,0.25);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        border-left: 5px solid var(--accent-color);
    }

    .hero-card.memory { border-left-color: #555; }

    .hero-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 14px 34px rgba(0,0,0,0.35);
    }

    .hero-name { margin: 0 0 0.5rem; color: var(--primary-color); font-size: 1.4rem; }

    .hero-rank { color: #666; font-style: italic; margin-bottom: 1rem; }

    .hero-desc { font-size: 0.95rem; margin: 0; }

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

    .badge-memory { background-color: #444; }

    .program-section {
        background: linear-gradient(135deg, rgba(10,42,82,0.95), rgba(0,80,158,0.95));
        color: white;
        padding: 3rem 1rem;
        text-align: center;
        border-radius: 10px;
        margin-top: 3rem;
        border: 1px solid rgba(217,180,91,0.6);
        box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    }

    .program-section h2 { margin-top: 0; color: var(--gold); }

    footer {
        text-align: center;
        padding: 2rem;
        background-color: rgba(5,15,32,0.85);
        color: #cccccc;
        margin-top: 3rem;
        border-top: 3px solid var(--gold);
    }
</style>
</head>
<body>
    <header>
        <svg class="star" viewBox="0 0 100 100" aria-hidden="true">
            <polygon points="50,5 61,38 96,38 68,58 79,92 50,71 21,92 32,58 4,38 39,38" fill="#d9b45b" stroke="#f3dc9a" stroke-width="2" stroke-linejoin="round"/>
        </svg>
        <h1>Герои России Саратовской области</h1>
        <div class="subtitle">Участники специальной военной операции, удостоенные звания Героя Российской Федерации</div>
    </header>

    <main>
        <div class="intro">
            Земляки, проявившие мужество и героизм при исполнении воинского долга. Вечная память павшим и слава живым.
        </div>

        <section class="heroes-grid">
            <article class="hero-card">
                <h3 class="hero-name">Белоглазов Александр Михайлович</h3>
                <div class="hero-rank">Родился 29 января 1978 г. в с. Большой Карай</div>
                <p class="hero-desc">Командир 604-го центра специального назначения «Витязь». Золотая Звезда вручена 20 мая 2022 года. С 2024 года — начальник Саратовского военного института войск национальной гвардии.</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Болилая Людмила Вячеславовна</h3>
                <div class="hero-rank">Ефрейтор, уроженка г. Петровск</div>
                <p class="hero-desc">Первая женщина, удостоенная звания Героя России с начала специальной военной операции.</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Палазник Никита Андреевич</h3>
                <div class="hero-rank">Родился в 1995 г. в Саратове</div>
                <p class="hero-desc">Командир разведывательной группы Центра специального назначения Северо-Кавказского округа Росгвардии. Выпускник Саратовского военного института ВНГ (2017). Золотая Звезда вручена 27 марта 2023 года.</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Дудкин Тимур Юрьевич</h3>
                <div class="hero-rank">Майор, родился 6 марта 1996 г. в Саратове</div>
                <p class="hero-desc">Командир мотострелкового батальона. В зоне СВО с мая 2022 года. Золотая Звезда вручена 31 мая 2023 года; награждён двумя орденами Мужества и медалью «За отвагу».</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card memory">
                <h3 class="hero-name">Потапов Александр Игоревич</h3>
                <div class="hero-rank">23.11.1989 — 30.08.2022, г. Шиханы</div>
                <p class="hero-desc">Офицер (инструктор) группы 604-го центра специального назначения «Витязь». Звание присвоено посмертно; в Шиханах на Аллее Славы установлен его бюст.</p>
                <span class="badge badge-memory">Посмертно</span>
            </article>

            <article class="hero-card memory">
                <h3 class="hero-name">Аксенов Александр Александрович</h3>
                <div class="hero-rank">Подполковник, 24.06.1984 — 17.09.2022</div>
                <p class="hero-desc">Родился в Саратове. Заместитель командира 18-й бригады армейской авиации по военно-политической работе, военный лётчик 1-го класса. Выпускник Сызранского высшего военного авиационного училища. В Саратове открыт мурал в его честь.</p>
                <span class="badge badge-memory">Посмертно</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Демьяненко Сергей Иванович</h3>
                <div class="hero-rank">Полковник, заслуженный военный лётчик РФ</div>
                <p class="hero-desc">Начальник и старший лётчик-испытатель 1338-го испытательного центра. Выполнял задачи на Северном Кавказе, в Сирии и в зоне СВО. Герой Российской Федерации (2022).</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card memory">
                <h3 class="hero-name">Назаров Сергей Сергеевич</h3>
                <div class="hero-rank">06.03.1983 — 04.12.2023, г. Хвалынск</div>
                <p class="hero-desc">Командир штурмовой роты 15-й отдельной мотострелковой бригады. Погиб в Красногоровке (Донецкая область). Звание присвоено указом № 240 от 8 апреля 2024 года посмертно.</p>
                <span class="badge badge-memory">Посмертно</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Султанов Арслан Булатович</h3>
                <div class="hero-rank">Родился 25 декабря 1999 г. в Новоузенске</div>
                <p class="hero-desc">Десантник 56-й гвардейской десантно-штурмовой бригады. Награждён медалями Суворова и Жукова. В августе 2023 года тяжело ранен; звание присвоено указом от 30 декабря 2023 года.</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card memory">
                <h3 class="hero-name">Максюков Алексей Вячеславович</h3>
                <div class="hero-rank">Ефрейтор, 31.12.1994 — 30.04.2024</div>
                <p class="hero-desc">Родился в селе Кирово Краснокутского района. Стрелок десантно-штурмового отделения. Участвовал в боевых действиях в Сирии и Нагорном Карабахе, затем в СВО. Погиб при выполнении боевого задания; звание присвоено посмертно.</p>
                <span class="badge badge-memory">Посмертно</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Джумагалиев Мирлан Андреевич</h3>
                <div class="hero-rank">Подполковник, уроженец пос. Нива Питерского района</div>
                <p class="hero-desc">Выпускник Саратовской государственной юридической академии. Участник операции в Сирии, с февраля 2022 года — в СВО. Заместитель командира 30-й отдельной гвардейской мотострелковой бригады. Звание Героя присвоено в 2024 году.</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Филоненко Андрей Михайлович</h3>
                <div class="hero-rank">Майор Росгвардии, позывной «Артист», уроженец Калининского района</div>
                <p class="hero-desc">В СВО с февраля 2022 года. Звание присвоено за мужество при выполнении боевых задач и отражении нападения на приграничные районы Курской области. Награждён медалью «За отвагу» и орденами Мужества.</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Казаков Алексей</h3>
                <div class="hero-rank">Гвардии капитан, уроженец Федоровского района</div>
                <p class="hero-desc">Командир разведывательного батальона, в зоне СВО с первых дней. Награду вручил министр обороны Андрей Белоусов. Награждён орденом Мужества и двумя медалями «За отвагу».</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card">
                <h3 class="hero-name">Кудряшов Виталий Вадимович</h3>
                <div class="hero-rank">14.06.2002 — 27.03.2026, г. Балаково</div>
                <p class="hero-desc">Позывной «Фанат». Вдвоём с напарником взял в плен семерых солдат противника и долгое время удерживал населённый пункт. Звание присвоено указом от 12 декабря 2025 года; Золотая Звезда вручена в госпитале.</p>
                <span class="badge">Герой России</span>
            </article>

            <article class="hero-card memory">
                <h3 class="hero-name">Мамкин Андрей Сергеевич</h3>
                <div class="hero-rank">Капитан, родился 3 мая 1996 г. в Пугачёве</div>
                <p class="hero-desc">Командир вертолёта-инструктор, лётчик Ка-52М, позывной «Саратов». Дважды награждён орденом Мужества. Погиб в 2026 году в зоне СВО; звание Героя России присвоено посмертно.</p>
                <span class="badge badge-memory">Посмертно</span>
            </article>
        </section>

        <section class="program-section">
            <h2>Наши герои</h2>
            <p>Региональная программа для участников СВО: обучение и работа в органах власти Саратовской области.</p>
        </section>
    </main>

    <footer>
        <p>Саратовская область · Слава героям!</p>
    </footer>
</body>
</html>
