# 📝 Relatório do Laboratório 1 - Introdução ao Linux

**Nome:** [PEDRO HENRIQUE LOPES SABAINSK]  
**RA:** [10735777]  

---

## 💡 Orientações Importantes
Este relatório é sua oportunidade de documentar não apenas o que você fez, mas principalmente o que você aprendeu. Como temos apenas um encontro semanal, é importante que você seja o(a) protagonista do seu aprendizado.

Para elaborar um relatório completo e que realmente agregue valor ao seu aprendizado, siga estas dicas:

- 📚 **Vá além do repositório**: Os materiais fornecidos são apenas o ponto de partida. Busque vídeos no YouTube, tutoriais, documentações oficiais e artigos que expliquem os conceitos de diferentes perspectivas.
- 🔍 **Seja curioso**: Quando encontrar um comando novo, não apenas execute-o - entenda o que ele faz, suas opções e em que situações reais ele é utilizado.
- 💭 **Conecte com a realidade**: Pesquise como empresas como Netflix, Google e Amazon utilizam Linux em seus servidores. Isso tornará o aprendizado mais tangível e relevante para sua carreira.
- 🎯 **Pratique além do lab**: Instale uma VM em casa, experimente distribuições diferentes, quebre coisas e conserte - é assim que se aprende de verdade!
- 🤝 **Compartilhe conhecimento**: Encontrou um tutorial bacana? Um comando útil? Compartilhe com seus colegas! O aprendizado colaborativo acelera o desenvolvimento de todos.

- **Lembre-se**: Em TI, a capacidade de aprender por conta própria é tão importante quanto o conhecimento técnico. Use este laboratório como uma oportunidade para desenvolver ambas as habilidades. Profissionais que sabem buscar, filtrar e aplicar informações são os mais valorizados no mercado!

## 1️⃣ Parte 1 - Experiência com Comandos Básicos

### 🔍 Primeiras Impressões

**1. Qual foi o comando mais útil que você aprendeu? Por quê?**

```
[O comando grep foi o mais útil porque permite buscar padrões específicos dentro de arquivos, o que é extremamente prático para filtrar logs, encontrar informações em documentos grandes e analisar saídas de outros comandos.]
```

**2. Qual comando você achou mais difícil de entender? Por quê?**

```
[O redirecionamento com > e >> foi inicialmente desafiador porque exigia entender a diferença entre sobrescrever e acrescentar a arquivos. ]
```

**3. Você conseguiu completar todos os exercícios? Se não, quais dificuldades encontrou?**

```
[Sim, consegui completar todos os exercícios. As principais dificuldades foram lembrar a sintaxe exata de alguns comandos mais complexos e a navegação entre diretórios usando caminhos absolutos e relativos. ]
```

---

## 2️⃣ Parte 2 - Comparação Windows vs Linux

### 💻 Diferenças Observadas

**1. Liste 3 diferenças principais entre usar Windows e Linux que você notou:**

```
1. [Interface de linha de comando - Linux prioriza o terminal como ferramenta principal, enquanto Windows foca mais na interface gráfica]

2. [Estrutura de diretórios - Linux usa uma hierarquia unificada (/, home, etc, bin) diferente da estrutura de unidades (C:, D:) do Windows]

3. [Instalação de software - Linux usa gerenciadores de pacotes (apt, yum) enquanto Windows geralmente usa instaladores .exe ou .msi]
```

**2. Para tarefas do dia a dia, qual sistema você prefere? Por quê?**

```
[Para tarefas do dia a dia, prefiro o Windows devido à sua compatibilidade com softwares comerciais e jogos, além da interface mais amigável para usuários comuns. No entanto, para desenvolvimento e tarefas técnicas, o Linux é superior devido à sua flexibilidade e ferramentas de linha de comando.]
```

**3. Em que situações o Linux seria mais vantajoso que o Windows?**

```
[O Linux é mais vantajoso em servidores web, desenvolvimento de software, ambientes de cloud computing, containers Docker, automação de tarefas via scripting, segurança e quando se busca estabilidade e custo zero com licenças. Também é ideal para máquinas com hardware limitado.]
```

---

## 3️⃣ Parte 3 - Reflexões sobre Sistemas Operacionais

