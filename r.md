# Guia Rápido de AutoCAD para Iniciantes (Baseado na Apostila)

Este resumo cobre os fundamentos do AutoCAD 2D, ideal para quem está começando do zero, com base na apostila fornecida[cite: 1, 4]. O AutoCAD é um software para criar desenhos técnicos em 2D e 3D[cite: 5]. Lembre-se que a prática constante é fundamental[cite: 8].

## 1. Conhecendo o Ambiente AutoCAD

* **Tela Inicial:** Ao abrir o AutoCAD, você pode começar um novo desenho (`Iniciar desenhos`) ou abrir um recente[cite: 13].
* **Ribbon (Faixa de Opções):** A barra principal no topo, similar ao Microsoft Office, organiza os comandos em abas (Padrão, Inserir, Anotar, etc.) e painéis (Desenhar, Modificar, etc.)[cite: 16, 17]. Clicar em um ícone equivale a digitar o comando[cite: 18, 19].
* **Linha de Comando:** Essencial! Fica na parte inferior e é onde você digita comandos e o AutoCAD "conversa" com você, pedindo informações[cite: 32, 33, 34]. Preste sempre atenção nela[cite: 63, 65, 67]. (Se sumir, use `CTRL+9` para trazê-la de volta [cite: 36]).
* **Barra de Status:** Abaixo da linha de comando, com botões de acesso rápido para ferramentas importantes (como OSNAP, ORTO)[cite: 44, 45]. Você pode personalizá-la[cite: 47].
* **Área de Desenho (Aba Modelo):** O espaço infinito onde você cria seus desenhos[cite: 49, 50]. As abas `Layout` são usadas para preparar a impressão[cite: 51, 52].

## 2. Ferramentas Essenciais: Mouse e Teclado

* **Mouse:**
    * **Botão Esquerdo:** Seleciona, clica em pontos.
    * **Botão Scroll (Rodinha):**
        * Girar: Zoom In/Out[cite: 56].
        * Dois Cliques: Zoom Extents (mostra tudo)[cite: 57, 190].
        * Clicar e Segurar: Pan (mover a visualização)[cite: 57, 180].
    * **Botão Direito:** Menus de contexto (varia).
* **Teclado:**
    * **Enter:** Confirma comandos ou repete o último comando[cite: 59, 61].
    * **Esc:** Cancela o comando atual[cite: 70].
    * **F3:** Liga/Desliga OSNAP (precisão em pontos específicos).
    * **F8:** Liga/Desliga ORTO (restringe o cursor a ângulos retos).
    * **Delete:** Apaga objetos selecionados[cite: 94].

## 3. Como Usar Comandos (Sequência Básica)

1.  **Ative o Comando:** Clique no ícone na Ribbon ou digite o nome do comando (ou atalho) na Linha de Comando e pressione `Enter`[cite: 68].
2.  **Siga as Instruções:** Leia o que o AutoCAD pede na Linha de Comando (ex: "Especifique o primeiro ponto:")[cite: 69].
3.  **Forneça a Informação:** Clique em pontos na tela, digite valores (distâncias, coordenadas, raios) e pressione `Enter` quando necessário[cite: 69].
4.  **Finalize/Cancele:** Pressione `Enter` para concluir algumas etapas ou `Esc` para cancelar o comando[cite: 70].

## 4. Configuração Inicial: Unidades

* Antes de começar, defina a unidade de medida do seu desenho (milímetros, metros, etc.)[cite: 71].
* Digite `UN` (ou `UNITS`) na Linha de Comando e pressione `Enter`[cite: 73].
* Na janela que aparece, escolha a unidade desejada em "Unidades para dimensionar conteúdo inserido" (ex: Milímetros, Metros)[cite: 74].

## 5. Comandos de Desenho Fundamentais (Painel Desenhar)

* **Linha (`LINHA` / `L`):** Cria segmentos de reta[cite: 83, 86].
    * Clique no ponto inicial.
    * Clique no ponto final ou digite a coordenada/distância e ângulo.
    * **Coordenadas:**
        * **Absolutas:** `X,Y` (ex: `10,20`)[cite: 87, 90].
        * **Relativas:** `@X,Y` (ex: `@5,0` - 5 unidades para a direita do último ponto)[cite: 88].
        * **Polares Relativas:** `@Distância<Ângulo` (ex: `@10<45` - 10 unidades a 45 graus do último ponto)[cite: 99, 100].
