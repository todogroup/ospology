---
title: "Capítulo 5: Gerenciando a segurança de open source"
status: Completed
weight: 60
---

# Capítulo 5: Gerenciando a segurança de open source

## Índice

- [Introdução](#introdução)
- [Treinamento e Educação](#treinamento-e-educação)
- [Etapas principais](#etapas-principais)
- [Aplicando isso à sua organização](#aplicando-isso-à-sua-organização)
- [Recursos e notas de rodapé](#recursos-e-notas-de-rodapé)


## Introdução

**NOTA:** Este capítulo foi desenvolvido com a experiência dos representantes da Fundação de Segurança de Código Aberto ou em inglês Open Source Security Foundation (OpenSSF), com o apoio do TODO Group

O software open source é uma parte importante da cadeia de suprimentos de software. Por isso, é responsabilidade de um Escritório de Programa de Código Aberto ou em inglês Open Source Program Office (OSPO) ajudar a proteger a cadeia de suprimentos de Software de Código Aberto ou em Inglês Open Source Software (OSS). Isso inclui tarefas como:

- Ajudar equipes de desenvolvimento a avaliar a segurança do OSS que usam em produtos.
- Incentivar equipes de desenvolvimento a contribuir com projetos de código aberto para ajudar a melhorar sua segurança.
- Seguindo as melhores práticas de desenvolvimento de software seguro em projetos de código aberto que a empresa mantém, contribui ou lidera.

Este capítulo inclui recursos úteis para ajudar OSPOs e desenvolvedores de open source a aplicar as melhores práticas de desenvolvimento de software seguro e de cadeia de suprimentos, tanto no software que usam quanto no software que criam.

De certa forma, a segurança é como qualquer outro requisito. No entanto, muitos desenvolvedores de software e seus gerentes não receberam treinamento suficiente em segurança. Além disso, a segurança envolve a defesa contra invasores inteligentes e, muitas vezes, depende de como todo o sistema funciona em conjunto — não apenas de uma parte.

Corrigir problemas de segurança mais tarde costuma ser caro. É melhor preveni-los, reduzir suas chances ou impacto e estar preparado caso algo dê errado. É importante planejar desde o início e alocar recursos (como tempo e dinheiro) para lidar com a segurança adequadamente.

Softwares open source podem ter uma vantagem em termos de segurança, pois permitem revisão em massa por pares e seguem o princípio de "open design" — mas esses benefícios não acontecem automaticamente.

## Treinamento e Educação

Muitos desenvolvedores e gerentes de software não sabem o que precisam saber sobre segurança. Essa falta de conhecimento costuma causar problemas. Aqui estão algumas áreas importantes para entender, juntamente com links para cursos gratuitos do OpenSSF que podem ajudar. Esses cursos específicos não são obrigatórios, mas é importante que todos os envolvidos no desenvolvimento de software recebam o treinamento adequado.

Gerentes (de projetos de código aberto e fechado) devem entender como gerenciar o desenvolvimento seguro de software. Isso inclui conhecer os termos básicos de segurança, como gerenciar riscos, como incorporar a segurança ao design, como proteger todos os ambientes, como identificar riscos precocemente e como definir expectativas claras com as partes interessadas. Os gerentes também devem entender o que seus desenvolvedores precisam aprender. Se ainda não receberam treinamento, podem fazer o curso gratuito Open Source Security Foundation OpenSSF. Segurança para Gerentes de Desenvolvimento de Software (LFD125)¹.

Os desenvolvedores devem fazer um curso sobre desenvolvimento seguro de software. Isso inclui como construir software seguro durante o planejamento, design, codificação, testes e lançamento. Os desenvolvedores também precisam saber como avaliar software de terceiros. Eles devem entender as vulnerabilidades comuns (como as listadas no Top Ten da OWASP para aplicativos web)² e CWE Top 25 para software em geral³) e como evitá-los. Eles também devem saber como proteger ambientes de desenvolvimento e responder a relatórios de vulnerabilidades. Caso não tenham recebido esse treinamento, podem fazer o curso gratuito do OpenSSF Desenvolvendo Software Seguro (LFD121)⁴.

Tanto desenvolvedores quanto gerentes devem compreender todas as leis ou regulamentações que precisam seguir. Por exemplo, qualquer pessoa envolvida com software que possa ser usado na União Europeia (UE) deve compreender a Lei de Resiliência Cibernética ou em inglês Cyber Resilience Act (CRA) da UE. Isso inclui entender a que a CRA se aplica, às diferentes funções que ela define (como fabricante ou administrador de código aberto) e as responsabilidades legais que ela cria. Como a CRA abrange uma ampla gama de funções e inclui penalidades severas, para aqueles que precisam entendê-la podem fazer o curso gratuito do OpenSSF "Compreendendo a Lei de Resiliência Cibernética (CRA) da União Europeia (UE)" (LFEL1001)⁵.


## Etapas principais

### Para desenvolver seu próprio software:

1. Revise o Guia Conciso do OpenSSF para Desenvolvimento de Software Mais Seguro, que contém links para recursos práticos⁶.
2. Trabalhar para atender à linha de base do OpenSSF, uma pequena lista de verificações de segurança⁷.
3. Ganhe um selo de Melhores Práticas do OpenSSF para o seu projeto. Comece com "aprovação" e planeje alcançar "prata" ou "ouro" ao longo do tempo⁸.
4. Melhore sua pontuação no OpenSSF Scorecard. Embora isso seja frequentemente usado para avaliar outros projetos, também pode ajudá-lo a medir sua própria pontuação⁹.

### A maioria dos softwares modernos utilizam outros softwares. Escolha e use componentes open source com cuidado:

1. Use o Guia Conciso para Avaliar Software Open Source¹⁰.
2. Verifique novamente os nomes dos softwares para evitar ataques de "typosquatting" (onde pacotes maliciosos têm nomes semelhantes aos confiáveis).
3. Use o OpenSSF Scorecard para avaliar o software antes de usá-lo⁹.

### Proteja seus ambientes, incluindo desenvolvimento, construção, teste e distribuição:

1. Use autenticação multifator (MFA) para dificultar o acesso de invasores.
2. Proteja seu ambiente de construção. Consulte o OpenSSF SLSA para obter mais orientações¹¹.

### Use ferramentas automatizadas em seu pipeline de integração contínua (CI) para detectar problemas de segurança precocemente:

1. Use vários tipos de ferramentas, pois cada uma pode encontrar problemas diferentes, consulte o Guia de Ferramentas de Segurança¹².
2. Para novos projetos ("campo verde"), habilite todas as verificações de segurança. Para projetos mais antigos ("campo marrom"), comece com as verificações mais importantes para que os relatórios sejam gerenciáveis.
3. Habilitar ferramentas que detectam vulnerabilidades conhecidas em componentes reutilizados

Prepare-se para relatórios de vulnerabilidades — eles podem ocorrer em qualquer projeto. Explique claramente como as pessoas podem relatar vulnerabilidades. Projetos de código aberto devem consultar o Guia do OpenSSF para implementar um processo coordenado de divulgação de vulnerabilidades¹³.


## Aplicando isso à sua organização

Melhorar a segurança do software livre (OSS) na sua organização não se resume apenas ao uso de ferramentas. Também exige mudanças na cultura e nos processos de trabalho diários.

Um dos primeiros passos é construir uma mentalidade em que a segurança seja responsabilidade de todos, não apenas tarefa de uma pequena equipe. Os líderes devem comunicar claramente a importância do desenvolvimento seguro de software e apoiar isso com tempo, recursos e reconhecimento para aqueles que trabalham nele.

As práticas de segurança devem fazer parte do trabalho diário de desenvolvimento, e não ser algo separado. Por exemplo, em vez de executar verificações de segurança apenas esporadicamente, inclua ferramentas como scorecards e varreduras de vulnerabilidades em seu pipeline regular de CI/CD. Isso ajuda a tornar a segurança uma parte normal e esperada de como sua equipe desenvolve software.

Treinamento e educação devem ocorrer regularmente, não apenas uma vez. Desenvolvedores e gerentes devem ser incentivados a aprender os conceitos básicos de desenvolvimento seguro de software. Isso pode incluir cursos gratuitos do OpenSSF e outros programas. Certifique-se de que suas equipes saibam que aprender sobre segurança é importante e será reconhecido. Isso gera interesse e responsabilidade a longo prazo.

Também ajuda ser transparente sobre o progresso da segurança. Incentive as equipes a monitorar e compartilhar seu progresso em metas como obter emblemas de Melhores Práticas ou melhorar os resultados do Scorecard. Isso cria um ambiente positivo onde as equipes se ajudam e melhoram juntas, em vez de se sentirem culpadas quando algo dá errado.

Por fim, apoie a melhoria contínua. Segurança não é algo que se termina — ela está sempre mudando. Estabeleça horários regulares para revisar riscos, atualizar ferramentas e práticas e compartilhar o que suas equipes aprenderam. Dê às equipes a liberdade de tomar decisões sobre segurança no início do processo de desenvolvimento, não apenas no final ou após a ocorrência de um problema.

Ao criar uma cultura de responsabilidade compartilhada, adicionar segurança ao trabalho diário, investir em aprendizado, incentivar a abertura e melhorar ao longo do tempo, sua organização pode fazer um progresso real na proteção do OSS que cria e usa.


## Recursos e notas de rodapé

### Recursos

- [OpenSSF](https://openssf.org)
- [OWASP](https://owasp.org/)
- [CWE](https://cwe.mitre.org/index.html)

### Notas de rodapé

1. Curso OpenSSF da Open Source Security Foundation Segurança para Gerentes de Desenvolvimento de Software (LFD125) https://training.linuxfoundation.org/training/seguranca-para-gerentes-de-desenvolvimento-de-software-lfd125/

2. OWASP Top Ten para aplicativos da web: https://owasp.org/www-project-top-ten/

3. CWE Top 25 para software geral: https://cwe.mitre.org/top25/

4. Curso OpenSSF Desenvolvimento de Software Seguro (LFD121): https://training.linuxfoundation.org/training/desenvolvendo-software-seguro-lfd121/

5. https://training.linuxfoundation.org/express-learning/entendendo-a-lei-da-resiliência-cibernética-da-ue-cra-lfel1001/

6. Guia conciso para desenvolver software mais seguro: https://best.openssf.org/Guia-conciso-para-o-desenvolvimento-de-software-mais-seguro

7. https://baseline.openssf.org/

8. Selo de Melhores Práticas do OpenSSF https://www.bestpractices.dev/

9. Scorecard do OpenSSF: https://github.com/ossf/scorecard

10. Guia conciso para avaliação de software de código aberto: https://best.openssf.org/Guia-conciso-para-avaliação-de-software-de-código-aberto

11. OpenSSF SLSA: https://slsa.dev/

12. Guia de ferramentas de segurança: https://github.com/ossf/wg-security-tooling/blob/main/guide.md#readme

13. Guia do OpenSSF para implementar um processo coordenado de divulgação de vulnerabilidades: https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md#readme
