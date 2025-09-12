# AI Projects 📚🤖

This repository is a personal collection of deep learning projects, developed as part of various advanced courses in applied artificial intelligence.
It is organized into topic-specific folders and includes Jupyter notebooks with solutions, implementations, and experiments across different domains.


## 📁 Repository Structure

The project is organized as a set of topic-based folders. Each folder contains notebooks related to specific problems or assignments. Currently, the main areas include:

---

## 🧪 Project Highlights

### 🧬 Reinforcement Learning & Control

| Notebook | Description |
|----------|-------------|
| `Taxi_Qlearn.ipynb` | Q-learning agent for the `Taxi-v3` environment. Covers epsilon-greedy strategies, reward shaping, and value iteration insights. |
| `Mount_cart.ipynb` | Solves CartPole balancing using custom reward shaping and function approximation. |
| `LunarLanderReto.ipynb` | Applies Q-learning and reward-based exploration for the `LunarLander-v2` challenge. |
| `Reto_II_MMMarkov.ipynb` | Models a Markov Decision Process (MDP) and solves it analytically and numerically. |
| `Function Approximation.ipynb` | Trains and visualizes approximators (NNs, polynomial regression) to estimate value functions in continuous state spaces. |

---

### 📚 NLP & Author Profiling

| Notebook | Description |
|----------|-------------|
| `Robertuito_author_profiling.ipynb` | Fine-tunes `RoBERTuito` (Spanish BERT) for gender and nationality prediction using social media data. |
| `Author_profiling_hier_attn.ipynb` | Builds a **Hierarchical Attention Network** to capture multi-level structure in tweet-based author profiling. |
| `Classic_NLP_tourist_review.ipynb` | Sentiment classification on tourist reviews using classical methods (BoW, TF-IDF, SVM). |
| `BOW_political_lang.ipynb` | Explores political orientation in Spanish text using logistic regression on bag-of-words representations. |
| `Web_scraping_word_statistics.ipynb` | Web scraping pipeline with BeautifulSoup for extracting, cleaning, and analyzing word statistics in online articles. |

---

### 🧪 Symbolic Regression, Physics & PINNs

| Notebook | Description |
|----------|-------------|
| `PINN_harm_oscillator.ipynb` | Implements a Physics-Informed Neural Network (PINN) to solve the harmonic oscillator ODE. Merges deep learning with physical constraints. |
| `Deficit_boost_bagging.ipynb` | Explores the effects of bagging and boosting (RandomForest, XGBoost) in classification tasks with class imbalance and limited samples. |

---

### 🧠 Information Retrieval & RAG

| Notebook | Description |
|----------|-------------|
| `RAG_technical_troubleshooting.ipynb` | Builds a **Retrieval-Augmented Generation (RAG)** system to assist in technical debugging using a local knowledge base. Uses OpenAI, LangChain, and FAISS vector stores. |

---

### 🎯 Decision Science & Experimentation

| Notebook | Description |
|----------|-------------|
| `AB_testing.ipynb` | Implements and compares traditional A/B testing with a **contextual bandit approach** to improve online decision-making in experiments with partial information. |

---

## 🧰 Technologies & Libraries

| Category        | Tools / Libraries |
|----------------|-------------------|
| 🧠 Machine Learning  | `scikit-learn`, `XGBoost`, `RandomForest`, `LightGBM` |
| 🤖 NLP               | `transformers`, `RoBERTuito`, `spaCy`, `NLTK`, `TF-IDF`, `BoW`, `Attention` |
| 🎮 Reinforcement Learning | `OpenAI Gym`, `Q-learning`, `epsilon-greedy`, `custom reward functions` |
| 📈 Experimentation | `p-value`, `uplift modeling`, `contextual bandits`, `RL for A/B testing` |
| 🔬 Scientific ML   | `PINNs`, `ODE solvers`, `torch.autograd` |
| 🌐 Web & RAG        | `LangChain`, `FAISS`, `OpenAI API`, `BeautifulSoup` |
| 📊 Visualization    | `Matplotlib`, `Seaborn`, `Plotly`, `WordCloud` |

---

## 🔍 Use Cases Covered

- Reinforcement learning agents for control and exploration
- Author and sentiment classification from social media
- Statistical A/B testing with ML enhancement
- Physics-informed modeling of dynamical systems
- Document retrieval and QA with generative LLMs
- Web scraping and token-level word analysis

---

## 🎓 Target Audience

This repository is ideal for:

- ML/NLP practitioners exploring diverse project templates  
- Students applying ML theory to hands-on use cases  
- Researchers prototyping custom RL/NLP pipelines  
- Portfolio builders showcasing real-world ML depth
