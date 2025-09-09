# Is Voynichese a Language? An Analysis of its Linguistic Properties

## Does Voynichese Act Like a Real Language?

To determine if the text in the Voynich manuscript is just gibberish or possesses the structure of a real language, we can analyze it using well-established linguistic laws and information theory principles.

### Zipf-Mandelbrot Law

The **Zipf-Mandelbrot Law** is a refined statistical formula, from Zipf's Law, that provides an accurate model for how word frequencies are distributed in natural languages. It is used because it provides a better fit for real-world text data than simpler rank-frequency models, especially for lower-ranked words.

The formula is: 
```
f(r) = C(r+ρ)^(-α)
```

Where:
- f(r) is the frequency of the word at rank r
- C is a constant related to the size of the text
- r is the rank of the word
- ρ and α are parameters that define the shape of the distribution curve

By analyzing the word frequencies in the Voynich manuscript and fitting them to this law, we can see that the text follows the same statistical pattern found in other known human languages, despite being more "curved" than other languages that I tested. A close fit to the Zipf-Mandelbrot curve is a strong indicator that the text is not random and possesses a language-like structure.

<img width="1490" height="1180" alt="Image" src="https://github.com/user-attachments/assets/b47fa360-2e37-49ad-8dd1-9f53d65e6004" />

### Shannon Entropy

**Entropy**, a concept from information theory, measures the amount of uncertainty or randomness in a system. In linguistics, it is used to quantify the average information content of a language.

The formula for Shannon Entropy (H) is:
```
H(X) = -∑ p(xi) log_b p(xi)
```

Where:
- X is a random variable with n possible outcomes
- p(xi) is the probability of the i-th outcome (e.g., a specific word or character appearing)
- b is the base of the logarithm, usually 2, to measure entropy in bits

While the final entropy value is useful, a deeper insight comes from analyzing the *rate at which entropy decreases* as we look at longer sequences of words. This reduction rate reveals fundamental differences in the underlying structure of the text.

<img width="398" height="543" alt="Image" src="https://github.com/user-attachments/assets/9b6c8e43-9b59-42e2-a618-778ded3de955" />

Natural languages like English and Latin exhibit a gradual and relatively stable reduction in entropy. Their reduction rate is small, typically between -0.017 and -0.026. This reflects a complex but flexible grammar where a preceding word influences the next one but does not rigidly determine it, leaving many possibilities open. 

The Voynich manuscript, however, behaves in a completely different manner. It shows an exceptionally steep drop in entropy when moving from single words to word pairs, with a massive reduction rate of -0.147. After this initial plummet, the rate stabilizes.

This starkly different pattern is very revealing. The enormous drop in entropy for word pairs means that the rules governing which "words" can follow each other in Voynichese are rigid. Knowing the first word severely restricts the choice for the second word to a very small set of options. Naturally evolved languages do not operate with such deterministic, low-level rules.

## Comparisons Between Voynichese and Other Languages

To put the analysis of Voynichese into context, it's essential to compare its statistical properties to those of both natural and constructed languages. The selection of comparison languages is crucial for a robust analysis.

The language selection strategy aimed for maximum linguistic diversity to test Voynichese against the full spectrum of human language variation:

- **Language families**: Germanic, Romance, Slavic, Finno-Ugric, Semitic, Celtic, Turkic, plus isolates (Basque) to cover major branches of European languages
- **Morphological types**: Analytic (English), synthetic (Latin), agglutinative (Finnish, Turkish), and fusional languages
- **Writing systems**: Latin, Arabic, Hebrew, Greek scripts to account for orthographic influences and for being liturgical languages
- **Geographic spread**: European, Middle Eastern, and diverse regional languages
- **Historical depth**: Both modern and classical languages
- **Constructed baselines**: Esperanto, Lingua Franca Nova, Simple English to distinguish natural from artificial patterns

The comparative analysis reveals intriguing patterns that complicate simple categorization of Voynichese. Each statistical test identifies different languages as "most similar" to the manuscript's text, but these supposedly similar languages share no linguistic relationships with each other. Albanian, Arabic, Lingua Franca Nova, Basque, Spanish and Maltese - the languages that appear most frequently as "matches" - belong to completely different language families and structural types. This inconsistency suggests that Voynichese doesn't closely match any specific known tested language pattern, rather than indicating genuine kinship with particular linguistic traditions.

