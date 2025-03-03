# Automated-Grammar-and-Language-Error-Correction-System
## Overview

This project aims to develop an **Automated Grammar and Language Error Correction System** that not only corrects grammatical errors but also provides users with explanations to help them understand their mistakes. The system is particularly beneficial for non-native English speakers looking to improve their writing skills.

## Authors

- **Chandana Gangaraju**
- **Akshitha Komatireddy**
- **Sai Avinash Polina**
- **Venkatesh Rakurthi**

## Course Details

- **Professor:** Dr. Liao  
- **Course Name & Number:** AIT526 - NLP, Section 001  
- **University:** George Mason University  

## System Architecture

The system is structured into multiple layers:

1. **Input Layer** - Accepts sentences with grammatical mistakes.
2. **Preprocessing Module** - Tokenizes and standardizes input for analysis.
3. **Model Layer** - Uses a fine-tuned **T5 model** trained on the **JFLEG dataset** for error correction.
4. **Feedback Generation Module** - Integrates **OpenAI’s API** to provide grammar explanations.
5. **Output Layer** - Displays the corrected text and explanation for better understanding.

## Software and Tools

- **Google Colab** - For model training and testing (includes GPU support).
- **Hugging Face Transformers** - Provides access to pre-trained models.
- **OpenAI API** - Generates feedback for grammar errors.

## Baseline Solution

- The baseline model uses the **T5 model** fine-tuned on the **JFLEG dataset**.
- Achieved a **GLEU Score of 0.0899**.
- Challenges identified:
  - Difficulty handling **complex phrases** and **idiomatic expressions**.
  - Struggles with **sentence restructuring** for natural fluency.

## Proposed Enhancements

To improve accuracy and usability, we:
- Integrated **OpenAI’s API** to generate real-time grammar explanations.
- Focused on enhancing the **GLEU score** through **hyperparameter tuning**.
- Improved handling of **idioms and complex phrases**.

## Experimental Results

- Improved **punctuation handling, subject-verb agreement, and capitalization**.
- Users found the **feedback mechanism educational and helpful**.
- Areas for improvement:
  - **Complex sentence structures** still present challenges.
  - Some feedback is **over-simplified** and needs further refinement.

## Future Work

- Fine-tune the model with a **larger dataset** to improve accuracy.
- Enhance **feedback quality** for better educational value.
- Improve handling of **idiomatic expressions** and **sentence restructuring**.

### Running the Model
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/GrammarCorrection.git
   cd GrammarCorrection
