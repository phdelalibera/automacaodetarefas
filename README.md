O que esse código faz?
-
Ele busca uma ação na Yahoo Finance no prazo de 6 meses, analisa os dados e envia um e-mail pelo gmail automaticamente.

Busca dados e analisa dados da ação inserida:
-
   • Importamos a biblioteca yfinance;
   • Inserimos o nome da ação da Petrobras(PETR4.SA) e mostramos em um gráfico de linha;
   • Fazemos a análise para puxar a cotação máxima, mínima e atual;

Passo a passo do envio do e-mail automático com o resultado da análise:
-
  • Instalamos e importamos as bibliotecas pyautogui e pyperclip.
  • Realizamos uma pausa do mouse em 5 segundos;
  • Copiamos o endereço www.gmail.com;
  • Efetuamos um ctrl + v do endereço do gmail;
  • Damos um enter;
  • Clicamos no botão "Escrever";
  • Copiamos os escolhidos;
  • Colamos os destinatários no campo dos remetentes;
  • Damos um tab;
  • Copiamos o título como "Análises diárias";
  • Colamos o título;
  • Damos um tab;
  • Efetuamos o template da mensagem do corpo do e-mail;
  • Copiamos os dados da variável mensagem;
  • Colamos o corpo do e-mail;
  • Clicamos no botão enviar;
  • Exibimos a mensagem para o usuário: "E-mail enviado com sucesso!".
