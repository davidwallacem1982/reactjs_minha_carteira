# Dashboard Financeiro - **Minha Carteira** 🚀👩‍💻&middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/main/LICENSE)

**Versão Atual:** 1.0.0  
**Data de Lançamento:** 2021  
**Desenvolvedor:** David Wallace Marques Ferreira [LinkedIn](https://linkedin.com/in/david-wallace-marques-ferreira) | [GitHub](https://github.com/davidwallacem1982)


## Descrição

Este projeto é um **dashboard financeiro** desenvolvido utilizando **ReactJs** com **TypeScript**, completamente componentizado para fins de estudo dessas tecnologias. A aplicação foi projetada para ser um exemplo prático de como criar interfaces dinâmicas e responsivas sem o uso de banco de dados, utilizando dados simulados para relatórios e gráficos.

<div align="center" >
  <img src="./docs/assets/minhacarteirapreview.gif">
</div>

## Estrutura dos Dados

- **Sem banco de dados**: Os dados da aplicação são carregados a partir de dois arquivos JavaScript que contêm arrays simulando repositórios de dados.
- **Dados simulados**: Esses arrays contêm informações utilizadas para gerar os relatórios e gráficos do sistema. **Importante:** os dados devem estar com o ano atual para que os relatórios e gráficos sejam corretamente exibidos nas telas.

## Tecnologias Utilizadas

- **ReactJs**: Framework principal utilizado para a construção da interface do usuário.
- **TypeScript**: Adiciona tipagem estática ao JavaScript, permitindo maior controle sobre o código e prevenindo erros.
- **Recharts**: Biblioteca de gráficos **open-source** usada para a criação de gráficos dinâmicos.
- **React CountUp**: Utilizada para criar efeitos visuais de contagem crescente nos números exibidos.
- **CSS Responsivo**: Todo o layout e componentes foram projetados para serem responsivos, garantindo que a interface funcione bem em dispositivos de diferentes tamanhos.

## Funcionalidades

- **Interface responsiva**: O layout ajusta-se automaticamente para telas de diferentes tamanhos, proporcionando uma experiência de usuário consistente em dispositivos móveis e desktops.
- **Componentização**: Cada parte da interface foi desenvolvida com componentes puros em React, permitindo a fácil reutilização e manutenção do código.
- **Gráficos dinâmicos**: Os gráficos são gerados a partir dos dados simulados, e são atualizados automaticamente conforme os dados são carregados.
- **Efeito visual de contagem**: Para exibir valores financeiros, o efeito de contagem crescente foi implementado utilizando o **React CountUp**.

## Pré-visualização

- [x] Você pode visualizar o sistema rodando clicando aqui em [**Minha Carteira**](https://reactjs-minha-carteira.vercel.app/), 
esse link de so sistema postado no [**Vercel**](https://vercel.com/) para testes de funcionalidades do sistemas online.

### Layout & Componentes Responsivos
Todos os componentes e o layout da aplicação foram projetados para serem responsivos, adaptando-se automaticamente a diferentes resoluções de tela.
<div align="center" >
  <img src="./docs/assets/resposiveview.png">
</div>

### Bibliotecas Utilizadas

- [x] Recharts: Biblioteca para a criação de gráficos dinâmicos e interativos. [**Recharts**](http://recharts.org/en-US), ele é opensource.
- [x] React CountUp: Biblioteca para exibir animações de contagem crescente em números [**React CountUp**](https://www.npmjs.com/package/react-countup).

## Credenciais de Acesso

Para acessar o sistema, utilize as seguintes credenciais:

- **Login**: david.ferreira@gmail.com  
- **Senha**: 123456

## Como Executar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/minha-carteira.git
   ```
   
2. Navegue até o diretório do projeto:
   ```bash
   cd minha-carteira
   ```

3. Instale as dependências::
   ```bash
   npm install
   ```

4. Execute o projeto:
   ```bash
   npm start
   ```

5. O projeto será iniciado em:
   ```bash
   http://localhost:3000
   ```


<h2 id="contribute">Contribuição 🚀</h2>

Se você quiser contribuir, clone este repository, crie seu branch de trabalho e coloque a mão na massa!

Para contribuir com este projeto:

Clone o Repository
```bash
git clone https://github.com/davidwallacem1982/WebApiProfissional
```
Crie uma branch.
```bash
git checkout -b new-branch
```
Faça commit das suas mudanças.
```bash
git commit -m 'Adiciona nova funcionalidade'
```
Faça push para a branch.
```bash
git push origin new-branch
```
Abra um Pull Request.

Ao final, abra um Pull Request explicando o problema resolvido ou recurso realizado, se existir, anexe screenshot das modificações visuais e aguarde a revisão!

[How to create a Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request) |
[Commit pattern](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)



<h2 id="license">License 📃 </h2>

Este projeto é licenciado sob a licença MIT. Consulte o arquivo [MIT](./LICENSE) para mais detalhes.
