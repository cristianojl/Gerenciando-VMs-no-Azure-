# Gerenciando-VMs-no-Azure-
Curso da DIO  --  Microsoft - Azure Administrator Certification (AZ-104)

# Guia de Provisionamento de Máquinas Virtuais no Microsoft Azure

Este repositório contém um guia detalhado sobre o processo de criação e configuração de Máquinas Virtuais (VMs) no Microsoft Azure, desenvolvido como parte do desafio de projeto da DIO (Digital Innovation One) pela mentora Valéria Baptista CloudData Tech & DevOps

## 📌 Introdução
O Microsoft Azure permite a criação de infraestrutura computacional de forma rápida e escalável. Este documento serve como um material de apoio para entender os requisitos e o passo a passo necessário para subir uma instância na nuvem.
Olá! Eu sou o Cristiano e este repositório contém a documentação técnica do meu desafio de configuração de uma VM Windows utilizando o portal do Microsoft Azure. O objetivo foi realizar o provisionamento completo.

## 🚀 Passo a Passo: Criando uma VM no Azure

### 1. Início do Provisionamento
1. Acesse o portal.azure.com e fazer o login na conta criada (No meu caso uma conta free para  o desafio)
2. No menu lateral ou na barra de busca, selecione **Máquinas Virtuais**.
3. Clique em **+ Criar** e selecione **Máquina virtual do Azure**.

### 2. Configurações Básicas (Aba: Básico)
Assinatura: Selecione a assinatura ativa 
Grupo de Recursos: VMs-01
Nome da Máquina: MVCJL01
Região: East US 2 (Foi necessário utilizar esse região pois a do “brasilsouth” não tinha o tamanho escolhido)..
Imagem: Windows Server 2022 Datacenter: Azure Edition - x64 Gen2
Tamanho: Standard_D2s_v3 – 2 vcpus, 8 GiB memória (US$ 0,02938)

### 3. Conta de Administrador
Nome de usuário: crisjlima
Senha: crisjlima@2026

### 5. Discos e Rede
Discos: Selecione o tipo de armazenamento (SSD Premium para performance ou HDD Padrão para baixo custo).
Rede Virtual (VNet): O Azure criará uma rede padrão automaticamente se você não tiver uma.
IP Público:  20.186.21.131( Interface de rede mvcjl01188_z1) Atribuído para acesso externo.

## 🛠️ Ferramentas Utilizadas
Portal do Azure
Git & GitHub

## 🎁 **BONUS**
Compartilhei aqui também o link do vídeo com o processo de criação da maquina virtual

##  ▶️ https://www.youtube.com/watch?v=tNtSkzlS3V8

Desenvolvido por Cristiano Jesus Lima

