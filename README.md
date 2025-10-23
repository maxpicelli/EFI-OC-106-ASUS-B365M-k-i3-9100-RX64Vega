# EFI OpenCore 1.0.6 - ASUS B365M-K + i3-9100 + RX Vega 64

EFI OpenCore 1.0.6 configurado para Hackintosh com hardware Intel Coffee Lake.

✅ **Compatível com macOS Tahoe 26.0.1**

## 📋 Especificações

- **CPU**: Intel Core i3-9100 (Coffee Lake)
- **GPU**: Gigabyte AMD Radeon RX Vega 64
- **Placa-Mãe**: ASUS B365M-K
- **Chipset**: Intel B365
- **RAM**: 32GB DDR4 2400MHz
- **Armazenamento**: HD 250GB

## 🔧 Versão do OpenCore

- **OpenCore**: 1.0.6
- **macOS Compatível**: Tahoe 26.0.1 (e versões anteriores)

## 📦 Kexts Incluídos

- AppleALC
- HibernationFixup
- Lilu
- NVMeFix
- RealtekRTL8111
- RestrictEvents
- SMCProcessor
- SMCSuperIO
- USBPorts
- VirtualSMC

## 📥 Instalação

### Método 1: Download da Release

1. Acesse a [página de Releases](https://github.com/maxpicelli/EFI-OC-106-ASUS-B365M-k-i3-9100-RX64Vega/releases)
2. Baixe a versão mais recente (arquivo `.zip`)
3. Extraia o arquivo

### Método 2: Git Clone

```bash
git clone https://github.com/maxpicelli/EFI-OC-106-ASUS-B365M-k-i3-9100-RX64Vega.git && open EFI-OC-106-ASUS-B365M-k-i3-9100-RX64Vega
```

## 🚀 Como Usar

1. Faça backup do seu EFI atual
2. Copie esta EFI para a partição EFI do seu sistema
3. Ajuste o config.plist conforme necessário para o seu hardware

## ⚠️ Aviso

Este EFI foi configurado para o meu hardware específico. Não use diretamente sem fazer as devidas adaptações para o seu sistema.

## 📝 Créditos

- [OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [Dortania's OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/)

