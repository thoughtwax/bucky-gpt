# Bucky GPT

AI-powered search and chat for Buckminster Fuller's ["Everything I Know"](https://www.bfi.org/about-fuller/everything-i-know/) series of lectures.

## Dataset

The dataset is a CSV file containing all text & embeddings used.

### Search

Search was created with [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) (`text-embedding-ada-002`).

Our database is a Postgres database with the [pgvector](https://github.com/pgvector/pgvector) extension hosted on [Supabase](https://supabase.com/).

### Chat

Chat builds on top of search. It uses search results to create a prompt that is fed into GPT-3.5-turbo.

This allows for a chat-like experience where the user can ask questions about the book and get answers.


## Credits

Adapted from Mckay Wrigley's [Wait But Why GPT](https://github.com/mckaywrigley/wait-but-why-gpt).

## Contact

If you have any questions, feel free to reach out to me on [Twitter](https://twitter.com/thoughtwax)!

## Notes

I am not a programmer.