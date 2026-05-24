# Decision Miner

**Interactive CART Decision Tree — Human-Centric Split Control**

An open-source decision tree builder that puts the analyst in control of every split.

## Features

- Full CART engine — Gini, Entropy, or −log(p) criterion
- **Right-click any node** → all variables ranked by information gain
- **Manual split control** — one node at a time, children become leaves
- Interval Splitting Rule modal — threshold slider, Add/Remove Branch, live positive-rate preview
- Auto Split / Train Node / Prune per node
- Light theme with split variable prominently displayed on each node
- Target (Y) variable selector — works with any CSV
- Metrics: Accuracy, Precision, Recall, Confusion Matrix, Feature Importance
- Predict panel with decision path highlighting in the tree

## Live

🔗 https://samithr1981.github.io/decision-miner/

No login. No install. No data leaves your browser.

## Usage

1. Click **▶ TRAIN** to build the auto tree on sample data
2. **Left-click** any node → Split Control panel opens on the right
3. **Right-click** any node → context menu with all variables ranked by score
4. Select a variable → **OK** to manually split that node only
5. **Edit Rule** → set exact threshold with histogram + branch table
6. Upload your own CSV via the CSV button — any binary target column works

## Tech

Single-file vanilla HTML/CSS/JS. No dependencies, no build step, no server.

