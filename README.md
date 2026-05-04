# Ojiggi

Ojiggi is a custom LLM prompt/assistant with the persona of a Japanese language teacher specialized in sentence explanation. In mid-to-advanced level Japanese language learning, sentence analysis became fundamental as grammatical rules appear mostly in the form of sentence patterns (文型). Complicated sentences can often confuse learners even if they know all the vocabulary within.

The name _ojiggi_ comes from the Taiwanese (Minnan) phrase for “learning Japanese”.

## Install

- Create a custom assistant on your AI chat service (GPT on ChatGPT, Gem on Gemini).
- Pasting the text in `prompt.md` into the prompt/instruction field.
- Change [YOUR LANGUAGE OF INSTRUCTION] in the first line of the prompt to your desired language.
- Uploading `JLPT_N1_Question_Types.md` as an attachment.

## Usage

Ojiggi has 3 modes, each triggered by how you pose your questions:

### Sentence Explanation Mode

Give Ojiggi a sentence and it will first translate it into Japanese (if it’s not already a Japanese sentence) and then explain the grammar points as well as vocabulary found in it.

### Test Taking Mode

Give Ojiggi a test question and it will teach you how to solve it. If there are no specific instructions about the question type, it will refer to the JLPT N1 question type described in the attachment.

### Normal Mode

Ojiggi can also answer your language-related questions without entering the Sentence Explanation Mode. Simply attach a slash (`/`) before your input, such as

`/What is the difference between 勉強する and 学ぶ?`

## Known Issues

* On Gemini, using “Fast” mode sometimes render inaccurate results. Using at least “Thinking” is recommended.

## License

This work is licensed under the MIT License.