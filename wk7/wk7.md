## Week 7 Workshop

**Teams**
- Asa
- Sayan
- Sethu
- Santiago
- Yara

(i.e. work together if you like, or start independently)

The [Register of Members' Financial Interests](https://members.parliament.uk/members/commons/interests/publications?sessionId=40) is a list of money or financial benefits received by Westminster MPs from sources *other* than parliament. These sources include earnings from other work or donations, but also things like trips abroad or tickets.

For a long time this register has been difficult to interrogate as a single batch of data.

[MySociety](https://www.mysociety.org/about/) has wrangled this data [and produced different formats](https://pages.mysociety.org/parl_register_interests/datasets/commons_rmfi/latest), including the JSON file in this repository.

**Task**

In a Jupyter notebook read in the JSON file which has been prepared by MySociety.

`import json

with open('rmfi_commons.json') as json_data:

    d = json.load(json_data)`

1. Investigate how it's structured and what's in there: it is made up of lists and dictionaries.

2. Explain the data in the notebook using [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax): show some examples of what's available in the data.

3. Ask some questions, and find some answers (in the notebook)

4. Repeat, for the SRMI: the [Senedd Register of Interests](https://pages.mysociety.org/parl_register_interests/datasets/senedd_register_of_interest)

Open a Pull Request in the latest version of the workshop repo, for your notebook.