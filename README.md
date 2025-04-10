# cibersecurity-desafio-phishing
(PHISHING PARA CAPTURA DE SENHAS E USUÁRIOS)


🎯 **Phishing Educacional para Captura de Senhas do Facebook com Kali Linux + SEToolkit**
⚠️ **Aviso Legal:** Este conteúdo é estritamente educacional, destinado a estudantes e profissionais da área de Segurança da Informação. Todas as etapas foram realizadas em ambiente controlado, com o objetivo de promover a conscientização sobre ataques de engenharia social.
**O uso indevido dessas técnicas em ambientes reais, sem consentimento, é crime previsto em lei.**

**🧰 Ferramentas Utilizadas:**
1. Kali Linux
2. SEToolkit
3. Terminal com acesso root
4. Navegador web
5. Encurtador de URL (opcional, para simulação realista)

**🛠️ Configurando o Phishing no Kali Linux:**
**Acesso root:**

--> sudo su

**Iniciando o SEToolkit:**

setoolkit

**Selecionar tipo de ataque:**

1) Social-Engineering Attacks

**Selecionar vetor de ataque:**
2) Website Attack Vectors

**Selecionar método de ataque:**
3) Credential Harvester Attack Method

**Selecionar método de clonagem:**
2) Site Cloner

**Obter o endereço IP da máquina:**

---> ifconfig
---> Use o IP da interface de rede ativa (ex: 192.168.0.105).

**Inserir a URL a ser clonada:**

http://www.facebook.com

**🔗 Camuflando o Endereço IP com um Encurtador de URL**

Para fins de simulação e conscientização, é possível encurtar a URL com IP visível usando ferramentas como:

https://bitly.com
https://tinyurl.com

(Isso torna o link menos suspeito visualmente, simulando com mais realismo o que um atacante mal-intencionado poderia fazer.)

**Exemplo:**
http://192.168.0.105 -> https://bit.ly/teste-seguro

**🔒 Conscientização**
Este experimento serve como alerta sobre a importância da educação digital, verificação de links recebidos, e o uso de autenticação de dois fatores em redes sociais.
O phishing continua sendo uma das principais ameaças digitais e a melhor defesa é o conhecimento.
