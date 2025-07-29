# 📖 Manual de como publicar na Apple Store
Documentação criada para os alunos e para a Fatec Zona Leste publicar seus aplicativos 

<img height="15px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/android/android-original.svg" /> **Documentação para a Play Store:** https://github.com/fatec-zona-leste/app-center

## **Links**
- <img height="15px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apple/apple-original.svg" /> **Apple Developer Account**: https://developer.apple.com/account
- <img height="15px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apple/apple-original.svg" /> **Apple Store Connect (onde os apps são gerenciados:)**: https://appstoreconnect.apple.com

## 🏫 Administrador/Fatec
É necessário que a Fatec crie os aplicativos para os alunos gerenciarem, pois apenas administradores podem criar o Bundle ID (identificador único do app usado no build, ex: com.fateczl.nomeapp), que é um requisito para a criação do aplicativo.

### Criar Bundle ID
Para isso, acesse a conta de desenvolvedor em: https://developer.apple.com/account e na opção do meio em "Certificates, IDs & Profiles", clique em "Identifiers".

<img width="1919" height="927" alt="Imagem11" src="https://github.com/user-attachments/assets/24645986-2d7b-45e3-9212-b02d002cac5e" />

Clique no ícone "+" para adicionar um novo Bundle ID.

<img width="1919" height="921" alt="Imagem7" src="https://github.com/user-attachments/assets/545f51e2-d7ec-4cf4-a1cf-3a17cdfd3149" />


Deixe marcado a primeira opção e clique em continuar. Depois deixe novamente a primeira opção marcada e clique em continuar mais uma vez.

<img width="1919" height="926" alt="Imagem8" src="https://github.com/user-attachments/assets/4a0d01f2-64eb-42e7-b1d7-237e6f6f3225" />
<img width="1919" height="919" alt="Imagem9" src="https://github.com/user-attachments/assets/427daad4-c827-421c-adf2-b50885bc1fab" />

Adicione uma descrição para o App ID e o valor do Bundle ID, como: com.fateczl.nomeapp 

É possível adicionar essas informações, podendo alterar depois:

- Capabilities (Capacidades): São funcionalidades que seu app pode usar, como câmera, notificações push, ou iCloud. Você ativa essas capacidades para que o app tenha permissão para usar esses recursos.

- App Services (Serviços do app): São serviços específicos que seu app pode utilizar, como Apple Pay, Game Center, ou CloudKit, que facilitam funcionalidades avançadas.

- Capability Requests (Solicitações de capacidade): São os pedidos que seu app faz para usar alguma capacidade, e que precisam ser aprovados pela Apple durante a submissão para garantir que o app tem autorização para usar esses recursos.

<img width="1919" height="929" alt="Imagem10" src="https://github.com/user-attachments/assets/fb0bc957-5ca6-4bb3-a2af-0d3f1a4812a4" />

# Criar App
A após ter criado o Bundle ID, é preciso criar o app (é possível adicionar permissão para os alunos criarem o aplicativo, portanto apenas a etapa de criação do Bundle ID é preciso ser feito pela Fatec).

Acesse a conta em: https://developer.apple.com/account e selecione em "App Store Connect" a primeira opção, "Apps".

<img width="1919" height="917" alt="Imagem13" src="https://github.com/user-attachments/assets/1f777d44-c5a6-47ee-9306-18ee10d7687f" />
<br>

Clique no ícone azul para adicionar um aplicativo

<img width="1919" height="919" alt="Imagem12" src="https://github.com/user-attachments/assets/33d05b3f-0dc1-4f6b-9de8-c5d6ead098bf" />
<br>

Preencha todas as informações que foram solicitadas

<img width="1919" height="922" alt="Imagem14" src="https://github.com/user-attachments/assets/d6b1c967-dc19-4324-a827-e92040a39c40" />
<br>

# Alunos
Manual para os alunos aceitarem o convite e gerenciarem os aplicativos

