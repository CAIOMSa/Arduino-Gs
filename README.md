# Sistema de Monitoramento e Controle de Energia em Tempo Real

## Descrição
Este projeto, desenvolvido na plataforma Wokwi, tem como objetivo monitorar e controlar o consumo de energia em um sistema específico. Utilizando três potenciômetros digitais, o sistema mede a quantidade de energia produzida, gasta e distribuída em Wh (watt-hora). A partir desses dados, é calculado o valor de energia armazenada e todas as informações são enviadas para uma API externa.

## Funcionalidades Principais
* Leitura de dados: Os três potenciômetros são utilizados para coletar dados em tempo real sobre a produção, consumo e distribuição de energia.
* Cálculo de energia armazenada: A energia armazenada é calculada a partir da diferença entre a energia produzida e a soma da energia gasta e distribuída.
* Envio de dados para API: Os dados coletados e calculados são enviados para uma API externa para armazenamento e análise.
* Tratamento de erros: O sistema implementa mecanismos para lidar com erros comuns, como a indisponibilidade da API.

## Requisitos
* **Hardware:**
    * Placa compatível com Wokwi (ESP32)
    * Três potenciômetros digitais
    * Conexão à internet (para comunicação com a API)
* **Software:**
    * Plataforma Wokwi
    * Ambiente de desenvolvimento para programação da placa (Arduino IDE, etc.)
* **API:**
    * API externa para receber e armazenar os dados do sistema

## Instalação e Configuração
1. **Criar uma conta na Wokwi:** Acesse o site da Wokwi e crie uma conta gratuita.
2. **Criar um novo projeto:** Inicie um novo projeto na plataforma Wokwi.
3. **Carregar o código:** Carregar o código do projeto para a plataforma Wokwi.
4. **Configurar a API:**
    * **Endereço da API:** Substituir o endereço da API no código pela URL correta.
    * **Credenciais:** Configurar as credenciais de autenticação, se necessário.

## Uso
1. **Simulação:** Simular o projeto na plataforma Wokwi para verificar o funcionamento.
2. **Hardware:** Carregar o código adaptado para ter a conexão com a rede e para a placa física e conectar os componentes.
2. **Api:** Executar a api em dispositivo que esteja na mesma rede da placa física ou hospedado em servidor.
3. **Início:** Ligar a placa e iniciar o sistema.

## Dependências
* **Bibliotecas:** HTTPClient.h e WiFi.h


## Informações Adicionais
* **Tratamento de erros:** Hospedar a api no ngrok gera a necessidade de um tratamento devido a página de segurança, sendo pagante da plataforma seria uma resolução, porém no ambiente ideal a api estaria em um servidor.
* **Melhorias futuras:** Hospedar a api em um servidor.
* **Agradecimentos:** Ao professor Yan por nos auxiliar com um metodo post no esp32

## Link do projeto:
https://wokwi.com/projects/415209101861876737

## Link dos demais repositorios:
* https://github.com/juniorlds98/Global-Solution-S1/tree/main/Projeto
