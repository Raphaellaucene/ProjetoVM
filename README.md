# ProjetoVM
Guia passo a passo para criar uma máquina virtual no Microsoft Azure.

----
# Criando uma Máquina Virtual no Microsoft Azure

Este guia fornece instruções detalhadas sobre como criar uma máquina virtual (VM) no Microsoft Azure.

## Passo 1: Login no Azure

1. Acesse o portal do Azure: [https://portal.azure.com](https://portal.azure.com)
2. Faça login com sua conta Microsoft.

## Passo 2: Criar um Novo Recurso

1. No menu à esquerda, clique em **"Criar um recurso"**.
2. Na barra de pesquisa, digite **"Máquina Virtual"** e selecione **"Máquina Virtual"** nos resultados.
3. Clique em **"Criar"**.

## Passo 3: Configurar a Máquina Virtual

1. **Assinatura**: Selecione sua assinatura do Azure.
2. **Grupo de Recursos**: Crie um novo grupo de recursos ou selecione um existente.
3. **Nome da VM**: Insira um nome para sua VM.
4. **Região**: Escolha a região onde a VM será criada.
5. **Imagem**: Selecione o sistema operacional desejado (por exemplo, Windows Server ou Ubuntu).
6. **Tamanho**: Escolha o tamanho da VM de acordo com suas necessidades.
7. **Nome de Usuário**: Insira um nome de usuário para a VM.
8. **Senha**: Crie uma senha forte para o usuário.

## Passo 4: Configurações Adicionais

1. **Discos**: Configure os discos de armazenamento conforme necessário.
2. **Rede**: Configure as opções de rede, incluindo a criação de um novo grupo de segurança de rede (NSG) para permitir o tráfego de entrada.
3. **Gerenciamento**: Configure as opções de monitoramento e gerenciamento conforme necessário.
4. **Revisar + Criar**: Revise as configurações e clique em **"Criar"**.

## Passo 5: Acessar a Máquina Virtual

### Acesso via RDP (para VMs Windows)

1. No portal do Azure, navegue até sua VM e clique em **"Conectar"**.
2. Selecione **"RDP"** e clique em **"Baixar arquivo RDP"**.
3. Abra o arquivo RDP baixado e clique em **"Conectar"**.
4. Insira o nome de usuário e a senha configurados anteriormente.

### Acesso via SSH (para VMs Linux)

1. No portal do Azure, navegue até sua VM e clique em **"Conectar"**.
2. Selecione **"SSH"** e copie o comando SSH fornecido.
3. Abra um terminal no seu computador e cole o comando SSH.
4. Insira a senha configurada anteriormente, se necessário.

## Conclusão

Parabéns! Você criou e acessou com sucesso uma máquina virtual no Microsoft Azure.
