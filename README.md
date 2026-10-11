# Voice Deception Research

Investigating whether acoustic features in English speech contain
predictive signals associated with truthful and deceptive statements.

## Research Question
Can audio-based models generalize to speakers unseen during training?

## Dataset
Real-Life Trial Deception Dataset.
Obtain data through an authorized access route. Raw recordings are
excluded from this repository.

## Roadmap
- [ ] Dataset inspection and validation
- [ ] Acoustic feature extraction: MFCC, pitch, energy, pauses
- [ ] Classical ML baselines
- [ ] Speaker-independent evaluation
- [ ] Pretrained speech representation experiments
- [ ] Cross-dataset generalization

## Structure
- `data/`: local datasets and processed features
- `notebooks/`: exploratory research
- `src/`: data, features, models, evaluation
- `experiments/`: experiment logs
- `reports/`: results and figures
- `tests/`: tests

## Disclaimer
Experimental research, not a validated lie detector. Predictions
must not be treated as proof that a person is lying.
