# VSCodium Python Setup

![VSCodium Python](/screenshots/example_1.png)

Configuração minimalista e produtiva do **VSCodium** focada em desenvolvimento **Python**, com layout limpo, formatação automática e extensões essenciais para produtividade.

## ✨ Objetivos
- Ambiente limpo e sem distrações
- Padronização de código Python (PEP 8)
- Salvamento automático e formatação ao salvar
- Experiência fluida com Jupyter Notebooks
- Visual agradável e funcional

---

## 🧩 Extensões Utilizadas

- Python (Microsoft)
- Jupyter (Microsoft)
- autopep8
- isort
- Error Lens
- Material Icon Theme
- MS Dev Theme (Cobalt)

A lista completa está em:
```text
extensions/extensions.txt
```

## ⚙️ Configurações

![VSCodium Python](/screenshots/example_2.png)

As configurações personalizadas do editor estão em:

```text
settings/settings.json
```

Principais destaques:

- Indentação padrão de 4 espaços (Python)
- Formatação automática ao salvar
- Limite visual de 120 caracteres
- Layout minimalista (sem minimap, status bar, activity bar)
- Fonte: JetBrains Mono Nerd Font
- Tema: Cobalt

## 🚀 Como usar em uma nova máquina

- Instale o VSCodium
- Instale as extensões listadas em `extensions/extensions.txt`
- Copie o conteúdo de `settings/settings.json` para:
```text
~/.config/VSCodium/User/settings.json(Linux)
```
- Reinicie o editor

## 🐍 Público-alvo

- Desenvolvedores Python
- Estudantes de Engenharia de Software / Data Science
- Quem busca foco, produtividade e código limpo

## 📄 Licença

Uso livre para fins pessoais e educacionais.
