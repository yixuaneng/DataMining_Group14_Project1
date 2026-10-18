# Project Files: Contributions and Workflow

This README explains the files in the project, the order they follow, and who contributed each part.

**Important:** Name every file exactly as listed in the File List table below before uploading to Git (for example, `EDA_DS1_EuroMart`). Do not add the sequence number or any other name to the file. The numbers in the table show the order of work and are for reference only.

## Naming Convention

```
<Analysis or Model>_<Dataset>_<Variant>
```

Exploratory files for datasets that were not pursued start with `Other_`.

Dataset codes:

| Code | Dataset | Link |
|------|---------|------|
| `DS1` | EuroMart (Dataset 1) | [braniac2000/retail-dataset](https://www.kaggle.com/datasets/braniac2000/retail-dataset) |
| `DS2` | POS (Dataset 2) | [arunsworkspace/retail-pos-dataset-for-market-basket-analysis](https://www.kaggle.com/datasets/arunsworkspace/retail-pos-dataset-for-market-basket-analysis) |
| `DS1n2` | Combined EuroMart and POS | |
| `DS3` | dunnhumby The Complete Journey (exploratory only) | [frtgnn/dunnhumby-the-complete-journey](https://www.kaggle.com/datasets/frtgnn/dunnhumby-the-complete-journey) |
| `DS4` | Online Retail II (exploratory only) | [dvaser/online-retail-ii](https://www.kaggle.com/datasets/dvaser/online-retail-ii) |
| `All_DS` | All datasets together (comparison) | | All the sources |

## Workflow Order

The sequence number shows the order of work. The project moves through four stages:

1. **Exploratory data analysis (1 to 3):** Understand each dataset, then visualise the graph structure.
2. **Models on EuroMart and combined data (4 to 7):** Apply GCN, GraphSAGE, GAT and LightGCN to Dataset 1 and the combined dataset.
3. **Models on POS (8 to 9):** Apply GCN and GAT to Dataset 2.
4. **Other datasets, exploratory only (10 to 12):** EDA and comparison for two further datasets. These were explored but not pursued in the main project.

## File List and Contributors

| # | File Name | Stage | Description | Owner |
|---|-----------|-------|-------------|-------|
| 1 | `EDA_DS1_EuroMart` | EDA | Exploratory analysis of EuroMart | Yi Xuan |
| 2 | `EDA_DS2_POS` | EDA | Exploratory analysis of POS | Hansen |
| 3 | `EDA_DS1n2_Graph Visualisation` | EDA | Graph visualisation of the datasets | Johan |
| 4 | `GCN_DS1_EuroMart` | Models | GCN on EuroMart | Yi Xuan |
| 5 | `GraphSAGE_DS1n2_EuroMart_POS` | Models | GraphSAGE on combined data | Johan |
| 6 | `GAT_DS1_EuroMart` | Models | GAT on EuroMart | Yi Xuan |
| 7 | `LightGCN_DS1n2_EuroMart_POS` | Models | LightGCN on combined data | Nicholas |
| 8 | `GCN_DS2_POS` | Models | GCN on POS | Hansen |
| 9 | `GAT_DS2_POS` | Models | GAT on POS | Yi Xuan |
| 10 | `Other_EDA_DS3_dunnhumby` | Other datasets (exploratory) | Exploratory analysis of dunnhumby | Nicholas |
| 11 | `Other_EDA_DS4_OnlineRetail2` | Other datasets (exploratory) | Exploratory analysis of Online Retail II | Nicholas |
| 12 | `Other_LightGCN_All_DS_Comparison` | Other datasets (exploratory) | LightGCN comparison across all datasets | Nicholas |

## Contributions by Person

- **Yi Xuan:** EDA on EuroMart (1), GCN on EuroMart (4), GAT on EuroMart (6), GAT on POS (9)
- **Hansen:** EDA on POS (2), GCN on POS (8)
- **Johan:** Graph visualisation (3), GraphSAGE (5)
- **Nicholas:** LightGCN (7), exploratory work on dunnhumby and Online Retail II (10, 11), LightGCN comparison across datasets (12)

## Notes

Follow the files in order to understand how the four graph models (GCN, GraphSAGE, GAT and LightGCN) are evaluated against the two main datasets (EuroMart and POS). Files prefixed `Other_` are exploratory work on two further datasets that the team decided not to pursue.
