🗂️ Projeto CMD – Gerenciador de Diretórios
📌 Descrição
Este projeto é um script em batch (.bat) feito no Prompt de Comando do Windows (CMD) com o objetivo de automatizar a organização de arquivos e diretórios no ambiente do usuário. Ele cria estruturas de pastas, gera arquivos simulados e os move para os locais corretos, funcionando como um mini gerenciador de arquivos via terminal.

Essa atividade foi desenvolvida com fins educacionais, durante os estudos iniciais de automação no Windows com CMD.

⚙️ O que o script faz?
✅ Define um diretório base (ProjetoCMD) na pasta Documentos

📁 Cria subpastas: Entrada, Imagens, Documentos, Planilhas e Backup

📄 Cria arquivos simulados nas pastas

🔀 Move arquivos para seus destinos corretos

💬 Exibe mensagens no terminal para acompanhar o progresso

🧾 Estrutura Criada
bash
Copiar
Editar
ProjetoCMD/
├── Entrada/
│   ├── ImageOne.jpg
│   ├── DocumentOne.txt
│   └── SheetOne.xlsx
├── Imagens/
├── Documentos/
├── Planilhas/
├── Backup/
📦 Tecnologias usadas
📂 CMD (Prompt de Comando do Windows)

🧱 Comandos: md, move, echo, title, color, pause, set, cd

▶️ Como usar
Abra o Bloco de Notas

Cole o código do script .bat

Salve como: GerenciadorCMD.bat

Execute com duplo clique no Windows

Acompanhe a criação das pastas e movimentação dos arquivos no terminal

💡 Certifique-se de que as pastas mencionadas existem ou que você tenha permissão para criá-las.

📍 Observação importante
Alguns comandos no script original possuem pequenos ajustes necessários para funcionar corretamente, como:

O comando md não cria arquivos, mas sim pastas. Para simular arquivos, use echo. com redirecionamento >.

Caminhos com espaço precisam estar entre aspas (") para evitar erros.

O comando move deve apontar para os caminhos reais de origem e destino.

Se quiser, posso te mandar o script corrigido e funcional!

👨‍💻 Autor
Leandro
Estudante de Desenvolvimento de Sistemas, explorando automação com terminal 🖥️
