# Student Dropout Risk Predictor

Predicts whether a higher-education student is likely to **Graduate**, **Drop out**, or remain **Enrolled** using a Logistic Regression model. The project uses student demographic details, tuition-fee status, scholarship information, and academic results. It is built with pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

`AI101 Mini-Project` `Team 69` `Python 3.15.2`

## Team and roles

| Member | Entry no. | Role |
|---|---|---|
| Gandrajupalli Jathin Bharadwaj | 2026AIB1034 | Execution lead |
| Rudransh Sharma | 2026EEB1402 | Documentation lead |
| Purvi Jain | 2026MCB1557 | PPT lead |
| Divyansh Kumar | 2026EEB1349 | Video lead |

All team members contributed to the code. See the repository's commit history.

## Project structure

```text
AI-model-/
├── code.ipynb                                   # Data analysis, preprocessing, model and evaluation
├── Predict dropout rate (csvfile dataset).csv   # Student dataset
├── requirements.txt                             # Required Python libraries
├── AI101_GroupProject_69.pdf                    # Presentation on Group Project
└── README.md
```

## Setup

The project was successfully run using the following environment:

- **Python:** 3.15.2 (Anaconda)
- **NumPy:** 2.5.4
- **Pandas:** 3.1.0
- **Matplotlib:** 3.11.2
- **Seaborn:** 0.13.2
- **Scikit-learn:** 1.9.1
- **IPyKernel:** 7.4.0

The required package versions are specified in `requirements.txt` to help maintain a consistent environment across team members.

### Prerequisites

- Python 3.15.2
- Visual Studio Code
- Python extension for VS Code
- Jupyter extension for VS Code

### 1. Clone the Repository

```bash
git clone https://github.com/Group-69-ai-proj/AI-model-.git
cd AI-model-
```

### 2. Create and Activate a Virtual Environment

Create a virtual environment:

```bash
python -m venv .venv
```

On Windows PowerShell, activate it with:

```powershell
.\.venv\Scripts\Activate.ps1
```

On macOS or Linux, activate it with:

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

## How to Run

1. Open the `AI-model-` project folder in Visual Studio Code.
2. Open `code.ipynb`.
3. Click **Select Kernel** in the top-right corner of the notebook.
4. Select the Python 3.15.2 environment in which you installed the project dependencies (the `.venv` environment, if you created it using the steps above).
5. Select **Run All** to execute the notebook from beginning to end. You can also use **Restart Kernel and Run All Cells** to run it from a fresh kernel.

The notebook performs data analysis, trains and evaluates the Logistic Regression model, and displays the generated graphs and evaluation results.

## Links

- **Presentation (PPT/PDF):** [Open presentation](AI101_GroupProject%20_69.pdf)
- **Project video:** [Watch project video](https://drive.google.com/file/d/1GiX1vjCV1aNfmAXPQkHh7MFtDorjV_dc/view?usp=drivesdk)

## AI-use disclosure

- **ChatGPT:** Used to understand project topics and concepts, including the scikit-learn pipeline with variables such as handle_unknown , min_frequency etc and Seaborn visualisations. It was also used to make some later changes to the README.
- **Google Gemini:** Used to understand GitHub branches and the related collaboration workflow.
- **Claude:** Used to review the project notebook and suggest improvements. Claude suggested the correlation-heatmap cell and some seaborn related graphs, which were added and tested by the team. Claude also prepared the first draft of this README.
- **Code creation:** No AI tool was used to generate the project's code apart from the correlation-heatmap and some seaborn graphs which were suggested by Claude. All remaining coding was done manually by team members. The team added, reviewed, understood and tested the correlation-heatmap cell.
- **Verification:** The team ran and tested the project code. AI was not used to generate or modify the dataset or the reported results; all results come from running `code.ipynb`.
Slides (5): [View Presentation](AI101_GroupProject%20_69.pdf) · Video (mp4): [Watch project video](https://drive.google.com/file/d/1GiX1vjCV1aNfmAXPQkHh7MFtDorjV_dc/view?usp=drivesdk)# AI-model-
