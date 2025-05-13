#  Simulação com Mininet: Topologia Linear com 6 Switches

##  Objetivo

Implementar, inspecionar e testar uma topologia linear no Mininet utilizando 6 switches, com configurações específicas e verificação de desempenho por comandos no terminal.

---

##  Tecnologias e Ferramentas

-  Mininet VM 
-  PuTTY 
-  Xming 

---

##  Etapas Executadas

### 1.  Configuração do PuTTY com X11 Forwarding

- Ativação da opção:  
  `Connection > SSH > X11 > Enable X11 forwarding`
  
- Configuração com IP `192.168.56.102` da VM Mininet

>  Print da configuração:  
>  ![alt text](image.png)

---

### 2.  Abertura do Xming no Windows

>  Xming rodando:  
> ![alt text](image-1.png)

---

### 3.  Conexão via SSH com Mininet

> Conexão da VM Mininet:  
> ![Criação da Topologia](image-2.png)

> Teste de ping
> ![Teste de ping](image-6.png)

> Inspecionando h1
> ![Inspeção de IP h1](image-3.png)

> Inspecionando h2
> ![Inspeção de IP h2](image-4.png)

> Especificando h1 como servidor TCP
> ![h1 como servidor TCP](image-7.png)

> Especificando h2 como cliente e emitindo relatório
> ![h2 como cliente ](image-8.png)

---

