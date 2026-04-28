# Sobre esta pesquisa

Esta pesquisa analisa como empresas do grupo J&F e grandes empresas de tecnologia aplicam acessibilidade na prática, investigando como isso impacta inclusão, conformidade legal e o desenvolvimento de produtos digitais.: Como empresas reais implementam (ou ignoram) acessibilidade?



# Principais descobertas

Lista de bullet points encontrados:

1. A JBS se destaca dentro do grupo J&F por ações estruturadas de inclusão, como centros de capacitação para PcDs e contratação acima da cota  legal.Fontes: Relatório de Sustentabilidade JBS 2024/2025

2. 

3. 

4. 

5. Existe uma série de diretrizes chamadas WCAG internacionais do W3C para tornar sites e aplicativos acessíveis para pessoas com deficiências, que funcionam como um guia para tornar interfaces perceptíveis, operáveis, compreensíveis e robustas

# Como isso afeta o nosso trabalho como desenvolvedores

Para muitas pessoas, a tecnologia torna as coisas mais fáceis. Para pessoas com deficiência, a tecnologia torna as coisas possíveis. 

Quando uma empresa adota uma política de acessibilidade, o trabalho do desenvolvedor deixa de ser apenas implementar funcionalidades e passa a incorporar, de forma estrutural, a responsabilidade de garantir que o produto digital seja utilizável por qualquer pessoa, independentemente de limitações físicas, cognitivas ou mesmo de contexto tecnológico. Isso muda profundamente tanto o processo quanto os critérios de qualidade do desenvolvimento. A acessibilidade deixa de ser um “extra” e passa a ser um requisito desde o início do projeto, influenciando decisões de arquitetura, design, código e testes ao longo de todo o ciclo de vida do produto. 

Na prática, isso significa que o desenvolvedor precisa dominar padrões específicos, principalmente as diretrizes WCAG, que funcionam como um guia técnico para tornar interfaces perceptíveis, operáveis, compreensíveis e robustas. Essas diretrizes não são apenas recomendações abstratas: elas impactam diretamente o código, exigindo uso correto de HTML semântico, descrição de imagens, navegação por teclado, compatibilidade com leitores de tela e cuidado com contraste e legibilidade. Além disso, o desenvolvedor passa a utilizar ferramentas de validação e testes de acessibilidade de forma contínua, integrando esse tipo de verificação ao fluxo de desenvolvimento, assim como já acontece com testes de performance ou segurança. 

Outro ponto importante é que a política de acessibilidade amplia o público considerado no desenvolvimento. Não se trata apenas de pessoas com deficiência permanente, mas também de usuários com conexão lenta, dispositivos limitados ou dificuldades temporárias. Isso obriga o desenvolvedor a pensar em soluções mais resilientes, como otimização de carregamento, interfaces simples e adaptáveis, e experiências que funcionem em diferentes condições de uso. Em contextos como o Brasil e outros países do Sul Global, onde o acesso à internet pode ser instável e predominantemente móvel, essa preocupação é ainda mais relevante e afeta diretamente decisões técnicas de implementação. 

Além das mudanças técnicas, há também uma transformação organizacional no papel do desenvolvedor. Em empresas com políticas de acessibilidade, ele deixa de ser apenas executor e passa a atuar como agente de inclusão, colaborando com designers, product managers e stakeholders para garantir que a acessibilidade seja considerada desde o planejamento até a entrega. Isso inclui participar de testes com usuários reais, inclusive pessoas com deficiência, e adaptar soluções com base nesses feedbacks, o que reforça a ideia de que acessibilidade não é uma etapa isolada, mas um processo contínuo. 

Por fim, a existência de uma política formal também muda o nível de exigência e responsabilidade. A acessibilidade passa a estar ligada não só à qualidade do produto, mas também a questões legais, reputacionais e de mercado. Ainda assim, estudos mostram que, sem políticas claras e treinamento, muitos desenvolvedores tendem a aplicar apenas critérios básicos ou negligenciar práticas mais avançadas, o que evidencia como diretrizes institucionais são determinantes para transformar efetivamente o trabalho técnico. Em outras palavras, quando a acessibilidade é uma política da empresa, o desenvolvedor deixa de apenas “escrever código” e passa a construir experiências digitais verdadeiramente inclusivas, assumindo um papel mais estratégico, crítico e responsável dentro do processo de desenvolvimento.



Após a turma ler esse documento, é esperado que partam a usar melhor as boas praticas de acessibilidade em seus serviços, sempre colocando textos alternativos em hmtl, tratar acessibilidade como requisito dos projetos, seguir os padrões WCAG, entre outros.
E

Exemplos em código:

- texto alternativo: <tag alt="exemplo de texto explicativo" />
- HTML semantico: 
<!-- Errado -->
<div onclick="enviarFormulario()">Enviar</div>

<!-- Correto -->
<button onclick="enviarFormulario()">Enviar</button>

- formularios semanticos e adequados:
<label for="email">Email:</label>
<input type="email" id="email" name="email">

- Seguir as 10 heuristicas de Nielsen: visibilidade do sistema, correspondência com o mundo real, controle do usuário, consistência, prevenção de erros, reconhecimento, flexibilidade, design minimalista, recuperação de erros e ajuda


# Referencias

https://www.thewcag.com/lawsuits/brown-v-bank-of-america-2000
https://www.ecommercebrasil.com.br/noticias/so-29-dos-sites-brasileiros-foram-aprovados-em-todos-os-testes-de-acessibilidade-mostra-pesquisa 
Microsoft
https://www.microsoft.com/accessibility/
https://support.microsoft.com/en-us/windows/discover-windows-accessibility-features-8b1068e6-d3b8-4ba8-b027-133dd8911df9  
https://www.microsoft.com/en-us/windows/tips/accessibility
Apple 
https://www.apple.com/accessibility/
https://support.apple.com/accessibility
Google 
https://www.google.com/accessibility/
https://support.google.com/accessibility/
USB Implementers Forum
https://www.usb.org/