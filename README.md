# 🚁 Drone Scanner 3D - Simulação de Mapeamento Aéreo

Uma simulação 3D avançada de um drone realizando mapeamento aéreo de território indígena, desenvolvida com Three.js e tecnologias web modernas.

![Drone Scanner Demo](https://img.shields.io/badge/Status-Completed-success)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🌟 Características Principais

### 🚁 Drone Realista
- **Modelo 3D detalhado** com 4 rotores, gimbal e sensores
- **Física de voo realista** com inércia e efeitos de vento
- **Materiais PBR** (Physically Based Rendering)
- **LEDs multicoloridos** piscantes
- **Efeito blur** nas hélices durante movimento
- **Sistema de estabilização** do gimbal da câmera

### 🔍 Sistema de Escaneamento
- **Feixe laser verde** sempre direcionado para baixo
- **Partículas dinâmicas** simulando coleta de dados
- **Efeitos de impacto** no terreno
- **Pontos de scan** visíveis temporariamente
- **Luz spotlight** com sombras realistas

### 🌍 Ambiente Natural Completo
- **Terreno procedural** com múltiplas camadas de noise
- **2 rios serpenteantes** com curvas naturais
- **3 lagos** com efeitos de água
- **Cordilheira de montanhas** com picos nevados
- **5 florestas densas** com centenas de árvores
- **Skybox** com nuvens animadas

### 🏘️ Aldeia Indígena Autêntica
- **8 ocas tradicionais** em layout circular
- **Fogueira central** com chamas animadas
- **4 totems espirituais** com detalhes esculpidos
- **3 canoas** próximas ao rio
- **Horta comunitária** sustentável
- **Caminhos de terra** conectando estruturas

### 🎮 Controles Interativos
- **3 modos de voo**: Circular, Espiral, Grid
- **Controles**: Play/Pause, Reset, Mudança de modo
- **Câmera orbital** com mouse (arrastar + scroll)
- **Interface em tempo real** com telemetria

## 🛠️ Tecnologias Utilizadas

- **Three.js** - Motor de renderização 3D
- **HTML5 Canvas** - Renderização otimizada
- **CSS3** - Interface moderna responsiva
- **JavaScript ES6+** - Lógica de controle e física
- **WebGL** - Aceleração por hardware

## 🚀 Como Executar

### Método 1: Abrir diretamente no navegador
```bash
# Abra o arquivo index.html diretamente no seu navegador
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Método 2: Servidor local (recomendado)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

Depois acesse: `http://localhost:8000`

## 🎯 Funcionalidades

### Controles da Simulação
- **⏯️ Play/Pause** - Pausar/retomar animação
- **🔄 Reset** - Resetar posição e estado do drone
- **🔍 Modo Scan** - Alternar entre padrões de voo

### Padrões de Voo
1. **Circular** - Movimento em círculo constante
2. **Espiral** - Movimento em espiral expandindo/contraindo  
3. **Grid** - Padrão de varredura em grade

### Interface de Telemetria
- **Altitude** - Altura atual do drone
- **Velocidade** - Velocidade em tempo real
- **Bateria** - Nível de energia restante
- **Pontos Scan** - Quantidade de dados coletados

## 🌟 Destaques Técnicos

### Física Avançada
- Sistema de inércia e aceleração
- Simulação de vento afetando movimento
- Inclinação baseada na velocidade
- Vibração independente dos motores

### Gráficos de Alta Qualidade
- Sombras em 4K (4096x4096)
- Tone mapping ACES cinematográfico
- Múltiplas fontes de luz (sol, ambiente, preenchimento)
- Anti-aliasing e pós-processamento

### Otimizações
- LOD (Level of Detail) para objetos distantes
- Culling de objetos fora da câmera
- Geometrias instanciadas para melhor performance
- Materiais compartilhados

## 📱 Compatibilidade

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Dispositivos móveis (iOS/Android)

## 🎨 Capturas de Tela

*[As capturas de tela podem ser adicionadas aqui]*

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Desenvolvedor

Desenvolvido com ❤️ para demonstrar tecnologias de mapeamento aéreo em harmonia com comunidades tradicionais.

## 🙏 Agradecimentos

- **Three.js Community** - Pela excelente documentação
- **Comunidades Indígenas** - Pela inspiração cultural respeitosa
- **Bityx/CaInvest** - Pelo contexto do projeto

---

**⭐ Se gostou do projeto, deixe uma estrela!** 