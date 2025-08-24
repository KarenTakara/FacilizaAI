<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h1>
        Facilize - Assistente Virtual para Inclusão Digital de Idosos
    </h1>
    <link rel="stylesheet" href="css/style.css">
    
</head>
<body>

<header>
    <img src="imagens/facilize.jpg" alt="Logo Facilize">
    <p>“Como facilitar o acesso dos idosos à tecnologia e promover inclusão digital de verdade?"</p>
</header>

<section>
    <h2>Desafio</h2>
    <p>
        A inclusão digital de idosos é uma barreira significativa em muitos países. Enquanto a tecnologia se expande, muitos ainda enfrentam dificuldades para acessar serviços essenciais como pagamento de contas, agendamento de consultas, renovação de documentos e até mesmo interações simples em redes sociais. A falta de familiaridade com dispositivos digitais muitas vezes gera insegurança e isolamento.
    </p>
</section>

<section>
    <h2>Cenário Atual</h2>
    <p>
        Atualmente, a inclusão digital da terceira idade ainda enfrenta grandes desafios em diversas partes do mundo. No Brasil, pesquisa do IBGE de 2019 apontou que apenas 40% dos idosos utilizam smartphones, e muitos relatam sentir-se excluídos ou inseguros ao usar tecnologias digitais. Além disso, grande parte desses idosos encontra dificuldades para realizar tarefas online essenciais, como pagar contas, agendar consultas e acessar serviços públicos, devido à falta de familiaridade com dispositivos e interfaces digitais. Essa exclusão digital contribui para o isolamento social e limita o acesso a informações e serviços que poderiam facilitar seu dia a dia. Por isso, promover a inclusão digital para esse grupo é fundamental para garantir autonomia e qualidade de vida.
    </p>
</section>

<section>
    <h2>Objetivo</h2>
    <p>
        O Facilize foi criado para promover a inclusão digital da terceira idade. Através de uma interface amigável e de interações simples, o chatbot guia o usuário em tarefas digitais comuns, oferecendo segurança, autonomia e conectividade.
    </p>
</section>

<section>
    <h2>Jornada do Usuário - Facilize</h2>
    <p>
        A jornada do usuário no Facilize foi pensada para ser simples, acolhedora e eficaz. Ao iniciar a interação, a assistente virtual, carinhosamente chamada de Fa, faz perguntas básicas para entender melhor o contexto do usuário, começando por qual dispositivo ele está usando — seja celular, tablet ou computador. Em seguida, Fa pergunta como pode ajudar, ouvindo atentamente a necessidade do usuário. Por exemplo, se alguém deseja renovar o RG, mas não sabe como fazer, o usuário simplesmente descreve sua dúvida para a Fa. A assistente então responde com orientações claras, passo a passo e em linguagem simples, garantindo que o usuário se sinta seguro e confiante para realizar a tarefa. Esse fluxo humanizado e personalizado ajuda a reduzir a ansiedade e a frustração que muitos idosos sentem diante da tecnologia, promovendo autonomia e inclusão digital de verdade.
    </p>
</section>

<section>
    <h2>Estrutura do Projeto</h2>
    <ul>
        <li><strong>index.html:</strong> O arquivo principal do front-end. Ele define a estrutura da página (o esqueleto do chat).</li>
        <li><strong>style.css:</strong> Cuida da aparência do chat, como cores, tamanhos e alinhamento das mensagens.</li>
        <li><strong>script.js:</strong> O "cérebro" do front-end. Ele gerencia a interação do usuário, adiciona as mensagens na tela e se comunica com o servidor back-end.</li>
        <li><strong>server.js:</strong> O servidor back-end. Ele recebe as requisições do front-end e envia as respostas.</li>
        <li><strong>computador.js:</strong> A "inteligência" do projeto. Este arquivo se conecta à API da Google Gemini e gera as respostas para as perguntas do usuário.</li>
    </ul>
</section>

<section>
    <h2>Como Instalar e Rodar</h2>
    <p>Para que o projeto funcione, você precisa ter o <strong>Node.js</strong> instalado em seu computador.</p>
    <h3>1. Clone o repositório</h3>
    <p>Se você estiver usando Git, clone o projeto para sua máquina.</p>
    <pre><code>git clone https://www.dio.me/articles/enviando-seu-projeto-para-o-github
cd [nome do seu repositório]
    </code></pre>
    <h3>2. Instale as dependências</h3>
    <p>Abra o terminal na pasta do projeto e instale as bibliotecas necessárias.</p>
    <pre><code>npm install express body-parser cors @google/generative-ai</code></pre>
    <h3>3. Adicione sua Chave de API</h3>
    <p>Abra o arquivo <code>computador.js</code> e substitua <code>"SUA_API_KEY"</code> pela sua chave da Google Gemini. Você pode obtê-la no <a href="https://ai.google.dev/maker">Google AI Studio</a>.</p>
    <h3>4. Inicie o servidor</h3>
    <p>No terminal, execute o comando para iniciar o back-end.</p>
    <pre><code>node server.js</code></pre>
    <p>Você deve ver a mensagem <strong>"Servidor rodando em http://localhost:3000"</strong>. Deixe este terminal aberto.</p>
    <h3>5. Abra o Front-end</h3>
    <p>Vá até a pasta do projeto e abra o arquivo <code>index.html</code> em seu navegador (Chrome, Firefox, etc.). Recomendamos usar a extensão <strong>Live Server</strong> do VS Code para facilitar.</p>

</section>


<footer>
    <p>Facilize © 2025 - Todos os direitos reservados</p>
</footer>

</body>

