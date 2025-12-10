# contraction-genre-english
# Variation in English Contractions Across Genres

## General information

This project investigates how often contractions (e.g. "don't", "I'm") occur in different English genres, comparing informal and formal contexts. The aim is to test whether informal genres such as Spoken, TV/Movies, and Fiction show higher contraction rates than formal genres such as Academic writing and Newspapers. By quantifying contraction frequency per genre, the project examines how situational context and communicative setting shape written and spoken style.

## Background information

Olohan, M. (2004). How frequent are the contractions? A study of contracted forms in the Translational English Corpus. Target, 15(1), 59–89. https://doi.org/10.1075/target.15.1.04olo
- Focuses directly on the frequency of English contractions in a large corpus and shows that contractions are strongly associated with less formal registers.
- Use this to justify that contractions are good markers of (in)formality and that you expect more contractions in informal genres.

Biber, D. (2012). Register as a predictor of linguistic variation. Corpus Linguistics and Linguistic Theory, 8(1), 9–37. https://doi.org/10.1515/cllt-2012-0002
- Argues that register/genre systematically predicts how often particular linguistic features occur across texts.
- Use this to support treating genre (spoken, TV/movies, fiction, academic, newspapers) as your independent variable and expecting systematic differences in contraction frequency.

## Research question and hypotheses

**Research question**  
Are contractions more frequent in informal genres (Spoken, TV/Movies, Fiction) than in formal genres (Academic, Newspapers)?

**Variables**

- Independent variable: Genre  
  - Informal: Spoken, TV/Movies, Fiction  
  - Formal: Academic, Newspapers  

- Dependent variable: Contraction frequency category  
  - High contraction rate  
  - Low contraction rate  

**Hypothesis**  
Contractions occur more often in informal genres than in formal genres.

## Method

### Dataset and sampling

- The project uses an English corpus (to be specified, e.g. a publicly available corpus interface or downloadable dataset) that contains the genres Spoken, TV/Movies, Fiction, Academic, and Newspapers.  
- For each genre, a balanced subset of texts will be sampled so that the total word count per genre is comparable (e.g. similar number of words in each genre).  
- Sampling decisions will be documented, including:
  - The exact corpus name and source (with link).  
  - The time period covered by the texts.  
  - Any filters used (e.g. English only, specific region, minimum text length).  

### Operationalisation of variables

- **Genre (independent variable)**: Each text is assigned a genre label according to the corpus classification (Spoken, TV/Movies, Fiction, Academic, Newspapers).  
- **Contraction frequency (dependent variable)**:
  - Contractions are counted per text and normalised as number of contractions per 1,000 words.  
  - A list or pattern of contractions (e.g. “don’t”, “can’t”, “I’m”, “we’ve”, “she’s”, “they’re”, “won’t”, “wouldn’t”, “it’s” when used as a contraction) will be defined and implemented in code.  
  - Based on the normalised rates, texts or genres can be described as having relatively high or low contraction rates for analysis and visualisation.

### Analysis and statistical tests

- For each text, a contraction frequency (per 1,000 words) is calculated.  
- For each genre, the mean and distribution of contraction frequency are computed across texts.  
- Informal genres (Spoken, TV/Movies, Fiction) are compared to formal genres (Academic, Newspapers) using appropriate statistical tests (for example, a t‑test or non‑parametric equivalent, or a comparison across all genres using ANOVA if assumptions are met).  
- Visualisations (e.g. boxplots or bar charts) will be used to show differences in contraction frequency between genres.

The final report (PDF) and all scripts necessary to reproduce the results will be added to this repository before submission, in line with the course guidelines.
