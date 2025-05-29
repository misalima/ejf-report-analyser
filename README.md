# 📊 Análise de Relatórios de Notas - E. E. Prof. José Félix de Carvalho Alves

Aplicação web para coordenadores pedagógicos, desenvolvida para facilitar a análise de desempenho dos estudantes a partir de relatórios específicos desta escola, extraídos do seu sistema escolar.

## ✨ Funcionalidades

- **Upload de múltiplos relatórios** (.xls ou .xlsx) exportados do sistema da escola. No momento suporte apenas para um relatório específico ('Mapa Geral de Notas' do sistema '[Sigeduc](https://sageal.educacao.al.gov.br/sigeduc)')
- **Análise automática**:
  - Resumo por disciplina: quantidade de alunos com nota baixa e sem nota.
  - Resumo por aluno: disciplinas em que cada estudante ficou com nota baixa.
  - Disciplinas sem nota lançada.
  - Mais análises serão adicionadas futuramente.
- **Geração de relatório Excel** com múltiplas abas, uma para cada turma, já com colunas ajustadas e nome da turma em destaque.
- **Outros relatórios serão suportados futuramente.**
- **Interface simples e intuitiva** (Streamlit).

## 🚀 Como usar

### Rodando localmente

1. Instale o Python 3.8+.
2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```
3. Coloque a logo da escola (ex: `logo_escola.png`) na mesma pasta do `app.py`.
4. Execute:
    ```bash
    streamlit run app.py
    ```

## 📂 Estrutura dos arquivos

- `app.py` — Código principal do aplicativo.
- `requirements.txt` — Lista de dependências.

## 📝 Observações

- Os relatórios devem ser exportados do sistema escolar no formato `.xls` ou `.xlsx`.
- O código da turma é extraído automaticamente da célula A3 de cada relatório.
- O app é otimizado para uso em navegador, sem necessidade de instalação para o usuário final (quando hospedado).

## 🏫 Sobre

Desenvolvido por e para coordenadores pedagógicos, com foco em praticidade e automação das tarefas do dia a dia.

---

---

Sinta-se à vontade para contribuir, sugerir melhorias ou relatar problemas!