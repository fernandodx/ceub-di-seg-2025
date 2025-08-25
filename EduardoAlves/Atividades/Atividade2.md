# Atividade de Web Design - Aplicativo ZenFlow

## Aplicativo Fictício: ZenFlow
**Categoria:** Bem-estar e Mindfulness
**Propósito:** Aplicativo para meditação, relaxamento e acompanhamento do bem-estar mental

---

## 1. Paleta de Cores

| Função | Cor | Hexadecimal | Justificativa |
|--------|-----|-------------|---------------|
| **Primária** | Verde Sálvia | `#8FBC8F` | Transmite tranquilidade, equilíbrio e conexão com a natureza. É uma cor que reduz o estresse e promove a sensação de calma, essencial para um app de mindfulness. |
| **Secundária** | Azul Sereno | `#6A9BD1` | Complementa o verde criando uma atmosfera relaxante. O azul está associado à paz interior e à clareza mental, valores centrais do aplicativo. |
| **Destaque** | Coral Suave | `#FF7F7F` | Usado em botões de ação e elementos interativos. O coral suave chama atenção sem ser agressivo, mantendo a harmonia visual. |
| **Fundo** | Branco Pérola | `#FAFAFA` | Fundo neutro e clean que reduz distrações visuais, permitindo foco total no conteúdo de meditação e exercícios de respiração. |
| **Texto** | Cinza Carvão | `#2C2C2C` | Tom escuro suave que garante excelente legibilidade sem o contraste severo do preto puro, mantendo a suavidade visual. |

**Ferramenta utilizada:** Coolors (coolors.co)

---

## 2. Tipografia

### Fonte Primária - Títulos
**Nome:** Merriweather
**Link:** [Google Fonts - Merriweather](https://fonts.google.com/specimen/Merriweather)
**Exemplo:** 
```
Encontre seu equilíbrio interior
Meditação guiada de 10 minutos
```

**Justificativa:** Merriweather é uma fonte serif elegante e altamente legível em telas digitais. Sua personalidade clássica e acolhedora transmite confiança e serenidade, criando uma atmosfera de sabedoria e tranquilidade ideal para títulos de sessões de meditação.

### Fonte Secundária - Corpo do Texto
**Nome:** Open Sans
**Link:** [Google Fonts - Open Sans](https://fonts.google.com/specimen/Open+Sans)
**Exemplo:**
```
Respire profundamente e permita-se relaxar. Este exercício de 
mindfulness vai ajudá-lo a encontrar clareza mental e reduzir 
a ansiedade do dia a dia.
```

**Justificativa:** Open Sans é uma fonte sans-serif extremamente legível e neutra, perfeita para textos longos de instruções de meditação. Sua simplicidade não compete com o conteúdo, garantindo fácil leitura durante exercícios de respiração e meditações guiadas.

---

## 3. Estudo de Guidelines - Material Design (Elevação e Profundidade)

### Princípio Estudado: Material Design - Sistema de Elevação

O sistema de elevação do Material Design é um princípio fundamental que simula profundidade através de sombras e camadas, criando uma hierarquia visual clara e intuitiva. Este conceito baseia-se na metáfora do papel físico, onde elementos podem estar empilhados em diferentes alturas, gerando sombras naturais. A elevação é medida em unidades de densidade de pixels (dp) e varia de 0dp (elementos no plano base) até 24dp (elementos flutuantes como modais). Cada nível de elevação tem uma sombra específica que comunica a importância e interatividade do elemento. Elementos mais elevados parecem "flutuar" sobre outros, indicando maior prioridade ou estado ativo. O sistema também responde a interações do usuário: botões podem elevar-se quando pressionados, cartões podem destacar-se ao serem tocados. Além disso, a elevação deve ser usada com parcimônia para evitar confusão visual, mantendo uma hierarquia clara entre elementos de interface. A consistência na aplicação das elevações em todo o aplicativo garante uma experiência coesa e previsível para o usuário.

### Aplicação Prática no ZenFlow

No aplicativo ZenFlow, o sistema de elevação seria aplicado de forma estratégica para criar uma experiência visual harmoniosa e funcional:

- **Cards de Meditação (4dp):** As sessões de meditação seriam apresentadas em cards com elevação média, destacando-se do fundo sem criar peso visual excessivo
- **Botão de Play Principal (8dp):** O botão para iniciar meditações teria elevação mais alta, sinalizando sua importância como ação principal
- **Menu de Navegação (2dp):** Barra inferior com elevação sutil para separá-la do conteúdo principal
- **Modal de Configurações (16dp):** Janelas de configuração flutuariam significativamente sobre o conteúdo, indicando sobreposição contextual
- **Estados Interativos:** Cards se elevariam de 4dp para 6dp ao toque, proporcionando feedback visual imediato

Esta aplicação manteria a sensação de calma do app enquanto fornece orientação visual clara através da profundidade simulada.
