# Plataforma ONG - Projeto Frontend

## 📋 Como Visualizar o Projeto

### Passo a Passo

1. **Abra a Página Inicial**
   - No navegador, abra o arquivo `index.html`
   - Você verá a página inicial com informações sobre a organização, missão, visão, valores, história, equipe e contato

2. **Navegue pelas Páginas**
   - Use o menu de navegação no topo da página para acessar:
     - **Início**: Informações institucionais da organização
     - **Projetos**: Projetos sociais, informações sobre voluntariado e como doar
     - **Cadastro**: Formulário completo de cadastro para voluntários e doadores

3. **Explore o Formulário de Cadastro**
   - Acesse a página `cadastro.html`
   - Preencha o formulário e observe:
     - As máscaras automáticas para CPF, Telefone e CEP enquanto você digita
     - A validação dos campos em tempo real
     - Os campos obrigatórios marcados com asterisco (*)
     - As mensagens de ajuda abaixo de cada campo

4. **Teste a Responsividade**
   - Redimensione a janela do navegador ou abra em diferentes dispositivos
   - O layout se adapta automaticamente a diferentes tamanhos de tela
   - Teste em modo mobile, tablet e desktop

5. **Teste a Navegação**
   - Clique nos links do menu para navegar entre as páginas
   - Todos os links estão funcionais
   - Teste o scroll suave entre seções

## 🚀 Formas de Visualizar

### Opção 1: Abrir Diretamente no Navegador
1. Navegue até a pasta do projeto
2. Clique duas vezes no arquivo `index.html`
3. O projeto será aberto no seu navegador padrão

### Opção 2: Usar um Servidor Local (Recomendado)
1. Abra o terminal/PowerShell na pasta do projeto
2. Execute um dos comandos abaixo:

**Com Python 3:**
```bash
python -m http.server 8000
```

**Com Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Com Node.js (http-server):**
```bash
npx http-server
```

3. Acesse no navegador: `http://localhost:8000`

### Opção 3: Usar Extensão do VS Code/Cursor
1. Instale a extensão "Live Server" no VS Code/Cursor
2. Clique com o botão direito no arquivo `index.html`
3. Selecione "Open with Live Server"

## 📁 Estrutura do Projeto

```
Frontend/
├── index.html          # Página inicial
├── projetos.html       # Página de projetos e doações
├── cadastro.html       # Formulário de cadastro
├── css/
│   └── styles.css      # Estilos do projeto
├── js/
│   ├── main.js         # Funcionalidades gerais
│   ├── masks.js        # Máscaras de input
│   └── form-validation.js  # Validação de formulário
└── images/
    └── [imagens SVG]   # Imagens do projeto
```

## ⚠️ Observações Importantes

- **Navegadores Suportados**: Chrome, Firefox, Edge, Safari (versões recentes)
- **JavaScript**: O projeto requer JavaScript habilitado para as máscaras e validações funcionarem
- **Imagens**: Todas as imagens estão incluídas na pasta `images/` em formato SVG

## 🎯 Funcionalidades para Testar

✅ Máscaras automáticas:
- CPF: Digite números e veja a formatação automática (000.000.000-00)
- Telefone: Formatação automática para (00) 00000-0000
- CEP: Formatação automática para 00000-000

✅ Validação de formulário:
- Campos obrigatórios não podem ficar vazios
- Validação de formato (e-mail, CPF, telefone, etc.)
- Mensagens de erro ao tentar enviar formulário inválido

✅ Design Responsivo:
- Teste em diferentes tamanhos de tela
- Menu adapta-se automaticamente

---

**Desenvolvido com dedicação para transformar vidas através da tecnologia social.**
