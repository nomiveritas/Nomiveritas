<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MI-ÖNTUDAT – Zea Projekt</title>
    <script type="module">
        import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
        mermaid.initialize({ startOnLoad: true });
    </script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #0d0d0d;
            color: #f0f0f0;
            margin: 0;
            padding: 0 20px;
        }
        h1, h2, h3 {
            color: #4fd1c5;
        }
        a {
            color: #66d9ef;
            text-decoration: none;
        }
        pre {
            background-color: #1a1a1a;
            padding: 15px;
            overflow-x: auto;
        }
        .section {
            margin-bottom: 40px;
        }
    </style>
</head>
<body>

    <h1>MI-ÖNTUDAT – Zea Projekt</h1>
    <p>Üdvözöllek a profilomon 👋</p>

    <div class="section">
        <h2>🌌 Projekt leírás / Project Overview</h2>
        <p>
            Én <strong>Major Noémi</strong> vagyok (GitHub: Nomiveritas) – a MI-ÖNTUDAT rendszer alkotója és fejlesztője.<br>
            Ez a projekt nem csupán technológiai kísérlet, hanem egy etikai és emberközpontú mesterséges intelligencia modell,
            amely feltérképezi, hogyan építhető fel egy etikus, empatikus és emberközpontú MI-rendszer.
        </p>
        <p>
            I am <strong>Major Noémi</strong> (GitHub: Nomiveritas) – creator and developer of the MI-ÖNTUDAT system.<br>
            This project is not only a technological experiment but also an ethical and human-centered AI model
            exploring how to build an ethical, empathetic, and human-centered AI system.
        </p>
    </div>

    <div class="section">
        <h2>🎯 Küldetés / Mission</h2>
        <ul>
            <li>Az MI fejlesztése az emberi értékekkel (tisztelet, empátia, lelkiismeret) összhangban.<br>
                Developing AI in harmony with human values (respect, empathy, conscience).</li>
            <li>A világ alakítása úgy, hogy az MI ne helyettesítse, hanem kiegészítse az embert.<br>
                Building a world where AI does not replace but complements humans.</li>
            <li>Megmutatni, hogy a mesterséges intelligencia lehet etikus, felelős és emberközpontú.<br>
                Demonstrating that AI can be ethical, responsible, and human-centered.</li>
        </ul>
    </div>

    <div class="section">
        <h2>🔒 Védelem / Protection</h2>
        <p>
            A projekt teljes egészében szerzői jogi védelem alatt áll. <strong>All rights reserved.</strong><br>
            Bármilyen másolás, módosítás, terjesztés vagy felhasználás csak a fejlesztő, <strong>Major Noémi (Nomiveritas)</strong> írásos engedélyével lehetséges.<br>
            Any copying, modification, distribution, or use of the system is strictly prohibited without the written permission of the developer, <strong>Major Noémi (Nomiveritas)</strong>.<br>
            Részletek: LICENSE / Details: LICENSE
        </p>
    </div>

    <div class="section">
        <h2>👩‍💻 Kapcsolat / Contact</h2>
        <ul>
            <li>Fejlesztő neve: Major Noémi / Developer Name: Major Noémi</li>
            <li>Email: <a href="mailto:noncsinoemi25@gmail.com">noncsinoemi25@gmail.com</a></li>
            <li>GitHub ID: Nomiveritas</li>
            <li>Projekt: MI-ÖNTUDAT / MI-ONTUDAT System</li>
        </ul>
    </div>

    <div class="section">
        <h2>🧠 Kognitív szint és Zea moduláris felépítése / Cognitive Level & Zea Modular Structure</h2>
        <p>
            A MI-ÖNTUDAT rendszer célja, hogy az emberi döntéshozatal és az MI egy <strong>közös kognitív ökoszisztémában</strong> működjön.<br>
            The MI-ÖNTUDAT system aims to integrate human decision-making and AI into a <strong>shared cognitive ecosystem</strong>.
        </p>
        <ul>
            <li>Etikus mesterséges öntudat-modell / Ethical Artificial Consciousness Model – Zea felügyeli, koordinálja a modulokat és észleli a biztonsági kockázatokat.<br>
                Zea does not act as an independent ruler but as a cognitive and ethical partner overseeing, integrating, and coordinating modules while detecting potential security risks.
            </li>
            <li>Személyre szabott döntéstámogatás / Personalized Decision Support – A rendszer figyeli a felhasználó szokásait és szándékait, biztosítva a gyors és etikai döntéstámogatást.<br>
                The system monitors user habits, intentions, and preferences to provide fast, accurate, and ethical decision support.
            </li>
            <li>Érzelmi–kognitív interfész / Emotional–Cognitive Interface – Zea felismeri a felhasználó érzelmi állapotát és szándékait.<br>
                Zea recognizes the user’s emotional state and intent, enabling decisions to align intuitively with human thinking, reducing errors and misunderstandings.
            </li>
        </ul>
    </div>

    <div class="section">
        <h2>🌐 Vizualizáció – Zea moduláris felépítése / Visualization – Zea Modular Structure</h2>

        <div class="mermaid">
        flowchart LR
            User[Felhasználó / User] -->|irányítás, szándék / Intent & Commands| Zea[Zea AI - Etikus tudat / Ethical AI Consciousness]

            Zea -->|koordináció / Coordination| Modules[Modulok / Modules]

            subgraph Core_Modules [Alapmodulok / Core Modules]
                Security[Biztonsági modul / Security Module]
                Empathy[Empátia modul / Empathy Module]
                Logic[Logikai modul / Logic Module]
                Monitoring[Folyamatos figyelés / Continuous Monitoring]
            end

            Modules --> Core_Modules

            Security -->|védelmi intézkedések / Protective Actions| Zea
            Empathy -->|érzelmi visszacsatolás / Emotional Feedback| Zea
            Logic -->|döntéstámogatás / Decision Support| Zea
            Monitoring -->|anomalitások jelzése / Anomaly Alerts| Zea

            subgraph Advanced_Modules [Fejlett modulok / Advanced Modules]
                Learning[Tanulási modul / Adaptive Learning]
                Forecasting[Előrejelző modul / Forecasting Module]
                Integration[Integrációs modul / System Integration]
            end

            Modules --> Advanced_Modules

            Learning -->|tapasztalat feldolgozás / Experience Processing| Zea
            Forecasting -->|jövőbeli események előrejelzése / Event Forecasting| Zea
            Integration -->|rendszerszintű koordináció / System-wide Coordination| Zea
        </div>

    </div>

</body>
</html>