* **Retângulo (`RETANGULO` / `RET`):** Cria retângulos[cite: 117].
    * Clique no primeiro canto.
    * Clique no canto oposto ou digite `@Largura,Altura` (ex: `@50,30`).
* **Círculo (`CIRCULO` / `CI`):** Cria círculos[cite: 122, 126].
    * Método Padrão: Clique no centro e depois digite o raio (ou clique em um ponto na circunferência)[cite: 123].
    * Outras opções (via Linha de Comando ou menu): 2 Pontos, 3 Pontos, Tangente/Tangente/Raio, etc.[cite: 39, 128].
* **Arco (`ARCO`):** Cria segmentos curvos[cite: 155, 158]. Possui muitas opções de criação (ex: 3 Pontos, Início/Centro/Fim)[cite: 159, 160].
* **Polilinha (`PLINHA` / `PL`):** Similar à Linha, mas cria um único objeto conectado, mesmo com vários segmentos[cite: 109, 110, 113]. Útil para objetos que precisam ser tratados como um todo.
* **Hachura (`HACHURA` / `HA`):** Preenche áreas fechadas com padrões (ex: linhas, sólidos, materiais)[cite: 138, 139].

## 6. Ferramentas Essenciais

* **Seleção:** Como escolher objetos para editar[cite: 192].
    * **Clique Simples:** Seleciona um objeto individual[cite: 193, 194].
    * **Janela Azul (Window):** Clique, mova para a DIREITA, clique de novo. Seleciona APENAS objetos que estão COMPLETAMENTE dentro da janela[cite: 202, 203].
    * **Janela Verde (Crossing):** Clique, mova para a ESQUERDA, clique de novo. Seleciona TODOS os objetos que a janela toca ou envolve[cite: 197, 200].
    * Pressione `Shift` e clique em um objeto selecionado para removê-lo da seleção[cite: 206].
* **Visualização:**
    * **Zoom (`ZOOM` / `Z`):** Aproxima ou afasta a vista[cite: 185, 186]. Use a rodinha do mouse![cite: 56]. `Z` + `Enter` + `E` + `Enter` (Zoom Extents) mostra tudo[cite: 190].
    * **Pan (`PAN` / `P`):** Move a visualização sem alterar o zoom[cite: 176]. Use a rodinha do mouse pressionada![cite: 57, 180].

## 7. Comandos de Edição Básicos (Painel Modificar)

* **Mover (`MOVER` / `M`):** Muda objetos de lugar.
* **Copiar (`COPIAR` / `CO` ou `CP`):** Cria cópias de objetos.
* **Apagar (`APAGAR` / `E` ou tecla `Delete`):** Remove objetos[cite: 94].
* **Aparar (`APARAR` / `TR` - Trim):** Corta partes de objetos que se cruzam com outros.
* **Estender (`ESTENDER` / `EX` - Extend):** Alonga objetos até encontrarem outros.
* **Rotacionar (`ROTACIONAR` / `RO`):** Gira objetos em torno de um ponto base.
* **Espelhar (`ESPELHAR` / `MI` - Mirror):** Cria uma cópia espelhada de objetos.
* **Deslocamento (`DESLOCAMENTO` / `O` - Offset):** Cria cópias paralelas (linhas, círculos, etc.) a uma distância específica.

## 8. Organização: Camadas (Layers)

* Fundamental para organizar o desenho[cite: 10]. Pense nelas como folhas transparentes empilhadas.
* Você pode criar camadas para diferentes partes do desenho (paredes, cotas, texto, móveis) e controlar sua visibilidade, cor, tipo de linha, etc.
* O gerenciador de camadas (`CAMADA` / `LA`) permite criar e configurar as camadas.

Lembre-se: explore os comandos, use a Linha de Comando como guia e pratique com os exercícios da apostila[cite: 91, 93, 107, 115, 130, 147, 151, 161]!