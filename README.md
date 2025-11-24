# flowstory-crie-suas-historias-interativas
# FlowStory - Crie suas Histórias Interativas

![FlowStory Logo](https://img.icons8.com/color/96/000000/fantasy.png)

**FlowStory** é uma plataforma criativa e intuitiva para criação de histórias interativas, webseries e jogos narrativos. Desenvolvida com carinho para autoras e criadoras de conteúdo.

## 🌟 Características Principais

### 🎨 **Interface Amigável**
- Paleta de cores feminina suave
- Design intuitivo e acessível
- Sistema de arrastar e soltar

### 📝 **Sistema de Código Similar**
- Escreva em português compreensível
- Sintaxe intuitiva e fácil de aprender
- Conversão automática de bolhas para código

### 🖼️ **Sistema Multimídia**
- Upload de imagens (PNG, JPEG, JPG)
- Gerenciamento visual de assets
- Organização por projetos

### 👥 **Rede Social Integrada**
- Perfil de criadora
- Sistema de seguidores
- Compartilhamento de projetos
- Comunidade de autoras

## 🚀 Começando

### Pré-requisitos
- Python 3.8 ou superior
- tkinter (geralmente incluído no Python)

### Instalação

1. **Baixe o arquivo executável:**
   ```bash
   # Disponível na página de releases
   FlowStory.exe
   ```

2. **Ou execute via Python:**
   ```bash
   python flowstory.py
   ```

### Primeiros Passos

1. **Crie sua conta:**
   - Clique em "Cadastrar"
   - Escolha seu nick e email
   - Receba seu código único (não expira!)

2. **Sua primeira história:**
   - Clique em "Criar História"
   - Dê um nome ao projeto
   - Use o editor visual ou de texto

## 📖 Como Usar

### 🎨 Editor Visual
1. **Arraste bolhas** da biblioteca para a mesa de trabalho
2. **Organize** cenas e personagens visualmente
3. **Configure ações** com duplo-clique nas bolhas

### 📝 Editor de Texto
```portugues
SE (personagem_esta_feliz) ENTÃO
    DIÁLOGO: "Que dia maravilhoso!"
    MUDAR_EXPRESSÃO(Ana, feliz)
SENÃO
    DIÁLOGO: "Estou um pouco triste..."
    MUDAR_EXPRESSÃO(Ana, triste)
FIM
```

### 🖼️ Trabalhando com Imagens
1. Clique em "Upload Imagem"
2. Selecione PNG, JPG ou JPEG
3. Arraste e posicione no workspace
4. Use em cenas e personagens

## 🎯 Exemplos de Código

### História Básica
```portugues
PERSONAGEM(Ana, neutra)
CENÁRIO(floresta, dia)

DIÁLOGO: "Ana entra na floresta encantada..."

SE (escolha_caminho == "esquerda") ENTÃO
    CENÁRIO(clareira, sol_poente)
    DIÁLOGO: "Você encontrou uma clareira mágica!"
SENÃO
    CENÁRIO(rio, noite)
    DIÁLOGO: "Um rio brilhante aparece à sua frente..."
FIM
```

### Sistema de Personagens
```portugues
PERSONAGEM(João, feliz)
MOVER(João, CENTRO)
MUDAR_EXPRESSÃO(João, surpreso)

CENÁRIO(cidade, entardecer)
TEMPO_SLIDE(3)
```

## 📦 Estrutura do Projeto

```
FlowStory/
├── 📁 autosave_projetos/     # Salvamento automático
├── 📁 imagens/               # Assets do projeto
├── 📄 flow_users.json        # Base de usuários
├── 📄 projeto_config.json    # Configurações
└── 📄 historias/             # Projetos exportados
```

## 🔧 Recursos Técnicos

### 🛡️ Sistema de Segurança
- Auto-salvamento a cada 15 segundos
- Códigos únicos de acesso
- Backup automático de projetos

### 🌐 Exportação
- **HTML/CSS/JS** - Para web
- **APK** - Dispositivos Android
- **EXE** - Windows (32x/64x)
- **GitHub** - Repositórios
- **itch.io** - Publicação

### 📊 Estatísticas
- Contador de linhas em tempo real
- Preview integrado
- Detecção de erros
- Relatório de bugs

## 👥 Comunidade

### 🏮 Sua Banca
- **Perfil personalizado**
- **Histórias publicadas**
- **Seguidores e métricas**
- **Atualizações (até 250 caracteres)**

### 🌍 Explorar
- **Descobrir novas autoras**
- **Participar de jams**
- **Grupos temáticos**
- **Wikis e fanfics**

## 🎨 Personalização

### Fontes Incluídas
- **Komika Axis** - Bolhas e títulos
- **Hey Comic** - Botões especiais
- **Sunlight Dreams** - Interface
- **Arial** - Diálogos e texto

### Temas de Cores
- Lilás suave
- Laranja pastel
- Rosa apagado
- Amarelo claro

## 🐛 Solução de Problemas

### Problemas Comuns

**"Não consigo fazer upload de imagens"**
- Verifique se o arquivo é PNG, JPG ou JPEG
- Tamanho máximo: 10MB
- Reinicie o aplicativo se necessário

**"Editor travando"**
- Verifique o auto-salvamento na pasta `autosave_*`
- O projeto será recuperado automaticamente

**"Login não funciona"**
- Use o código único enviado por email
- Ou recupere sua senha pelo sistema

### Suporte
- 📧 Email: suporte@flowstory.com
- 🐛 Issues: GitHub Repository
- 💬 Comunidade: Discord Server

## 📄 Licença

Este projeto é licenci sob a MIT License - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

## 🏆 Créditos

Desenvolvido com 💜 para a comunidade de criadoras de histórias interativas.

**Equipe FlowStory:**
- Design e Desenvolvimento
- Comunidade e Suporte
- Documentação e Tutoriais

---

<div align="center">

**✨ Comece sua jornada criativa hoje mesmo! ✨**

[Download] | [Documentação] | [Comunidade]

*FlowStory - Onde cada escolha cria uma nova realidade*

</div>

## 🔄 Histórico de Versões

### v1.0.0 (Atual)
- ✅ Sistema completo de histórias interativas
- ✅ Editor visual e de texto integrados
- ✅ Rede social de criadoras
- ✅ Exportação multiplataforma
- ✅ Sistema de upload de imagens

### Próximas Atualizações
- 🚧 Editor de webseries
- 🚧 Sistema de colaboração
- 🚧 Loja de assets
- 🚧 Traduções

---

**📣 Junte-se à nossa comunidade de criadoras!**  
Crie, compartilhe e inspire-se com outras autoras na FlowStory. Sua próxima grande história está esperando para ser contada! 📖✨
