# JOGO-DA-MEMORIA

const readline = require('readline');

// Configura a interface para receber entrada do usuário
const rl = readline.createInterface({
    input: process.stdin,
    output: process.stdout
});

// Função que soma dois números
function teste(a, b) {
    return a + b;
}

// Pergunta ao usuário o primeiro número
rl.question('Digite o primeiro número: ', (num1) => {
    // Pergunta ao usuário o segundo número
    rl.question('Digite o segundo número: ', (num2) => {
        const resultado = teste(parseFloat(num1), parseFloat(num2));
        console.log(O resultado da soma é: ${resultado});
        rl.close();
    });
});

executar_teste.bat
