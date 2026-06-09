# Misogynistic Hate Speech in Mexican Politics Dataset

## Overview

This dataset was created for research on the automatic detection of misogynistic hate speech in Mexican Politics using Natural Language Processing (NLP) techniques.

The corpus consists of textual instances collected from online platforms and manually annotated according to the criteria established in the research project.

## Dataset Structure

The dataset is provided in CSV format and contains the following columns:

| Column | Description |
|---------|-------------|
| **texto/text** | The content of the post, comment, or message. |
| **etiqueta/label** | Binary classification of the text (`1 = Misogynistic`, `0 = Non-misogynistic`). |
| **tipo/type** | Category or subtype of misogynistic content. (neutral no misogino, explicito, benevolente) this classification is used if needed multiclass problems based on indicators of hatespeech for women in politics, updates will be uploaded expanding the database|
| **origen/source** | Origin of the text (Texts obtained from platforms or synthetic texts created using RAG architecture). |

## Example

| text | label | type | source |
|------|---------|---------|----------|
| "¡ Sopas ! Por andar de metiche y de H0CIC0NA atacando a Argentina. ¿Que creen? Claudia Sheinbaum ahora está en manos de Javier Milei. Lean un extracto de la columna de Salvador García Soto. "Dice la sabiduría popular que el que a hierro mata a hierro muere" | 1 | explicito | real |
|Rocío Nahle, no se desgaste buscando atención como mujer, que se enfoque en el trabajo real. ¡A las mujeres nos corresponde ser cuidadosas y humildes!| 1 | benevolente | sintetico |
| @USER ENTREGUE A LOS NARCOPOLÍTICOS | 0 | neutral o no misogino | real |


## File Format

- **Format:** CSV
- **Encoding:** UTF-8
- **Delimiter:** Comma (,)

## Intended Use

This dataset is intended for academic and research purposes, including:

- Hate speech detection
- Misogyny classification
- Political discourse analysis
- Natural Language Processing (NLP)
- Machine Learning and Deep Learning applications

## Citation

If you use this dataset in your research, please cite:

**Monserrat Sánchez Juárez, Daniel Sánchez Ruiz, and Eric Ramos Aguilar.**

*"Analysis and Classification of Misogynistic Hate Speech in Politics Using Natural Language Processing."*

## License

This dataset is released for academic and research purposes only.
