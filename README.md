# Sua Voz

Ferramenta em português do Brasil para praticar a fala em público, com personalização, cinco práticas, cronômetro, palavras de apoio, áudio local e histórico opcional.

## Publicação na Vercel

Projeto estático. Framework: Other. Sem comandos de instalação ou build. Output Directory: public. Nenhuma variável de ambiente ou dependência necessária. A configuração está em vercel.json.

## Privacidade

Texto e áudio não são enviados a serviços de análise. Áudio permanece em memória e é descartado ao sair da prática. Histórico opcional em localStorage, restrito ao perfil do navegador. O servidor de hospedagem pode processar registros técnicos normais de acesso. Feedback baseado em regras, sem análise de voz, diagnóstico ou promessa terapêutica.

## Desenvolvimento

Sirva a pasta public com um servidor HTTP local. A gravação precisa de HTTPS ou localhost e permissão explícita do microfone. O HTML também pode ser aberto diretamente, mas gravação e armazenamento variam por navegador.
