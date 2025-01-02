# Classification of Gender, Age, and Emotion Using Keras and TensorFlow

## Projektbeskrivning

Detta projekt använder Convolutional Neural Networks (CNN) för att klassificera kön, ålder och känslor i bilder. Modellen har tränats med hjälp av Keras och TensorFlow. Resultaten varierar beroende på attribut, och det finns potential för förbättring, särskilt i åldersklassificeringen.

---

## Innehåll

- **`main.ipynb`****\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*:** Huvudfilen som kör hela projektet. Den sammanställer och exekverar de olika delarna av klassificeringen.
- **`gender.ipynb`****\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*:** Notebook för att träna och testa modellen för könsklassificering. Den använder `gender_classification_model.keras`.
- **`age.ipynb`****\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*:** Notebook för att träna och testa modellen för åldersklassificering. Den använder `age3_classification_model.keras`.
- **`emo.ipynb`****\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*:** Notebook för att träna och testa modellen för känsloklassificering. Den använder 61p\_model.h5.keras.
- **Modellfiler:**
  - `gender_classification_model.keras`: Förtränad modell för könsklassificering.
  - `age3_classification_model.keras`: Förtränad modell för åldersklassificering.
  - `61p_model.h5.kas`: Förtränad modell för känsloklassificering.

---

## Förutsättningar

För att köra projektet behöver du följande:

- **Python 3.8+**
- **Jupyter Notebook**
- Installerade Python-bibliotek:
  ```bash
  pip install tensorflow keras numpy pandas matplotlib
  ```

---

## Så här kör du projektet

1. Klona detta repo:
   ```bash
   git clone https://github.com/julia.kronm/projekt-repo.git
   cd projekt-repo
   ```
2. Öppna och kör `main.ipynb` i Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
3. Kör alla celler i filen med "Run All".

---

## Prestanda och förbättringsmöjligheter

- **Prestanda:**

  - **Emotion:** Goda resultat.
  - **Gender:** Goda resultat.
  - **Age:** Presterar sämre, med stor potential för förbättring.

- **Förbättringsmöjligheter:**

  1. **Åldersklassificering:** Experimentera med fler lager eller andra arkitekturer.
  2. **Dataset:** Använd ett större eller mer balanserat dataset.
  3. **UI:** Integrera ett gränssnitt för enklare användning.

---

## Licens

[MIT License](LICENSE)

---

## Framtida arbete

Jag planerar att förbättra modellens prestanda och integrera ett enkelt användargränssnitt för att göra projektet mer interaktivt.

# ai_classification
