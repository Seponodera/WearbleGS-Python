# Registro de Glicose - Dispositivo Wearable de Monitoramento

Este é um programa em Python representando um MVP (Produto Mínimo Viável) para um dispositivo wearable de monitoramento de glicose. Ele oferece funcionalidades básicas para registrar leituras, visualizar o histórico, calibrar o dispositivo, calcular a média das leituras e persistir os dados entre execuções.

## Funcionalidades

1. **Menu Principal:**
   - Exibe um menu com opções numeradas de 1 a 5.
   - Opções incluem registrar leitura, ver histórico, calibrar dispositivo, calcular média e sair.

2. **Registrar Leitura de Glicose:**
   - Solicita ao usuário inserir o nível de glicose.
   - Registra a leitura com a data e hora atuais.

3. **Ver Histórico de Leituras:**
   - Exibe o histórico de leituras com nível de glicose e data/hora de cada leitura.

4. **Calibrar Dispositivo:**
   - Simula a calibração do dispositivo, exibindo uma mensagem indicando o processo.

5. **Calcular Média das Leituras:**
   - Calcula e exibe a média dos níveis de glicose registrados.

6. **Salvar e Carregar Dados:**
   - As leituras são salvas em um arquivo CSV (leituras.csv) para persistência entre execuções.
   - Ao iniciar o programa, leituras anteriores são carregadas, se disponíveis.

7. **Tratamento de Erros:**
   - O programa trata erros, como inserção de valores não numéricos durante o registro.

## Utilização

- Execute o script em um ambiente Python.
- Escolha as opções no menu digitando o número correspondente.
- Siga as instruções para realizar as operações desejadas.

## Observações

- Certifique-se de ter as permissões necessárias para gravar e ler arquivos no diretório do script.
- Os dados são salvos no arquivo leituras.csv e carregados automaticamente ao iniciar o programa.

## Participantes

- Gabriel Onodera - RM533779
- Soraya Haddad - RM554032

## Video no Youtube

- https://youtu.be/S6ARi4HPzto