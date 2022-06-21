# Passo a passo; Como Fazer Root no celular, "Criando Arquivo Boot.img":book:



## O que você irá precisar;

- ***Você vai precisar de um computador:***

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\Computador.png)

- ***Cabo Usb, micro usb ou tipo C:***

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\Cabo usb tipo C.png)

- ***Drivers da Samsung instalados no computador:***

https://samsung-usb-driver-for-mobile-phones.softonic.com.br👈

- ***7-ZIP Instalado no seu computador;***

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\7zip.png)

https://www.7-zip.org/download.html👈

- **Samsung Odin, baixar e descompactar em seu computador;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\Odin.png)

https://samsungodin.com👈

- **Magisk Instalado em seu celular;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\magisk.png)

https://magiskmanager.com👈

### **Anotando informações do Celular**

**1. vá em *config.* no seu celular;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\conf.png)

**2. Entre em *Sobre o telefone*;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\sobretelefone.png)

**3. Entre em *Informações do Software*;**

   ![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\Informacaosoftware.png)

**4. Anote as versões: *do One UI*, *Android*, *número de compilação* e *patch*;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\versao.png)

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\ncompilacao.png)

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\patch.png)

**5. Ente no site da *Stock Roms / Firmwares*, busque pelo número de compilação. Baixe a rom com o mesmo número e patch do seu aparelho;**

https://www.stockrom.net/samsung👈

**6. Extraia os arquivos, com winrar ou 7zip;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\arqzip.png)

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\extrair.png)

**7. Será  utilizado somente o arquivo AP, click com o botão esquerdo sobre o arquivo, vá em 7-Zip > Extrair Aqui;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\7ziputilizar.png)

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\extrairaqui.png)

**8. Será extraído alguns arquivos, entre eles o arquivo: bootimg, que será modificado;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\bootimg.png)

**9. Abra o app 7-zip File Manager e aponte o arquivo boot.img;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\bootimgzip.png)

**10. Selecione o arquivo e vá em *adicionar*;**       

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\adicionar.png)

**11. abrirá uma janela, vá em *Formato do arquivo compactado,* selecione "tar" e click em "OK", criará um arquivo de imagem .tar;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\extensaoTar.png)

**12. Agora com o cabo usb, conecte o celular ao computador e transfira o arquivo para o celular, na pasta download. Com o Magisk instalado em seu celular, abra o app;**

https://samsungodin.com👈

       - *Magisk Instalado em seu celular:*

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\magisk.png)

**13. Ir na opção *instalar*;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\magiskinstalar.png)
        
**14. Selecione "*Selecione e corrija um arquivo*"**;

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\selecionecorrija.png)

**15. localize o arquivo *boo.timg.tar* e click nele;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\selecionearquivo.png)

**16. Agora click em "*vamos lá*", Será criado um arquivo corrigido, dentro da pasta download;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\vamosla.png)

**17. Transfira o arquivo que foi criado "magisk_patched", para o computador via cabo usb;**

**18. Abra a pasta do Odin e click em Odin, click em "AP" e aponte o arquivo magisk_patched**;

Link baixar Odin: https://samsungodin.com👈

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\patchedodin.png)

**19. Entre no modo download do celular, desligue o celular , ligue-o segurando as teclas;**

    **"volume para baixo", power" e "home", ira aparecer a tela warning;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\warning.png)

**20. Aperte a tecla volume para cima, o aparelho entrará em modo download;**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\mododownload.png)

**21. Conecte o cabo usb no celular e computador, o Odin ira reconhecer o celular na "ID:COM", "devera ficar azul";**

![](C:\Workspace\Meus-Projetos\Primeiro-Projeto\Como Fazer Root no Celular\Imagens\reconhecerOdin.png)

**22. Agora aperte a em "Start", Aguarde todo processo. Se não ocorrer nenhum problema o celular ira inicializar sozinho, com a configuração de fabrica, lembrando que o celular devera esta no mínimo 50% carregado. ""FAÇA POR SUA CONTA E RISCO"\".**

