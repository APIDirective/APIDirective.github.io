# Replication Package of learning based Extraction of First-Order Logic Representations of API Directives

## Empirical Study

- [1167 API sentences FOL](https://github.com/APIDirective/APIDirective.github.io/blob/master/empirical_research/empirical_research_FOL.xlsx). We sample 1167 candidate sentences from the reference documentation of JDK 1.81 that include one of the keywords or conform to one of the regular expressions based on two criteria: sample at least 200 sentences from each of the five types of text; sample at least 5 sentences for each keyword or regular expression. 

- Keywords for sampleing candidate sentence
> call*, invo*, before, after, between, once, prior, generic, must, mandat*, require*, shall, should, encourage*, recommend*, may, restrictions assum*, only, debug*, restrict*, never, condition*, strict*, necessar*, portab*, strong*, performance, performan*, efficien*, fast, quick, better, best, concurrency, concurren*, synchron*, lock*, thread*, simultaneous*, alternative, desir*, alternativ*, addition*, subclassing, extend*, overrid*, overload*, overwrit*, reimplement*, subclass*, super*, inherit*, warning, warn*, aware*, error*, note*, equal, equivalent, less, fewer, greater, larger, smaller, below, same, range, outside, negative, positive, nonnegative, nonpositive, null, nullable, non-null, <, >, >=, <=, =, !=, instance of, derived from, between, one of

## Fast-text Classifier 

## Entity Recognization

  ### Valid Annotation Data for Entity Recognization 
  - [valid annotation data](https://github.com/APIDirective/APIDirective.github.io/blob/master/entity_recognization/valid.json). The annotation data for entity recognization without negative data. 

  ### Entity Recognization Data By Auto Extension
  - [auto extension data](https://github.com/APIDirective/APIDirective.github.io/blob/master/entity_recognization/train_data.json). The training data for entity recognization extended automatically. 

## Entity Linking
- [sentence pattern](https://github.com/APIDirective/APIDirective.github.io/blob/master/entity_linking/sentence_pattern.xlsx). Sentence pattern. 
