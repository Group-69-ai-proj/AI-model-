# Student Dropout Risk Predictor

Predicts whether a higher-education student is likely to **Graduate**, **Drop out**, or remain **Enrolled** using a Logistic Regression model. The project uses student demographic details, tuition-fee status, scholarship information, and academic results. It is built with pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

`AI101 Mini-Project` `Team 69` `Python 3.11 / 3.12`

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
├── docs/                                        # Supporting project files
└── README.md
```

## Setup

The project was tested with **Python 3.11 and 3.12** on Ubuntu Linux. Python 3.13 or newer is not supported by the pinned library versions.

```bash
git clone https://github.com/Group-69-ai-proj/AI-model-.git
cd AI-model-
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## How to run

Run the following commands from the `AI-model-` project folder after activating the virtual environment:

```bash
jupyter notebook code.ipynb
```

Open `code.ipynb` and select **Kernel → Restart Kernel and Run All Cells**. The notebook performs the data analysis, trains and evaluates the Logistic Regression model, and displays the generated graphs and evaluation results. Expected runtime is approximately 15 seconds.

## Links

- **Presentation (PPT/PDF):** [Open presentation](AI101_GroupProject%20_69.pdf)
- **Project video:** [Watch project video](https://drive.google.com/file/d/1GiX1vjCV1aNfmAXPQkHh7MFtDorjV_dc/view?usp=drivesdk)

## AI-use disclosure

- **ChatGPT:** Used to understand project topics and concepts, including the scikit-learn pipeline with variables such as handle_unknown , min_frequency etc and Seaborn visualisations. It was also used to make some later changes to the README.
- **Google Gemini:** Used to understand GitHub branches and the related collaboration workflow.
- **Claude:** Used to review the project notebook and suggest improvements. Claude suggested the correlation-heatmap cell and some seaborn related graphs, which were added and tested by the team. Claude also prepared the first draft of this README.
- **Code creation:** No AI tool was used to generate the project's code apart from the correlation-heatmap and some seaborn graphs which were suggested by Claude. All remaining coding was done manually by team members. The team added, reviewed, understood and tested the correlation-heatmap cell.
- **Verification:** The team ran and tested the project code. AI was not used to generate or modify the dataset or the reported results; all results come from running `code.ipynb`.
Slides (5): `docs/<file name>` · Video (mp4): `https://drive.google.com/file/d/1GiX1vjCV1aNfmAXPQkHh7MFtDorjV_dc/view?usp=drivesdk`# AI-model-
