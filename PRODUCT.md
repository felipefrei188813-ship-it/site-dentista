# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Pacientes de qualquer perfil em Caçapava (SP) e região — famílias, crianças, adultos que buscam estética e adultos que precisam de reabilitação com implantes. A clínica não prioriza um público sobre outro: o site precisa servir igualmente a quem procura uma consulta de rotina e a quem chega com um tratamento maior em mente.

Situação típica: a pessoa encontra a clínica pelo Instagram ou por busca local, quer entender se pode confiar, que tratamentos existem e como agendar — muitas vezes pelo celular. Parte desse público tem medo ou ansiedade em relação ao dentista.

## Product Purpose

Site institucional da Xavier Odontologia, clínica odontológica em Caçapava-SP. Existe para transformar quem descobre a clínica (principalmente pelo Instagram @xavier.odontologia) em paciente agendado, substituindo o link da bio que hoje está quebrado.

Sucesso = o visitante entende quem cuida dele, que a clínica atende o que ele precisa e inicia o agendamento pelo WhatsApp.

## Positioning

"Referência em odontologia humanizada" em Caçapava, sustentada por três fatos confirmados:

- **Atendimento humanizado:** o paciente é ouvido, entende o tratamento e não é apressado — inclusive quem tem medo de dentista.
- **Equipe completa:** clínico geral e especialidades no mesmo lugar.
- **Estrutura nova:** clínica nova e moderna (fachada com letreiro e recepção visíveis nas fotos reais).

## Operating Context

- Descoberta principal pelo Instagram; acesso majoritariamente pelo celular.
- O agendamento acontece no WhatsApp da clínica; o site não tem sistema de agenda nem backend.
- Responsável técnica: Dra. Vilma Xavier, CRO/SP 92590.
- Publicidade odontológica segue o código de ética do CFO: nome e CRO do responsável técnico visíveis; sem preços ou promoções; antes/depois apenas com autorização do paciente.

## Capabilities and Constraints

Funcionalidades existentes que devem ser mantidas:

- Botões de agendamento que abrem o WhatsApp com mensagem pronta.
- Formulário (nome, telefone, período, tratamento de interesse, convênio) que monta a mensagem e abre o WhatsApp — sem armazenar dados.
- Comparador antes/depois arrastável.
- Seções: abertura, apresentação, resultados, tratamentos, atendimento para quem tem medo, sobre a Dra. Vilma, a clínica, depoimentos, dúvidas frequentes, contato com mapa.
- Tratamentos listados: implantes, lentes e estética (facetas, clareamento), ortodontia (aparelhos e alinhadores), clínico geral, canal e gengiva, odontopediatria.

Restrições técnicas: página estática única (`index.html`) em HTML/CSS/JS puro, imagens em `imagens/`, sem build.

Ainda não definidos (não inventar): número de WhatsApp, endereço, horários, convênios aceitos, formas de pagamento, valor da avaliação, atendimento de urgência, formação e especializações da Dra. Vilma.

## Brand Commitments

- Nome: Xavier Odontologia. Identidade existente: logotipo com dente facetado dourado e letreiro "XAVIER ODONTOLOGIA" em azul-marinho (ver `imagens/logo.jpg` e a fachada em `imagens/post-01.jpg`).
- Voz: acolhedora, próxima, sem jargão; fala com o paciente na segunda pessoa ("você").
- Instagram oficial: @xavier.odontologia.

## Evidence on Hand

- Fotos reais vindas do Instagram, em baixa resolução (aprox. 360×640), em `imagens/`: fachada (`post-01`), equipe (`post-03`, `post-05`, `post-09`), atendimento (`post-12`), Dra. Vilma (`post-06`), logo (`logo.jpg`). Fotos com texto sobreposto (`post-04`, `07`, `08`, `10`, `11`) não servem para o site.
- Fotos de antes/depois com autorização existem, mas ainda não foram entregues ao projeto.
- **Não existem ainda:** depoimentos reais, nota/avaliações do Google, fotos profissionais em alta resolução. Não fabricar depoimentos, notas, estrelas, métricas ou números de pacientes.

## Product Principles

1. **Confiança antes de conversão:** o visitante precisa sentir segurança (quem atende, CRO, equipe, estrutura real) antes de ser chamado a agendar.
2. **Acolher quem tem medo:** reduzir ansiedade explicando o que acontece, sem pressa e sem julgamento.
3. **Um caminho claro até o WhatsApp:** agendar deve ser óbvio em qualquer ponto, sem excesso de chamadas competindo.
4. **Só prova real:** usar apenas fotos, casos e depoimentos verdadeiros e autorizados; espaço vazio é melhor que prova inventada.
5. **Servir todos os perfis:** nenhum tratamento ou público pode parecer secundário ou esquecido.

## Accessibility & Inclusion

Público amplo, incluindo idosos e pessoas usando o celular: texto legível, contraste no mínimo WCAG AA, áreas de toque confortáveis e funcionamento sem depender de animação.
