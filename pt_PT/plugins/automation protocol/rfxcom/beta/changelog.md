# Registro de alterações RFXcom

>**IMPORTANTE**
>
>Como lembrete, se não houver informações sobre a atualização, isso significa que se trata apenas da atualização da documentação, tradução ou texto

# 02/07/2022

- Corrigido problema ao instalar dependências no jeedom 4.2


# 02/03/2022

- Corrigido problema ao instalar dependências no jeedom 4.2
- Correção de bug em módulos do tipo 0x71 (obrigado @Doubledom)

# 08/02/2021

- Possibilidade de autorizar apenas um determinado tipo de pacote no processamento de informações do equipamento (caso raro)
- Correção de um bug em conf 0x1A : Somfy RTS Motor que pode não aparecer em certos casos.

# 01/07/2020

- Correções de bugs e otimização (obrigado @Doubledom)

# 12/07/2020

- Correção de um bug no equipamento Somfy (ID de 8 em vez de 6)

# 12/03/2020

- Bugs corrigidos no processo de atualização
- Correção da direção do vento (divisão por 10 demais)


# 01/12/2020

- Correções de bugs

# 29/11/2020

- Correção de bugs na recuperação da bateria
- Resolução de bug no controle do fogão com ventoinha MCZ 2
- Correções de bugs

# 26/11/2020

- Revisão completa do daemon do plugin
- Passagem em python3
- Suporte total de todos os módulos RFXcom

Atenção : Esta atualização é importante e requer reiniciar a instalação de dependências. Também é possível que seja necessário refazer a inclusão de determinados sensores.

# 27/05/2019

- Correções de bugs

# 02/10/2019

- Melhoria da função de detecção de porta rfxcom

# 16/05/2019

- Interface de correção de bug

# 03/03/2019

- Remova o ventilador MCZ 3 fan

# 30/04/2019

- Bug fix

# 29/04/2019

- Correção de um erro se o nível de log for nenhum
- Suporte para ventilador MCZ 3
- Atualizando o documento

# 08/08/2018

- Corrija os protocolos de comparação esperados e desejados em minúsculas

# 08/08/2018

- Revisão de inicialização do demônio (por Sarakha)
- Compatível com o mais recente RFXCOM (da Sarakha)
- Separação no encadeamento do soquete de escuta e da chave RFXCOM (por Sarakha)

# 14/04/2018

- A correção de um bug ou o demônio pode perder certas mensagens se elas chegaram antes de serem enviadas ao Jeedom ao mesmo tempo com o mesmo tipo de pacote

# 17/03/2018

- Atualizando o documento

# 28/02/2018

- Correção de um bug na troca da bateria

# 01/12/2017

-   Os comandos de ação para os módulos do tipo controle remoto são
    criado automaticamente
