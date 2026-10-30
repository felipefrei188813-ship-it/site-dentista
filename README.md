# Xavier Odontologia — site

Site da Xavier Odontologia, clínica odontológica em Caçapava (SP). Responsável técnica: Dra. Vilma Xavier, CRO/SP 92590.

Página única, em HTML, CSS e JavaScript puros: não precisa de instalação nem de build.

## O que o site faz

- Abertura com um seletor que monta a mensagem de agendamento (tratamento + período) e abre o WhatsApp da clínica.
- Mapa do sorriso: pontos sobre um caso real que explicam lentes de contato, clareamento e ortodontia.
- Tratamentos, primeira consulta para quem tem medo de dentista, a Dra. Vilma e a equipe, casos reais de antes e depois (arraste para comparar), dúvidas frequentes e contato.
- Funciona em celular, tablet e computador; respeita quem pede menos movimento no sistema.

## Estrutura

```
index.html            a página inteira (estilos e scripts dentro dela)
fonts/                fontes Funnel Display e Funnel Sans (servidas pelo próprio site)
imagens/              logo, fotos da clínica e casos de antes/depois
video/hero.mp4        vídeo do dente usado como marca d'água na abertura
PRODUCT.md            quem é a clínica, público e regras do conteúdo
DESIGN.md             sistema visual: cores, fontes, componentes e regras
.impeccable/          design.json (o mesmo sistema em formato de dados) e a ficha da página
prompt-video-flow.md  roteiro usado para gerar o vídeo
```

## Ver no computador

Abra um terminal nesta pasta e rode:

```
python -m http.server 8765
```

Depois acesse `http://localhost:8765`. Abrir o `index.html` com dois cliques também funciona, mas alguns navegadores bloqueiam o vídeo e as fontes fora de um servidor.

## Publicar com GitHub Pages

1. Envie esta pasta para um repositório no GitHub.
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Antes de publicar

Alguns dados ainda estão entre colchetes `[ ... ]` no `index.html` e precisam ser preenchidos pela clínica:

- **Número do WhatsApp** (o mais importante): no fim do `index.html`, troque `const WHATSAPP = "5512900000000";` pelo número real, só dígitos, com 55 e o DDD.
- Endereço, horários e telefone (seção de contato e rodapé).
- Convênios, valor da avaliação, formas de pagamento e atendimento de urgência (dúvidas frequentes).
- Formação e especializações da Dra. Vilma.
- Depoimentos reais de pacientes.
- Link da política de privacidade.

As fotos de antes e depois só podem ser publicadas com autorização por escrito dos pacientes, conforme o código de ética do Conselho Federal de Odontologia.
