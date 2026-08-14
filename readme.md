# 🎓 Ausência da Representatividade Feminina na Docência no IFRN

[![Django Version](https://img.shields.io/badge/Django-6.1-0C4B33?style=for-the-badge&logo=django)](https://www.djangoproject.com/)
[![Python Version](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python)](https://www.python.org/)
[![Bootstrap Version](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap)](https://getbootstrap.com/)

Plataforma web desenvolvida como **Trabalho de Conclusão de Curso (TCC)** focada na coleta, análise visual e apresentação de indicadores sobre a distribuição por gênero no corpo docente do **Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte (IFRN)**.

---

## 📌 Sobre o Projeto

O estudo busca discutir a equidade de gênero no ambiente acadêmico do IFRN, analisando historicamente e estatisticamente a ocupação das vagas de docência, com especial atenção à sub-representação feminina em áreas **STEM** (*Science, Technology, Engineering, and Mathematics*).

### 🎯 Objetivos
* **Mapeamento Estatístico:** Mapear o percentual de professoras nos diversos *campi* do IFRN.
* **Análise por Área:** Identificar a disparidade de gênero nas áreas de Exatas e Tecnológicas em comparação às Humanas e Linguagens.
* **Sensibilização:** Prover um espaço informativo e acadêmico para divulgação de dados e entrevistas.

---

## 🛠️ Tecnologias Utilizadas

* **Back-end:** Python 3.12, Django 6.1
* **Front-end:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5
* **Iconografia e Fontes:** FontAwesome 6, Google Fonts (Inter)
* **Banco de Dados:** SQLite (Desenvolvimento) / PostgreSQL (Produção)

---

## 📂 Estrutura do Projeto

```text
AusênciaDaRepresentatividadeFemininaNaDocência_IFRN/
├── core/                         # Aplicação principal
│   ├── static/core/css/          # Estilos CSS específicos/customizados
│   ├── templates/core/           # Templates HTML da app core (ex: home.html)
│   ├── views.py                  # Lógica das rotas da aplicação
│   └── urls.py                   # Mapeamento de rotas do app
├── Mulheres/                     # Configuração global da aplicação Django
│   ├── settings.py               # Configurações do projeto
│   └── urls.py                   # URLs globais do projeto
├── templates/                    # Templates globais e compartilhados
│   └── fragments/                # Componentes globais (ex: base.html, navbar, footer)
├── manage.py                     # Script de gerenciamento do Django
├── requirements.txt              # Dependências do projeto
└── README.md                     # Documentação do repositório