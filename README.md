# Brazil Forest Fires
## Dataset
The dataset comes from the Portal Brasileiro de Dados Abertos in the section
[Sistema Nacional de Informacões Florestais / National System of Forest Information](https://dados.gov.br/dataset/sistema-nacional-de-informacoes-florestais-snif)
the dataset is:
[Incêndios Florestais / Forest Fires](https://dados.gov.br/dataset/sistema-nacional-de-informacoes-florestais-snif/resource/39308794-da81-4cab-89e7-1691c2f3893b)

## Preparing the dataset
Before opening the data with Pandas I realized that each line was inside quotes. Therefore, I removed the quotes by opening the csv file in vim editor with the commands:
```sh
0,$ s/^"//
```
and
```sh
0,$ s/"$//
```

