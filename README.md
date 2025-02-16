## Dataset Description

This dataset contains extracted entities and their relationships from text, stored in triple format. The main file is named `relation.csv`. Below is a detailed description of the dataset:

---

## File Structure
- **`relation.csv`**: The main data file containing triple information about entities and their relationships.

---

## Data Format
The `relation.csv` file contains the following columns:
1. **Column 1**: Entity 1 (Subject Entity).
2. **Column 2**: Type of Entity 1 (Subject Entity Type).
3. **Column 3**: Relationship between Entity 1 and Entity 2 (Relation).
4. **Column 4**: Entity 2 (Object Entity).
5. **Column 5**: Type of Entity 2 (Object Entity Type).

### Example Data (Mental Health Domain)
| Entity 1          | Entity 1 Type | Relation         | Entity 2               | Entity 2 Type |
|-------------------|---------------|------------------|------------------------|---------------|
| Decline_of_memory | Symptoms      | diagnosis        | Schizophrenia          | Disease       |
| Seroquel          | Medicine      | Treat            | Schizophrenia          | Disease       |
| Y+0101398014      | Patient       | Illness          | Manic                  | Disease       |

---

## Field Descriptions
- **Entity 1 (Subject Entity)**: The first entity in the triple.
- **Entity 1 Type (Subject Entity Type)**: The category of Entity 1.
- **Relation**: The semantic relationship between Entity 1 and Entity 2.
- **Entity 2 (Object Entity)**: The second entity in the triple.
- **Entity 2 Type (Object Entity Type)**: The category of Entity 2.
---

## License
This dataset is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the data, provided that proper attribution is given.

---

## Feedback
If you find any issues with the dataset or have suggestions for improvement, please submit an Issue on the GitHub repository or contact us via email: `zzh_016@nuist.edu.cn`.

---

Thank you for using this dataset! We hope it proves useful for your research in the mental health domain.
