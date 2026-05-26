// Função para mostrar/esconder os detalhes de cada card de hobby
function toggleCard(id) {
    const detalhe = document.getElementById(id);
    
    // Alterna a classe 'hidden' (escondido)
    if (detalhe.classList.contains('hidden')) {
        detalhe.classList.remove('hidden');
    } else {
        detalhe.classList.add('hidden');
    }
}

// Função para gerar um status aleatório sobre o que você está fazendo
function mudarStatus() {
    const atividades = [
        "🍿 Assistindo ao novo episódio da minha série favorita!",
        "🎮 Jogando uma partida intensa no momento, não disturbe.",
        "🏋️‍♂️ Na academia puxando ferro. Foco no shape!",
        "🤔 Escolhendo qual vai ser o próximo jogo da lista...",
        "🥤 Tomando um pré-treino para dar aquela energia."
    ];

    // Seleciona uma atividade aleatória do array
    const indiceAleatorio = Math.floor(Math.random() * atividades.length);
    const statusTexto = document.getElementById('status-atual');
    
    // Atualiza o texto na tela
    statusTexto.textContent = atividades[indiceAleatorio];
}
