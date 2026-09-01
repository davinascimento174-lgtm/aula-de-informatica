# aula-de-informatica

# MEU PORTFOLIO - CURSO TECNICO EM INFORMATICA

# sobre mim 
sou uma pessoa muito decidida gosto de cozinhar tenho 1,80 de altura,tenho cabelo cacheado e sou bonito
 MEU NOME Davi ferreira do nascimento

## O QUE EU FAÇO estudo 
faço curso de (ti) ciencias da informaçao e estudo emtegral
## o que estou estudando
- html e css
- lógica de programação
- arquitetura e manutenção de computadores
- planejamento de carreira

## projetos

aqui vou guardar os projetos e exercicios desemvolvidos durante o curso

## hard skills
(competencias tecnicas)
-gosto de escrever
-gosto de fazer slids e fazer planilhas e estou desposto a melhorar cada vez mais no núcleu escolar
-estou  me proficionalizando em (ti) tecnologia da informaçao

## soft skillis
-(habilidades e competencias)
-gosto de trabalho em grupo 
-gosto de compartilhar serviço
-gosto de liderar pessoas
-gosto de resolver comflitos de um forma pacifica
-amo conhecer pessoas novas

## interesses
- gosto de animais, gosto de cuidar da minha casa, tenho interesse em livros, gosto de historia, e sou muito estudioso
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
    <title>Física Quântica | Moema Távora & Instituto Ecolocar</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,500;14..32,600;14..32,700;14..32,800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* ===== RESET & BASE ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: #0a0e1a;
            background-image: 
                radial-gradient(ellipse at 10% 20%, #141b33 0%, #070a14 100%),
                radial-gradient(ellipse at 90% 80%, #1a1040 0%, transparent 60%);
            color: #e8edf5;
            line-height: 1.6;
            padding: 12px;
            min-height: 100vh;
            display: flex;
            align-items: flex-start;
            justify-content: center;
        }

        .container {
            max-width: 100%;
            width: 100%;
            background: rgba(12, 18, 38, 0.88);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border-radius: 32px;
            border: 1px solid rgba(100, 180, 255, 0.10);
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.8), inset 0 1px 0 rgba(255, 255, 255, 0.03);
            padding: 16px 16px 24px;
            transition: all 0.3s;
        }

        /* ===== PARTÍCULAS DE FUNDO ===== */
        .particle-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
            overflow: hidden;
        }

        .particle-bg span {
            position: absolute;
            width: 3px;
            height: 3px;
            background: rgba(100, 200, 255, 0.12);
            border-radius: 50%;
            animation: float-particle 20s infinite linear;
        }

        .particle-bg span:nth-child(1) { left: 5%; animation-duration: 18s; animation-delay: 0s; width: 4px; height: 4px; }
        .particle-bg span:nth-child(2) { left: 15%; animation-duration: 22s; animation-delay: 2s; width: 6px; height: 6px; }
        .particle-bg span:nth-child(3) { left: 30%; animation-duration: 16s; animation-delay: 4s; }
        .particle-bg span:nth-child(4) { left: 45%; animation-duration: 24s; animation-delay: 1s; width: 8px; height: 8px; }
        .particle-bg span:nth-child(5) { left: 58%; animation-duration: 19s; animation-delay: 3s; }
        .particle-bg span:nth-child(6) { left: 72%; animation-duration: 21s; animation-delay: 5s; width: 5px; height: 5px; }
        .particle-bg span:nth-child(7) { left: 85%; animation-duration: 17s; animation-delay: 2s; }
        .particle-bg span:nth-child(8) { left: 95%; animation-duration: 23s; animation-delay: 4s; width: 7px; height: 7px; }

        @keyframes float-particle {
            0% { transform: translateY(100vh) scale(0); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-10vh) scale(1); opacity: 0; }
        }

        /* ===== TOP BAR ===== */
        .top-bar {
            display: flex;
            flex-direction: column;
            gap: 8px;
            border-bottom: 1px solid rgba(100, 180, 255, 0.08);
            padding-bottom: 14px;
            margin-bottom: 18px;
        }

        .logo h1 {
            font-size: 1.5rem;
            font-weight: 800;
            letter-spacing: -0.5px;
            background: linear-gradient(135deg, #7ec8ff, #a78bfa, #7ec8ff);
            background-size: 200% 200%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shimmer 5s ease-in-out infinite;
            display: flex;
            align-items: center;
            gap: 10px;
            flex-wrap: wrap;
        }

        @keyframes shimmer {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .logo h1 i {
            -webkit-text-fill-color: initial;
            color: #7ec8ff;
            font-size: 1.6rem;
        }

        .logo .sub {
            font-size: 0.75rem;
            font-weight: 500;
            color: #8ab4d6;
            background: rgba(100, 180, 255, 0.06);
            display: inline-flex;
            align-items: center;
            gap: 6px;
            padding: 3px 16px;
            border-radius: 40px;
            border: 1px solid rgba(100, 180, 255, 0.06);
            width: fit-content;
            -webkit-text-fill-color: initial;
            color: #8ab4d6;
        }

        .school-badge {
            background: rgba(100, 180, 255, 0.05);
            padding: 6px 16px;
            border-radius: 60px;
            font-weight: 600;
            font-size: 0.75rem;
            color: #8fcbff;
            border: 1px solid rgba(100, 180, 255, 0.06);
            display: inline-flex;
            align-items: center;
            gap: 6px;
            width: fit-content;
        }

        .school-badge i {
            color: #7ec8ff;
        }

        /* ===== NAVEGAÇÃO ===== */
        .nav-links {
            display: flex;
            flex-wrap: nowrap;
            overflow-x: auto;
            gap: 4px 16px;
            margin: 10px 0 14px;
            padding: 4px 0 10px;
            border-bottom: 1px solid rgba(100, 180, 255, 0.05);
            -webkit-overflow-scrolling: touch;
            scrollbar-width: none;
        }

        .nav-links::-webkit-scrollbar {
            display: none;
        }

        .nav-links a {
            text-decoration: none;
            font-weight: 500;
            color: #aac8e6;
            padding: 6px 4px 8px;
            border-bottom: 2px solid transparent;
            transition: 0.2s;
            font-size: 0.85rem;
            white-space: nowrap;
            display: flex;
            align-items: center;
            gap: 5px;
            flex-shrink: 0;
        }

        .nav-links a i {
            font-size: 0.8rem;
            color: #6a9fc7;
        }

        .nav-links a:hover, .nav-links a:active {
            border-bottom-color: #7ec8ff;
            color: #d6edff;
        }

        /* ===== HERO ===== */
        .hero-card {
            background: linear-gradient(145deg, rgba(40, 70, 120, 0.20), rgba(20, 40, 80, 0.10));
            border-radius: 24px;
            padding: 20px 18px 18px;
            margin-bottom: 20px;
            border: 1px solid rgba(100, 180, 255, 0.05);
            backdrop-filter: blur(4px);
        }

        .hero-card h2 {
            font-size: 1.3rem;
            font-weight: 700;
            color: #b8dfff;
            display: flex;
            align-items: center;
            gap: 10px;
            flex-wrap: wrap;
        }

        .hero-card h2 i {
            color: #7ec8ff;
            font-size: 1.4rem;
        }

        .hero-card p {
            font-size: 0.95rem;
            margin-top: 6px;
            color: #b8d0e6;
            font-weight: 400;
        }

        .hero-card .highlight {
            color: #a78bfa;
            font-weight: 600;
        }

        /* ===== GRID PRINCIPAL ===== */
        .grid-2col {
            display: grid;
            grid-template-columns: 1fr;
            gap: 16px;
            margin: 18px 0 16px;
        }

        .info-card {
            background: rgba(18, 30, 58, 0.5);
            border-radius: 22px;
            padding: 18px 16px 20px;
            border: 1px solid rgba(100, 180, 255, 0.05);
            backdrop-filter: blur(4px);
            transition: 0.2s;
        }

        .info-card:hover {
            border-color: rgba(100, 180, 255, 0.12);
        }

        .info-card h3 {
            font-size: 1.1rem;
            font-weight: 700;
            margin-bottom: 10px;
            color: #b8dfff;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .info-card h3 i {
            color: #7ec8ff;
            font-size: 1.2rem;
            width: 1.8rem;
        }

        .info-card ul {
            list-style: none;
            margin: 0;
        }

        .info-card li {
            margin-bottom: 10px;
            display: flex;
            align-items: flex-start;
            gap: 10px;
            font-size: 0.9rem;
            color: #c5d9ee;
        }

        .info-card li i {
            color: #6a9fc7;
            width: 1.2rem;
            font-size: 0.85rem;
            margin-top: 3px;
            flex-shrink: 0;
        }

        .info-card li .tag {
            background: rgba(100, 180, 255, 0.06);
            padding: 0 10px;
            border-radius: 30px;
            font-size: 0.65rem;
            font-weight: 600;
            color: #7ec8ff;
            margin-left: 4px;
        }

        .btn-pesquisa {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: linear-gradient(135deg, #1f4a7a, #3a2f7a);
            color: white;
            font-weight: 600;
            padding: 12px 22px;
            border-radius: 60px;
            text-decoration: none;
            margin-top: 12px;
            font-size: 0.88rem;
            border: none;
            box-shadow: 0 4px 20px rgba(60, 100, 200, 0.12);
            width: 100%;
            justify-content: center;
            transition: 0.2s;
        }

        .btn-pesquisa:active {
            transform: scale(0.97);
            box-shadow: 0 2px 10px rgba(60, 100, 200, 0.08);
        }

        .btn-pesquisa i {
            color: #aac8ff;
        }

        /* ===== PESQUISAS ===== */
        .pesquisas-box {
            background: rgba(18, 30, 58, 0.4);
            border-radius: 22px;
            padding: 18px 16px 20px;
            margin: 18px 0 16px;
            border-left: 4px solid #7ec8ff;
            border: 1px solid rgba(100, 180, 255, 0.05);
            border-left-width: 4px;
        }

        .pesquisas-box h3 {
            font-size: 1.1rem;
            font-weight: 700;
            color: #b8dfff;
            display: flex;
            align-items: center;
            gap: 10px;
            flex-wrap: wrap;
            margin-bottom: 14px;
        }

        .pesquisas-box h3 i {
            color: #7ec8ff;
        }

        .pesquisa-item {
            background: rgba(8, 16, 38, 0.5);
            border-radius: 16px;
            padding: 14px 16px;
            margin-bottom: 12px;
            border: 1px solid rgba(100, 180, 255, 0.03);
            transition: 0.2s;
        }

        .pesquisa-item:last-child {
            margin-bottom: 0;
        }

        .pesquisa-item .titulo-pesq {
            font-weight: 600;
            color: #d6edff;
            font-size: 0.95rem;
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            gap: 6px;
        }

        .pesquisa-item .titulo-pesq i {
            color: #a78bfa;
            font-size: 0.85rem;
        }

        .pesquisa-item .desc-pesq {
            font-size: 0.85rem;
            color: #b0c8e0;
            margin-top: 4px;
            padding-left: 24px;
        }

        .pesquisa-item .status {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            font-size: 0.65rem;
            font-weight: 600;
            padding: 2px 12px;
            border-radius: 30px;
            background: rgba(100, 200, 150, 0.08);
            color: #7ecfaa;
        }

        .pesquisa-item .status.em-andamento {
            background: rgba(255, 200, 80, 0.08);
            color: #f0c060;
        }

        .pesquisa-item .status.concluido {
            background: rgba(100, 200, 150, 0.08);
            color: #7ecfaa;
        }

        .pesquisa-item .status.planejado {
            background: rgba(100, 150, 255, 0.06);
            color: #7e9fcf;
        }

        .pesquisa-item .meta-info {
            font-size: 0.75rem;
            color: #6a8fb0;
            margin-top: 4px;
            padding-left: 24px;
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }

        .pesquisa-item .meta-info i {
            margin-right: 3px;
            color: #4a7fa0;
        }

        /* ===== LABORATÓRIO / INSTITUTO ===== */
        .lab-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 16px;
            margin: 18px 0 16px;
        }

        .lab-card {
            background: rgba(18, 30, 58, 0.5);
            border-radius: 22px;
            padding: 18px 16px 20px;
            border: 1px solid rgba(100, 180, 255, 0.05);
            backdrop-filter: blur(4px);
            transition: 0.2s;
        }

        .lab-card h3 {
            font-size: 1.1rem;
            font-weight: 700;
            margin-bottom: 10px;
            color: #b8dfff;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .lab-card h3 i {
            color: #7ec8ff;
            font-size: 1.2rem;
            width: 1.8rem;
        }

        .lab-card ul {
            list-style: none;
            margin: 0;
        }

        .lab-card li {
            margin-bottom: 10px;
            display: flex;
            align-items: flex-start;
            gap: 10px;
            font-size: 0.9rem;
            color: #c5d9ee;
        }

        .lab-card li i {
            color: #6a9fc7;
            width: 1.2rem;
            font-size: 0.85rem;
            margin-top: 3px;
            flex-shrink: 0;
        }

        .btn-lab {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: linear-gradient(135deg, #2a5f8a, #1f4a7a);
            color: white;
            font-weight: 600;
            padding: 12px 22px;
            border-radius: 60px;
            text-decoration: none;
            margin-top: 12px;
            font-size: 0.88rem;
            border: none;
            box-shadow: 0 4px 20px rgba(60, 100, 200, 0.10);
            width: 100%;
            justify-content: center;
            transition: 0.2s;
        }

        .btn-lab:active {
            transform: scale(0.97);
        }

        /* ===== FOOTER ===== */
        .recursos-footer {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-top: 24px;
            padding-top: 18px;
            border-top: 1px solid rgba(100, 180, 255, 0.05);
            font-size: 0.8rem;
            color: #8ab0d0;
        }

        .recursos-footer .contato {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 6px 14px;
        }

        .recursos-footer .contato i {
            margin-right: 4px;
            color: #6a9fc7;
        }

        .recursos-footer a {
            color: #8fcbff;
            text-decoration: none;
            font-weight: 500;
        }

        .recursos-footer a:active {
            text-decoration: underline;
        }

        .recursos-footer .creditos {
            opacity: 0.5;
            font-size: 0.75rem;
        }

        /* ===== INFOS EXTRAS ===== */
        .extra-infos {
            display: flex;
            flex-wrap: wrap;
            gap: 8px 16px;
            margin-top: 16px;
            padding-top: 14px;
            border-top: 1px solid rgba(100, 180, 255, 0.04);
            font-size: 0.7rem;
            color: #6a8fb0;
            justify-content: center;
        }

        .extra-infos span {
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }

        .extra-infos i {
            color: #4a7fa0;
        }

        .aviso-quantico {
            text-align: center;
            margin-top: 16px;
            font-weight: 400;
            color: #6a9fc7;
            background: rgba(100, 180, 255, 0.03);
            border-radius: 60px;
            padding: 8px 16px;
            max-width: 100%;
            font-size: 0.8rem;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            border: 1px solid rgba(100, 180, 255, 0.03);
        }

        .aviso-quantico i {
            color: #a78bfa;
        }

        /* ===== RESPONSIVO ===== */
        @media (min-width: 600px) {
            body {
                padding: 20px;
            }

            .container {
                max-width: 700px;
                padding: 24px 28px 30px;
            }

            .top-bar {
                flex-direction: row;
                justify-content: space-between;
                align-items: center;
            }

            .logo h1 {
                font-size: 1.7rem;
            }

            .grid-2col {
                grid-template-columns: 1fr 1fr;
                gap: 20px;
            }

            .lab-grid {
                grid-template-columns: 1fr 1fr;
                gap: 20px;
            }

            .btn-pesquisa, .btn-lab {
                width: auto;
                padding: 10px 28px;
            }

            .recursos-footer {
                flex-direction: row;
                justify-content: space-between;
                align-items: center;
            }

            .extra-infos {
                justify-content: space-between;
            }
        }

        @media (min-width: 900px) {
            body {
                padding: 30px;
            }

            .container {
                max-width: 1100px;
                padding: 32px 40px 36px;
            }

            .logo h1 {
                font-size: 2.1rem;
            }

            .hero-card h2 {
                font-size: 1.8rem;
            }

            .grid-2col {
                gap: 28px;
            }

            .lab-grid {
                gap: 28px;
            }

            .pesquisas-box {
                padding: 24px 24px 26px;
            }
        }

        /* ===== TOQUE ===== */
        a, .btn-pesquisa, .btn-lab, .pesquisa-item {
            touch-action: manipulation;
            -webkit-tap-highlight-color: rgba(100, 180, 255, 0.03);
        }

        @media (prefers-reduced-motion: reduce) {
            * {
                transition: none !important;
                animation: none !important;
            }
        }
    </style>
</head>
<body>

<!-- ===== PARTÍCULAS DE FUNDO ===== -->
<div class="particle-bg" aria-hidden="true">
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
</div>

<div class="container">

    <!-- ===== CABEÇALHO ===== -->
    <header class="top-bar">
        <div class="logo">
            <h1><i class="fas fa-atom"></i> Quântica<span style="font-weight: 300;">Lab</span></h1>
            <div class="sub"><i class="fas fa-flask"></i> Moema Távora · Instituto Ecolocar</div>
        </div>
        <div class="school-badge">
            <i class="fas fa-graduation-cap"></i> Pesquisa & Inovação
        </div>
    </header>

    <!-- ===== NAVEGAÇÃO ===== -->
    <nav class="nav-links" aria-label="Navegação principal">
        <a href="#inicio"><i class="fas fa-house-chimney"></i> Início</a>
        <a href="#conceitos"><i class="fas fa-brain"></i> Conceitos</a>
        <a href="#pesquisas"><i class="fas fa-microscope"></i> Pesquisas</a>
        <a href="#laboratorio"><i class="fas fa-flask"></i> Lab</a>
        <a href="#recursos"><i class="fas fa-circle-info"></i> Recursos</a>
    </nav>

    <!-- ===== HERO ===== -->
    <section id="inicio" class="hero-card">
        <h2><i class="fas fa-superpowers"></i> Onde a realidade se desfaz</h2>
        <p>
            <span class="highlight">⚛️ Física Quântica</span> — o estudo dos menores componentes do universo. 
            Na <strong>Escola Moema Távora</strong> e no <strong>Instituto Escolar</strong>, 
            exploramos partículas, ondas e probabilidades para entender o mundo além do que os olhos veem.
        </p>
        <p style="margin-top: 8px; font-size: 0.82rem; color: #8ab4d6;">
            <i class="fas fa-arrow-right" style="color: #7ec8ff;"></i> Participe das nossas pesquisas!
        </p>
    </section>

    <!-- ===== CONCEITOS PRINCIPAIS ===== -->
    <div class="grid-2col" id="conceitos">
        <article class="info-card">
            <h3><i class="fas fa-wave-square"></i> Dualidade</h3>
            <ul>
                <li><i class="fas fa-circle"></i> Partícula <span class="tag">corpúsculo</span></li>
                <li><i class="fas fa-wave-sine"></i> Onda <span class="tag">frequência</span></li>
                <li><i class="fas fa-arrow-right-arrow-left"></i> Complementaridade</li>
                <li><i class="fas fa-lightbulb"></i> Experimento da fenda dupla</li>
            </ul>
            <a href="#" class="btn-pesquisa"><i class="fas fa-chevron-circle-right"></i> Explorar dualidade</a>
        </article>

        <article class="info-card">
            <h3><i class="fas fa-dice"></i> Incerteza</h3>
            <ul>
                <li><i class="fas fa-ruler-combined"></i> Posição × Momento</li>
                <li><i class="fas fa-clock"></i> Energia × Tempo</li>
                <li><i class="fas fa-chart-line"></i> Princípio de Heisenberg</li>
                <li><i class="fas fa-eye"></i>classclassclass="fas class="fas  Observador influencia</li>
            </ul>
            <a href="#" class="btn-pesquisa"><i class="fas fa-chevron-circle-righclass="fas t"></i> Ver mais</a>
        </article>
    </div>

    <!-- ===== PESQUISAS EM DESTAQUE ===== -->
    <section id="pesquisas" class="pesquisas-box">
        <h3><i class="fas fa-microscope"></i> Pesquisas em andamento</h3>

        <div class="pesquisa-item">
            <div class="titulo-pesq">
                <i class="fas fa-quote-right"></i> Emaranhamento quântico em laboratório
                <span class="status em-andamento"><i class="fas fa-spinner fa-pulse"></i> Em andamento</span>
            </div>
            <div class="desc-pesq">
                Estudando como partículas podem se conectar instantaneamente — Instituto Escolar, turma do 1º ano.
            </div>
            <div class="meta-info">
                <span><i class="fas fa-users"></i> Equipe: 8 estudantes</span>
                <span><i class="fas fa-calendar"></i> Início: Mar/2026</span>
            </div>
        </div>

        <div class="pesquisa-item">
            <div class="titulo-pesq">
                <i class="fas fa-quote-right"></i> Computação quântica com qubits
                <span class="status em-andamento"><i class="fas fa-spinner fa-pulse"></i> Em andamento</span>
            </div>
            <div class="desc-pesq">
                Simulação de algoritmos quânticos em parceria com a Escola Moema Távora.
            </div>
            <div class="meta-info">
                <span><i class="fas fa-users"></i> Equipe: 6 estudantes</span>
                <span><i class="fas fa-calendar"></i> Início: Fev/2026</span>
            </div>
        </div>

        <div class="pesquisa-item">
            <div class="titulo-pesq">
                <i class="fas fa-quote-right"></i> Efeito túnel e aplicações
                <span class="status concluido"><i class="fas fa-check-circle"></i> Concluído</span>
            </div>
            <div class="desc-pesq">
                Pesquisa sobre tunelamento quântico em diodos — apresentada na Feira de Ciências 2025.
            </div>
            <div class="meta-info">
                <span><i class="fas fa-users"></i> Equipe: 5 estudantes</span>
                <span><i class="fas fa-calendar"></i> Concluído: Nov/2025</span>
            </div>
        </div>

        <div class="pesquisa-item">
            <div class="titulo-pesq">
                <i class="fas fa-quote-right"></i> Superposição quântica e interferência
                <span class="status planejado"><i class="fas fa-clock"></i> Planejado</span>
            </div>
            <div class="desc-pesq">
                Estudo teórico sobre superposição de estados e padrões de interferência.
            </div>
            <div class="meta-info">
                <span><i class="fas fa-users"></i> Equipe: 4 estudantes</span>
                <span><i class="fas fa-calendar"></i> Previsto: Ago/2026</span>
            </div>
        </div>

        <div style="margin-top: 16px;">
            <a href="#" class="btn-pesquisa" style="background: linear-gradient(135deg, #2a2f6a, #1f4a7a);">
                <i class="fas fa-flask"></i> Ver todas as pesquisas
            </a>
        </div>
    </section>

    <!-- ===== LABORATÓRIO & INSTITUTO ===== -->
    <div class="lab-grid" id="laboratorio">
        <div class="lab-card">
            <h3><i class="fas fa-flask"></i> Lab Quântico</h3>
            <ul>
                <li><i class="fas fa-microchip"></i> Simulador de qubits</li>
                <li><i class="fas fa-laser"></i> Óptica quântica</li>
                <li><i class="fas fa-chart-bar"></i> Análise de probabilidades</li>
                <li><i class="fas fa-users"></i> Equipe Moema + Ecolocar</li>
                <li><i class="fas fa-desktop"></i> Laboratório de informática</li>
            </ul>
            <a href="#" class="btn-lab"><i class="fas fa-chevron-circle-right"></i> Conheça o lab</a>
        </div>

        <div class="lab-card">
            <h3><i class="fas fa-graduation-cap"></i> Instituto Ecolocar</h3>
            <ul>
                <li><i class="fas fa-seedling"></i> <strong>Ecolocar</strong> – pesquisa e sustentabilidade</li>
                <li><i class="fas fa-handshake"></i> Parceria com a Moema Távora</li>
                <li><i class="fas fa-globe"></i> Projetos de inovação quântica</li>
                <li><i class="fas fa-calendar-check"></i> Workshops mensais</li>
                <li><i class="fas fa-trophy"></i> Premiações em feiras de ciência</li>
            </ul>
            <a href="#" class="btn-lab"><i class="fas fa-chevron-circle-right"></i> Sobre o Ecolocar</a>
        </div>
    </div>

    <!-- ===== FOOTER ===== -->
    <footer id="recursos" class="recursos-footer">
        <div class="contato">
            <i class="fas fa-envelope"></i> <a href="mailto:quantica@moematavora.edu">quantica@moematavora.edu</a>
            <i class="fas fa-phone" style="margin-left: 4px;"></i> <a href="tel:+5585999999999">(85) 9 9999-9999</a>
        </div>
        <div class="creditos">
            <i class="fas fa-atom"></i> Moema Távora · Ecolocar
        </div>
        <div>
            <a href="#inicio" aria-label="Voltar ao topo"><i class="fas fa-arrow-up"></i> Topo</a>
        </div>
    </footer>

    <!-- ===== INFOS EXTRAS ===== -->
    <div class="extra-infos">
        <span><i class="fas fa-map-pin"></i> Lab 3 · 2º andar</span>
        <span><i class="fas fa-clock"></i> Seg–Sex, 8h–18h</span>
        <span><i class="fas fa-users-between-lines"></i> <a href="#" style="color: #8fcbff; text-decoration: none;">Grupo de pesquisa</a></span>
        <span><i class="fas fa-file-pdf"></i> <a href="#" style="color: #8fcbff; text-decoration: none;">Publicações</a></span>
    </div>

    <!-- ===== AVISO QUÂNTICO ===== -->
    <div class="aviso-quantico">
        <i class="fas fa-infinity"></i> A realidade é probabilística — e você faz parte dela.
        <i class="fas fa-infinity"></i>
    </div>

</div> <!-- fim container -->
</body>
</html>