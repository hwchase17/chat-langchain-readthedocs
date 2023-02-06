# Chat-LangChain-ReadTheDocs

Create a ChatGPT like experience over your ReadTheDocs using [LangChain](https://github.com/hwchase17/langchain).


## 📊 Example Data
This repo uses the [LangChain Documentation](https://langchain.readthedocs.io/en/latest/) as an example.

## 🧑 Instructions for ingesting your own ReadTheDocs documentation

Run the following command to download html for a given website. Replace `https://langchain.readthedocs.io/en/latest/` with a URL to your website.

```shell
wget -r -A.html https://langchain.readthedocs.io/en/latest/
```

## Ingest data

The only thing that is needed is to be done to ingest data is run `python ingest_data.py`

## Query data
Custom prompts are used to ground the answers in LangChain Documentation files.

## Running the Application

By running `python app.py` from the command line you can easily interact with your ChatGPT over your own data.
