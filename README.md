📦 RoboDeEnvioDeArquivos

Este projeto é um robô automatizado em Python que envia qualquer tipo de arquivo em lotes sequenciais ou todos de uma vez por e-mail utilizando o Microsoft Outlook.

🚀 Funcionalidades

Envio automático de todos os arquivos de uma pasta.

Possibilidade de enviar todos de uma vez ou em lotes configuráveis (ex: 50 por vez).

Os arquivos são enviados em ordem sequencial até que todos sejam processados.

O programa roda no CMD e solicita:

📂 Caminho da pasta dos arquivos

📧 E-mail destinatário

📦 Quantidade de arquivos por lote (quando escolhido o envio em lotes)

O CMD permanece aberto até que o processo seja concluído, exibindo mensagens de status a cada lote ou envio único.

🔧 Requisitos

Python 3.8+

Microsoft Outlook instalado e configurado

Dependência:

pip install pywin32

▶️ Como usar

Clone o repositório:

git clone https://github.com/MATEUSMSILV4/RoboDeEnvioDeArquivos.git
cd RoboDeEnvioDeArquivos


Execute o programa:

python main.py


Informe os dados solicitados (pasta, e-mail e escolha entre envio único ou em lotes).

🛠 Gerar Executável (Windows)

Se quiser rodar sem precisar do Python instalado:

pip install pyinstaller
pyinstaller --onefile --console main.py


O executável será gerado em:

dist/main.exe
