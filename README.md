# Decision Miner

**Interactive CART Decision Tree**

Built Credit Card churn and customer persona analytics.

## Features

- Full CART decision tree with Gini / Entropy / −log(p) criterion
- **Manual split control** — click any node to choose the split variable
- Right-click context menu — ranked variable list with info gain scores
- Interval Splitting Rule modal — threshold slider, Add/Remove Branch, live churn preview
- Auto Split / Train Node / Prune per node
- Light theme with prominent split variable display on each node
- Target (Y) variable selector — works with any CSV
- Metrics: Accuracy, Precision, Recall, Confusion Matrix, Feature Importance
- Predict panel with decision path highlighting

## Usage

Open [https://samithr1981.github.io/decision-miner/](https://samithr1981.github.io/decision-miner/) in Chrome or Edge.

1. Click **▶ TRAIN** to build the initial auto tree on RuPay CC sample data
2. **Left-click** any node to open the Split Control panel on the right
3. **Right-click** any node for a quick context menu with all variables ranked
4. Select a variable → **OK** to manually split that node only
5. Click **Edit Rule** to fine-tune the threshold with a histogram and branch table
6. Upload your own CSV via the CSV button

## Tech

Vanilla HTML/CSS/JS — no dependencies, no build step. Single file.

