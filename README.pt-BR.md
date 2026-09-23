# ImageConverter

**Conversor de imagens gratuito para Windows: arraste suas imagens e transforme-as em JPG · PNG · GIF · WEBP · TIFF com um clique.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/imageconverter?lang=pt)

![Tela do ImageConverter](images/imageconverter-en.webp)

> A janela do programa não tem tradução para português; ela é exibida em inglês. Os nomes de botões abaixo aparecem como na tela. O menu de contexto do Explorador aparece em português.

## Visão geral

Uma foto HEIC do iPhone que não abre no PC, um monte de fotos para reduzir para o blog, um PDF que você precisa como uma imagem por página — o ImageConverter resolve.

Arraste arquivos ou pastas para a janela e clique no botão **Convert to**. Pronto. O JPG é salvo menor com o MozJPEG e, se você definir um tamanho, a imagem é ajustada a ele mantendo as proporções. Também dá para converter direto do Explorador de Arquivos com o botão direito.

Os resultados são sempre salvos como **arquivos novos**. O ImageConverter nunca sobrescreve os originais nem qualquer arquivo existente.

## Principais recursos

- **Vários de uma vez** — Adicione vários arquivos ou pastas inteiras (com subpastas) e converta tudo de uma só vez.
- **5 formatos de saída** — JPG · PNG · GIF · WEBP · TIFF.
- **Muitos formatos de entrada** — JPG, PNG, GIF, BMP, WEBP, TIFF, HEIC, AVIF, PSD, PDF, SVG, TGA, ICO e outros.
- **JPGs menores** — O MozJPEG guarda a mesma qualidade em menos bytes.
- **Redimensionar mantendo a proporção** — Defina só a largura ou a altura; a outra segue a proporção.
- **PDF → imagens** — Salva cada página de um PDF de várias páginas como uma imagem separada.
- **Reconhece sem extensão** — O formato é lido do conteúdo do arquivo, não do nome.
- **Originais protegidos** — Se o nome já existir, salva como `photo (1).jpg`.
- **Menu de contexto do Explorador** — No Windows 10 e 11, inclusive no menu padrão do Windows 11.
- **7 idiomas** — Coreano · inglês · japonês · chinês · russo · italiano · francês. Segue o idioma de exibição do Windows.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Download](https://down.kilho.net/imageconverter?lang=pt) |
| Portátil (ZIP) | [Download](https://down.kilho.net/imageconverter?lang=pt&nosetup) |

Com o instalador, o ImageConverter abre assim que a instalação termina, e a entrada no menu Iniciar e o menu de contexto do Explorador são registrados. Na versão portátil, descompacte o ZIP e execute `ImageConverter.exe` — mantenha a pasta `vendor` junto ao executável. **O menu de contexto do Explorador vem com o instalador.**

## Como usar

### Fluxo básico

1. Abra o ImageConverter. **Home** mostra uma lista de arquivos vazia.
2. Arraste para a lista as imagens ou pastas que quer converter. Só entram os arquivos cujo formato é reconhecido; a coluna **Type** mostra o formato de origem e **Status** mostra `Ready`.
3. Na caixa de tamanho, no canto inferior esquerdo, escolha **Original**, **Width** ou **Height**. Com Width ou Height, aparece ao lado uma caixa de tamanho (px).
4. Confira o formato de saída. O botão no canto inferior direito o mostra, por exemplo **Convert to JPG**. Para mudar, clique com o **botão direito** no botão e escolha JPG · PNG · GIF · WEBP · TIFF.
5. Clique no botão. Aparece uma barra de progresso e o status de cada arquivo passa de `Convert` para `Success`.
6. Por padrão, os arquivos convertidos são salvos na **mesma pasta do original**, com o mesmo nome e a nova extensão.

### Organização da tela

**Home**

| Elemento | O que faz |
|---|---|
| Lista de arquivos | **FileName** · **Type** (formato de origem detectado) · **Status** (`Ready` / `Convert` / `Success` / `Fail`) |
| Botão direito na lista | **Delete** · **Delete All** |
| Escolha de tamanho | **Original** · **Width** · **Height** |
| Caixa de tamanho | Escolha um tamanho comum na lista ou digite um número (visível só com Width ou Height) |
| Botão **Convert to JPG** | Clique para começar. Botão direito para escolher o formato de saída |

**Config**

| Elemento | O que faz |
|---|---|
| **Output Path** | **Original File Folder** ou uma pasta escolhida (padrão `Área de Trabalho\ImageConverter`). Troque com o botão `…` |
| **Format** | JPG · PNG · GIF · WEBP · TIFF (a mesma configuração do menu do botão direito do botão) |
| **Quality** | 40 a 100, padrão 75. Vale para formatos com perda (JPG · WEBP) |

### O que fazer quando…

**Converter fotos do iPhone (HEIC) para JPG**
Arraste os arquivos HEIC, ou a pasta com eles, para a lista, deixe o formato em **JPG** e clique. As fotos são salvas **na posição certa** conforme a rotação registrada pelo celular, então não é preciso girar à mão as que saíram deitadas.

**Ajustar o tamanho de fotos para blog ou loja virtual**
Escolha **Width** na caixa de tamanho e selecione a largura desejada, por exemplo `1280`. A altura segue a proporção, então nada fica distorcido. Para um valor fora da lista, basta digitar o número (1 a 30000). Fotos mais estreitas que essa largura também são levadas a ela.

**Deixar todas as imagens com a mesma altura, como miniaturas**
Escolha **Height**: todos os resultados ficam com a mesma altura e cada largura segue a própria proporção. Prático para alinhar numa fileira fotos horizontais e verticais misturadas.

**Diminuir arquivos para enviar por e-mail ou mensageiro**
Com **JPG**, o MozJPEG guarda a mesma qualidade num arquivo menor. Para reduzir mais, baixe **Config → Quality** para cerca de 60 e reduza também o tamanho com **Width**. Salvar em **WEBP** costuma dar um arquivo menor que o JPG.

**Manter o fundo transparente**
PNG, SVG e outras imagens com transparência a mantêm quando salvas em **PNG** ou **WEBP**. O JPG não comporta transparência, então escolha PNG ou WEBP para logotipos e ícones.

**Exportar um logotipo SVG como PNG no tamanho necessário**
Adicione o SVG, defina **Width** como `512`, por exemplo, e converta para **PNG**. Em vez de ampliar uma imagem pequena, ele **desenha a imagem de novo nesse tamanho**, então fica nítida mesmo grande.

**Transformar um PDF em uma imagem por página**
Adicione um PDF e converta: cada página é salva num arquivo numerado — `document-001.jpg`, `document-002.jpg` … Com **Original**, as páginas saem no tamanho da tela; com **Width**, são desenhadas nítidas nessa largura. O fundo é branco. O status mostra `Success` quando todas as páginas foram salvas.

**Trocar um GIF animado por WEBP**
Quando o formato de saída é **GIF** ou **WEBP**, todos os quadros da animação são mantidos. Converter um GIF animado em WEBP mantém o movimento e reduz o tamanho. Ao salvar em JPG · PNG · TIFF, fica salvo o primeiro quadro.

**Salvar em WEBP sem perder qualidade**
Suba **Quality** para **100** e o WEBP é salvo sem perdas. Serve para guardar uma cópia idêntica pixel a pixel e menor que um PNG.

**Converter todas as imagens de uma pasta**
Arraste uma pasta inteira: todas as subpastas são percorridas e só as imagens entram na lista. Outros arquivos, como documentos ou vídeos, ficam de fora automaticamente, e o mesmo arquivo nunca entra duas vezes.

**Arquivos sem extensão ou com a extensão errada**
O ImageConverter lê o formato do **conteúdo do arquivo**, não do nome. Arquivos sem extensão, ou um `.jpg` que na verdade é PNG, são reconhecidos corretamente, e o resultado recebe a extensão certa.

**Reunir os resultados numa só pasta**
Em **Config → Output Path**, escolha a opção de pasta de baixo e todos os resultados irão para lá. O padrão é `Área de Trabalho\ImageConverter`, criada na conversão se ainda não existir. Escolha outra pasta com o botão `…`. Para deixar os resultados ao lado dos originais, escolha **Original File Folder**.

**Já existe um arquivo com o mesmo nome**
Nada é sobrescrito. Se `photo.jpg` existir, o resultado é salvo como `photo (1).jpg`, `photo (2).jpg` e assim por diante. Mesmo reduzindo um JPG para JPG, o original fica intacto.

**Converter direto do Explorador de Arquivos**
Selecione uma ou mais imagens no Explorador, botão direito → **Conversor de Imagem** → **Converter para WebP**, **Converter para PNG** ou **Converter para JPG**. Abre uma janela com esses arquivos; escolha um tamanho e clique no botão.
- Os resultados são salvos na **mesma pasta dos originais**, e a janela fecha sozinha ao terminar.
- Clique com o botão direito em outros arquivos e converta de novo: cada um abre sua própria janela, então podem rodar ao mesmo tempo.
- O menu aparece quando você seleciona arquivos JPG · PNG · GIF · BMP · WEBP · TIFF · HEIC · AVIF · PSD · PDF · SVG · TGA.

**Fazer as mesmas fotos em vários formatos**
A lista continua lá depois da conversão. Clique com o botão direito no botão, troque o formato e clique de novo para gerar os mesmos arquivos em outro formato.

**Organizar a lista**
Selecione as linhas a remover (`Ctrl` · `Shift` para várias), clique com o botão direito na lista e escolha **Delete**. Para limpar tudo, escolha **Delete All**. As linhas só saem da lista; os arquivos em si não são apagados.

**Parar no meio de uma conversão**
Feche a janela e aparece a pergunta **Stop converting and quit?** Clique em **Sim**: ele termina o arquivo em andamento e então fecha. Os resultados já salvos continuam onde estão.

## Configuração

As mudanças feitas em **Config** e a escolha de tamanho em Home são lembradas automaticamente para a próxima vez.

| Item | Padrão |
|---|---|
| Format | JPG |
| Tamanho | Original (Width 640 / Height 540) |
| Quality | 75 |
| Output Path | Original File Folder (pasta escolhida padrão: `Área de Trabalho\ImageConverter`) |
| Idioma | Idioma de exibição do Windows (inglês se não for suportado) |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Tudo o que é preciso para converter vem incluído — nada mais para instalar. Não requer permissão de administrador para executar o programa.
- A conexão com a Internet é usada apenas para avisos de nova versão. Todas as conversões acontecem no seu PC.

## Atualizações

O ImageConverter **não** se atualiza sozinho. Ao iniciar, verifica se há uma versão nova e mostra um aviso; ao clicar em **Sim**, a página de download é aberta e o programa é encerrado. As novas versões são publicadas manualmente após verificação interna e anunciadas na [página do ImageConverter](https://v2.kilho.net/imageconverter). Veja o [aviso sobre a política de atualização](https://en.kilho.net/archives/notice/2940).

**Histórico de versões**

| Versão | Data | Mudanças |
|---|---|---|
| 2.0.0 | 2026-09-22 | Tela renovada, tamanhos escolhidos numa lista ou digitados, configurações existentes mantidas após atualizar, conversão pelo botão direito no Explorador aprimorada |
| 1.6.3 | 2026-09-03 | Conversão mais rápida pelo menu de contexto do Windows 11, instalação de atualizações aprimorada, conversão de PDF mais nítida e documentos grandes mais estáveis, melhor reconhecimento de HEIC · AVIF, arquivos vazios filtrados da lista logo de início |
| 1.6.2 | 2026-08-17 | Motor de conversão de PDF aprimorado para mais qualidade, encerramento seguro durante a conversão, proteção reforçada dos arquivos existentes, melhor suporte a nomes de arquivo com caracteres especiais, lista de arquivos mais rápida |
| 1.6.1 | 2026-07-16 | Conversão de JPG e PDF de várias páginas mais confiável, melhor reconhecimento de HEIC e outros formatos, menu de contexto do Explorador e configurações mais práticos |

## Licença

O ImageConverter é **freeware**. Use gratuitamente e sem restrições em qualquer lugar — empresa, casa, órgãos públicos, escola — e redistribua livremente.

## Links

- Site: <https://v2.kilho.net/imageconverter>
- Fórum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
