> [!IMPORTANT]
> **Repositório Central da Disciplina (DSW):**  
> Todas as atividades desta matéria foram reunidas, padronizadas e documentadas no repositório oficial:  
> 🔗 [**kellyson71/Desenvolvimento-de-Sistemas-Web**](https://github.com/kellyson71/Desenvolvimento-de-Sistemas-Web)  
> *(Acesse o link acima para visualizar o índice completo de atividades do curso de ATV-001 a ATV-007)*

---

# Atividade Templates e Views (Estúdio Fluxo)

**Disciplina:** Desenvolvimento de Sistemas Web (DSW)  
**Professor:** Irlan Arley Targino Moreira  
**Aluno:** Kellyson Medeiros  

Projeto Django demonstrando o uso de renderização de templates HTML com o Django Template Engine (DTE), herança de templates (`base.html`), inclusão de arquivos estáticos (`{% static %}`) e sistema de rotas nomeadas (`{% url %}`).

## Funcionalidades
- Separação entre template base (`templates/base.html`) e páginas filhas (`index.html`, `portfolio.html`).
- Estilização completa através de folhas de estilo em `static/css/`.
- Testes automatizados de carregamento de páginas e status code HTTP (`tests.py`).

## Como Executar
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 manage.py runserver
```
Acesse `http://127.0.0.1:8000/` no navegador.
