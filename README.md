# 🏛️ Minerva - Italian Cuisine Portfolio

Este repositório contém o código-fonte e a versão estática do website do restaurante **Minerva**. O projeto foi desenvolvido em WordPress e exportado para uma estrutura estática de alta performance.

🌐 **Site ao Vivo:** [https://minerva.velrid.com/](https://minerva.velrid.com/)  


## Estrutura do Repositório

O projeto utiliza uma estratégia de branches para separar o desenvolvimento da produção:

* **`main`**: Contém o código-fonte do tema WordPress (`astra-child`), configurações e backups do banco de dados (`.sql`).
* **`gh-pages`**: Contém os ficheiros estáticos (HTML/CSS/JS) otimizados para hospedagem direta no GitHub Pages.

## Tecnologias Utilizadas

* **CMS:** WordPress
* **Tema Base:** Astra
* **Design/Personalização:** Astra Child Theme & Microthemer
* **Conversão Estática:** Simply Static
* **Hospedagem:** GitHub Pages

## Como Replicar este Projeto

1.  **Código:** Os ficheiros do tema estão na pasta `wp-content/themes`.
2.  **Conteúdo:** O backup das tabelas do banco de dados está disponível no ficheiro `.sql` na raiz da branch `main`.
3.  **Deploy:** A versão estática é gerada via plugin e enviada para a branch `gh-pages`.

---
Desenvolvido por **Jey Godoy** - [godoyjey](https://github.com/godoyjey).
