# RastroPro
This project aims to assist everyone who works with vehicle tracking and fleet management. The goal is to provide the most comprehensive instructions possible regarding tracking equipment, all for free.

In this project, I aim to create an easy option for professionals in the field and interested individuals to find the most comprehensive information about telemetry equipment, as well as to develop my skills in React.


# RastroPro 
é uma aplicação com o objetivo de centralizar e gerenciar todas as informações relacionadas a equipamentos de rastreamento. A ideia é criar uma ferramenta completa para profissionais da área, com funcionalidades como:

# Catálogo de Equipamentos:
Listagem de dispositivos de rastreamento, com informações detalhadas sobre cada um (modelos, fabricantes, etc.).

# Configurações e Comandos:
Repositório de comandos SMS para cada equipamento, explicando como configurá-los e usá-los.

# Guias de Instalação:
Passo a passo detalhado de instalação de cada dispositivo, com diagramas e instruções claras.

# Esquemas de Fios:
Diagramas de fiação mostrando como conectar cada dispositivo corretamente, com a identificação das cores dos fios e suas funções.

# Assecibilidade
Design intuitivo e amigável para facilitar a consulta e o gerenciamento das informações.


# Modelo de Objeto 
{
  "nome": "EXEMPLO",
  "descricao": "Rastreador compacto ideal para veículos leves e pesados, com localização em tempo real e funcionalidades avançadas de segurança.",
  "tipoDeSinal": "2G/4G",
  "valorMedioDeMercado": 249.90,
  "linkParaConfigurador": "https://exemplo.com/configurador-tk303",
  "contatoDoSuporte": "suporte@fabricante.com",
  "listaDeComandosBasicos": [
    "Status: STATUS#",
    "Reiniciar dispositivo: RESET#",
    "Obter localização: LOC#"
  ],
  "listaDeComandosMoto": [
    "Cortar combustível: CUT#",
    "Restaurar combustível: RES#",
    "Alarme de movimento: MOV#"
  ],
  "todosOsComandos": [
    "Status: STATUS#",
    "Reiniciar dispositivo: RESET#",
    "Obter localização: LOC#",
    "Cortar combustível: CUT#",
    "Restaurar combustível: RES#",
    "Alarme de movimento: MOV#",
    "Obter localização via SMS: SMSLOC#",
    "Ativar modo de escuta: LISTEN#"
  ]
}

## Estrutura das Propriedades:
nome: Nome do rastreador.
descricao: Breve descrição do dispositivo.
tipoDeSinal: Tipo de sinal suportado (pode ser "2G", "4G" ou "2G/4G").
valorMedioDeMercado: Valor médio do dispositivo no mercado.
linkParaConfigurador: Link para o configurador online.
contatoDoSuporte: E-mail de contato do suporte técnico.
listaDeComandosBasicos: Lista de comandos básicos do rastreador.
listaDeComandosMoto: Lista de comandos voltados para dispositivos instalados em motocicletas.
todosOsComandos: Lista completa de todos os comandos disponíveis.
