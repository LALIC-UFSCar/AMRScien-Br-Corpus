# AMRScien-Br Corpus

This repository contains AMRScien-Br, a corpus of scientific news texts in Brazilian Portuguese annotated in Abstract Meaning Representation - AMR. The corpus is composed by two hundred sentences which come from the FAPESP corpus (Aziz and Specia, 2011), a Portuguese-English paralell corpus (pt-en) of scientific news texts belonging to the Brazilian magazine Pesquisa FAPESP Online (<https://revistapesquisa.fapesp.br>).

For more information about what is AMR and its specific notations, we indicate the AMR guidelines (<https://github.com/amrisi/amr-guidelines>).

This corpus is distributed under the [CC-BY-NC-SA](LICENSE.md) license.

## Corpus Notation

AMRScien-Br follow a standard notation to ease the reading of files. A corpus file contains multiple sentences, each with some metainformation, which starts with a hashtag followed by double colons (# ::) and a keyword (id, snt). Then, the AMR graph representation in the PENMAN notation is written. An example is shown below:

  <pre> 
  # ::id 16
  # ::snt Os otimistas entendem que a crise é passageira. 
  (u1 / entender-01
        :ARG0 (o0 / otimista)
        :ARG1 (t3 / passageiro
              :domain (c2 / crise))) </pre>
            
A blank line separates each sentence.

## Annotation Guidelines

For more details about the annotation guidelines, please see [here](guidelines.pdf).

