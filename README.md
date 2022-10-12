![Logo Cuidamos Bem](https://user-images.githubusercontent.com/97892626/195355720-b539c7a8-4ea8-43a3-beb3-b0944a00f457.png)
# SAÚDE ONLINE
## MONITORAMENTO REMOTO DE PACIENTES
### Projeto Aplicado do MBA de Arquitetura de Software - IGTI

***
<br/>

## Descrição
Projeto arquitetural da solução de Monitoramento Remoto de Saúde da clínica Cuidamos Bem.

<br/>

## Requisitos Funcionais<br/>

> ### Permissões para o App
> **Identificador:**	Permissões para o aplicativo<br/>
> **Descrição:**	No primeiro acesso deve-se solicitar autorização para acessar o Bluetooth, Fazer chamadas telefônicas e Enviar mensagens, sendo que o primeiro é obrigatório, e, não autorizando, o aplicativo não abre, já os demais apenas irá informar que ninguém será comunicado em caso de emergência.<br/>
> **Interesses relacionados:**	RF - Emparelhar<br/>
<br/>

> ### Identificação
> **Identificador:**	Identificação do paciente<br/>
> **Descrição:**	Quando abrir a tela inicial e o aplicativo não tiver o paciente cadastrado, o usuário deverá informar um código fornecido pela Clínica e sua data de nascimento, para que sejam sincronizados os dispositivos pré-cadastrados que ele irá utilizar.
Juntamente com os dados informados, o usuário deve concordar com os Termos de uso antes de acessar o aplicativo definitivamente.<br/>
> **Interesses relacionados:**	RF - Atribuir Dispositivos

<br/>

## Requisitos Não Funcionais<br/>

> **Identificador:**	Usuários simultâneos<br/>
> **Atributos:**	Desempenho<br/>
> **Descrição:**	Os dados de monitoramento de todos os pacientes monitorados devem ser enviados para o Banco de dados cloud, a cada 1 minuto ou a cada alteração do estado de saúde, sendo que quando ocorrer problema no envio, esses dados devem ser acumulados e adicionados no próximo envio.<br/>
>  **Interesses relacionados:**	Nenhum<br/>
> **Partes interessadas:**
> * Cliente<br/>
> * Testadores (QA (Quality assurance))<br/>
