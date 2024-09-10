<footer class="rodape">
        <img src="img/Logo.png" alt="Alura+" class="rodape__logo">
        <ul class="rodape__lista">
            <li class="lista__link">
                <a href="#">Idioma</a>
            </li>
            <li class="lista__link">
                <a href="#">Dispositivos compatíveis</a>
            </li>
            <li class="lista__link">
                <a href="#">Contrato de assinatura</a>
            </li>
            <li class="lista__link">
                <a href="#">Politica de privacidade</a>
            </li>
            <li class="lista__link">
                <a href="#">Proteção de dados no Brasil</a>
            </li>
            <li class="lista__link">
                <a href="#">Anuncios personalizados</a>
            </li>
            <li class="lista__link">
                <a href="#">Ajuda</a>
            </li>
        </ul>
        <p class="rodape__texto">® 2021 Alura, Alura+ e Alura Língua. Todos os direitos reservados. Serviço de assinatura paga. Conteúdo sujeito a disponibilidade.</p>
        <p class="rodape__texto">Alura+ é um serviço pago, baseado em assinatura e sujeito a termos e condições. O serviço Alura+ é comercializado por Aovs Sistemas de Informática S.A., Rua Vergueiro, 3185 - Liberdade, São Paulo - SP, 04101-300, Brasil e CNPJ 05.555.382/0001-33</p>
    </footer>.rodape__lista {
    display: flex;
    justify-content: center;
    list-style-type: none;
    margin-top: 1em;
}.lista__link a{
    text-decoration: none;
    color: var(--branco-principal);
    margin-left: 1em;
}.rodape__texto {
    margin: 1em 0;
    color: var(--cinza-secundario);
    font-size: 14px;
}.rodape {
    text-align: center;
    margin: 5em 3em;
}.lista__link a:hover {
    color: var(--botao-azul);
}.lista__link a:active {
    color: purple;
}:root {
    --branco-principal: #FFFFFF;
    --cinza-secundario: #C0C0C0;
    --botao-azul: #167BF7;
    --cor-de-fundo: #00030C;
    --fonte-principal: 'Inter';
    --botao-azul-efeito: #3c92fa;
}.container__botao:hover {
    background-color: var(--botao-azul-efeito);
    color: var(--cor-de-fundo);
}  <section class="container secundario">
  </section  <img src="img/Plataformas.png" alt="Um monitor e um celular com a alura plus aberta" class="secundario__imagem">  <div class="container__descricao">
    <h2 class="descricao__titulo">Assista do seu jeito</h2>
    <p class="descricao__texto">Aproveita a tela grande da TV ou assista no Tablet, Laptop, Celular e outros aparelhos. Nossa seleção de cursos não para de crescer.</p>
        </div><section class="container secundario">
        <img src="img/Plataformas.png" alt="Um monitor e um celular com a alura plus aberta" class="secundario__imagem">
        <div class="container__descricao">
            <h2 class="descricao__titulo">Assista do seu jeito</h2>
            <p class="descricao__texto">Aproveite a tela grande da TV ou assista no tablet, laptop, celular e outros
                aparelhos. Nossa seleção de cursos não para de crescer.</p>
        </div>
        </section>  .secundario__imagem {
      width: 80%;
  }  .secundario {
      align-items: center;
      margin: 0 10em;
  }  .descricao__titulo {
      font-weight: 700;
      font-size: 48px;
      color: var(--branco-principal);
      margin-bottom: 0.1em;
  }  .descricao__texto {
      color: var(--cinza-secundario);
  }
