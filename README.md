# Análise financeira bancária

## Materiais finais

localizados na pasta ```artefatos```

```
Análise financeira bancária.pdf

analise_explicativa-storytelling.html

analise_exploratoria.html
```


A análise exploratória (```analise_exploratoria.ipynb```) foi feita para responder as peguntas no arquivo ```perguntas.docx```

A análise explicativa (```analise_explicativa-storytelling.ipynb```) é um resumo dos principais insigths e é o material completo da linha de raciocínio para a apresentação.

A ```Análise financeira bancária.pdf``` é a apresentação final.

## Execução dos códigos

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

Para executar os jupyter notebook's e gerar os HTML's:

```
upyter nbconvert --execute --TemplateExporter.exclude_input=True --to html_toc analise_explicativa-storytelling.ipynb --output artefatos/analise_explicativa-storytelling.html
```

e

```
jupyter nbconvert --execute --TemplateExporter.exclude_input=True --to html_toc analise_exploratoria.ipynb --output artefatos/analise_exploratoria.html
```