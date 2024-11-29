![Logo Ardudeck](https://github.com/klausseidner/ardudeck/blob/main/logo.png)


# Ardudeck

**Ardudeck** é um dispositivo IoT modular desenvolvido para automação e monitoramento de ambientes domésticos e industriais, utilizando a plataforma Arduino. O projeto visa oferecer uma solução acessível e personalizável para o controle de variáveis como temperatura, umidade, iluminação e automação de dispositivos. O Ardudeck integra estudantes, empresas de IoT e a comunidade técnica para criar um dispositivo fácil de usar e eficiente.

## Objetivos do Projeto

- Desenvolver um dispositivo IoT acessível e adaptável para automações domésticas e industriais. (Um dispositivo pequeno e versátil)
- Permitir o controle eficiente de variáveis como iluminação, climatização e produção em ambientes diversos. (Já incluso no dispositivo)
- Facilitar a adoção de tecnologias IoT com uma solução de automação fácil de configurar e utilizar. (Interface gráfica usando a biblioteca Flask no Python)
- Integrar o ensino prático de IoT na formação de estudantes, preparando-os para as demandas do mercado de automação. (Mostrando como os circuitos padrões funcionam)

## Características do Ardudeck

- **Automação de Sensores**: Monitoramento de variáveis como temperatura e umidade através de sensores de baixo custo e com visualização Web integrando a "internet das coisas".
- **Atuação de Dispositivos**: Controle automatizado de dispositivos como iluminação e sistemas de climatização. (Utilizando os atuadores para efetuar os controles de dispositivos)
- **Modularidade**: Fácil integração de novos sensores e atuadores para diferentes aplicações. (Disponibilizando um led para aleta visual e interruptores para facil acesso á qualquer porta do arduino)
- **Conectividade**: Integração com serviços de nuvem para coleta de dados e monitoramento remoto. (Com a biblioteca Flask é possivel uma construção de uma api para integração á qualquer sistema)
- **Simplicidade de Uso**: Programação baseada em Arduino, com foco em soluções de fácil implementação.

## Tecnologias Utilizadas

- **Hardware**: Placa Arduino, sensores de temperatura, umidade e outros atuadores. <<ESPECIFICAR TODOS COMPONENTES>>
- **Software**: Programação em Python no VSCode IDE, integração com serviços de nuvem para monitoramento através de API.
- **Bibliotecas**: Flask (Python)

## Colaboradores

O projeto Ardudeck envolve várias partes interessadas, incluindo:
- **Estudantes e Professores Universitários**: Principalmente da área de engenharia e tecnologia.
- **Empresas de Automação**: Parceiros que fornecem equipamentos e suporte técnico para o desenvolvimento do projeto.
- **Comunidade Técnica Arduino**: Entusiastas e profissionais que apoiam o aprimoramento e aplicação do Ardudeck.

## Cronograma do Projeto

| **Etapa**                      | **Tempo**      | **Descrição**                                                     |
| ------------------------------ | -------------- | ----------------------------------------------------------------- |
| Pesquisa e coleta de requisitos | -------------- | Entrevistas, reuniões online, relatórios semanais                 |
| Design do protótipo             | -------------- | Desenvolvimento no VSCode IDE, reuniões de progresso             |
| Desenvolvimento do dispositivo  | -------------- | Montagem do protótipo com sensores e atuadores                    |
| Testes em campo                 | -------------- | Feedback de usuários e ajustes no protótipo                       |
| Avaliação e ajustes finais      | -------------- | Revisão geral e análise de indicadores                            |

## Como Contribuir

Contribuições são bem-vindas! Se você deseja colaborar com o projeto, siga os passos:

1. Fork o repositório.
2. Crie um branch para suas modificações (`git checkout -b feature/nome-da-feature`).
3. Faça o commit das alterações (`git commit -m 'Descrição das mudanças'`).
4. Faça um push para o branch (`git push origin feature/nome-da-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
