# Rust Brazil Mobilizers’ Handbook
*(Manual de Mobilizadores do Rust Brasil)*

Caro Mobilizador Rust,

Seja bem-vindo! **A partir de agora você faz parte da nossa missão.** Nós somos pensadores e apaixonados por tecnologia trabalhamos juntos para manter a Internet saudável, aberta e acessível a todos, acreditamos que o trabalho comunitário em uma plataforma de código aberto é essencial para nosso crescimento pessoal e para o futuro da sociedade.

As pessoas são a essência da Mozilla. Colocamos as pessoas em primeiro lugar e fazemos o nosso melhor para reconhecer, valorizar e respeitar a diversidade dos nossos contribuidores globais. O Projeto Mozilla recebe contribuições de todos que compartilham nossos objetivos e querem colaborar de maneira saudável e construtiva dentro da nossa comunidade. Sendo assim, adotamos este [**código de conduta**](https://www.mozilla.org/pt-BR/about/governance/policies/participation/) a fim de nos ajudar a criar uma experiência segura e positiva para todos da comunidade.

Nós criamos esse manual ou handbook *(como é conhecido)* para garantir que você esteja alinhado com a Mozilla, o experimento e a nossa estratégia, além de dar orientações que lhe apoiará durante seu trabalho conosco.

**Obrigado por  juntar-se a nós! 🎉**

*2018 Rust Mobilizers Experiment team, [Mozilla Brasil](https://mozillabr.org)*

----------
# O experimento
![Put-Your-Trust-in-Rust.png](https://lh5.googleusercontent.com/I8elilCEhrMBEUnusjvovnNW6r-gL4J3vPcBcYhTL-vxG-UzBKeiKegPH8WoO3bYon4GcR0tz2FcGs4dSY3AUCOQyCDqscignGhVvDOSkACJLZ-6bDoHF0nn4aPtdBpbveFYEVSI)


Este experimento é o nosso próximo passo após organizar [3 oficinas de Rust no Brasil](https://www.eventbrite.com.br/o/mozilla-brasil-14167163781) apoiadas pela Mozilla e com envolvimento direto de voluntários das comunidades Mozilla e Rust.

A [Mozilla foi a primeira a investir em Rust](https://research.mozilla.org/rust/) e há anos empodera e usa a linguagem no [Servo](https://github.com/servo/servo) e no Firefox. A Mozilla está apostando em Rust para inovar o produto e [garantir segurança de ponta no navegador](https://blog.mozilla.org/firefox/put-trust-rust-shipping-now-firefox/). Não restam dúvidas de que Rust é uma linguagem importante para o futuro da web pois a faz segura, rápida e incrível.

Assim como a Mozilla está radiante ao usar Rust para inovar o Firefox nós queremos garantir que mais programadores **conheçam, usem e evangelizem Rust no Brasil**. Nós iremos apoiar um grupo de programadores Rust durante o experimento ***2018 Rust Mobilizers Experiment*** que empoderará mobilizadores a criarem coisas incríveis com Rust por meio de oficinas pequenas, locais e apoiadas pela Mozilla ao ensinar e engajar programadores em uma linguagem de programação de sistemas que roda incrivelmente rápido, previne falhas de segmentação, e garante segurança entre threads.

Na próxima sessão você entenderá como funciona a nossa proposta de oficina de Rust.

----------
# Mergulhando em Rust

Mergulhando em Rust é um formato de evento cuja proposta é expor os participantes a Rust. Ao final do evento, um participante deve ter entendido o **propósito de Rust e seus casos de uso,** e deve ter praticado **habilidades básicas de trabalho** com Rust. O público alvo são pessoas que já programam em alguma linguagem.

## Material de Referência

Existe muito [material disponível](https://www.rust-lang.org/en-US/documentation.html) sobre o ensino de Rust, inclusive [exercícios para workshops](https://github.com/rust-community/rustbridge/tree/master/workshops/src) e [exercícios para iniciantes](http://exercism.io/languages/rust/exercises), até [coisas em português](https://blog.bltavares.com/). Nos workshops Dive Into Rust realizados em 2017 no Brasil, utilizamos o material disponível em: [https://github.com/mozillabrasil/dive-into-rust](https://github.com/mozillabrasil/dive-into-rust). Este material está em constante evolução, fique a vontade para utilizar, modificar, propor mudanças ou desenvolver sua própria versão do material.

## Programação

A atividade é programada para um máximo de **cinco horas**, por exemplo no horário das 13h às 18h, e no máximo **vinte participantes**.
Antes:

- Chegue no local com antecedência e deixe seu material pronto. Descubra a senha do WiFi, ligue o projetor ou TV, arrume as cadeiras e mesas e garanta que estejam próximas de pontos de energia suficientes para todos. Pré-arrume a mesa do o coffee-break, deixando os snacks próximos.
- Dê boas vindas individualmente aos participantes conforme cheguem. Inicie a atividade dando boas-vindas a todos.

Atividades (duração sugerida):

- Inicie com uma [apresentação](https://github.com/mozillabrasil/dive-into-rust/blob/master/apresentacoes/rust%20o%20que%20e.pdf) cujo objetivo é apresentar Rust e motivar os participantes a aprender a respeito. (15min)
- Garanta que todos consigam rodar código Rust (compilador instalado ou [online](https://play.rust-lang.org/)) e explique o cargo e o “cargo new”.
- Demonstrações, exercícios e soluções de exercícios devem ser intercalados em fluxos de 30min na forma:
  - Demonstração com live coding. (10min)
    - Evite improvisar tudo, tenha [uma cola](https://github.com/mozillabrasil/dive-into-rust/tree/master/demos) e disponibilize ela com antecedência.
    - Discuta os conceitos conforme eles são exercitados no código.
  - Explicação do exercício (2min)
  - Realização individual do exercício (10min)
    - Neste momento, tire dúvidas individualmente e estime quantos já terminaram para saber o momento de finalizar.
  - Revisão do exercício (10min)
    - Resolva você mesmo passo a passo caso poucos tenham resolvidos. Tente chamar alguém para mostrar e explicar sua solução caso muitos tenham solucionado.
- O fluxo dos exercícios pode ser modificado conforme necessário. Para conceitos complexos como [ownership](https://github.com/mozillabrasil/dive-into-rust/blob/master/apresentacoes/rust%20ownership.pdf) uma apresentação antes pode ajudar. Exercícios podem ser feitos coletivamente ao invés de individualmente, especialmente os mais difíceis ou para acelerar a programação.

Finalização (30min):

- Fale sobre a comunidade Rust, como ela funciona, como ela pode ajudar e como os participantes podem ajudá-la. Dê foco à comunidade local, como o [grupo do Telegram](https://t.me/rustlangbr) e a [tradução do livro](https://github.com/rust-br/rust-book-pt-br/issues).
- Peça que preencham o feedback oficial da Mozilla em [https://mzl.la/howwasit](https://mzl.la/howwasit).
- Distribua swag.
## Dicas
- O [fluxo do material de referência](https://docs.google.com/document/d/1dIEEOG8WojipobiBq9UpjGJ1Gs4vuh2gh85yjeMYAK4/edit#) propõe uma ordem para os assuntos e exercícios. Se quiser modificar, uma boa referência é a ordem em que os assuntos são introduzidos no [livro](https://doc.rust-lang.org/book/second-edition/).
- [Dicas e Truques](https://mozillascience.github.io/open-science-leadership-workshop/facilitator_tips_&_tricks.html) para facilitadores.
- Você terá pouco tempo para tirar dúvidas individuais, caso alguém esteja bloqueado ajude como possível e recomende que a pessoa passe para o próximo exercício. Assim a pessoa se frustra menos e aproveita melhor o workshop.
- Coloque todo material que irá utilizar em único local na web e disponibilize logo no início do workshop, isto facilita para todos.
- Caso vá compartilhar muitos links, crie uma sala de chat temporária, por exemplo no [https://riot.im/](https://riot.im/).

**Controle o tempo**. Tenha no máximo três apresentações de no máximo 15 minutos cada. Chame para o coffee-break após 2h do início. Reserve o espaço para 5h mas busque encerrar pelas 4h30, quando notar que os participantes estão cansados. Planeje menos atividades do que o tempo que você tem, pois vai faltar tempo.

# Logística
## Crie sua equipe

Crie uma equipe de pessoas para trabalhar na organização da oficina junto com você, é uma grande oportunidade para trabalhar em conjunto, olhe a sua volta e veja como as pessoas podem te ajudar. Procure aquela pessoa que faz parte de comunidades, hackerspaces, ativistas e quem já organiza outras atividades também para somar esforços. Envolva todas as pessoas da sua equipe em todas as etapas de organização do evento, dê a oportunidade para que escolham no que querem trabalhar em específico.

## Encontre um local

Ao considerar onde realizar seu evento, procure um **espaço confortável e flexível**, **apropriado para o número de participantes que você espera**. Seja criativo - universidades, centros comunitários, espaços colaborativos, bibliotecas e hackerspaces são ótimos lugares para começar.

## Recursos mínimos necessários

Certifique-se que no local contenha:

- Internet confiável;
- Tomadas de energia suficientes para os participantes;
- Dispositivo para transmitir o conteúdo (projetor/datashow/monitor);
- Boa iluminação;

Verifique se alguma pessoa responsável pelo local estará presente no dia, para abrir o local e te auxiliar na organização. Lembre de convidar, com antecedência, as próprias pessoas que frequentam o local para participar o workshop.

## Página do evento, gerenciamento de inscrições e plataformas

Criar uma página para o seu evento é essencial para mostrar aos participantes o que é o evento, o que eles podem esperar e as informações cruciais para que eles possam chegar ao seu evento.
Ao criar uma página para o seu evento garanta que você adicionou as seguintes informações:

- Título
- Descrição
- Hora e data
- Endereço
- Agenda
- Formato
- Público
- Código de Conduta
- Contato do organizador

O formulário de inscrição do seu evento **deve conter não apenas nome completo e e-mail**, mas também informações que são necessárias para fazer check-in ou autorização de entrada no lugar do evento, verifique se é necessário com o responsável pelo local onde acontecerá o evento. *Exemplo: Se você fará um evento em um prédio comercial, será necessário nome completo + um número de documento de identificação oficial, como RG ou CNH.*
Você pode criar a página do seu evento de forma muito fácil usando algumas ferramentas populares como:

- Eventbrite - [https://www.eventbrite.com.br](https://www.eventbrite.com.br)
- Sympla - [https://www.sympla.com.br](https://www.sympla.com.br)
- Meetup.com - [https://www.meetup.com](https://www.meetup.com)
- vpEventos - [https://www.vpeventos.com](https://www.vpeventos.com)
- Doity - [https://doity.com.br](https://doity.com.br)

Exemplos de páginas de eventos passados:

- [Mergulhando em Rust — O futuro da programação de sistemas #1](https://www.eventbrite.com.br/e/mergulhando-em-rust-o-futuro-da-programacao-de-sistemas-1-registration-35237171328#)
- [Mergulhando em Rust — O futuro da programação de sistemas #2](https://www.eventbrite.com.br/e/mergulhando-em-rust-o-futuro-da-programacao-de-sistemas-2-registration-36876136517#)
- [Mergulhando em Rust — O futuro da programação de sistemas #3](https://www.eventbrite.com.br/e/mergulhando-em-rust-o-futuro-da-programacao-de-sistemas-3-registration-37744693394#)
- [Mergulhando em Rust — O futuro da programação de sistemas #4](https://www.eventbrite.com.br/e/mergulhando-em-rust-o-futuro-da-programacao-de-sistemas-3-registration-37744693394#)
## Comunicados

Use a plataforma de evento que você está gerenciando as inscrições para enviar comunicados importantes por e-mail:
**Uma semana antes do evento e um dia antes do evento** — informe que o evento está próximo, os recursos que precisam trazer, tarefas pré evento (instalação de software?), endereço, data e hora e formas de chegar ao evento. [**[modelo]**](https://docs.google.com/a/mozilla-community.org/document/d/1RDrTBQLVibV0a1B-ibj4XsaWw02msbR-69GWl8Sndj0/edit?usp=sharing)
**Pós evento** — agradeça por participarem da oficina, incentive que compartilhem o que criaram, entrem nos canais de comunicação da comunidade, anexe material do oficina e todos os links relevantes, peça que publiquem fotos no Twitter com a hashtag. [**[modelo]**](https://docs.google.com/a/mozilla-community.org/document/d/1cAHawRH7Z8OxfmTjI7oIKm9gSZyxCA7lxp1ztJn3MGQ/edit?usp=sharing)

## Coffee-break

O coffee break é essencial para manter os participantes ativos nas atividades, uma oficina de Rust é longa, então atente-se a necessidade de organizar um momento para degustar um petisco e beber algo.

![](https://lh6.googleusercontent.com/koeK52kusvvZIzAe5eiufn1PWZzo3UU1wzKXDXNpA0taX6uD1naA8TtIwD_kdNL5-vXjczP6X21TBtAPEwXKMrblwJZuwGColebIvc3YAX5emXnNkbFr_U3aUwOMqZPPPWhgwAO6)


Para ter sucesso em seu coffee break sugerimos seguir algumas recomendações:

- Saiba a quantidade exata de pessoas para calcular os comes e bebes;
- Escolha o local ideal para montagem do lanche e tenha certeza que ele não será apertado demais, dificultando que as pessoas alcancem a mesa e nem grande demais, de forma que as pessoas se espalhem muito e não aproveitem o intervalo para socializar (*networking)*;

Confira um cardápio indicado para um coffee break simples:
–  Pães recheados
–  Mini sanduíches
–  Bolos frescos
–  Sucos naturais
–  Refrigerante
Atente-se a necessidade de opções vegetarianas/veganas, e ao material descartável necessário.

# Marketing

Há muitas maneiras de promover seu evento que atrairá mais participantes. Aqui temos algumas **dicas e recursos** que você pode remixar para promover sua oficina:

- Crie a página do evento no Facebook e adicione o link de inscrições, você pode usar essa ferramenta do Facebook para convidar colegas e amigos.
- Compartilhe o link de inscrições/página do seu evento em grupos de Facebook, Telegram, WhatsApp, lista de e-mail ou fórum de universidades, imprensa estudantil e calendários de eventos.
- Poster! Sim, subestime o alcance de um poster na universidade, colégio técnico ou escola de cursos de tecnologia.
## Recursos

Nós criamos um kit de imagens, posters, capas e outros para você remixar e usar nas redes sociais, páginas de eventos, grupos de mensagens e onde quiser. Você pode clicar em cada um dos templates, editar usando o Google Desenhos, fazer download no formato preferido e publicar onde quiser.

- [Imagem (feed) para Facebook (1200x630px)](https://docs.google.com/a/mozilla-community.org/drawings/d/1Z_rvWRpy3vxS_-TX7tlPXcaPgGG444nwwU8STjONvc8/edit?usp=sharing)
- [Imagem (capa para página de evento) para Facebook (1920x1080px)](https://drive.google.com/a/mozilla-community.org/file/d/1pJZfIYKN9vrHsO128x0kQ76QNEsXDkit/view?usp=sharing)
- [Imagem (linha do tempo) para Twitter (1024x512px)](https://docs.google.com/a/mozilla-community.org/drawings/d/1ygHPy7jPApeiwKQY0YbvVXtHZjqppRj_Mw4UrmKACcg/edit?usp=sharing)
- [Imagem (capa) para Twitter (1500x500px)](https://docs.google.com/a/mozilla-community.org/drawings/d/1BW1gPHLto06cA1gUE44GXFqHm7nfPQrcToKIW6Ycz7I/edit?usp=sharing)
- [Imagem (capa) para Eventbrite (2160x1080px)](https://drive.google.com/a/mozilla-community.org/file/d/1vXJNxCBYe2Nsobi2jF9GHBNSm4cpzjok/view?usp=sharing)
- [Poster A4 (colorido)](https://docs.google.com/a/mozilla-community.org/drawings/d/1XG8nGRPcuRYUAdQPbC7kWgaN7ZVc8iDXL6zZuHggiZQ/edit?usp=sharing)
- [Poster A3 (colorido)](https://docs.google.com/a/mozilla-community.org/drawings/d/1y3jZUW5UzehOXBo_vfHmXVwtoZiotxMGjpxLekiIIDc/edit?usp=sharing)
- [Wallpaper HD (1920x1080px)](https://drive.google.com/a/mozilla-community.org/file/d/1-lBZjNgzJWTdvFOzz0lPWequupQll9Xr/view?usp=sharing)

Se preferir você pode fazer [download do pacote de arquivos vetoriais](https://drive.google.com/a/mozilla-community.org/file/d/1A48ilYOl63tSYp3bonaDcP0pfZuTQZKI/view?usp=sharing) caso você queira fazer algo e diferente. =)

# Reportando

Falar sobre o sucesso e relatar como foi a sua oficina de Rust. Isto permite inspirar outros a se juntar a sua comunidade local, organizar novas oficinas, envolver-se em Rust e nas atividades que você fez lá.
Antes do evento organize com sua equipe quem será o responsável por documentar tudo o que acontece na oficina, tenha em mente essas questões para discutir com sua equipe:

- Quem registrará o que acontecer no evento?
- Quais momentos da oficina são essenciais para capturar?
- Quais redes têm mais sentido para informar a sua comunidade? (Medium, Blog post, Twitter, Facebook)

Aqui temos algumas dicas do que sua equipe pode fazer no dia da oficina para coletar o máximo de informações garantindo que tenha bons recursos para documentar posteriormente como foi a oficina.

- Anotações
- Gravações
- Tirar fotos (muitas, por favor!)
- Entrevistar os participantes (antes e depois da oficina)
  - [Antes] O que você espera da oficina de hoje? O que você espera descobrir sobre o  Rust?
  - [Depois] Como foi a oficina? O que mais gostou? O que mais Rust te surpreendeu? O que achou das atividades?
- Publique os momentos da oficina usando uma hashtag como #rustlang

Mantenha as escolhas de privacidade dos participantes em mente ao gravar ou tirar fotos em eventos. Muitos eventos oferecem pulseiras ou etiquetas com cores diferentes onde cada cor representa diferentes opções de privacidade.
*Veja essas e outras dicas em* [*Documenting & Reporting por Open Leaders*](https://mozilla.github.io/open-leadership-training-series/articles/running-awesome-community-events/documenting-and-reporting/)*.*

![giphy.gif](https://lh6.googleusercontent.com/5QWGIr5owl0IVmXVStJR6fusmW0fcrQPcRV6XKDBOyOlNvnIa8BfDd7-pMe4_ARMGQ5VqfMwydplc7rTE2naOqLApxX9YnOuUj84J0XsZsar69DUSB4shEm-Yv4m_1J3350dXwyp)

# Boa sorte!

Não esqueça de fazer sua oficina ser uma festa divertida (com moderação) e acolhedora!

**Anytime via** [**rust@mozillabr.org**](mailto:rust@mozillabr.org).

*(a qualquer momento)*

![giphy.gif](https://lh5.googleusercontent.com/3hyKpC9AUJYzOF6kbbIQc55harTrQLKEP0TskjKtsLfaTNPbQ6qCUBmWOR3Z630yzqb8k6jSneTxAKX3gZZRTjqg-I6RINMabt4fOKlHrTswU7-l1AST0UVimb-JtlQ5SVD5ewxA)



