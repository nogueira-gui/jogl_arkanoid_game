# JOGL Arkanoid Game

## Descrição

O **JOGL Arkanoid Game** é um projeto desenvolvido em Java que utiliza a biblioteca JOGL (Java OpenGL) para criar uma versão do clássico jogo Arkanoid. O projeto implementa um loop principal para controle do jogo, gerenciamento de entrada de teclado e renderização do mundo do jogo.

## Pré-requisitos

Para compilar e executar o projeto, é necessário ter instalado:

- **Java Development Kit (JDK)** – versão 8 ou superior.
- **JOGL (Java OpenGL)** – biblioteca para renderização 3D. Certifique-se de que as dependências do JOGL estejam configuradas corretamente no seu ambiente (por exemplo, adicionando os jars e as bibliotecas nativas ao classpath).

## Como Executar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/nogueira-gui/jogl_arkanoid_game.git
   ```

2. **Importe o projeto em sua IDE de preferência** (como Eclipse, IntelliJ IDEA, NetBeans, etc.) ou configure-o via linha de comando.

3. **Configure as dependências do JOGL:**

   - Adicione os arquivos JAR do JOGL ao classpath do projeto.
   - Certifique-se de que as bibliotecas nativas estejam corretamente configuradas (via variáveis de ambiente ou parâmetros de execução).

4. **Compile e execute a classe `org.engine.Main.java`:**

   Esta classe contém o método `main` que inicia o jogo.

## Funcionamento do Jogo

- **Loop Principal:**  
  A classe `GameLoop.java` é responsável por manter o ciclo de execução do jogo, atualizando a lógica dos elementos do mundo e realizando a renderização dos gráficos.

- **Entrada de Usuário:**  
  A classe `KeyboardListener.java` capta as entradas do teclado e as transforma em comandos para o jogo, como movimentação da "raquete" ou outras interações.

- **Renderização:**  
  A classe `RendererInputControl.java` integra os comandos do usuário com o sistema de renderização, facilitando a atualização dos elementos gráficos conforme as ações do jogador.

- **Mundo do Jogo:**  
  A classe `World.java` define e gerencia os objetos que compõem o ambiente do jogo, como a raquete, a bola e os blocos, além de implementar as regras de colisão e pontuação.


## Contribuição

Contribuições são bem-vindas! Caso deseje melhorar ou expandir o projeto, sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_ com suas sugestões e correções.

## Licença

Defina a licença do projeto, se aplicável (por exemplo, MIT, Apache 2.0, etc.). Caso não haja uma licença definida, recomenda-se incluí-la para esclarecer os termos de uso.

## Contato

Para dúvidas ou sugestões, entre em contato através do [perfil do GitHub do autor](https://github.com/nogueira-gui).
