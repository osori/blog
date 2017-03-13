---
layout: post
title: Korean Phonology Project
comments: true
published: true
---

&nbsp;&nbsp;These days I'm working on a project about Korean Phonology, specifically concerned with its phonetic transcriptions, such as IPA (International Phonetic Alphabet) transcription. To transcribe any text from a language, phonological processes should be simulated accordingly to correctly generate the actual phonetic realization of the text. 

&nbsp;&nbsp;To understand the difference between the original text, which linguists call the **underlying form** in the *phonemic* level, and the actual pronounciation, which is called the **surface form** in the *phonetic* level, let's look at the English flap rule. This rule states that the voicing contrast between /t/ (voiceless) and /d/ (voiced) is neutralized in the environment of V_V (between vowels). 'Writer' and 'Rider' are good examples of the words affected by the flap rule. See the chart below:

|                                            |&nbsp;&nbsp; writer |&nbsp;&nbsp;  rider |
|-------------------------------------------:|:------:|:------:|
| Phonemic Level (Underlying Representation) | &nbsp;&nbsp;raɪtər |&nbsp;&nbsp; raɪdər |
|                Some Phonological Processes | &nbsp;&nbsp;   ↓   | &nbsp;&nbsp;   ↓   |
|    Phonetic level (Surface Representation) | &nbsp;&nbsp; raɪɾər |&nbsp;&nbsp; raɪɾər |

&nbsp;&nbsp;As you can see from the chart, both words in the phonemic level are different because there is a contrast in voicing. However, after some phonological processes, such as the flap rule, change /t/ and /d/ to flap r(ɾ in IPA). Finally, both sound the same (raɪɾər) in their surface representations, that is, how we actually pronounce two words.

&nbsp;&nbsp;You now should be able to see that phonetic transcription is not just matching each letter of a word to its corresponding sound. Rather, the original text must go through every phonological processes applicable to be transcribed in the phonetic transcription. Same goes to all the languages in the world. 

&nbsp;&nbsp;Korean has its own writing system called Hangul and this system is pretty different from the system of most Indo-European languages. Hangul characters are not different from other writing systems in that it consists of just the consonants and vowels, no tone and long/short sounds. However, to form a syllable, you must follow its ordered structure of *choseong*, *jungseong*, and *jongseong*, *cho* meaning 'initial', *jung* 'medial', *jong* 'final', and *seong* meaning 'sound.' The best way to understand them would be thinking them as onset-nucleus-coda because they actually behave like them. 

&nbsp;&nbsp;For initial, only consonants can come (with some restrictions). For medial, you can have any vowels. For final, still only some consonants can be put (with some restrictions different from the initial one). Let me give you an example. The word 'Github' in Korean consists of six Hangul characters, '**ㄱ**g', '**l**i', '**ㅌ**t', '**ㅎ**h', '**ㅓ**eo', '**ㅂ**b'. You can't write six characters on the same line, like ㄱㅣㅌㅎㅓㅂ, but syllables must be formed to represent the orthographical form. In the first syllable, git, we see that it is in the order of CVC (Consonant-Vowel-Consonant) and this is a possible syllable structure in Korean (fyi the maximum syllable structure is CGVC). So we end up getting 깉 for git. The second syllable, hub, is also in the structure of CVC so we end up getting 헙 for heob. (Note that in Korean academia, the conventional way to transcribe the ʌ sound as in 'hub' is to write it as 'eo')  Can you see how the characters were used in forming the syllable?

-TODO: explain how each Korean syllable is represented in computers
-TODO: how to divide the characters from a syllable
-TODO: examples of korean phonological processes