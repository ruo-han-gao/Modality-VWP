# L2 early- and late-stage prediction: The effect of proficiency

Project for lab rotation Linguistics at RPTU

Recent research suggests that prediction in both native and non-native (L2) speakers occurs in two stages: an automatic early-stage and a cognitively demanding late-stage. In L2 speakers, delayed prediction was only found at the more costly late-stage, but if this delay is driven by proficiency remains unclear. 

## The present study:
This study compares the timing of early-stage and late-stage predictions between low-proficiency and high-proficiency English L2 speakers using the Visual World Paradigm, and found that high-proficiency speakers showed higher accuracy in offline comprehension tasks, but this advantage does not extend to the speed of online semantic prediction, even in the more cognitively demanding late stage.

## Experimental procedures:
A total of 54 L2 English speakers listened to predictable sentences (e.g., The singer plays the guitar) and unpredictable sentences (e.g., The cousin forgets the guitar) while viewing four images (target: guitar; distractors: microphone (agent-related), cards (verb-related), strawberry (distractor)). Their task was to select the image that best matched the sentence which was used as a measure of offline accuracy. Divergence point analysis (DPA) was employed to assess early-stage (agent-related fixation) and late-stage (suppression of agent-related distractor) predictions, and LexTALE was administered to test language proficiency.

## Analyses

- Offline comprehension accuracy: generalized linear mixed-effects model
  - Fixed effects: predictability, proficiency
  - Random intercepts: participant, item
- Online eye movements - divergence point analyses (DPA)

### DPA: 
- Compare fixations between two images using t-tests at each time window.
- Find the first run of 10 consecutive significant windows (20 ms each) as the divergence point.
- Perform bootstrapping (2,000 iterations) for reliability and stability.


