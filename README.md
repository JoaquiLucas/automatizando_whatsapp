# Script Python para Encaminhamento Automatizado de Mensagens no WhatsApp

Este script automatiza o processo de envio e encaminhamento de mensagens no WhatsApp Web.

## Visão Geral

Este script em Python utiliza Selenium WebDriver para automatizar a interação com o WhatsApp Web.
Ele permite enviar uma mensagem inicial para o próprio usuário e depois encaminhá-la para uma lista de contatos específica.

## Pré-requisitos

- Python 3.x instalado no seu sistema
- Navegador Google Chrome instalado
- ChromeDriver (gerenciado automaticamente pelo `webdriver_manager`)

## Instalação

Instale as bibliotecas Python necessárias usando pip:

```sh
pip install selenium pyperclip webdriver_manager

### 4. Estrutura do Script

Explique brevemente a estrutura do script, destacando os principais passos ou seções importantes.

```markdown
## Estrutura do Script

O script é dividido em várias partes:

1. **Importações e Configuração**: Importa as bibliotecas necessárias e configura o navegador.
2. **Mensagem Predefinida e Lista de Contatos**: Define a mensagem a ser enviada e os contatos para encaminhamento.
3. **Inicializar o Navegador e Acessar o WhatsApp Web**: Inicia o navegador e acessa o WhatsApp Web.
4. **Enviar a Mensagem para o Próprio Usuário**: Envia a mensagem para o próprio usuário no WhatsApp.
5. **Encaminhar a Mensagem para a Lista de Contatos**: Encaminha a mensagem para os contatos em blocos de cinco.


