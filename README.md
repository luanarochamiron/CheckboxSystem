# Custom Checkbox System Settings Panel - CodingNepal

Um painel de configurações (System Settings) moderno, elegante e totalmente responsivo desenvolvido exclusivamente com HTML5 e CSS3. O projeto substitui as caixas de seleção (*checkboxes*) nativas do navegador por interruptores táteis estilo pílula (*toggle switches*), simulando perfeitamente a interface de controle de conexões de um sistema operacional.

## Tecnologias Utilizadas

* HTML5: Estruturação semântica do card, uso de elementos nativos de múltipla escolha (`<input type="checkbox">`) ocultos e vinculação com tags `<label>`.
* CSS3: Estilização completa, uso de cantos suavizados, gerenciamento de estados visuais e criação de profundidade com sombras.
* Animações em CSS: Utilização de propriedades de transição (`transition`) otimizadas para controlar o deslizamento horizontal do interruptor e a mudança de cor do trilho.

## Funcionalidades e Técnicas Aplicadas

* Customização de Checkboxes em Toggle Switches: Ocultação acessível dos inputs padrão do navegador, reconstruindo do zero os trilhos e esferas deslizantes utilizando pseudo-elementos (`::before` ou `::after`).
* Layout Organizado de Opções de Conexão: Alinhamento vertical simétrico de recursos essenciais de conectividade: Wi-Fi, Bluetooth e Portable Hotspot (Roteador Portátil).
* Microinterações de Deslizamento Fluido: Uso avançado da pseudo-classe `:checked` combinada com seletores de irmãos para mover a esfera branca horizontalmente e alterar a cor de fundo do trilho ao ativar um recurso.
* Estética Clean de Alto Contraste: Um card centralizado branco com cantos arredondados por meio de `border-radius` projeta uma sombra sutil (`box-shadow`), destacando-se sobre o plano de fundo azul-escuro profundo.
* Hierarquia Visual Clara: Inclusão de um título robusto e amigável em tom azul destacado ("System Settings"), orientando imediatamente o foco do utilizador.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone 
