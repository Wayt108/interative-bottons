// Selecionar os botões
const blueButton = document.getElementById('blue-btn');
const greenButton = document.getElementById('green-btn');
const redButton = document.getElementById('red-btn');

// Adicionar eventos de clique aos botões
blueButton.addEventListener('click', function() {
    document.body.style.backgroundColor = '#3498db';
});

greenButton.addEventListener('click', function() {
    document.body.style.backgroundColor = '#2ecc71';
});

redButton.addEventListener('click', function() {
    document.body.style.backgroundColor = '#e74c3c';
});
