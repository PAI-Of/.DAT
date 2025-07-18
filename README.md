# DotData (.DAT) – Clean Data / Open Source.

> Coding is easy. Finding high-quality, cleaned data is the real challenge.

**DotData (.DAT)** is an open-source initiative to make clean, structured, and license-safe datasets available for developers, researchers, and AI builders.

🔹 Curated, AI-ready datasets
    - Our teammates (contributors contribute in providing the datasets.)
🔹 Built-in cleaning and normalization tools  
    - Our contributors and even i develop many normalization and cleaning tools.
🔹 Fetchable via API  
    - We will provide a API in future (if we get a domain)
🔹 Auto-license checker
    - .ddat contains the License Info.
🔹 Community-powered vault


## What we are going to do?
Finding Images and Corpus.

## Welcome, please maintain the Dicipline and Format.
The .DAT includes data in many formats:
### QAFormat (QAF-Format)
Write the whole dataset in qa/genere.txt for example qa/about_ddat.txt and **mention the dataset in the .ddat**
Example you wrote a data on topic AI/QAs:
```
Q=Who are you?
A=I am an AI named X.

Q=What is AI?
A=AI stands for Artificial Intelligence, a simulation of human thinking by machines.
```
You would:
1. Save the dataset in `qaf/aiqa-0`
2. Write a update on .ddat inside the QAF like
```
... Contributors
AIQA-0 By: <Pawan Yadav> <pawanyadav@virtual-intelligence.xyz>
```
### WORD VOCAB
Write the whole dataset in word_vocab/
like word_vocab/science.txt
```
Gravity=The force that attracts objects toward one another
Photosynthesis=The process by which green plants use sunlight to make food
```
And same mention your dataset SCI-1.
### SENSE DATALOG
Same but in sense/
```
Time (s),Temperature (°C),Pressure (Pa)
0.0,25.4,101325
0.5,25.6,101300
```
Useful for future predictions or graphs.

### IM GEN FORMAT
Still same in gen/
```
[
  {
    "image": "cat1.jpg",
    "caption": "A brown cat sitting on a couch"
  },
  {
    "image": "dog2.png",
    "caption": "A dog playing with a ball in the garden"
  }
]
```
### CONTRIBUTORS
Enter your name in .dat.json where you contributed like 
i contributed in gen/dog.txt / .pngs
so i will goto gen/ and find .dat.json and fill
the data like this :
```json
{
  "name": "DOG-IMG-10",
  "description": "10 Images of Dog",
  "type": "json/gen",
  "license": "CC-BY 4.0",
  "source": "My Pet Dog in different places and angles.",
  "contributors": ["Pawan"],
  "note": "No Copyright Attribution Image."
}
```
### Banned Entities:
- Ambika Sharma - Owner of Pixella (dumb ai)
- Dhruv Yadav   - Owner of Apostropy.ai

## Quick Start
```bash
git clone https://github.com/PAI-Of/.DAT.git
cd .DAT
npm run start
```