<img width="574" height="519" alt="Image" src="https://github.com/user-attachments/assets/8565efdd-1a58-4cbb-b5a4-4eb5a4581d57" />

Particularly noteworthy is the behavior of constructed languages in our analysis. Esperanto, Lingua Franca Nova, and Simple English do not behave statistically differently from natural languages, nor do they show any special similarity to Voynichese. This finding doesn't contradict the hypothesis that Voynichese might be an artificial linguistic creation, because all those constructed languages are based on European languages.

From the lens of the Zipf-Mandelbrot Law, Voynichese exhibits clear statistical signatures of a real language. However, when comparing Voynichese with other languages, we can see that while its behavior is indeed similar to other languages, it shows a distinctive "flattening" in its frequency curve that other languages do not exhibit at all.

<img width="1589" height="1180" alt="Image" src="https://github.com/user-attachments/assets/7fc502c5-15f2-48e7-bc4a-de51433d9d56" />

The n-gram entropy progression analysis provides another compelling illustration of Voynichese's distinctive linguistic behavior. When examining how entropy increases from 1-gram to 4-gram sequences, Voynichese demonstrates significantly higher predictability than other languages once the initial n-gram is established. In natural languages, knowing one character or syllable provides limited information about what follows, but in Voynichese, the first n-gram appears to constrain subsequent possibilities much more dramatically than observed in any of our comparison languages.

<img width="1189" height="790" alt="Image" src="https://github.com/user-attachments/assets/625d30b7-6e86-4f7b-96d2-4fa34e274f5a" />

This enhanced predictability suggests either highly regular phonotactic constraints or systematic structural patterns that, while linguistically plausible, represent an extreme end of the natural language spectrum, although it can still be a language (a constructed one).

<img width="985" height="590" alt="Image" src="https://github.com/user-attachments/assets/dfbecbbe-32df-4494-a8d3-e61746330c67" />

Character transition entropy analysis reinforces this pattern of moderate but distinctive complexity. This metric measures how predictable the next character is given the current character in a writing system, examining both the diversity of characters and the complexity of their combinations. Voynichese demonstrates moderate transition complexity with 24 unique characters and a transition entropy of 2.02, placing it in the middle range of comparison languages - more complex than languages like Spanish or Turkish (which show simpler, more regular character transitions), but less complex than languages like Hebrew or Bulgarian (which exhibit higher transition entropy due to more varied character combination patterns).

This positioning suggests a writing system of intermediate sophistication, neither overly simple nor excessively complex, which aligns with expectations for a language with a high amount of phonotactic constraints. However, like the n-gram analysis, it maintains the pattern of being linguistically plausible while occupying a unique statistical position that doesn't closely match any known language family.

## What Can We Know About Voynichese?

Having established that Voynichese exhibits statistical properties consistent with languages, probably constructed, we can now examine its internal structure to identify linguistic patterns. This analysis shifts from asking whether Voynichese behaves like a language to investigating how its linguistic system is organized.

### Functional Word Analysis

Functional words - articles, prepositions, conjunctions, and pronouns - constitute the grammatical skeleton of any language. Unlike content words, which vary by topic and context, functional words appear with consistent frequency and in predictable syntactic positions across all texts in a language. They are typically short, very frequent, and have little semantic meaning on their own. In English, words like "the," "a," "of," and "in" are functional words.

To identify functional words in Voynichese, conditional entropy analysis was applied to the top 50 most frequent words of Voynich, English, Arabic, German, Hungarian, Finnish, Romanian and Russian. The results were compared against established stopword lists. The method successfully distinguishes word classes in all comparison languages.

This method calculates how predictable the next word is given the current word - functional words show low conditional entropy because they appear in fixed grammatical contexts, while content words show higher entropy due to semantic variability. Words falling below the language's average conditional entropy are classified as structural, while those above are classified as content words.

<img width="965" height="703" alt="Image" src="https://github.com/user-attachments/assets/49e13bf2-65eb-45c1-94fe-343d653e1cac" />
<img width="962" height="642" alt="Image" src="https://github.com/user-attachments/assets/7e712628-0632-4352-bb9e-b970896ceaba" />

