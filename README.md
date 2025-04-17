# Desafio DIO: Criação e Configuração de VM no Microsoft Azure

Este repositório documenta a criação e configuração de uma máquina virtual no Azure, realizada como parte do laboratório da [Digital Innovation One (DIO)](https://dio.me).

## 📌 Objetivos do Laboratório
- Aplicar conceitos básicos de computação em nuvem.
- Criar e configurar uma máquina virtual (VM) no Azure.
- Documentar o processo para referência futura.

## 🚀 Tecnologias Utilizadas
- Microsoft Azure
- GitHub
- Markdown

## 📋 Etapas Realizadas

### 1. Acesso ao Portal do Azure
Acesse [portal.azure.com](https://portal.azure.com/) e faça login com suas credenciais.

### 2. Criação da Máquina Virtual (VM)
- Clique em **Criar um recurso** → **Máquina Virtual**
- Escolha o Sistema Operacional (ex: Windows Server ou Ubuntu)
- Selecione ou crie um Grupo de Recursos
- Configure detalhes da instância (tamanho, armazenamento, etc.)
- Configure acesso (usuário, senha, chaves SSH)
- Revise e clique em **Criar**.

### 3. Configuração e Teste da VM
- Conecte-se à VM utilizando Remote Desktop (Windows) ou SSH (Linux)
- Realize testes iniciais de conectividade e desempenho

## 📸 Capturas de Tela (opcional)
Veja as imagens do processo na pasta `/images` deste repositório:
- Criação da VM (`img01-criando-maquina-virtual.png`)
- Configuração da VM (`img02-configuracao-vm.png`)

## 💡 Dicas e Observações Importantes
- Considere sempre definir claramente o tamanho adequado para seu uso (não exagere!)
- Configure o desligamento automático da VM para economizar custos.

## 📚 Links Úteis
- [Documentação Azure - Criando uma VM Windows](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [Guia Markdown GitHub](https://docs.github.com/pt/get-started/writing-on-github)

## ✅ Conclusões
Este desafio reforçou os conceitos essenciais sobre criação e gerenciamento de recursos na nuvem pública Azure, além de aprimorar minhas habilidades em documentação técnica.

Solução:

1. Acesse o Portal do Azure
Acesse: https://portal.azure.com

Faça login com sua conta Microsoft.

2. Vá até "Máquinas Virtuais"
No menu lateral esquerdo, clique em “Máquinas Virtuais”.

Clique no botão “+ Criar” > “Máquina virtual”.

3. Configuração Básica
Assinatura: selecione sua assinatura ativa.

Grupo de recursos: selecione um existente ou clique em “Criar novo”.

Nome da VM: insira um nome único, como vm-windows2022.

Região: selecione a região mais próxima (ex: Brazil South).

Disponibilidade: mantenha como padrão (opcional).

Imagem: selecione Windows Server 2022 Datacenter – Gen2.

Tamanho da VM: clique em “Ver todos os tamanhos” e escolha, por exemplo, Standard_B1s para testes.

Usuário e senha: configure um nome de usuário e uma senha segura.

Portas de entrada públicas: selecione Permitir portas selecionadas e marque a porta RDP (3389).

4. Disco da Máquina Virtual
Mantenha a opção padrão Disco SSD Premium (recomendado).

5. Rede
Selecione a rede virtual e a sub-rede padrão (ou mantenha as criadas automaticamente).

Grupo de segurança da rede: mantenha padrão com RDP permitido.

6. Opções avançadas e tags
Para este desafio, você pode deixar as configurações padrão.

Tags são opcionais.

7. Revisar e criar
Clique em “Revisar + criar”.

Verifique se todos os campos estão corretos.

Clique em “Criar”.

8. Acompanhe a implantação
Aguarde alguns minutos até que a implantação seja concluída.

Clique em “Ir para o recurso” quando a VM estiver pronta.

9. Conectar-se à Máquina Virtual
Clique em “Conectar” > RDP.

Baixe o arquivo .rdp e abra no seu computador.

Use o nome de usuário e senha que você configurou para fazer login no Windows Server 2022.
