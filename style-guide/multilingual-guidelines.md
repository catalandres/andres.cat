# Multilingual Guidelines - andres.cat

## Language philosophy

### Central principle

Technical content should be available in all three languages (English, Spanish, Catalan) to serve different audiences with equivalent quality and depth.

### Strategic distribution

- **Technical posts**: Full translation/adaptation across all three languages
- **Quantum songbook**: Song translations in the most appropriate language for context and relevance

## Content creation strategy

### Technical content approach

**Primary language selection**: Choose the language most natural for initial creation, then adapt to others.

**Full translation approach**: Rather than language-specific content, create equivalent versions that maintain:

- Technical accuracy and depth
- Appropriate cultural context  
- Natural language flow
- Consistent voice and expertise

### Quantum songbook approach

**Translation focus**: Select songs that provide relevant insights or perspectives.

**Language selection**: Use the target language that best serves the song's meaning and cultural context.

**Quality standard**: Prioritize faithful translation that preserves meaning and relevance over literal accuracy.

## Multilingual content strategies

### Technical content translation

**Preferred approach**: Create comprehensive content in the most natural language, then carefully adapt to others.

**Process**:

1. Develop full content in primary language
2. Adapt (don't just translate) to other languages
3. Adjust cultural references and examples
4. Maintain technical accuracy and voice
5. Ensure natural flow in target language

### Cultural adaptation

**Technical examples**: Adapt to be relevant for each language community while maintaining technical accuracy.

**References**: Adjust cultural touchpoints to resonate with each audience without losing meaning.

**Voice consistency**: Maintain the same level of expertise and approachability across languages.

## Technical implementation in Ghost

### URL structure

```
andres.cat/post-title/           # English (default)
andres.cat/es/titulo-del-post/   # Spanish
andres.cat/ca/titol-del-post/    # Catalan
```

### Tag system

```
#lang-en    # English content
#lang-es    # Spanish content
#lang-ca    # Catalan content
#translation-of-[slug]  # To link translations
```

### Custom fields for translations

```
translation_es: "slug-in-spanish"
translation_ca: "slug-in-catalan"
canonical_lang: "en|es|ca"
translation_status: "available|planned|none"
```

### Language switcher widget

- Show only if translations available
- Clearly indicate current language
- Link to translated versions

## Multilingual creation workflow

### Step 1: Conceptualization

- In which language do you naturally "think" this content?
- Which audience would benefit most?
- Does the topic have specific cultural nuances?

### Step 2: Primary language

- Write in most natural language for topic
- Develop completely in that language
- Don't think about translations during creation

### Step 3: Evaluation for other languages

- Is there demonstrable audience in other languages?
- Does content add unique value in translation?
- What changes would be necessary for each language?

### Step 4: Adaptation (if applicable)

- Adapt examples and references
- Adjust register and tone
- Modify structure if necessary
- Maintain essence but optimize for target culture

## Multilingual SEO considerations

### Keywords

- Research language-specific terms
- Don't assume direct translations
- Consider culturally appropriate synonyms

### URLs and metadata

- Descriptive URLs in each language
- Adapted meta descriptions, not translated
- Alt texts in content language

### Cross-language linking

- Contextual links when valuable
- No automatic links just for translation
- Signal what each language version adds

## Multilingual red flags

### Avoid

- ❌ Automatic translations without review
- ❌ Syntactic calques between languages
- ❌ Unadapted cultural references
- ❌ Forcing content in languages where it doesn't add value
- ❌ Mixing languages without clear purpose (except Quantum Songbook)

### Good practice signals

- ✅ Each language version reads naturally in its language
- ✅ Cultural references appropriate for each audience
- ✅ Specific value in each language, not repetition
- ✅ Tone adjusted to cultural expectations
- ✅ Content leveraging specific strengths of each language
