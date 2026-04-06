🎬 CloudClipper

Aplicação web que identifica automaticamente o trecho mais viral de um vídeo usando transcrição + inteligência artificial.

⸻

🚀 Funcionalidades
	•	Upload de vídeo via Cloudinary
	•	Geração automática de transcrição
	•	Análise da transcrição com IA (Gemini)
	•	Identificação do trecho mais relevante
	•	Geração de vídeo recortado automaticamente
	•	Reprodução direta no navegador

⸻

🧠 Como funciona
	1.	O usuário envia um vídeo
	2.	O Cloudinary processa e gera a transcrição
	3.	A aplicação aguarda a transcrição ficar disponível
	4.	A transcrição é enviada para a API Gemini
	5.	A IA retorna o intervalo mais viral (ex: so_12.5,eo_45.2)
	6.	O vídeo é recortado dinamicamente via URL
	7.	O resultado é exibido no player

  ⸻

🛠️ Tecnologias utilizadas
	•	HTML5
	•	CSS3
	•	JavaScript
	•	Cloudinary (upload, transcrição e corte de vídeo)
	•	Google Gemini API (análise de conteúdo)


🔐 Uso da API Gemini
	•	Insira sua chave no campo da interface
	•	A chave é usada para analisar a transcrição do vídeo
	•	Não é armazenada

⸻

▶️ Como usar
	1.	Insira sua API Key do Gemini
	2.	Clique em “Upload files”
	3.	Envie um vídeo
	4.	Aguarde o processamento
	5.	O trecho viral será exibido automaticamente

⸻

⚠️ Limitações
	•	Depende da transcrição do Cloudinary
	•	Pode haver atraso no processamento
	•	Requer API Key do Gemini
	•	Não possui backend
