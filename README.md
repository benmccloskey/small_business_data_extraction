# Natural Language Processing Analysis of Online Reviews for Small Business: Extracting Insight from Small Corpora

[Link to the Published Paper](https://link.springer.com/article/10.1007/s10479-023-05816-2)

## Abstract

Receiving and acting on customer input is essential to sustaining and growing any service organization, particularly a small family business whose livelihood depends on strong relationships with its customers. The competitive advantage offered by advanced analytical approaches for supporting decisions is not trivial, and enterprises across virtually all domains of society are investing heavily in this emerging discipline. Natural Language Processing (NLP) is a subset of computer science that employs computational approaches to analyze human language; it is effective at extracting insight from text data but frequently requires large corpora to train its models, in the scale of thousands or millions of documents. This restricts its accessibility to those large enterprises with the capability to capture, store, manage, and analyze such corpora. This research explores a pilot study that applies NLP approaches, specifically topic modeling and large language models (LLM), to assist a small, family-owned business in assessing its strengths and weaknesses based on customer reviews. The relevant corpora of online Facebook, Google Reviews, TripAdvisor, and Yelp reviews is far smaller than ideal, numbering only in the hundreds. Results demonstrate that coherent and actionable insights from big-data approaches are obtainable and that small organizations are not automatically excluded from the benefits of these advanced analytical approaches, with complementary employment of both topic modeling and LLM presenting the greatest potential for similarly-positioned organizations to exploit.

## Project Structure

```plaintext
small_business_data_extraction/
│
├── README.md                                  # Main project documentation (This file)
├── data/                                      # Directory containing raw and processed data
│   ├── README.md                              # Information about the data used in this project
│   └── Altomontes_reviews.csv                 # Customer reviews dataset
├── Excursions/                                # Additional experiments and explorations
│   ├── README.md                              # Documentation for Excursions
│   ├── italian_market_review_analysis_part_II.ipynb  # Analysis notebook
│   └── generated_data/                        # Data generated using LLMs
└── Topic_Modeling.ipynb                       # Main notebook for topic modeling analysis
└── requirements.txt                           # Current environment requirements


```

## Introduction

This repository accompanies a research paper on the use of Natural Language Processing (NLP) techniques for extracting insights from small corpora of customer reviews. The project focuses on small businesses, particularly a family-owned Italian market, and demonstrates how advanced analytical techniques, such as topic modeling and the use of large language models (LLMs), can be effectively applied even when data is limited.

## Contents

- **Topic_Modeling.ipynb**: The main Jupyter notebook where the primary analysis, including topic modeling and sentiment analysis, is conducted.
- **data/**: Contains the `Altomontes_reviews.csv` file with customer reviews from various platforms (TripAdvisor, Google Reviews, Yelp) and a `README.md` explaining the data.
- **Excursions/**: This directory includes additional analyses and experiments that complement the main study. It contains a notebook focused on analyzing real vs. fake reviews, as well as data generated using LLMs.
- **README.md**: This file provides an overview of the project, its structure, and instructions for use.

## Setup and Installation

### Prerequisites

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Lab

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/benmccloskey/small_business_data_extraction.git
   cd small_business_data_extraction
   ```

2. **Create and activate a virtual environment** (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required Python packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Lab**:
   ```bash
   jupyter lab
   ```

## Usage

1. **Running the Notebooks**: Navigate to the `Topic_Modeling.ipynb` or any other notebook in Jupyter Lab. Run the cells sequentially to reproduce the analysis.

2. **Data Directory**: The `data/` directory contains the raw data used in the analyses. The `Altomontes_reviews.csv` file includes customer reviews that are analyzed in the notebooks.

3. **Excursions Directory**: Explore the `Excursions/` directory for additional experiments and analyses that complement the main study. This includes the analysis of real vs. fake reviews and data generated by large language models.

## Results and Insights

The analyses in this repository provide insights into customer sentiment, key topics of discussion, and trends within the small business environment. By leveraging these insights, small businesses can enhance their operations and customer satisfaction.

### Key Findings

- **Sentiment Analysis**: Highlights the overall sentiment expressed by customers in their reviews.
- **Topic Modeling**: Identifies key themes and topics discussed in the reviews.
- **Comparative Analysis**: Examines differences between real and generated reviews to understand the impact of synthetic data.

## Conclusion

This project demonstrates that even small businesses with limited data can benefit from advanced NLP techniques. The tools and methods presented here can be adapted to other small datasets, offering valuable insights that can drive business decisions.

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.




