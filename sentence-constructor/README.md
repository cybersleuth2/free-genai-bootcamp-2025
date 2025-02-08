**##Business Goal(s) of Sentence Constructor**

A chat agent that acts as a teaching assistant to guide students from translating a target English sentence into Russian. The teaching assistant is not there to provide the direct answer, only guidance.

**##The developer will choose from these**
Meta AI https://www.meta.ai/
ChatGPT https://openai.com/index/chatgpt/
Anthropic Claude https://www.anthropic.com/claude
Mistral AI https://mistral.ai/
*Ollama + Open WebUI https://openwebui.com/
*LibreChat https://www.librechat.ai/
Leon https://github.com/leon-ai/leon



**##Technical Uncertainties of Sentence Constructor**

The AI-Powered Agent should not be used to replace the real teacher due to the following technical uncertainties and limitations:  

Ambiguity in Sentence Structure: Sentences can often be constructed in multiple ways, leading to ambiguities that a model might not resolve properly. For example, syntactically different structures might convey similar meanings, but subtle differences in interpretation can lead to miscommunication. LLMs might not always select the most contextually fitting structure.

Word Sense Disambiguation (WSD): Words can have multiple meanings depending on their context (e.g., "bank" could refer to a financial institution or the side of a river). LLMs can sometimes struggle with disambiguating words in complex sentences, particularly if they lack explicit context that makes the meaning clear.

Handling Different Dialiects, or Rare/Out-of-Vocabulary Words: Despite vast training data, LLMs can encounter words or phrases that are rare, domain-specific, or newly coined. Their ability to generate accurate sentences with such terms can be uncertain, as they might not have learned the correct associations or might generate an incorrect or awkward construction.

Grammatical and Stylistic Consistency: Although LLMs can produce grammatically correct sentences, they can still exhibit inconsistency in style, tone, or formality, especially in longer passages. Achieving a consistent voice across a document is challenging, as the model might switch registers (e.g., from formal to informal) or make stylistic shifts that feel jarring.

Pragmatic and Cultural Nuances: Sentence construction isn't just about grammar—it's also about appropriateness within the cultural and social context. LLMs can sometimes generate sentences that sound grammatically correct but are socially awkward, insensitive, or inappropriate based on the situation or the cultural norms of the intended audience.

Generating Sentences with Correct Factual Information: LLMs may generate sentences that are syntactically correct but factually incorrect. This is particularly problematic when the model constructs sentences that sound plausible but are based on incorrect data, outdated information, or biases in the training data.


**##To Be Determined**
How well can an AI-Powered Assistant perform a very broad task?

Would a very broad task be better performed by dividing it into subtasks with specialized agents?

Does using an AI-Powered Assistant make for a good place to rapidly prototype agents?

How could we take the agent we built in an AI-Powered Assistant and reimplement it into a stack that allows for direct integration into our platform?	

How much do we have to rework our prompt documents from one AI-Powered Assistant to another?

What prompting techniques can we naturally discover working in the confines of an AI-Powered Assistant?

Are there any interesting innovations unique to specific AI-Powered Assistants for our business goal?

What were we able to achieve based on our AI-Powered Assistant choice and our hardware, or budget limitations?
