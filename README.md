# Calculadora de Prova de Concurso Melhorada

Uma ferramenta interativa para auxiliar candidatos de concursos públicos a analisar seu desempenho em provas, planejar estudos e gerar cronogramas personalizados.

## Descrição

A **Calculadora de Prova de Concurso Melhorada** é uma aplicação web que permite aos usuários inserir informações detalhadas sobre suas matérias de estudo, como número de questões, valor de cada questão e quantidade de acertos. Com base nesses dados, a ferramenta:

- Calcula o desempenho geral e individual em cada matéria.
- Gera gráficos visuais para facilitar a compreensão do desempenho.
- Sugere uma divisão otimizada do tempo de estudo com base nas áreas que precisam de mais atenção.
- Integra com uma API para gerar um cronograma de estudos personalizado.

## Funcionalidades

- **Inserção de Dados Personalizados:** Adicione informações específicas de cada matéria.
- **Análise de Desempenho:** Visualize porcentagens de acertos, erros e pontuação total.
- **Divisão Otimizada do Tempo de Estudo:** Receba sugestões de como alocar seu tempo de estudo semanal.
- **Geração de Gráficos Dinâmicos:** Visualize seu desempenho através de gráficos interativos.
- **Cronograma Personalizado:** Gere um cronograma de estudos detalhado utilizando inteligência artificial.
- **Exportação de Relatório:** Baixe um relatório completo em formato HTML para referência futura.

## Como Utilizar

1. **Obtenha sua Chave API:**
   - Acesse [https://console.groq.com/settings/profile](https://console.groq.com/settings/profile) para obter sua chave API.
   - Insira a chave no campo "Sua Chave API" na aplicação.

2. **Adicione as Matérias:**
   - Preencha o nome da matéria, quantidade de questões, valor de cada questão e quantidade de acertos.
   - Clique em "Adicionar Matéria" para inserir os dados na calculadora.

3. **Configure os Detalhes do Estudo:**
   - Insira o nome do concurso.
   - Especifique o tempo de estudo diário em horas.
   - Indique quantos dias por semana você pretende estudar.
   - Selecione o período disponível para estudo (Matutino, Vespertino, Noturno ou Integral).

4. **Calcule o Resultado:**
   - Clique em "Calcular Resultado" para gerar a análise completa.
   - Visualize o desempenho geral, divisão do tempo de estudo e áreas para melhorar.

5. **Gere o Cronograma de Estudos:**
   - A aplicação utilizará a API para criar um cronograma personalizado baseado nos dados fornecidos.

6. **Baixe o Relatório:**
   - Clique em "Baixar Resultado" para exportar um relatório detalhado em formato HTML.

## Requisitos

- **Navegador Web:** Qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
- **Conexão com a Internet:** Necessária para acessar a API e gerar o cronograma.
- **Chave API Válida:** Obtenha em [https://console.groq.com/keys](https://console.groq.com/keys).

## Instalação

Nenhuma instalação é necessária. Basta clonar o repositório ou baixar os arquivos e abrir o `index.html` em seu navegador web.

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/calculadora-concurso-melhorada.git
```

## Contribuição

Contribuições são bem-vindas! Se você deseja melhorar este projeto:

1. Faça um fork do projeto.
2. Crie uma nova branch com sua feature ou correção: `git checkout -b minha-feature`.
3. Commit suas alterações: `git commit -m 'Minha nova feature'`.
4. Faça push para a branch: `git push origin minha-feature`.
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## Contato

Para quaisquer dúvidas ou sugestões:

- **Email:** seu-email@example.com
- **GitHub:** [seu-usuario](https://github.com/seu-usuario)

---

**Nota:** Lembre-se de manter sua chave API segura e não compartilhá-la publicamente.
