# PRUMO - Simulador de Conciliação Jurídica

## 📋 Sobre o Projeto

O **PRUMO** é uma aplicação web desenvolvida uma maratona de inovação jurídica com o tema **"Simples é o Certo, Reconstruindo o Futuro em Redes"**. 

O sistema permite que jurisdicionados simulem cenários de conciliação, comparando as vantagens de aceitar um acordo versus prosseguir para julgamento, fornecendo informações detalhadas sobre tempo, custos, probabilidades e um roadmap completo do processo.

## 🎯 Funcionalidades Principais

### 💡 Simulação Comparativa
- **Cenário 1**: Aceitar acordo proposto
- **Cenário 2**: Prosseguir para julgamento
- Análise de tempo, valores, probabilidades e custos

### 📊 Cálculos Inteligentes (falta integrar)
- Algoritmos baseados em dados reais do CNJ
- Fatores de complexidade e qualidade de evidências
- Estatísticas por estado e tipo de juizado
- Tendências históricas e projeções

### 🗺️ Roadmap Detalhado
- Cronograma completo de cada cenário
- Etapas processuais com prazos estimados
- Interface visual com timeline interativa

### 🎯 Sistema de Recomendações
- Análise automatizada dos dados inseridos
- Recomendações personalizadas com nível de confiança
- Identificação de fatores decisivos


## 🚀 Como Executar

### Opção 1: Abrir Diretamente
1. Extraia todos os arquivos em uma pasta
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. A aplicação funcionará completamente offline

### Algoritmos de Cálculo

#### Tempo Estimado
```
Tempo = (TempoBase × FatorComplexidade × FatorCongestionamento) + TempoAdicionalTipo
```

#### Probabilidade de Sucesso
```
Probabilidade = (TaxaSucessoJuizado + TaxaSucessoTipo) / 2
               × FatorComplexidade 
               × FatorQualidadeEvidencias
```
### Tipografia
- **Fonte**: Inter (Google Fonts)
- **Escalas**: Modular scale de 1.125
- **Pesos**: 300, 400, 500, 600, 700

### Componentes
- **Cards**: Elevação com sombras suaves
- **Formulários**: Validação em tempo real
- **Botões**: Estados interativos
- **Timeline**: Progressão visual
- **Métricas**: Cards informativos

## 📊 Metodologia de Cálculo

### Dados Base por Juizado

| Juizado | Tempo Base (dias) | Taxa Sucesso (%) | Congestionamento |
|---------|------------------|------------------|------------------|
| Cível | 180 | 75 | 1.2-1.6 |
| Criminal | 120 | 80 | 1.0-1.4 |
| Fazenda Pública | 360 | 60 | 1.4-2.0 |
| Trabalho | 240 | 85 | 1.2-1.7 |
| Família | 300 | 70 | 1.3-1.8 |

### Fatores de Complexidade

| Complexidade | Multiplicador | Impacto Sucesso |
|--------------|---------------|-----------------|
| Baixa | 0.8x | +10% |
| Média | 1.0x | 0% |
| Alta | 1.5x | -15% |

### Qualidade das Evidências

| Qualidade | Multiplicador Sucesso | Descrição |
|-----------|----------------------|-----------|
| Forte | 1.2x | Documentação sólida |
| Média | 1.0x | Algumas lacunas |
| Fraca | 0.7x | Evidências limitadas |

## 🔧 Funcionalidades Avançadas

### Validação Inteligente
- Validação em tempo real dos campos
- Feedback visual imediato
- Validação cruzada entre campos
- Mensagens de erro contextuais

### Interface Responsiva
- Design mobile-first
- Breakpoints otimizados
- Componentes adaptativos
- Navegação touch-friendly

### Acessibilidade
- Semântica HTML adequada
- Contraste de cores conforme WCAG
- Navegação via teclado
- Screen reader friendly

### Performance
- CSS e JS otimizados
- Lazy loading de animações
- Debounce em eventos frequentes
- Memory management adequado

## 🧪 Dados de Teste

### Cenário Exemplo 1: Favor ao Acordo
- **Juizado**: Especial Cível
- **Estado**: São Paulo
- **Tipo**: Direito do Consumidor
- **Valor Acordo**: R$ 2.500
- **Valor Pedido**: R$ 4.000
- **Complexidade**: Baixa
- **Evidências**: Forte

### Cenário Exemplo 2: Favor ao Julgamento
- **Juizado**: Especial Cível
- **Estado**: Rio Grande do Sul
- **Tipo**: Indenização
- **Valor Acordo**: R$ 1.000
- **Valor Pedido**: R$ 8.000
- **Complexidade**: Média
- **Evidências**: Forte

## 🔮 Roadmap de Melhorias

### Versão 2.0 (Próximas Features)
- [ ] Integração com APIs reais (DataJud/CNJ)
- [ ] Dashboard administrativo para juízes
- [ ] Sistema de notificações via WhatsApp
- [ ] Geração de relatórios PDF
- [ ] Histórico de simulações do usuário

### Versão 3.0 (Futuro)
- [ ] Machine Learning para predições
- [ ] Integração com sistemas dos tribunais
- [ ] App mobile nativo
- [ ] Análise de jurisprudência automática
- [ ] Chatbot jurídico integrado

## 🤝 Contribuições

### Como Contribuir
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

### Padrões de Código
- **JavaScript**: ES6+, JSDoc comments
- **CSS**: BEM methodology, CSS Custom Properties
- **HTML**: Semântico, acessível
- **Commits**: Conventional Commits

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais e de hackathon. É livre para uso, modificação e distribuição.

## 👥 Equipe de Desenvolvimento

Nicolly Mayara Xavier Lima - nicollymayara078@gmail.com

**PRUMO** - *"Simples é o Certo, Reconstruindo o Futuro em Redes"*
