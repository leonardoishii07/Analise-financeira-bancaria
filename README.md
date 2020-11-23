# Análise financeira bancária

Inserir os dados na pasta ```dados```

```
dados
├──account.asc
├──district.asc
├──trans.asc
└──loan.asc
```

Instalar os requirements: 
```
pip install requirements.txt
```

É necessário ter o graphviz instalado

```
sudo apt-get install graphviz
```

A análise exploratória (```analise_exploratoria.ipynb```) foi feita para responder as peguntas no arquivo ```perguntas.docx```

A análise explicativa (```analise_explicativa-storytelling.ipynb```) é um resumo dos principais insigths e é o material completo da linha de raciocínio para a apresentação.

A ```Análise financeira bancária.pdf``` é a apresentação final.

Para executar os jupyter notebook's e gerar os HTML's:

```
jupyter nbconvert --execute --TemplateExporter.exclude_input=True --to html_toc analise_explicativa-storytelling.ipynb
```

e

```
jupyter nbconvert --execute --TemplateExporter.exclude_input=True --to html_toc analise_exploratoria.ipynb
```