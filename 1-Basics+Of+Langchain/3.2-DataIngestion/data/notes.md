# Data Ingestion Notes

Loading is the **first step** of any RAG pipeline.

## Common Sources

- Local files (txt, pdf, csv, docx)
- Web pages and APIs
- Databases

## Key Idea

> Every loader returns a list of `Document` objects with `.page_content`
> and `.metadata`.

See the [LangChain docs](https://python.langchain.com) for the full loader list.
