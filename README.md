## OpenAI Function Call to Semantically Search Words in the Quran

Yesterday, OpenAI announced a new feature that allows descriptive functions to query GPT. This non-deterministic paradigm opens up many new dimensions for software developers. In this notebook, I share how to use the API.

In this notebook, we use semantic search to find word matches in the Quran. Instead of quering a relational database, we simply ask GPT using a function call. Function calls are different from prompting as we can control the returned values and also preserve tokens as no exhuberant or uncessary content is returned other than that which we have requested.
