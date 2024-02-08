# Reconhecimento de Texto em Imagens

Este projeto tem como objetivo realizar o reconhecimento de texto em imagens utilizando técnicas de processamento de imagens e OCR (Reconhecimento Óptico de Caracteres).

## Descrição do Projeto

Neste projeto, utilizei técnicas de processamento de imagens e a biblioteca Tesseract para realizar o reconhecimento de texto em imagens. O objetivo é extrair informações de texto a partir de imagens, permitindo a automação de tarefas de leitura e análise de documentos.

## Processo

### Coleta de ImagensCrie um recurso de serviços de IA do Azure
Você pode usar os recursos de análise de imagem do Azure AI Vision com um recurso multisserviço de serviços de IA do Azure . Se ainda não o fez, crie um recurso de serviços de IA do Azure na sua assinatura do Azure.

Em outra guia do navegador, abra o portal do Azure em https://portal.azure.com , entrando com a conta da Microsoft associada à sua assinatura do Azure.

Clique no botão ＋Criar um recurso e pesquise os serviços de IA do Azure . Selecione criar um plano de serviços de IA do Azure . Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
Assinatura : sua assinatura do Azure .
Grupo de recursos : selecione ou crie um grupo de recursos com um nome exclusivo .
Região : Leste dos EUA.
Nome : Insira um nome exclusivo .
Nível de preços : Padrão S0.
Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado .
Selecione Revisar + criar e depois Criar e aguarde a conclusão da implantação.

Em outra guia do navegador, navegue até Vision Studio .

Entre com sua conta e certifique-se de usar o mesmo diretório onde você criou seu recurso de serviços de IA do Azure.

Na página inicial do Vision Studio, selecione Visualizar todos os recursos no título Introdução ao Vision .

O link Visualizar todos os recursos está destacado em Introdução ao Vision no Vision Studio.

Na página Selecione um recurso para trabalhar , passe o cursor do mouse sobre o recurso que você criou acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão .

## Estrutura do Repositório

- `inputs/`: Pasta contendo as imagens utilizadas para o reconhecimento de texto.
- `output/`: Pasta contendo os resultados do reconhecimento de texto nas imagens.
- `README.md`: Descrição detalhada do projeto, processo de reconhecimento de texto, resultados e insights.

## Próximos Passos
- Pretendo explorar técnicas mais avançadas de processamento de imagens para melhorar a precisão do reconhecimento de texto.
- Investigar a integração do reconhecimento de texto em aplicações web e móveis para automação de tarefas.

---

Espero que este projeto demonstre minha habilidade em processamento de imagens e reconhecimento de texto. Se tiver alguma dúvida ou sugestão, não hesite em entrar em contato!
