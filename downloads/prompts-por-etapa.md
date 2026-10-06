# Prompts por etapa da revisão

Troque o que está entre colchetes. Os prompts não pedem que a IA cite estudos de memória: toda referência vem de uma base de busca ou de um documento que você tem em mãos.

## 1. Fechar a pergunta

```
Quero fazer uma revisão rápida de literatura sobre o tema abaixo. Antes de buscar qualquer estudo, me ajude a fechar a pergunta. Proponha:
- a pergunta principal, em uma frase;
- população, intervenção ou exposição, comparação e desfecho;
- se a pergunta é de efeito (pede estudos que comparam quem recebeu com quem não recebeu) ou de descrição (aceita surveys e estudos qualitativos);
- até três perguntas secundárias;
- os termos que podem ser lidos de mais de um jeito e precisam de definição.
Não cite estudos.
Tema: [descreva o tema e para que a revisão vai servir]
```

## 2. Definir critérios de inclusão

```
Com base na pergunta abaixo, proponha critérios de inclusão e de exclusão: tipo de estudo, população, intervenção, desfecho, período, idioma e tipo de publicação.
Para cada termo que possa ser lido de mais de um jeito, dê uma definição e um caso de fronteira, dizendo se ele entra ou não.
Não cite estudos.
Pergunta: [cole a pergunta fechada]
```

## 3. Montar a busca

```
Monte a estratégia de busca para a pergunta abaixo:
- uma string booleana em inglês e outra em português, com sinônimos;
- a adaptação para ERIC, Scopus e Google Acadêmico;
- repositórios de avaliação onde vale procurar.
Não liste estudos. Só a estratégia.
Pergunta: [cole a pergunta]
```

## 4. Triagem por título e resumo

```
Trabalhe apenas com os títulos e resumos abaixo.
Para cada um, aplique os critérios de inclusão e responda: entra, não entra ou dúvida. Justifique com o trecho do resumo.
Se um critério não puder ser avaliado pelo resumo, responda dúvida.
Não reinterprete os critérios. Se achar que algum está ambíguo, aponte a ambiguidade em vez de decidir.
Critérios: [cole os critérios]
Títulos e resumos: [cole a lista]
```

## 5. Leitura e extração (com os PDFs anexados)

```
Trabalhe apenas com os documentos anexados. Não use conhecimento externo e não cite estudos que não estejam anexados.
Para cada estudo, preencha uma tabela com as colunas: estudo, pergunta, desenho (mede efeito com comparação, revisão ou descritivo), amostra e contexto, desfecho e quando foi medido, efeito encontrado (houve efeito, não houve ou inconclusivo, com a magnitude), se o resultado é da média ou de um subgrupo, limitações declaradas pelos autores, exemplo prático e página de cada informação.
Se a informação não estiver no documento, escreva "não informado". Não arredonde nem converta números.
```

## 6. Síntese

```
Com base apenas na tabela de extração abaixo, escreva uma síntese de até uma página que responda à pergunta: [cole a pergunta].
Organize por dimensão. Em cada afirmação:
- termine com o estudo de origem entre parênteses;
- deixe claro se vem de estudo que mede efeito, de revisão ou de estudo descritivo;
- diga se o resultado é da média ou de um subgrupo, e se o desfecho é de curto prazo ou final.
Quando um achado depender de um único estudo, diga isso.
Marque como [inferência] tudo o que não estiver na tabela.
Tabela: [cole a tabela]
```

## 7. Verificação (num chat novo, com os PDFs anexados)

```
Abaixo está uma síntese, e os estudos em que ela se baseia estão anexados.
Confira a síntese frase por frase. Para cada frase, mostre o trecho literal do estudo que a sustenta e a página, e classifique: sustentada; parcialmente sustentada (diga o que falta); não sustentada; inferência não marcada.
Aponte também: números que não aparecem nos estudos; resultados de subgrupo apresentados como média; desfechos de curto prazo apresentados como resultado final; estudos descritivos usados como prova de efeito.
Não reescreva a síntese.
Síntese: [cole a síntese]
```

Rode a verificação num chat novo, sem o histórico da síntese. Quem confere não deve ter visto o trabalho sendo feito.
