# Como Contribuir com os Projetos da Secretaria de Saúde de Juiz de Fora

A Secretaria de Saúde de Juiz de Fora incentiva a participação da comunidade no desenvolvimento e aprimoramento de seus projetos de código aberto. Suas contribuições são essenciais para a construção de soluções mais robustas e eficientes para a saúde pública do nosso município.

Este guia estabelece as diretrizes para quem deseja colaborar com os projetos da nossa organização no GitHub. Seguir estas orientações garante que o processo de contribuição seja claro, eficiente e transparente para todos os envolvidos.

## Como Começar

Para contribuir com um de nossos projetos, siga os passos abaixo. Este fluxo de trabalho, conhecido como "fork and pull", é um padrão amplamente adotado na comunidade de software de código aberto.

### 1. Faça um "Fork" do Repositório

O primeiro passo é criar uma cópia (um "fork") do repositório original para a sua conta pessoal no GitHub. Para isso, navegue até a página principal do projeto que deseja contribuir e clique no botão **Fork** no canto superior direito da tela. Isso criará uma réplica do projeto sob seu usuário.

### 2. Clone o Seu Fork

Agora, clone o repositório que você acabou de "forkar" para a sua máquina local. Isso permitirá que você trabalhe nas alterações em seu próprio ambiente de desenvolvimento.

### 3. Crie uma Nova "Branch"

É uma boa prática criar uma nova "branch" (ramificação) para cada nova funcionalidade ou correção que você for implementar. Isso mantém o histórico de alterações organizado e facilita a integração do seu trabalho.

```bash
git checkout -b minha-nova-funcionalidade
```
Escolha um nome descritivo para a sua branch, que resuma a alteração que você está fazendo (por exemplo, `corrige-bug-login` ou `adiciona-grafico-vacinacao`).

### 4. Faça Suas Alterações

Com a nova branch criada, você está pronto para fazer as alterações no código-fonte. Utilize seu editor de código ou IDE de preferência para implementar as melhorias, corrigir bugs ou adicionar novas funcionalidades.

### 5. "Commite" Suas Alterações

Após realizar as alterações, adicione os arquivos modificados e "commite" suas mudanças com uma mensagem clara e concisa.

```bash
git add .
git commit -m "feat: Adiciona nova funcionalidade de agendamento"
```

Procure seguir o padrão de [Commits Semânticos](https://www.conventionalcommits.org/en/v1.0.0/) para as mensagens de commit, o que ajuda a manter o histórico do projeto mais legível.

### 6. Envie Suas Alterações para o Seu Fork

Envie a sua branch com as alterações para o seu repositório "forkado" no GitHub.

```bash
git push origin minha-nova-funcionalidade
```

### 7. Abra um "Pull Request"

Com as suas alterações no seu fork, você pode agora solicitar que elas sejam incorporadas ao projeto original. Para isso, vá até a página do seu fork no GitHub e você verá um aviso para criar um "Pull Request". Clique no botão **Compare & pull request**.

Preencha o formulário do Pull Request com um título claro e uma descrição detalhada das alterações que você realizou. Se a sua contribuição resolve uma "Issue" existente, mencione o número da issue na descrição (por exemplo, `Resolve #42`).

### 8. Aguarde a Avaliação

Após a abertura do Pull Request, a equipe da Secretaria de Saúde de Juiz de Fora irá revisar o seu código. É possível que sejam solicitadas alterações ou que a equipe faça comentários para aprimorar a sua contribuição. Fique atento às notificações do GitHub para interagir durante o processo de revisão.

Assim que sua contribuição for aprovada, ela será mesclada ao projeto principal.

## Reportando Bugs e Sugerindo Melhorias

Se você encontrar um problema ou tiver uma ideia para uma nova funcionalidade, mas não tem tempo ou conhecimento para codificar a solução, você ainda pode contribuir abrindo uma **Issue** no repositório do projeto. Descreva o problema ou a sugestão com o máximo de detalhes possível.

---

Agradecemos o seu interesse e sua colaboração para aprimorar as ferramentas de saúde de Juiz de Fora!
