# Imaginary-Inventions-Database
Each book should have minimum one csv file, which can be accessed in the google drive folder [https://drive.google.com/drive/folders/1-DBvE0XTSv8watFR2o4U63QOqN5W3ej3?usp=sharing], which is also used by the colab notebook. The data for each book needed is as follows:

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
| **category**               | General category, if you want to use multiple, separate labels with commas e.g., **communication, electronics, medicine, manufacturing, transportation, energy, other** (open to additional labels). |
| **classification**         | What kind of invention is it, use the labels **original, reengineered** (open to additional labels). |
| **use_case**               | A phrase or sentence explaining the problem this invention addresses. |
| **irl_status**             | Status of the invention in real life: <br> 🔹 **Fully** – Exists as described <br> 🔹 **Partial** – Some elements exist, but not exactly as in the book <br> 🔹 **Conceptually** – Theoretical or in early development <br> 🔹 **Fictional** – Does not exist at all <br> 🔹 **Unsure** – Unclear status |
| **comments**               | Optional. Add any notes, especially if the invention is **unnamed** (e.g., “a strange contraption that hovered above the ground”). |



## exampleTitle_exampleAuthor.csv

| invention_name | first_appearance_excerpt | category | classification | use_case | irl_status | comments |
|---------------|--------------------------|----------|--------------|----------|------------|----------|
| Televox | "The first mechanical man stood up and..." | electronics | original | Assists humans with tasks | Partial | Early robots like ASIMO exist, but not as advanced. |
| unnamed | "A strange contraption hovered above the ground..." | transportation | Reengineered | Flying personal transport | Fictional | Described as a "floating disk." |


## FAQ - Clarifications and Guidelines

Here are some key clarifications regarding what constitutes an "invention" for our analysis, based on recent discussions.

**Key Takeaway:** When in doubt, lean towards inclusion ("The more data the better").

And please let us know and ask about any more edge cases or ambiguities! Shout-out to our meticulous readers who asked these questions that helped us refine our project further! And if you have further questions, please please don't hesitate to ask!

---

**Q: Do biological inventions count? For example, sharks and giant squids engineered in the future based on "old Earth" data?**

**A:** Yes, these should be included. We should label them as **"reengineered"** rather than **"original"** in the classification column, especially if the narrative itself frames them as such. 

**Q: What about non-scientific inventions like pagan curses? Can a curse be considered an invention?**

**A:** Absolutely! A curse created through specific arrangements of words can be considered an invention. This highlights the idea that language and specific formulations can be powerful tools for change and can function like an invention within the context of a story.


**Q: If a contemporary object is simply disguised to look "sci-fi-ey," but its function remains the same (e.g., a flashlight in disguise), is it notable as an invention?**

**A:** Probably not as a *new* invention in itself. However, if these objects are updated or upgraded in some way (e.g., a flashlight with significantly enhanced features), then they should be included and labeled as **"reengineered"** The key is whether there's a functional difference, not just an aesthetic one. Please let us know if you're still unsure or if you doubt any of our categorizations!

**Q: Where do alien inventions fit into our analysis? Does it matter how similar the aliens are to humans?**

**A:** Alien inventions are valid for our analysis. The degree to which the aliens are "human-like" is less important than whether their creations function as technology or inventions within the narrative. However, if alien beings are so far removed from a technological understanding (e.g., god-like beings whose "technology" appears as magic), their creations might fall outside the scope of "invention" as we're defining it. Use your judgment and let us know/note any such cases.


**Q: If human-like aliens invent things that humans have already invented in our past (e.g., cars, nukes), should we include them?**

**A:** Yes, if these items are invented within the story's timeline, even if they are similar to past human inventions, they should be included in our analysis. The act of invention within the fictional context is what makes them relevant.

