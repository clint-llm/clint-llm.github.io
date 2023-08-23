# Clint LLM

Check out the [live project](https://clint-llm.github.io).

Clint is an open-sourced medical information lookup and reasoning tool.

Clint enables a user to have an interactive dialogue about medical conditions, symptoms, or simply to ask medical questions.
Clint helps connect regular health concerns with complex medical information. 
It does this by converting colloquial language into medical terms, 
gathering and understanding information from medical resources, 
and presenting this information back to the user in an easy-to-understand way.

One of the key features of Clint is that its processing is local. 
It's served using GitHub pages and utilizes the user's OpenAI API key to make requests to directly to GPT. 
All processing, except for that done by the LLM, happens in the user's browser.

**Clint, a proof-of-concept tool, is not always accurate or reliable, and should not replace medical professionals. 
Any information given by Clint should not be used for diagnosing or treating health issues. 
Don't ignore or delay professional medical advice due to Clint.**

## Development

See the associated repositories:

- <https://github.com/clint-llm/clint-ui>
- <https://github.com/clint-llm/clint-lib>
- <https://github.com/clint-llm/clint-cli>

## Example

The following example is taken from a sample US Medical Licensing Examination question.

Clint responding to a message about symptoms:

![symptoms](https://clint-llm.github.io/images/symptoms.png)

Clint asking follow-up questions:

![follow-up](https://clint-llm.github.io/images/followup.png)

Clint taking clinical notes:

![notes](https://clint-llm.github.io/images/notes.png)

Clint reasoning about possible diagnoses:

![reasoning](https://clint-llm.github.io/images/reasoning.png)

## Resources

Overview of helpful online resources for non-medical professionals to understand medicine.

### Databases

- <https://icd.who.int/browse11/>: International Classification of Diseases (10th edition is still prevalent)

### Encyclopedias

- <https://www.cdc.gov/health-topics.html#cdc-atozlist>: text about diseases, can contain epidemiology, references
- <https://www.ncbi.nlm.nih.gov/books/NBK430685/>: comprehensive, private publisher, text is CC
- <https://www.medicalhomeportal.org/diagnoses-and-conditions/diagnosis-prevalence-list>: pediatrics

### Articles

- <https://www.ncbi.nlm.nih.gov/>: medicine library
- <https://pubmed.ncbi.nlm.nih.gov/>: articles from various medical journals

### Clinical manuals, clinical resources, medical references

- <https://www.ncbi.nlm.nih.gov/books/NBK482263/>: free, creative commons
- <https://emedicine.medscape.com/>: free
- <https://www.merckmanuals.com/professional>: free
- <https://www.dynamed.com/>: non-free, comprehensive
- <https://www.uptodate.com>: non-free, comprehensive
- <https://www.orpha.net>: free academic resource for rare diseases

### References

- <https://en.wikipedia.org/wiki/Category:Anatomy>
- <https://en.wikipedia.org/wiki/Category:Embryology>
- <https://en.wikipedia.org/wiki/Category:Histology>
- <https://en.wikipedia.org/wiki/Category:Physiology>
- <https://en.wikipedia.org/wiki/Category:Pathology>
- <https://en.wikipedia.org/wiki/Category:Microbiology>
- <https://en.wikipedia.org/wiki/Category:Immunology>
- <https://en.wikipedia.org/wiki/Category:Biochemistry>
- <https://en.wikipedia.org/wiki/Category:Medical_terminology>

### Case studies

- <https://www.merckmanuals.com/en-ca/professional/pages-with-widgets/case-studies?mode=list>
- <https://path.upmc.edu/cases.html>

## Terminilogy

- Disease: abnormal systemic function or structure
- Disorder: abonormal function (borader than disease)
- Condition: diseases, lesions, and disorders
- Syndrome: a group of symptoms which typically co-occur
- Morbidity: suffering from a condition
- Epidemiology: study of distribution of diseases in populations
- Prevalence: number of individuals sudiffering a condition in a population
- Indicence: number of new cases of a condition in a population in a given time period
- Clinician: provide healthcare for patients, includees registered nurses
- Physician: diagnosis and non-surgical procedures and treatements. Includes family medicine, internal medicine, emergency medicine.
- Differential diagnosis (DDx): processing of listing conditions that match a patient's symptoms.
