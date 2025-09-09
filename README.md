📦 Robô de Envio de XML via Outlook

Este projeto é um robô automatizado em Python que envia arquivos XML em lotes sequenciais por e-mail utilizando o Microsoft Outlook.

🚀 Funcionalidades

Envio automático de todos os XMLs de uma pasta.

Envio realizado em lotes configuráveis (ex: 50 por vez).

Os arquivos são enviados em ordem sequencial até que todos sejam processados.

O programa roda no CMD e solicita:

📂 Caminho da pasta dos XMLs

📧 E-mail destinatário

📦 Quantidade de arquivos por lote

O CMD permanece aberto até que o processo seja concluído, exibindo mensagens de status a cada lote enviado.

🔧 Requisitos

Python 3.8+

Microsoft Outlook instalado e configurado

Dependências:

pip install pywin32

▶️ Como usar

Clone o repositório:

git clone https://github.com/seu-usuario/robo-envio-xml.git
cd robo-envio-xml


Execute o programa:

python main.py


Informe os dados solicitados (pasta, e-mail e tamanho do lote).

🛠 Gerar Executável (Windows)

Se quiser rodar sem precisar do Python instalado:

pip install pyinstaller
pyinstaller --onefile --console main.py


O executável será gerado em:

dist/main.exe
