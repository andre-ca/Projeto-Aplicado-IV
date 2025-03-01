# Projeto-Aplicado-IV

{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Análise de Séries Temporais da Poluição Atmosférica no Estado de São Paulo\n",
    "\n",
    "## Introdução\n",
    "A poluição atmosférica é um dos principais desafios ambientais enfrentados por grandes centros urbanos ao redor do mundo. Esse fenômeno é causado pela emissão de poluentes oriundos de atividades industriais, transporte, queimadas e processos naturais, podendo resultar em sérios impactos na saúde humana e no meio ambiente.\n",
    "No Brasil, e especificamente no estado de São Paulo, a qualidade do ar é uma preocupação constante devido à alta concentração populacional, à frota veicular extensa e às atividades industriais que contribuem significativamente para a liberação de substâncias nocivas na atmosfera.\n",
    "A análise de séries temporais se apresenta como uma ferramenta essencial para compreender o comportamento dos poluentes atmosféricos ao longo do tempo e identificar padrões que possam auxiliar na formulação de políticas públicas voltadas para a melhoria da qualidade do ar."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Descrição da Base de Dados\n",
    "Os dados analisados compreendem medições de poluentes atmosféricos entre 2015 e 2021, totalizando mais de 10 milhões de registros coletados em 87 estações de medição espalhadas pelo estado de São Paulo.\n",
    "### Estrutura do Dataset:\n",
    "- **ID**: identificação única de cada registro;\n",
    "- **Data**: data da medição;\n",
    "- **Hora**: horário da medição;\n",
    "- **Estação**: local da medição;\n",
    "- **Código**: código associado à estação;\n",
    "- **Poluente**: tipo de poluente medido;\n",
    "- **Valor**: concentração do poluente;\n",
    "- **Unidade**: unidade de medida;\n",
    "- **Tipo**: forma da medição (manual ou automática)."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Importação de Bibliotecas e Carregamento dos Dados"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "import pandas as pd\n",
    "import matplotlib.pyplot as plt\n",
    "import seaborn as sns\n",
    "\n",
    "# Carregar dataset\n",
    "# df = pd.read_csv('caminho/do/dataset.csv')\n",
    "\n",
    "# Exibir as primeiras linhas do dataset\n",
    "# df.head()"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Análise Exploratória"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Visualização de distribuições\n",
    "# sns.histplot(df['Valor'], bins=50, kde=True)\n",
    "# plt.show()"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8"
  }
 }
}
