# Atualizações BYDION

Este repositório distribui versões oficiais assinadas do BYDION. O arquivo update.json contém a versão atual, o tamanho e o SHA-256 do APK publicado em Releases.

O app consulta novas versões ao abrir, com intervalo mínimo de seis horas, e permite consulta manual em Atualizar BYDION. O cliente confirma o download e a instalação. Atualizar o BYDION independe da assinatura da loja.

Instalações antigas anteriores ao canal precisam receber esta versão inicial uma vez, com mesmo pacote e mesma chave, preservando dados. Este repositório não cadastra retrospectivamente as centrais já instaladas. Não há notificação com o app fechado nesta implementação.

Para publicar a próxima versão: compilar aumentando versionCode; assinar com a chave original; criar uma nova Release e enviar o APK; conferir que o download está acessível; atualizar update.json com URL, versão, tamanho e hash exatos. Publicar o manifesto por último. Manter os arquivos de versões já anunciadas disponíveis.

Não publicar chaves privadas, senhas, dados de clientes nem APKs de terceiros neste repositório.
