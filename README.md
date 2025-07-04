# 📝 Subdiretriz de Desenvolvimento - hidrosolucoes_site

Este documento estabelece as diretrizes específicas para o desenvolvimento, manutenção e rastreabilidade de tudo que for realizado dentro da pasta `hidrosolucoes_site/`.

## 📋 Objetivos
- Garantir rastreabilidade total de todas as ações, alterações e decisões técnicas referentes ao site institucional.
- Padronizar o fluxo de trabalho, documentação e versionamento do site.
- Facilitar auditoria, manutenção e evolução do site por qualquer membro do time ou IA.

## 🚦 Protocolo de Operação
1. **Toda alteração, correção ou implementação no site deve ser registrada no arquivo `LOG_OPERACIONAL_SITE.md`** (log detalhado de ações técnicas).
2. **Toda entrega, release ou funcionalidade implementada deve ser registrada no arquivo `LOG_SITE.md`** (log de entregas e releases).
3. **Alterações críticas ou estruturais devem ser documentadas também no LOG_OPERACIONAL.md geral do projeto.**
4. **Scripts, automações e testes devem ser documentados e mantidos na própria pasta do site.**
5. **Sempre manter este README atualizado com novas diretrizes, padrões ou decisões técnicas.**

## 📁 Estrutura Recomendada
- `index.html` — Página principal do site
- `css/` — Estilos
- `images/` — Imagens
- `abrir_site_chrome.bat` / `abrir_site_chrome.py` — Scripts de automação
- `LOG_OPERACIONAL_SITE.md` — Log detalhado de ações técnicas
- `LOG_SITE.md` — Log de entregas/releases do site
- `README.md` — Esta subdiretriz

## 🛡️ Padrão de Registro
- Sempre registrar: data, ação, responsável, motivo e resultado esperado.
- Exemplo de entrada no log:
  ```
  [04/07/2025] Implementação de script de automação para abrir o site no Chrome. Responsável: Copilot. Motivo: Facilitar validação local. Resultado: Script funcional e testado.
  ```

## 🔄 Atualização e Auditoria
- Auditorias periódicas devem ser registradas no `LOG_OPERACIONAL_SITE.md`.
- Mudanças de padrão ou diretriz devem ser refletidas neste README.

---

**Esta subdiretriz garante que o desenvolvimento do site seja transparente, rastreável e padronizado, alinhado com a governança do repositório principal.**
