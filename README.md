# CPSC_4420_Assignment_2
This project uses Blackjack Gymnasium and uses Q-learning to find the best move.
How to run
1. Open Google Collab
2. Upload 'Blackjack_Minimal_Colab.ipynb'
3. Install all libraries and run the code.
4. When the code is finished running, it displays four training plots and evaluation results, records an MP4, and downloads blackjack_results.zip.
Training and experiments
- Environment: Gymnasium Blackjack-v1
- Training: 50,000 episodes with tabular Q-learning.
- Baseline: alpha = 0.1, gamma = 0.9, epsilon = 0.2 (constant epsilon; no decay).
- Learning-rate test: alpha = 0.1, 0.5, 0.9 (other settings held fixed).
- Discount-factor test: gamma = 0.5, 0.9, 0.99 (other settings held fixed).
- Exploration test: epsilon = 0.05, 0.2, 0.5 (other settings held fixed).
- Best-policy selection: compare average rewards over 500 episodes.
- Final test: compare the baseline and selected policy on 2,000 separate episodes each, with no exploration.
Files
- Blackjack_Minimal_Colab.ipynb: code and Collab notebook.
- results/baseline.png: baseline training graph.
- results/alpha.png: learning-rate comparison graph.
- results/gamma.png: discount-factor comparison graph.
- results/epsilon.png: exploration comparison graph.
- results/evaluation.txt: final evaluation summary.
- results/blackjack_demo.mp4: recording of five games played by the selected agent.
