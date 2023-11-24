# Read Me

1. Clone the repo.
```bash
git clone https://github.com/RaiyanArsh/Reelo-Assignment.git
```

2. Add questions inside data object in question-store.json file. \
```json
["What is the speed of light", "Physics", "Waves", "Easy", 5]
```

3. Setup config.json file.
```json
{
  "totalMarks": 100,
  "difficulty": {
    "easy": 20,
    "medium": 50,
    "hard": 30
  },
  "filePath": "./question-store.json"
}
```

4. Run the project
```bash
cd qustion-paper-gen

node main
````

5. Result format 
```json
{
  "easy": [],
  "medium": [],
  "hard": []
}
```
