# Sample Data Directory

Drop this `data/` folder next to your notebook. Each file matches one loader
from the ingestion examples.

| File                  | Loader                          | Extra package        |
|-----------------------|---------------------------------|----------------------|
| sample.txt            | TextLoader                      | (none)               |
| paper.pdf             | PyPDFLoader                     | pypdf                |
| data.csv              | CSVLoader                       | (none)               |
| data.xlsx             | pandas.read_excel               | pandas, openpyxl     |
| data.json             | JSONLoader (jq_schema=".[].content") | jq              |
| report.docx           | Docx2txtLoader                  | docx2txt             |
| notes.md              | UnstructuredMarkdownLoader      | unstructured, markdown |
| subfolder/extra.txt   | DirectoryLoader (glob="**/*.txt") | (none)             |

Install everything at once:

    pip install -U langchain-community pypdf pandas openpyxl jq docx2txt unstructured markdown
