# Hi, I'm Stephen Box

I'm a self-taught developer who enjoys breaking down complex systems and building tools that solve real-world problems.

Most of my projects begin with a question or challenge I encounter personally and evolve through experimentation, iteration, and system design.

---

## Projects

### [NBA Statistical Edge Development](https://github.com/Box-Builds/nba-statistical-edge-development)

A multi-phase analytics system exploring how to evaluate NBA player prop outcomes using historical player data.

The project evolved from market-comparison experiments into a fully automated, cloud-deployed pipeline — a nightly Google Cloud Run job maintains the dataset, triggering a GitHub Actions workflow that handles model training, inference, and delivery to Google Sheets with zero manual intervention.

From there, the project grew into a structured framework combining:

- a probability and interpretability application built on historical distribution analysis
- a rule-based filtering engine that automates candidate-finding
- human-in-the-loop decision systems for edge cases that can't be automated

This project serves as a case study in developing analytical systems under uncertainty.

---

### [Tennis API](https://github.com/Box-Builds/Tennis.API)

A Python API that exposes structured ATP Tour match, tournament, and head-to-head data.

The project reverse-engineers ATP website endpoints and wraps them in a clean developer-friendly interface using **FastAPI**, allowing tennis statistics to be accessed programmatically. Currently expanding to support the WTA Tour with a Python client wrapper.

---

## Technologies I Work With

- Python
- Pandas / NumPy
- Scikit-learn
- FastAPI
- Streamlit
- SQL
- Google Cloud Run
- GitHub Actions / CI/CD
- Data pipelines
- API development
- Statistical analysis

---

## Connect

[LinkedIn](https://www.linkedin.com/in/stephen-box-176b9a3b5/)
