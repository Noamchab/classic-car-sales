# From Machine to Masterpiece : Artification and Price Formation of Classic Cars at Auctions (2025) 

### Noam Chabot & Léna Rebours - Université PSL

## Repository purpose

This repository provides the datasets used in the research article. It does not include analysis scripts or regression code.

## Overview

This repository accompanies the research article *From Machine to Masterpiece: Artification and Price Formation of Classic Cars at Auctions (2025)*. The project investigates how industrial automobiles become cultural luxury assets and how auction prices are formed through institutional mechanisms, narrative qualification, and market contexts.
The study combines historical archival research on early automobile auctions, institutional and qualitative analysis of the contemporary auction market, combined with hedonic price regressions
Key findings include positive price associations with pedigree, rarity, and narrative qualification; statistically significant brand fixed effects (e.g., premium brands); contextual event effects associated with specific sale environments; and evidence that auction prices reflect institutional and narrative framing rather than intrinsic value alone.

## Data

This study relies on two datasets. 

### Early Public Automobile Auction Sales in France (1898–1930)

First, a dataset containing early public auctions of automobiles and automobile-related goods in France during the late nineteenth and early twentieth centuries. It contains 41 auction lots drawn from three public sales held in 1898, 1922, and 1930. The data were collected from official auction records (procès-verbaux) consulted at the Paris Archives. The sales were identified through a systematic review of La Gazette Drouot beginning with its first publication in 1891, which allowed the identification of one of the earliest documented public automobile auctions in France (December 1898). Two additional sales from 1922 and 1930 were selected to complement this early observation. For each lot, the dataset records the sale date, a textual description of the item, the sale price when available, and the identities of the auctioneer, buyer, and seller as reported in the archival documents. The lots include automobiles, trucks, and various types of automotive equipment, such as spare parts and accessories.


### Classic Car Sales, Primarily in France (2025)

Secondly, a dataset containing information on collectible automobiles sold at public auctions in 2025, primarily in France. It includes more than 600 auction lots and was constructed as part of an academic research project in Art Economics. The dataset focuses on vehicles manufactured or first registered before 1995, in order to capture a coherent segment of the collectible car market. The data were collected manually from auction catalogues and published results between September and December 2025. Auctions were identified through La Gazette Drouot and through targeted consultation of the websites and catalogues of major auction houses active in the collectible automobile market, including Christie’s, Sotheby’s, Bonhams, Phillips, and Artcurial. The dataset is not intended to be exhaustive; auctions with insufficient information, particularly missing hammer prices or estimates, were excluded to ensure data quality. For each vehicle, the dataset records core auction and vehicle characteristics, including the year of manufacture, brand, textual lot description, low and high pre-sale estimates, and, when available, the hammer price. Additional metadata include the auction house, sale name, auction dates, lot number, and information on buyer’s fees. When possible, final prices including buyer’s premiums were computed, and all prices are reported in both euros and U.S. dollars. In addition to manual annotation, a large language model was used to extract structured variables from the textual lot descriptions using a standardized, rule-based prompt. This process was limited to information explicitly stated in the catalogues and allowed the extraction of supplementary variables related to vehicle characteristics (e.g., color, engine configuration), administrative information (e.g., registration documents, chassis numbers), and, when mentioned, elements of provenance or condition.

## LLM data 

A large language model (Qwen2.5-7B) was used to extract structured variables from auction lot descriptions. Some extracted features were subsequently excluded when the underlying textual information was insufficiently precise. For transparency, the original standardized prompt including all initially defined variables is reproduced in the appendice part of the paper.


## Data Source Notice

Auction catalogues and sale results remain the intellectual property of the respective auction houses and publishers. This repository provides structured research data compiled for academic purposes only.


## Authors

Noam Chabot - Université PSL - noam.chabot@psl.eu & Léna Rebours - Université PSL - lena.rebours@psl.eu

## License

This dataset is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the LICENSE file for details.
