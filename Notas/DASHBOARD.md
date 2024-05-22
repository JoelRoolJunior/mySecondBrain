---
cssclasses:
  - dashboard
  - dashboard-ReadLineLength
banner: "[[banner_mesa_de_trabalho.jpg]]"
---
# Ciência da Computação
- tópico 1
	- subtópico
- topico 2
	- subtópico
# Vault Info
- 🗄️ Recent file updates `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
- 🔖 Tagged: favorite `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(4).file.link)`
- 〽️ Stats
    - File Count: `$=dv.pages().length`
    - Personal recipes: `$=dv.pages('"Family/Recipes"').length`
