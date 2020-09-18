# Arquivos de tradução para o Sendy

Traduções para o sistema de gerenciamento de newsletter's Sendy para Português do Brasil (pt_BR)

## Sobre o Sendy
O [Sendy](https://sendy.co/?ref=Q3yhn) é um sistema de envio e gerenciamento de e-mail marketing auto-hospedado que permite enviar e-mails rastreáveis via Amazon Simple Email Service (SES). Ou seja, possui um alto nível de escalabilidade enquanto mantém o custo de manutenção extremamente baixo, além disso é uma ferramente bastante intuitiva e de fácil gestão.

## Versões disponíveis

- 4.1.0.0

## Download

A versão mais recente está disponível na branch master. Porém também é possível realizar o download de versões
anteriores selecionando a tag correspodente a versão desejada.

## Instalação

Basta copiar a pasta pt_BR na pasta `/locale/` que está localizada na raiz da sua instalação do Sendy.

## Solução de problemas

Visite a [página](https://sendy.co/troubleshooting) de solução de problemas para verificar os problemas mais comuns.

Se você estiver executando o Sendy no Ubuntu, você precisa primeiro [adicionar localidades](https://www.linhadecomando.com/so-linux/linux-instalando-o-locale-pt_br-utf-8) adequadas ao seu sistema. Caso contrário, o idioma que você definiu não aparecerá. 

Adicionalmente, nas versões mais recentes do Ubuntu, também é preciso adicionar um alias para o locale pt_BR.UTF-8 para que a tradução seja exibida, para isso, basta adicionar `pt_BR pt_BR.UTF-8` na última linha do arquivo localizado em `/etc/locale.alias` e reiniciar o Apache/Nginx.
  
  
