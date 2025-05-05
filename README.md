===============================
🎯 APOSTA+ — Aplicativo Mobile
===============================

📌 Descrição:
Aposta+ é um aplicativo mobile desenvolvido com React Native (via Expo) com o objetivo de conscientizar usuários sobre os gastos com apostas, fornecendo alternativas de investimento, histórico de gastos e visualização gráfica com feedback inteligente. É ideal para quem busca controle financeiro com usabilidade simples e moderna.

---------------------------------------
🛠️ Tecnologias Utilizadas
---------------------------------------
- React Native + Expo
- TypeScript
- React Navigation
- AsyncStorage (armazenamento local)
- react-native-chart-kit (gráficos)
- Context API (tema e autenticação)
- Styled with Dark Mode Support

---------------------------------------
📱 Funcionalidades do App
---------------------------------------

🔐 Autenticação
- Login com persistência de sessão
- Cadastro simples e rápido

🏠 Tela Inicial (Home)
- Exibe valor apostado na semana (gerado aleatoriamente)
- Sugestão de reinvestimento com CTA
- Acesso direto ao perfil, simulador e estatísticas

📈 Simulador de Investimento
- O usuário digita quanto gastou
- Resultado com retorno mensal e anual estimado

📊 Estatísticas
- Gráfico de linha com gastos dos últimos 7 dias
- Gráfico de barras comparativo
- Médias semanais e mensais
- Botão para limpar histórico

👤 Perfil do Usuário
- Exibe nome, idade, cidade, e-mail
- Mensagem “Bem-vindo ao seu perfil!” que desaparece após 2 segundos

🌙 Modo Escuro
- Adaptação de cores com base no tema
- Suporte completo a dark mode em todas as telas

---------------------------------------
📁 Estrutura do Projeto
---------------------------------------

AppApostasXP/
├── assets/               → imagens e ícones
├── components/           → botões, gráficos, etc.
├── context/              → ThemeContext, AuthContext
├── navigation/           → configuração de rotas
├── screens/              → todas as telas (Login, Register, Home, etc.)
└── App.tsx               → arquivo principal

---------------------------------------
▶️ Como Executar o Projeto
---------------------------------------

1. Clone o repositório:
   git clone [https://github.com/efsartorelli/fiap-checkpoint4]

2. Acesse a pasta:
   cd AppApostasXP

3. Instale as dependências:
   npm install

4. Inicie o projeto:
   npx expo start

---------------------------------------
📦 Instale também:
---------------------------------------

npm install @react-navigation/native @react-navigation/native-stack
npm install react-native-chart-kit react-native-svg
npm install @react-native-async-storage/async-storage

---------------------------------------
👨‍💻 Autor
---------------------------------------
Nome: EDEZKANIRO
GitHub: https://github.com/efsartorelli 
Turma: 3ESPV - Engenharia de Software — FIAP 2025

---------------------------------------
📚 Observações Finais
---------------------------------------
- Projeto acadêmico com fins educativos
- Todos os dados são gerados localmente e armazenados com AsyncStorage
- Visual moderno, ícones e navegação intuitiva

Eduardo de Oliveira Nistal - RM94524
Enzo Vazquez Sartorelli - RM94618 
Kaue Pastori - RM98501
Nicolas Nogueira Boni - RM551965 
Rodrigo Viana - RM551057
