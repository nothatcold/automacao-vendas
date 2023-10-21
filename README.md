# Projeto de Automação de Vendas com OpenPyXL e PyAutoGUI

Este é um projeto de automação que combina as bibliotecas OpenPyXL e PyAutoGUI para inserir informações de vendas em um sistema. O projeto assume que as informações de vendas estão armazenadas em uma planilha Excel chamada "vendas_de_produtos.xlsx" e utiliza o PyAutoGUI para controlar o mouse e inserir as informações nas coordenadas específicas do sistema. As coordenadas mencionadas no código devem ser personalizadas de acordo com o sistema e a interface do usuário em uso.

## Requisitos

Antes de executar o código, certifique-se de que você tenha as seguintes bibliotecas instaladas:

- OpenPyXL: Para a leitura das informações de vendas a partir da planilha Excel.
- PyAutoGUI: Para a automação do mouse e do teclado.

Você pode instalar as bibliotecas usando o pip:

pip install openpyxl pyautogui

Além disso, é necessário que você tenha o sistema ou a aplicação que deseja automatizar aberto e pronto para receber as informações.

## Executando o Projeto

Para executar o projeto, siga as etapas a seguir:

1. Clone ou faça o download deste repositório para o seu ambiente local.
2. Certifique-se de que a planilha Excel "vendas_de_produtos.xlsx" contém as informações de vendas que você deseja inserir no sistema.
3. Abra o arquivo Python (geralmente com a extensão .py) que contém o código de automação. Certifique-se de que as coordenadas utilizadas pelo PyAutoGUI estejam corretas para o seu sistema ou aplicação.
4. Execute o código Python. Isso controlará o mouse e inserirá as informações de vendas nos campos apropriados do sistema. Certifique-se de que o sistema ou a aplicação esteja em primeiro plano e pronto para receber as informações.

## Personalização

Você deve personalizar o código de acordo com as coordenadas e campos específicos do sistema ou aplicação que deseja automatizar. Certifique-se de que as coordenadas utilizadas correspondam aos campos corretos em seu sistema. Você pode fazer isso alterando as coordenadas nos comandos `pyautogui.click()` e `pyautogui.write()` de acordo com a interface do usuário do seu sistema.

## Considerações Finais

Este projeto de automação é um exemplo básico que pode ser adaptado para automatizar tarefas repetitivas em sistemas ou aplicações. Certifique-se de entender completamente a estrutura e a interface do usuário do sistema que você está automatizando e ajustar o código de acordo com as necessidades específicas.
