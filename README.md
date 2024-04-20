O que esse código faz?
-
Ele busca uma ação na Yahoo Finance no prazo de 6 meses, analisa os dados e envia um e-mail pelo gmail automaticamente.

Busca dados e analisa dados da ação inserida:
-
   • Importamos a biblioteca yfinance;<br>
   • Inserimos o nome da ação da Petrobras(PETR4.SA) e mostramos em um gráfico de linha;<br>
   • Fazemos a análise para puxar a cotação máxima, mínima e atual;<br>

Passo a passo do envio do e-mail automático com o resultado da análise:
-
  • Instalamos e importamos as bibliotecas time, pyautogui e pyperclip.<br>
  • Realizamos uma pausa do mouse e da automação em 5 segundos;<br>
  • Copiamos o endereço www.gmail.com;<br>
  • Efetuamos um ctrl + v do endereço do gmail;<br>
  • Damos um enter;<br>
  • Clicamos no botão "Escrever";<br>
  • Copiamos os escolhidos;<br>
  • Colamos os destinatários no campo dos remetentes;<br>
  • Damos um tab;<br>
  • Copiamos o título como "Análises diárias";<br>
  • Colamos o título;<br>
  • Damos um tab;<br>
  • Efetuamos o template da mensagem do corpo do e-mail;<br>
  • Copiamos os dados da variável mensagem;<br>
  • Colamos o corpo do e-mail;<br>
  • Clicamos no botão enviar;<br>
  • Exibimos a mensagem para o usuário: "E-mail enviado com sucesso!".<br>