## Aceitar convite
Ao abrir o link do convite, é necessário criar uma conta na Apple se não tiver. Preecnha todos os dados e clique em Continuar, confirme seu email e número de telefone. É possível e provavel que de erro. Você pode tentar novamente ou criar uma conta por um dispositivo iOS ou MacOS, que facilita na criação. por fim, aceite os termos de uso.

<img width="1914" height="919" alt="Imagem1" src="https://github.com/user-attachments/assets/40b24eb0-11f3-4f24-bd72-db0237af3636" />
<img width="1916" height="923" alt="Imagem2" src="https://github.com/user-attachments/assets/4ba94a31-3224-49f2-a1c5-bdec7edd9cfe" />
<img width="1916" height="924" alt="Imagem3" src="https://github.com/user-attachments/assets/1cb59611-0ac9-4109-9998-2522036ea066" />
<img width="1918" height="920" alt="Imagem4" src="https://github.com/user-attachments/assets/46c6783c-348d-4c2d-82cf-71924839e90a" />

## Apps
Após aceitar o convite, você verá uma tela como essa, com os aplicativos que você tem acesso no [Apple Store Connect](https://appstoreconnect.apple.com/apps)

<img width="1916" height="920" alt="Imagem5" src="https://github.com/user-attachments/assets/8b2c552d-c1f8-47a3-8b63-0a7cb385e2e6" />
<br>

Ao selecionar o aplicativo, é apresentado a tela de configuração do app que contém a lista de passos para a publicação na Apple Store

<img width="1918" height="927" alt="Imagem6" src="https://github.com/user-attachments/assets/25f23468-62a7-4347-a322-2ab3f051d266" />

## Plataformas
Na parte superior direita do aplicativo é listado todas as plataformas selecionadas para seu app (iOS, macOS, tvOS ou visionOS) e em cada uma é possível adicionar captura de telas e descrições sobre o aplicativo.

![Imagem15](https://github.com/user-attachments/assets/4c44f90c-fc06-4f81-bf4f-47c6a86c7d55)

### Visualizações e capturas de tela
É aqui que você vai adicionar as capturas de telas para a plataforma selecionada 

As capturas de tela devem estar no formato JPG ou PNG e no espaço de cores RGB. As visualizações de aplicativos devem estar no formato M4V, MP4 ou MOV e não podem exceder 500 MB. [Saiba Mais](https://developer.apple.com/help/app-store-connect/manage-app-information/upload-app-previews-and-screenshots)

<img width="1341" height="630" alt="Imagem16" src="https://github.com/user-attachments/assets/c2437256-3a1c-461d-95e1-38907280513f" />
<img width="1248" height="408" alt="Imagem18" src="https://github.com/user-attachments/assets/72aee7c4-2255-459c-b3ce-ed4b9aae7e1f" />

Mais abaixo, é preciso aidionar as informações do seu aplicativo. Nenhuma dessas informações é obrigatória.

##### Texto promocional:
O texto promocional permite que você informe os visitantes da App Store sobre os recursos atuais do aplicativo sem exigir um envio atualizado. Esse texto aparecerá acima da sua descrição na App Store para clientes com dispositivos com iOS 11 ou posterior e macOS 10.13 ou posterior.

##### Descrição
Uma descrição do seu aplicativo, detalhando os recursos e funcionalidades.

##### Keywords
Inclua uma ou mais palavras-chave que descrevam seu aplicativo. As palavras-chave tornam os resultados de pesquisa da App Store mais precisos. Separe as palavras-chave com uma vírgula em inglês, uma vírgula em chinês ou uma mistura de ambas.

##### URL de suporte
Uma URL com informações de suporte para seu aplicativo. Isso aparece na página do produto do seu aplicativo assim que você lança seu aplicativo na App Store.

##### Marketing URL
Um URL com informações de marketing sobre seu aplicativo. Este URL ficará visível na App Store.

##### Versão
A versão do aplicativo que você está adicionando. A numeração deve seguir as convenções de controle de versão de software.

##### Direitos autorais
O nome da pessoa ou entidade que detém os direitos exclusivos do seu aplicativo, precedido pelo ano em que os direitos foram obtidos (por exemplo, "2008 Acme Inc."). Não forneça uma URL.

##### Arquivo de cobertura de aplicativo de roteamento
Especifique as regiões geográficas compatíveis com seu aplicativo. O arquivo deve estar no formato .geojson e pode conter apenas um elemento MultiPolygon. [Saiba Mais](https://developer.apple.com/help/app-store-connect/reference/platform-version-information)

<img width="1173" height="703" alt="Imagem19" src="https://github.com/user-attachments/assets/95e6c5cf-dded-456b-8bcc-0fbb831ea1d5" />

### Clipe de Aplicativo
Não é obrigatório. Permite ao usuário acessar uma parte do app sem precisar instalá-lo completamente. Para isso, é necessário primeiro enviar uma compilação que contenha o clipe. Após o envio, é possível adicionar uma imagem de cabeçalho no formato JPG ou PNG (1800x1200 px), um subtítulo com até 56 caracteres descrevendo a ação principal do clipe e selecionar a ação desejada (como fazer um pagamento ou reserva). Quando tudo estiver configurado corretamente, o link do clipe será gerado automaticamente para ativação via Safari.

<img width="1328" height="685" alt="Imagem20" src="https://github.com/user-attachments/assets/fc1003b9-b4dc-493e-8e1c-a019446d9da8" />

### Clipe de Aplicativo
Não é obrigatório. Capturas de tela específicas para aplicativos que usam iMessage.

<img width="1264" height="544" alt="Imagem21" src="https://github.com/user-attachments/assets/b477f36c-f1d1-4cd6-b6c6-78ef0998713a" />

### Build
Mostra todos os buids que você subiu no seu aplicativo.
<img width="1178" height="343" alt="Imagem22" src="https://github.com/user-attachments/assets/68895d3f-31d9-4b15-8d02-e38b268d7e37" />

Se você ainda não subiu, terá essa tela
<img width="1168" height="305" alt="Imagem23" src="https://github.com/user-attachments/assets/68580372-63c0-4bd7-b715-2d9b881cf01b" />

### Game Center (Central de Jogos)
Marque essa opção se o seu aplicativo for um jogo

        O Game Center é a plataforma da Apple que permite integrar funcionalidades sociais e competitivas aos aplicativos de jogos, como rankings, conquistas, partidas multiplayer e perfis de jogadores. Ele melhora a experiência do usuário ao permitir que jogadores comparem pontuações, desafiem amigos e acompanhem seu progresso entre dispositivos Apple.


### Informações de revisão do aplicativo
Se o seu aplicativo tiver alguma funcionalidade restrita por meio de login, é necessário informar um login e senha de teste para a Apple analisar, adicionar informações adicionais (se houver) para realizar o login e informações de contato caso a Apple encontre algum problema.

Sobre o anexo:

        Você pode anexar documentação específica do aplicativo, vídeos de demonstração e outros itens para ajudar a evitar atrasos durante o processo de revisão do aplicativo. Certifique-se de usar arquivos com as seguintes extensões: .pdf, .doc, .docx, .rtf, .pages, .xls, .xlsx, .numbers, .zip, .rar, .plist, .crash, .jpg, .png, .mp4 ou .avi.

<img width="1190" height="452" alt="Imagem24" src="https://github.com/user-attachments/assets/4cee1fbb-1dda-4f91-85a6-fe67b585b9b6" />

### Lançamento da versão da App Store
Você decide se o aplicativo vai ser lançado automaticamente ou manualmente ao ser aprovado pela Apple. 

<img width="1303" height="279" alt="Imagem25" src="https://github.com/user-attachments/assets/e40f9f5c-42e7-4629-bc0d-25603fe9ea29" />