In Voynichese, from the 20 most common words, only 4 of them have low entropy, being "or", "s", "qokain", "qokedy". In other languages we have a totally different scenario - almost all of them have more than 15 confirmed functional words in the top 20. At the same time, Voynich shows an unusual pattern where most words ranked 30-50 exhibit low entropy values, a distribution not observed in any comparison language.

### Stolfi's Grammar Validation

To further investigate the structural organization of Voynichese, we can apply Jorge Stolfi's systematic grammar rules, which propose that Voynich words follow specific density-based patterns. This framework provides testable structural constraints that can be algorithmically validated across the entire manuscript.

**Character Classification System**: Stolfi's grammar organizes Voynichese characters into hierarchical categories based on visual complexity and structural importance:

- **Gallows (Core level, density 3)**: k, t, p, f - the most structurally important characters
- **Benches (Mantle level, density 2)**: ch, sh, ee, eee, eeee - multi-character sequences with moderate importance
- **Staves, Loops, Legs, Jibs (Crust level, density 1)**: i, l, r, s (staves); a, o, y (loops); d (legs); q (jibs)
- **Others (Crust level, density 1)**: m, g, n, x - remaining characters

**Core Grammar Rules and Phonotactic Constraints**: The validation system implements three fundamental structural rules that reveal the rigid phonotactic constraints governing Voynichese:

- **Unimodal Density Rule**: Each word must have a single density peak, with character density increasing toward the core then decreasing toward word boundaries. This rule effectively constrains which character sequences are permissible, explaining the high predictability observed in our n-gram entropy analysis.
- **Gallows Constraint**: Generally only one gallows character is permitted per word, severely limiting character combination possibilities and contributing to the systematic phonotactic restrictions.
- **Q Placement Rule**: The character 'q' may only appear at the beginning of words, representing absolute positional constraints that further restrict possible character sequences.

Our testing of these grammatical rules on the Voynich manuscript reveals they function as strict phonotactic constraints that govern character combinations and sequences. The empirical analysis shows a compliance rate of 56.9% of the unique words tested, demonstrating that Voynichese operates under systematic restrictions that limit which character sequences are linguistically valid, pointing to a non-natural language scope. This testing result explains the enhanced predictability patterns observed in our character transition entropy analysis, where knowing one character provides unusually strong constraints on what characters can follow.

<img width="531" height="157" alt="Image" src="https://github.com/user-attachments/assets/6b57299b-fdba-44d3-8c7b-eb61c12f1206" />

### Word Embeddings Application

Word embeddings represent words as dense vectors in a continuous vector space, capturing semantic and syntactic relationships based on contextual usage patterns. This computational technique allows us to analyze how words co-occur and relate to each other within the text, providing insights into the underlying linguistic organization.

Word2Vec embeddings were trained using a sliding context window approach (window size=5, vector dimensions=100). The model learns vector representations where contextually similar words cluster closer together in the vector space, measured by cosine similarity.

**Functional Words**: The functional score represents a composite metric designed to quantify the likelihood that a word serves a grammatical rather than semantic role within the text. This score combines three normalized linguistic indicators: frequency percentile, entropy, and inverted similarity variance. By averaging these three components, the functional score produces values between 0 and 1, where higher scores indicate words that behave like grammatical function words.

<img width="408" height="286" alt="Image" src="https://github.com/user-attachments/assets/cbb3f302-68bf-4d85-9076-48e58fd75485" />

As we see, we do have a high amount of words that act like highly functional words (some sections have almost 260), although they are not even on the most used words, as expected. Those words are used in different contexts leading to a low entropy and a low similarity variance.

**Vocabulary Consistency**: This table shows vocabulary consistency analysis across different sections of the Voynich manuscript, measuring how much word overlap exists within each thematic section using Jaccard similarity.

<img width="800" height="175" alt="Image" src="https://github.com/user-attachments/assets/d03e36d1-924e-487a-8475-caea5ac6ccd5" />

The key findings indicate remarkably low vocabulary consistency across all sections. Even within supposedly thematic sections like "Herbal_A" (which has 117 internal transitions between text segments), the average Jaccard similarity is only 0.0788, meaning less than 8% vocabulary overlap between different parts of the same section - at the same time that the vocabulary overlap is more than 30% in each folio. The "Astronomical" section shows even lower consistency with only 5 internal transitions and 0.0763 average similarity.

