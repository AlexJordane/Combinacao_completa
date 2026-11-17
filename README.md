# Combinações Completas: O Método das Estrelas e Barras (*Stars and Bars*)

Material teórico e metodológico de apoio sobre **Análise Combinatória e Pensamento Combinatório**, desenvolvido no âmbito do **Instituto Federal do Espírito Santo (Ifes)** — Pós-Graduação / Licenciatura em Matemática.

O documento aborda o raciocínio combinatório subjacente aos problemas de seleção com repetição (combinações completas), conduzindo o leitor desde uma situação-problema intuitiva até a formalização algébrica por equações diofantinas lineares e a representação semiótica pelo método das estrelas e barras (*stars and bars*).

## Links de Acesso

- **Página do Projeto (GitHub Pages):** https://alexjordane.github.io/Combinacao_completa/
- **Documento em PDF:** [Combinacao_Completa.pdf](./Combinacao_Completa.pdf)
- **Código-fonte LaTeX:** [Combinacao_Completa.tex](./Combinacao_Completa.tex)
- **Repositório no GitHub:** https://github.com/AlexJordane/Combinacao_completa

---

## Estrutura do Material

1. **Capítulo 1 — O Problema Disparador:**
   - Parte do clássico *Problema dos Sorvetes* ("De quantos modos é possível comprar 4 sorvetes de uma só bola numa sorveteria que oferece 7 sabores diferentes?").
   - Analisa as propriedades centrais (a ordem não importa e há repetição de elementos) e constrói a modelagem por equação linear inteira não negativa ($x_1 + x_2 + \dots + x_7 = 4$).

2. **Capítulo 2 — O Método das Estrelas e Barras (*Stars and Bars*):**
   - Apresenta a representação semiótica e visual (com diagramas em TikZ) que estabelece a bijeção entre partições de objetos indistinguíveis em categorias distintas e sequências formadas por estrelas ($\bigstar$) e barras ($\mid$).
   - Desenvolve a resolução passo a passo utilizando o **Princípio Fundamental da Contagem**, **Combinação Simples** e **Permutação com Repetição**.

3. **Capítulo 3 — A Formalização Teórica Geral:**
   - Demonstra o **Teorema Fundamental das Combinações com Repetição**:
     $$CR_n^k = \binom{n + k - 1}{k} = \binom{n + k - 1}{n - 1}$$
   - Explora a variação com restrição de **soluções estritamente positivas** ($x_i \geqslant 1$), demonstrando o resultado $\binom{k - 1}{n - 1}$ tanto geometricamente (pelos espaços entre estrelas) quanto algebricamente (por mudança de variável).

4. **Capítulo 4 — Quadro de Sistematização Geral:**
   - Síntese operacional das fórmulas e parâmetros para consulta rápida.

5. **Capítulo 5 — Sugestão de Problemas Correlatos:**
   - Problemas propostos com gabarito envolvendo variáveis estritamente positivas, limites inferiores assimétricos (cotas mínimas diferenciadas) e restrição de teto superior com o Princípio da Inclusão-Exclusão.

---

## Arquivos do Repositório

- `Combinacao_Completa.tex`: Código-fonte em LaTeX (utiliza pacotes como `tikz`, `tcolorbox`, `amsmath`).
- `Combinacao_Completa.pdf`: Versão compilada pronta para leitura e impressão.
- `ifes.png`, `Educimat.png`, `CC.png`: Imagens institucionais e selo da licença Creative Commons utilizados na compilação do documento.

## Como Compilar o Código LaTeX

Para gerar o PDF a partir do arquivo `.tex`, utilize uma distribuição LaTeX (como TeX Live, MiKTeX ou Overleaf) e execute:

```bash
pdflatex Combinacao_Completa.tex
pdflatex Combinacao_Completa.tex
```
*(A dupla compilação garante a correta geração do sumário e das referências cruzadas).*

---

## Autoria e Licença

- **Autor:** Professor Alex Jordane (em colaboração com Inteligência Artificial, Gemini).
- **Licença:** Esta obra está licenciada sob uma Licença **Creative Commons Atribuição-NãoComercial-SemDerivações 4.0 Internacional (CC BY-NC-ND 4.0)**. O compartilhamento e a reprodução deste material são permitidos para fins didáticos, desde que citadas a fonte e a autoria.
