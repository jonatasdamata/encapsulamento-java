# Projeto Controle Remoto (POO - Encapsulamento)

Bem-vindo ao Sistema de Controle Remoto! Este projeto em Java simula as funcionalidades de um controle remoto para um dispositivo eletrônico. O sistema oferece opções para ligar/desligar, ajustar o volume, controlar a reprodução de mídia e exibir o menu de configurações.

### Funcionalidades Principais

#### Ligando e Desligando
- **Ligar:** Ativa o controle remoto, permitindo o uso das demais funcionalidades.
- **Desligar:** Desativa o controle remoto e interrompe qualquer operação em andamento.

#### Controle de Volume
- **Aumentar Volume:** Aumenta o volume em 5 unidades, se o controle estiver ligado.
- **Diminuir Volume:** Diminui o volume em 5 unidades, se o controle estiver ligado.
- **Ligar Mudo:** Silencia o volume, mantendo-o em 0, se o controle estiver ligado e o volume não estiver em zero.
- **Desligar Mudo:** Restaura o volume para o último valor antes de ligar o mudo, se o controle estiver ligado e o volume estiver em zero.

#### Controle de Reprodução
- **Play:** Inicia a reprodução de mídia, se o controle estiver ligado e não estiver reproduzindo.
- **Pause:** Pausa a reprodução de mídia, se o controle estiver ligado e estiver reproduzindo.

#### Menu de Configurações
- **Abrir Menu:** Exibe o menu de configurações com informações sobre o estado do controle remoto, como ligado/desligado, reproduzindo/pausado e volume atual.
- **Fechar Menu:** Fecha o menu de configurações.

### Requisitos do Sistema
- Java JDK: Certifique-se de ter o Java Development Kit (JDK) instalado na sua máquina.
- IDE ou Editor de Texto: Utilize uma IDE como IntelliJ IDEA, Eclipse, NetBeans ou mesmo um editor de texto como VS Code para compilar e executar o programa.

### Estrutura do Código
O código está dividido em três partes principais:
1. **Controlador (Interface):** Define os métodos que um controle remoto deve implementar.
2. **ControleRemoto (Classe):** Implementa a interface Controlador e fornece as funcionalidades do controle remoto.
3. **Main (Classe):** Contém o método principal para execução do programa, onde são criadas instâncias do ControleRemoto e suas funcionalidades são utilizadas.

### Uso do Sistema
1. Abra o projeto em sua IDE ou editor de texto.
2. Compile e execute o código.
3. Experimente as funcionalidades do controle remoto, como ligar/desligar, ajustar o volume e controlar a reprodução.

Este projeto me ajudou a entender melhor alguns conceitos básicos de programação orientada a objetos, como interfaces, encapsulamento, métodos e atributos. Tudo isso foi aplicado de uma forma prática, no contexto de um controle remoto.

Divirta-se explorando o Controle Remoto! 😊📺🔊