This pattern suggests that the Voynich manuscript doesn't maintain consistent vocabulary even within its apparent thematic divisions. For a text dealing with herbal or astronomical topics, you would typically expect significant vocabulary reuse - specialized terms for plants, celestial objects, or procedural language should appear repeatedly throughout relevant sections.

<img width="1188" height="590" alt="Image" src="https://github.com/user-attachments/assets/f976682f-213f-4dfc-9e39-5a226a53a7f6" />

Despite the vocabulary discontinuity, the cosine similarity (green line) shows much higher values and dramatic variability (0.1-0.8), suggesting that while exact words change, the underlying contextual patterns and usage styles remain more consistent. This is maybe related to Jaccard similarity being less than 8% in the entire section but higher than 30% in the same folio.

**Uniqueness Score**: The uniqueness score measures how much of each folio's vocabulary consists of words that don't appear in its surrounding folios, calculated using a sliding window approach. Specifically, it represents the ratio of unique words (found only in the target folio) to the total vocabulary size within the comparison window.

<img width="1188" height="590" alt="Image" src="https://github.com/user-attachments/assets/89153746-48b8-4dd0-8baa-3031f68dacf0" />

The vocabulary uniqueness patterns across Voynich folios reveal systematic linguistic organization that further supports the constructed language hypothesis. The consistently elevated uniqueness scores (0.22-0.52) indicate that each folio introduces substantial vocabulary distinct from surrounding pages, a pattern rarely observed in natural texts where topic continuity and linguistic repetition typically create more gradual vocabulary transitions. The dramatic peak around folio 70, reaching approximately 0.52 uniqueness, suggests highly specialized vocabulary that operates independently from adjacent content, yet this peak doesn't correspond to apparent visual section boundaries, indicating that vocabulary management follows internal systematic principles rather than thematic divisions.

This pattern of high vocabulary uniqueness, combined with the low Jaccard similarity observed in previous analyses, demonstrates deliberate vocabulary control characteristic of constructed systems. Natural languages typically exhibit more repetitive vocabulary patterns due to functional requirements and cognitive processing constraints, while the Voynich manuscript appears designed to minimize lexical redundancy while maintaining structural consistency


## What We Know So Far

This analysis applied multiple linguistic and statistical methods to examine the structural properties of the Voynich manuscript's text. The results provide quantitative evidence about Voynichese's organizational patterns and how they compare to documented languages.

**Observed Statistical Properties**: Voynichese demonstrates several measurable language-like characteristics. Word frequency distributions follow the Zipf-Mandelbrot Law with parameters similar to natural languages, though exhibiting a distinctive "flattening" in the frequency curve. The text contains approximately 24 unique characters with moderate transition entropy (2.02), positioning it within the range observed across comparison languages. The manuscript shows consistent structural patterns across its 240 folios. Stolfi's proposed phonotactic rules show 56.9% compliance rates across unique words tested.

**Distinctive Patterns Identified**: Several patterns distinguish Voynichese from the comparison language set. Shannon entropy analysis reveals an initial steep reduction (-0.147) from single words to word pairs, contrasting with the gradual reductions (-0.017 to -0.026) observed in natural languages. This pattern indicates high sequential predictability once initial elements are established. Vocabulary analysis shows low consistency across manuscript sections (Jaccard similarity ~0.078) while maintaining higher similarity within individual folios (>30%). Uniqueness scores range from 0.22-0.52 across folios, with notable peaks around folio 70. Only 4 of the 20 most frequent words demonstrate low entropy characteristics typical of natural language function words.

**Comparative Analysis Results**: Statistical comparisons across 18 languages from diverse families yielded inconsistent similarity matches. Different analytical methods identified various languages as "most similar" to Voynichese (Albanian, Arabic, Spanish, Maltese), but these languages share no linguistic relationships, suggesting Voynichese does not closely align with any tested natural language pattern. Constructed languages in the comparison set (Esperanto, Lingua Franca Nova) showed no special similarity to Voynichese and behaved statistically similar to their natural language bases.

## License

MIT License
