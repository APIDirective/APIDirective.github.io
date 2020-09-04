# Replication Package of Learning Based Extraction Of First-Order Logic Representations of API Directives

## Empirical Study

- Keywords for sampleing candidate sentence
> call*, invo*, before, after, between, once, prior, generic, must, mandat*, require*, shall, should, encourage*, recommend*, may, restrictions assum*, only, debug*, restrict*, never, condition*, strict*, necessar*, portab*, strong*, performance, performan*, efficien*, fast, quick, better, best, concurrency, concurren*, synchron*, lock*, thread*, simultaneous*, alternative, desir*, alternativ*, addition*, subclassing, extend*, overrid*, overload*, overwrit*, reimplement*, subclass*, super*, inherit*, warning, warn*, aware*, error*, note*, equal, equivalent, less, fewer, greater, larger, smaller, below, same, range, outside, negative, positive, nonnegative, nonpositive, null, nullable, non-null, <, >, >=, <=, =, !=, instance of, derived from, between, one of

- [1167 Candidate Sentence](https://github.com/APIDirective/APIDirective.github.io/blob/master/empirical_research/empirical_research_FOL.xlsx). We sample 1167 candidate sentences from the reference documentation of JDK 1.81 that include one of the keywords or conform to one of the regular expressions based on two criteria: sample at least 200 sentences from each of the five types of text; sample at least 5 sentences for each keyword or regular expression. 

- [directive sentences annotation for candidate sentences](https://github.com/APIDirective/APIDirective.github.io/blob/master/empirical_research/empirical_research_FOL.xlsx). We sample 1167 candidate sentences from the reference documentation of JDK 1.81 that include one of the keywords or conform to one of the regular expressions based on two criteria: sample at least 200 sentences from each of the five types of text; sample at least 5 sentences for each keyword or regular expression. 

- [729 directive sentences with identified FOL fomulas](https://github.com/APIDirective/APIDirective.github.io/blob/master/empirical_research/empirical_research_FOL.xlsx). We sample 1167 candidate sentences from the reference documentation of JDK 1.81 that include one of the keywords or conform to one of the regular expressions based on two criteria: sample at least 200 sentences from each of the five types of text; sample at least 5 sentences for each keyword or regular expression. 

## Directive Sentence Classifier

## Atomic Formula Extraction

### manually annotated data for training BERT-BiLSTM-CRF model
- [valid annotation data](https://github.com/APIDirective/APIDirective.github.io/blob/master/entity_recognization/valid.json). The annotation data for entity recognization without negative data. 

### Automatically generated annotated data for training BERT-BiLSTM-CRF model
- [auto extension data](https://github.com/APIDirective/APIDirective.github.io/blob/master/entity_recognization/train_data.json). The training data for entity recognization extended automatically. 

## Logical Relation Recognition
- [51 linguistic patterns for conditional Structure Parsing](https://github.com/APIDirective/APIDirective.github.io/blob/master/entity_linking/sentence_pattern.xlsx). Sentence pattern. 

## Argument Parsing
- [manually annotate 246 API related arguments for training SVM model](https://github.com/APIDirective/APIDirective.github.io/blob/master/entity_linking/sentence_pattern.xlsx). Sentence pattern. 
