# Country-Wise E-Commerce Sales and Supply Chain Analysis

This project uses DataCo Global's public supply chain dataset to explore sales, products, customer segments, country and regional performance, and delivery outcomes.

## Dataset source

The original files are published on [Mendeley Data](https://data.mendeley.com/datasets/8gx2fvg2k6/5). The dataset covers provisioning, production, sales, and commercial distribution. Cite the dataset authors and follow its license and attribution terms when reusing the data.

## Files

- `DataCoSupplyChainDataset.csv` — structured order and supply chain data.
- `DescriptionDataCoSupplyChain.csv` — descriptions of the structured dataset fields.
- `tokenized_access_logs.csv` — clickstream data for analyzing website activity.

The data files are kept in `Raw Datasets/` as received from the source. The clickstream and structured files are separate datasets and should be joined only when a suitable shared key is documented.

## Project questions

- Which countries, markets, and product categories contribute the most sales?
- How do sales and profit vary by customer segment and product category?
- Which shipping modes and regions have the highest late-delivery rates?
- How do website clicks relate to order activity, where identifiers permit a valid join?

## Tools

Python or R can be used for cleaning, analysis, visualizations, and machine learning. The CSVs are large, so use a tool that can handle them comfortably.
