# APP-IMC

# FECAP - Fundação de Comércio Álvares Penteado
Integrantes: <a href="https://github.com/ThiagoAkira0">Thiago Akira Higa Mitami: 24026254</a>

## Descrição
O IMC App é um aplicativo simples e intuitivo para calcular o Índice de Massa Corpórea (IMC) com base no peso e altura do usuário. Após a análise, o app direciona para a tela correspondente, exibindo suas informações e uma mensagem motivacional.

## 🚧 Desafios enfrentados
🔹 Gerenciamento de Navegação
->Para garantir que cada resultado de IMC levasse o usuário para a tela correta, foi implementado um sistema de Intent baseado nas faixas do IMC.

🔹 Passagem de Dados entre Telas
->Um desafio importante foi enviar os valores de peso, altura e IMC para a tela de resultado. Isso foi resolvido utilizando Bundle e putExtras() nas Intents.

🔹 Manutenção e Usabilidade
->Criado um botão "Limpar" para melhorar a experiência do usuário, permitindo novos cálculos sem precisar reiniciar o app.
