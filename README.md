# Project Files: Contributions and Workflow

This README explains the files in the project, the order they follow, and who contributed each part.

**Important:** Every file is named with its sequence number as a prefix, exactly as listed in the table below (for example, `1_EDA_DS1_EuroMart`). Use the exact name when uploading to Git.

## Naming Convention

```
<Sequence>_<Analysis or Model>_<Dataset>_<Variant>
```

Dataset codes:

| Code | Dataset |
|------|---------|
| `DS1` | EuroMart (Dataset 1) |
| `DS2` | POS (Dataset 2) |
| `DS1n2` | Combined EuroMart and POS |

## Workflow Order

The sequence number shows the order of work. The project moves through three stages:

1. **Exploratory data analysis (1 to 3):** Understand each dataset, then visualise the graph structure.
2. **Models on EuroMart (4 to 7):** Apply the graph models to Dataset 1, followed by the combined model.
3. **Models on POS (8 to 9):** Apply the remaining models to Dataset 2.

## File List and Contributors

| # | File Name | Stage | Description | Contributor |
|---|-----------|-------|-------------|-------------|
| 1 | `1_EDA_DS1_EuroMart` | EDA | Exploratory analysis of EuroMart | Yi Xuan |
| 2 | `2_EDA_DS2_POS` | EDA | Exploratory analysis of POS | Hansen |
| 3 | `3_EDA_DS1n2_Graph Visualisation` | EDA | Graph visualisation of the dataset | Johan |
| 4 | `4_GCN_DS1_EuroMart` | Models | GCN on EuroMart | Yi Xuan |
| 5 | `5_GraphSAGE_DS1n2_EuroMart_POS` | Models | GraphSAGE on combined data | Johan |
| 6 | `6_GAT_DS1_EuroMart` | Models | GAT on EuroMart | Yi Xuan |
| 7 | `7_GraphLight_DS1n2_EuroMart_POS` | Models | GraphLight on combined data | Nicholas |
| 8 | `8_GCN_DS2_POS` | Models | GCN on POS | Hansen |
| 9 | `9_GAT_DS2_POS` | Models | GAT on POS | Yi Xuan |

## Contributions by Person

- **Yi Xuan:** EDA on EuroMart (1), GCN on EuroMart (4), GAT on EuroMart (6), GAT on POS (9)
- **Hansen:** EDA on POS (2), GCN on POS (8)
- **Johan:** Graph visualisation (3), GraphSAGE (5)
- **Nicholas:** GraphLight (7)

## Notes
Follow the files in order to understand how the 4 GCN models are evaluated against the 2 datasets. 
