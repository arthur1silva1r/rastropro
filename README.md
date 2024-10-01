# RastroPro
O projeto tem como objetivo melhorar minhas ideias e capacidades utilizando React. Além disso, desejo disponibilizar futuramente uma versão utilizável para auxiliar pessoas que trabalham com rasteramento veicular como uma central de apoio onde serão encontrados diversos equipamentos e suas configurações.

## Funcionalidade que desejo implementar:

-> Filtro por Nome do equipamento;
-> Filtro por Nome do fabricante;
-> Cada comando num campo que seja possivel ele clicar e já copiar o comando;
-> Consulta ao valor medio de mercado de cada equipamento.

## Catálogo de Equipamentos:
Listagem de dispositivos de rastreamento, com informações detalhadas sobre cada um (modelos, fabricantes, etc.).

## Configurações e Comandos:
Repositório de comandos SMS para cada equipamento, explicando como configurá-los e usá-los.


### Modelo de Objeto 
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

### Estrutura das Propriedades:
nome: Nome do rastreador.
descricao: Breve descrição do dispositivo.
tipoDeSinal: Tipo de sinal suportado (pode ser "2G", "4G" ou "2G/4G").
valorMedioDeMercado: Valor médio do dispositivo no mercado.
linkParaConfigurador: Link para o configurador online.
contatoDoSuporte: E-mail de contato do suporte técnico.
listaDeComandosBasicos: Lista de comandos básicos do rastreador.
algunsComandosEspeciais: Lista completa de todos os comandos disponíveis.
