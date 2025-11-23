📘 SkillUp IA – Recomendação de Carreira com Gemini

Projeto da disciplina de IoT / Deep Learning, integrado ao ecossistema do projeto SkillUp.

Este notebook utiliza IA Generativa (Google Gemini 2.0 Flash) para gerar recomendações profissionais personalizadas com base no perfil do usuário.

A saída da IA é totalmente estruturada em JSON e segue o mesmo formato utilizado pela API do projeto SkillUp em .NET, garantindo integração entre as disciplinas, mesmo que o backend não esteja sendo executado no vídeo.

🧠 Objetivo do Projeto

Criar uma aplicação de Deep Learning capaz de:

Ler informações do usuário:

objetivo profissional

habilidades

experiência

Enviar esse perfil para o modelo Gemini

Receber uma resposta estruturada contendo:

profissões sugeridas

habilidades a desenvolver (hard/soft skills)

cursos recomendados

resumo do perfil

Exibir o resultado em formato JSON pronto para uso em sistemas externos

🔗 Integração com a API .NET (RWD)

A IA foi configurada para gerar o JSON exatamente no mesmo formato utilizado pela API em .NET.

Isso permite:

O JSON gerado pode ser enviado diretamente ao endpoint POST /api/v1/recomendacoes

A API pode salvar a recomendação no banco de dados


▶️ Como usar (passo a passo)

Abra o notebook no Google Colab

Insira sua API Key do Gemini

Execute as células

A IA irá gerar automaticamente um JSON completo com orientações de carreira

🧪 Tecnologias usadas

Google Gemini 2.0 Flash

Python + Google Colab

Modelo generativo para recomendação

Formato JSON compatível com o backend .NET


Luan Dantas dos Santos RM 559004 

Matheus Henrique Germano Reis RM 555861

Enzo Dias Alfaia Mendes 558438
