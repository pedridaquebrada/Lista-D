<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista D - Nossos Eventos</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet"> <!-- Fonte Roboto -->
    <style>
        /* Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif; /* Fonte alterada para Roboto */
            background-color: #FFFAE3; /* Fundo claro com tom de verão */
            color: #333;
            line-height: 1.8;
            margin: 0;
        }

        header {
            background: linear-gradient(90deg, #FFD700, #FFA500);
            padding: 30px;
            text-align: center;
            color: white;
        }

        header h1 {
            font-size: 3rem;
        }

        header p {
            font-size: 1.5rem;
        }

        nav {
            margin-top: 20px;
        }

        nav a {
            text-decoration: none;
            color: #FFFFFF;
            font-size: 1.2rem;
            margin: 0 15px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #FFE4B5;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }

        section {
            background-color: #FFF8DC; /* Fundo creme */
            margin: 30px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #FF6347;
            font-size: 2.5rem; /* Garantir que o título tenha o mesmo tamanho */
        }

        section p {
            font-size: 1.2rem;
            margin-bottom: 15px;
        }

        /* Remover a borda arredondada da imagem */
        header img {
            display: block;
            margin: 20px auto; /* Centraliza a imagem */
            width: 240px; /* Define a largura */
            height: 240px; /* Define a altura */
        }

        footer {
            background: linear-gradient(90deg, #32CD32, #FFA500);
            color: white;
            padding: 15px;
            text-align: center;
        }

        footer a {
            color: #FFD700;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Lista D</h1>
        <p>Olá, Bem-vindo à Lista D! Somos dez crianças que queremos um futuro melhor e uma escola também melhor. Por isso, já sabem, votem D!</p>
        <p>Conheça as nossas propostas</p>
        <nav>
            <a href="#evento1">Cyberbullying</a>
            <a href="#evento2">Tecnologias</a>
            <a href="#evento3">Privacidade</a>
        </nav>
        <img src="site/logotipo.jpg" alt="Logotipo Lista D"> <!-- Imagem sem borda arredondada -->
    </header>

    <div class="container">
        <!-- Cyberbullying -->
        <section id="evento1">
            <h2>Cyberbullying: um problema muito comum!</h2>
            <p>O cyberbullying, ou assédio online, é uma forma moderna de violência que utiliza a internet como meio. Com a expansão das redes sociais e plataformas digitais, crianças, adolescentes e até mesmo adultos estão sujeitos a experiências negativas que podem causar sérios danos emocionais e psicológicos. Este evento visa conscientizar sobre o impacto do cyberbullying e como todos nós podemos agir para preveni-lo.</p>
            <p>O cyberbullying ocorre quando alguém utiliza mensagens, comentários ou publicações para intimidar, humilhar ou ameaçar outra pessoa. Ele pode ser sutil, como excluir alguém de um grupo, ou explícito, como enviar mensagens de ódio. Estudos mostram que as vítimas de cyberbullying podem desenvolver ansiedade, depressão e, em casos extremos, pensamentos suicidas.</p>
            <p>Neste evento, discutiremos formas práticas de lidar com esse problema:</p>
            <ul>
                <p>Educar jovens e crianças sobre o uso responsável das redes sociais.</p>
                <p>Ensinar os professores a identificar sinais de que seus alunos podem ser vítimas ou praticantes de cyberbullying e a ajudar.</p>
                <p>Promover ambientes escolares e digitais mais acolhedores.</p>
            </ul>
            <p>Queremos criar um espaço seguro e acolhedor para todos. Acreditamos que a educação é a chave para transformar a internet em um lugar mais respeitoso e inclusivo.</p>
        </section>

        <!-- Tecnologias -->
        <section id="evento2">
            <h2>As Novas Tecnologias</h2>
            <p>O futuro já chegou, e ele está repleto de inovações que moldam nosso cotidiano. Neste evento, mergulharemos nas tecnologias emergentes que estão transformando a maneira como vivemos, trabalhamos e interagimos. Da inteligência artificial à realidade aumentada, as possibilidades são infinitas.</p>
            <p>A inteligência artificial (IA), por exemplo, está presente em assistentes virtuais, diagnósticos médicos e até mesmo em veículos autônomos. Essa tecnologia está revolucionando indústrias inteiras ao permitir decisões mais rápidas e precisas. Já a realidade aumentada (RA) combina o mundo real com elementos digitais, criando experiências imersivas que antes pareciam ficção científica.</p>
            <p>Abordaremos temas como:</p>
            <ul>
                <p>Como a IA pode ajudar a resolver problemas globais, como mudanças climáticas.</p>
                <p>A importância da ética no desenvolvimento de tecnologias.</p>
                <p>O impacto dessas inovações no mercado de trabalho.</p>
            </ul>
            <p>Venha explorar como as novas tecnologias podem ser ferramentas poderosas para melhorar nossa qualidade de vida, enquanto discutimos os desafios e oportunidades desse futuro digital.</p>
        </section>

        <!-- Privacidade -->
        <section id="evento3">
            <h2>Privacidade e Proteção de Dados</h2>
            <p>Na era digital, a privacidade é uma das questões mais importantes que enfrentamos. Todos os dias, bilhões de dados são coletados, compartilhados e analisados. Embora a tecnologia facilite nossas vidas, ela também expõe informações sensíveis a riscos como roubo de identidade e violações de privacidade.</p>
            <p>Nosso evento aborda questões como:</p>
            <ul>
                <p>A importância de entender termos de uso e políticas de privacidade.</p>
                <p>Como proteger suas informações com senhas fortes e autenticação em duas etapas.</p>
            </ul>
            <p>Com especialistas no tema, exploraremos as melhores práticas para manter seus dados seguros e minimizar os riscos de exposição indevida. Nosso objetivo é empoderar você com conhecimentos práticos para navegar no mundo digital de forma segura e responsável.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Lista D. Todos os direitos reservados. <a href="#topo">Voltar ao topo</a></p>
    </footer>
</body>
</html>
