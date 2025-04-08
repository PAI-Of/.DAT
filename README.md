# DotData (.DAT) – Clean Data. At Dev Speed.

> Coding is easy. Finding high-quality, cleaned data is the real challenge.

**DotData (.DAT)** is an open-source initiative to make clean, structured, and license-safe datasets available for developers, researchers, and AI builders.

🔹 Curated, AI-ready datasets  
🔹 Built-in cleaning and normalization tools  
🔹 Fetchable via API  
🔹 Auto-license checker  
🔹 Community-powered vault

## What we are going to do?
MAANG, OpenAI and even my brand (Powered Intelligece) suffer from the problem of finding good data for AIs.
So .DAT will find non CopyRight Data and Paste in this DB no code needed.
If you can help please help.

## Welcome, please maintain the Dicipline and Format.
The .DAT includes data in many formats:
### QA Format (Question = Answer)
Write the whole dataset in 
qa/genere.txt
for example qa/about_ddat.txt
```
Q=Who are you?
A=I am an AI named X.

Q=What is AI?
A=AI stands for Artificial Intelligence, a simulation of human thinking by machines.
```
### WORD WONT
Write the whole dataset in word_wont/
like word_wont/about_ddat.txt
```
Gravity=The force that attracts objects toward one another
Photosynthesis=The process by which green plants use sunlight to make food
```
### SENSE DATALOG
Same but in sense/
```
Time (s),Temperature (°C),Pressure (Pa)
0.0,25.4,101325
0.5,25.6,101300
```
OR Like this
```


```
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
  "name": "doggo_image_10",
  "description": "10 Images of Dog",
  "type": "json/gen",
  "license": "CC-BY 4.0",
  "source": "Google_Searches + manual curation",
  "contributors": ["Google_Searches", "Pawan"],
  "note": "Google_Searches_with_no_copyrights"
}
```
### Banned Entities:
- Ambika Sharma - DONT KNOW BRAND
- Dhruv Yadav   - Owner of Apostropy.ai

## Quick Start
```bash
git clone https://github.com/PAI-Of/.DAT.git
cd .DAT
npm run start
```
