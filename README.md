# MSCS_634_Lab_6


## Purpose
The purpose of this lab is to explore association rule mining techniques using Apriori and FP-Growth algorithms. The lab demonstrates how to identify frequent itemsets, generate association rules, and visualize patterns using Python libraries such as Pandas, Seaborn, and Matplotlib.

## Dataset
A small transactional dataset was used to demonstrate the workflow of association rule mining. The dataset contains item-level transaction records and was converted into a one-hot encoded format using the TransactionEncoder.

## Methods Used
- Apriori Algorithm
- FP-Growth Algorithm
- Association Rule Mining (support, confidence, lift)
- Data Visualization using Seaborn and Matplotlib

## Key Insights
The analysis showed that Bread was the most frequent item in the dataset. Bread and Milk appeared together in multiple transactions, indicating a strong association. Association rules with high confidence and lift helped identify meaningful relationships between items.

## Comparative Analysis
Both Apriori and FP-Growth produced similar frequent itemsets when using the same support threshold. However, FP-Growth was faster because it uses a tree-based structure, while Apriori generates and tests many candidate itemsets, making it less efficient for larger datasets.

## Challenges
One challenge was converting the transactional data into the required one-hot encoded format for the algorithms. This was resolved using the TransactionEncoder from the mlxtend library. Another challenge was understanding and interpreting support, confidence, and lift, which are key metrics in association rule mining.

## Conclusion
This lab demonstrated how association rule mining can be used to uncover hidden patterns in transactional data. These techniques are useful in real-world applications such as market basket analysis, recommendation systems, and business decision-making.