### 🎯 Importância para SI

**1. Por que é importante para um profissional de Sistemas de Informação conhecer Linux?**

```
[O Linux é fundamental para profissionais de SI porque é o sistema operacional predominante em servidores, nuvem e infraestrutura crítica.]
```

**2. Como o conhecimento de comandos Linux pode ajudar na gestão de TI de uma empresa?**

```
[O conhecimento de comandos Linux permite automatizar processos, monitorar sistemas, solucionar problemas rapidamente via terminal, gerenciar usuários e permissões, além de otimizar recursos computacionais. Isso aumenta a eficiência operacional e reduz custos com licenças de software.]
```

**3. Cite 3 aplicações práticas do Linux no ambiente empresarial:**

```
1. [Servidores Web e Aplicações - Hospedagem de sites e APIs usando Apache/Nginx]
2. [Infraestrutura em Nuvem - Base para AWS, Google Cloud e Azure]
3. [Segurança e Redes - Firewalls (iptables), VPNs e ferramentas de monitoramento]
```

---

## 4️⃣ Parte 4 - Comandos e Outputs

### 📊 Análise dos Resultados

**1. Quantos arquivos você criou no diretório `outputs/`?**

```
Total de arquivos: __26___
```

**2. Qual foi o tamanho total do diretório `meu_diretorio` que você criou?**

```bash
# Use o comando: du -sh meu_diretorio/
Tamanho: __36B___
```

**3. Liste os 5 comandos que você mais usou durante o laboratório:**

```
1. __ls___
2. __cd___
3. __cp___
4. __mkdir___
5. __cat___
```

---

## 5️⃣ Parte 5 - GitHub e Versionamento

### 🔧 Experiência com Git

**1. Você já tinha usado Git antes? Se sim, em que contexto?**

```
[Nunca tinha utilizado o Git antes]
```

**2. Qual a importância do versionamento de código para empresas?**

```
[O versionamento de código é crucial para empresas pois permite o controle sistemático de alterações no código-fonte, facilitando a colaboração entre equipes de desenvolvimento. Ele possibilita o rastreamento de mudanças, a reversão para versões estáveis em caso de erros e a manutenção de diferentes linhas de desenvolvimento simultaneamente.]
```

---

## 6️⃣ Parte 6 - Aplicações Futuras

### 🚀 Próximos Passos

**1. Que tipo de tarefas você poderia automatizar usando comandos Linux?**

```
[Com os comandos Linux, poderia automatizar backups periódicos de bancos de dados usando scripts com cron, e automatizar o deployment de aplicações através de pipelines CI/CD que executam testes, build e deploy automaticamente. Além disso, poderia criar scripts para monitoramento automático de recursos do sistema (CPU, memória, disco) e alertas por email quando atingissem limites críticos.]
```

**2. Você consideraria usar Linux como sistema operacional principal? Por quê?**

```
[Sim, consideraria usar Linux como sistema principal devido à sua estabilidade, segurança superior e custo zero com licenças. A flexibilidade para personalizar o ambiente de desenvolvimento, a grande variedade de ferramentas de linha de comando para automação e o fato de ser o ambiente padrão para desenvolvimento web e DevOps tornam-no ideal para profissionais de TI. ]
```

---

## 💡 Feedback do Laboratório

**O que você achou mais interessante no laboratório?**

```
[Achei mais interessante a prática com comandos essenciais do Linux como ls, cd, cp, mv e a manipulação de arquivos e diretórios. A experiência com redirecionamento de entrada/saída e pipes (|, >, >>) foi muito valiosa para entender como automatizar tarefas. A exploração da estrutura de diretórios e permissões também foi fundamental para compreender o funcionamento do sistema.]
```

**O que poderia ser melhorado para próximos labs?**

```
[Seria interessante incluir mais exercícios práticos com scripts de automação simples usando bash]
```

---

## 📤 Checklist Final

Antes de enviar, verifique:

- [x ] Preenchi todas as seções do relatório
- [x ] Completei todos os exercícios em EXERCICIOS.md
- [x ] Salvei todos os outputs na pasta outputs/
- [x] Criei o diretório meu_diretorio com os arquivos solicitados
- [x] Fiz git add, commit e push

---