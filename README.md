# Imaginary-Inventions-Database

Each book will have at least one CSV file, stored in the Google Drive folder: [Insert Link]. This folder is also used by the Colab notebook for easy access.  Each book should have minimum one csv file, which can be accessed in the google drive folder [insert link], which is also used by the colab notebook. The data for each book needed is as follows:

##  Deliverable Format  

Each book's data will be saved as:  
```plaintext
{title}_{author}.csv
```
## CSV File Columns  

| Column Name                | Description |
|----------------------------|-------------|
| **invention_name**         | The exact name of the technological invention as stated in the text. If unnamed, use **"unnamed"**. |
| **first_appearance_excerpt** | A 500-word excerpt (or a handful of paragraphs) **before** the invention is introduced, **including** the sentence where it appears. Copy from the Project Gutenberg link/text. |
| **category**               | General category, e.g., **communication, electronics, medicine, manufacturing, transportation, energy, other** (open to additional categories). |
| **use_case**               | A phrase or sentence explaining the problem this invention addresses. |
| **irl_status**             | Status of the invention in real life: <br> 🔹 **Fully** – Exists as described <br> 🔹 **Partial** – Some elements exist, but not exactly as in the book <br> 🔹 **Conceptually** – Theoretical or in early development <br> 🔹 **Fictional** – Does not exist at all <br> 🔹 **Unsure** – Unclear status |
| **comments**               | Optional. Add any notes, especially if the invention is **unnamed** (e.g., “a strange contraption that hovered above the ground”). |



## exampleTitle_exampleAuthor.csv

| invention_name | first_appearance_excerpt | category | use_case | irl_status | comments |
|---------------|--------------------------|----------|----------|------------|----------|
| Televox | "The first mechanical man stood up and..." | Electronics | Assists humans with tasks | Partial | Early robots like ASIMO exist, but not as advanced. |
| unnamed | "A strange contraption hovered above the ground..." | Transportation | Flying personal transport | Fictional | Described as a "floating disk." |
