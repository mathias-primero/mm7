# Decodificador Seguro 🔐

Uma ferramenta educativa e prática para decodificar textos em **Base64** ou **Hexadecimal** diretamente no seu navegador, com total segurança e privacidade.

## 🌟 Características

- ✅ **100% Local**: Toda a decodificação acontece no seu navegador — nenhum dado é enviado para servidores
- 🎓 **Ferramenta Educativa**: Perfeita para estudar codificação e segurança digital
- 🎨 **Interface Moderna**: Design limpo e responsivo para desktop e mobile
- 🛡️ **Seguro**: Nenhum rastreamento, cookies ou coleta de dados
- ⚡ **Rápido**: Processamento instantâneo sem latência de rede
- 🌐 **Multilíngue**: Interface em português

## 🚀 Como Usar

1. Acesse o arquivo `index.html` em seu navegador
2. Escolha o formato de entrada (Base64 ou Hexadecimal)
3. Cole o texto codificado no campo de entrada
4. Clique em "Decodificar" ou use o botão "Carregar exemplo"
5. O resultado será exibido no campo de saída
6. Use "Copiar resultado" para copiar para a área de transferência

## 📋 Formatos Suportados

### Base64
- Representação de bytes usando caracteres ASCII
- Comum em: emails, dados de URL, armazenamento de imagens
- Não é criptografia — apenas uma codificação

### Hexadecimal
- Cada byte é representado por dois dígitos (00 a FF)
- Comum em: valores binários, endereços de memória, hashes
- Exemplo: `48656c6c6f` = "Hello"

## ⚠️ Limitações Importantes

Esta ferramenta **NÃO pode descriptografar**:
- Senhas (bcrypt, Argon2, SHA-256, MD5 etc.)
- Dados criptografados (AES, RSA, etc.)
- Hashes de qualquer tipo

Decodificar Base64 ou Hexadecimal é o oposto de criptografia — é apenas uma transformação reversível de representação de dados.

## 🏗️ Estrutura do Projeto

```
mm7/
├── index.html          # Página principal com interface e lógica
├── styles.css          # Estilos CSS (integrados no HTML)
├── senha.svg          # Ícone SVG
└── README.md          # Este arquivo
```

## 🎨 Tecnologias

- **HTML5**: Estrutura semântica acessível
- **CSS3**: Design responsivo com variáveis CSS
- **JavaScript Vanilla**: Decodificação sem dependências externas
- **Web APIs**: TextDecoder para decodificação UTF-8 segura

## 🔒 Privacidade

- ✅ Nenhuma requisição de rede
- ✅ Nenhum cookie ou armazenamento
- ✅ Nenhum rastreamento
- ✅ Código-fonte aberto e auditável

## 🎯 Casos de Uso

- 📚 Estudar codificação e representação de dados
- 🔍 Decodificar dados para fins educacionais
- 🛡️ Aprender sobre segurança digital
- 💡 Trabalhos acadêmicos sobre criptografia
- 🔧 Debugging de dados codificados

## 📝 Exemplos

### Base64
- Entrada: `U2VuaGEgZGUgZXhlbXBsbzE=`
- Saída: `Senha de exemplo`

### Hexadecimal
- Entrada: `48656c6c6f`
- Saída: `Hello`

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir melhorias
- Submeter pull requests
- Melhorar a documentação

## 📄 Licença

Este projeto é fornecido como-é para fins educacionais e de demonstração.

## ⚖️ Responsabilidade

Este projeto é fornecido apenas para fins educacionais. Os usuários são responsáveis por:
- Compreender as limitações de Base64 e Hexadecimal
- Usar a ferramenta de forma ética e legal
- Não tentar descriptografar dados protegidos por criptografia

---

**Desenvolvido por**: [mathias-primero](https://github.com/mathias-primero)  
**Categoria**: Ferramentas Educativas  
**Status**: Ativo ✅
