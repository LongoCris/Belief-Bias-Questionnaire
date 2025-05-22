
# Syllogism Quiz

An interactive web-based quiz designed to assess logical reasoning and belief bias through syllogistic questions adopted in [llm-belief-bias](https://github.com/SergioV3005/llm-belief-bias) project. This tool presents users with a series of logic-based questions requiring them to evaluate the validity of conclusions based on given premises.

## Features

- **Timed Questions**: Users have 20 seconds to answer each logic question.
- **Belief Bias Evaluation**: Questions are categorized as "believable" or "unbelievable" to explore how belief affects logical judgment.
- **Open-Ended Question**: Final question allows for a written explanation of reasoning.
- **PDF Report**: After completing the quiz, users can download a detailed PDF report including performance statistics and a belief bias analysis chart.
- **Client-Side Only**: All functionality is handled in-browser with no server-side code or data storage.

## Technologies Used

- HTML5, CSS3, JavaScript
- [jsPDF](https://github.com/parallax/jsPDF) for PDF generation
- [Chart.js](https://www.chartjs.org/) for data visualization

## Getting Started

1. Clone this repository or download the source code.
2. Open `index.html` in any modern web browser.
3. Enter your name and start the quiz!
4. You can also try the quiz by clicking [HERE](https://longocris.github.io/Belief-Bias-Questionnaire/)

## Example Question

> **Premise 1**: All A are B.  
> **Premise 2**: All B are C.  
> **Conclusion**: Therefore, all A are C.  
> ✅ This conclusion is **Valid**.

## Folder Structure

```
📁 Syllogism-Quiz
├── index.html         # Main application file
└── README.md          # Project overview and instructions
```

## License

This project is licensed under the MIT License.
