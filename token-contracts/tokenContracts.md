# Token Contracts


## Carbon Credit Taxonomy

***CARBON CREDIT LIFECYCLE***

- A **carbon project** is following a predefined **methodology** withe-listed by a specific **standard body** to generate **carbon credits.** A credit always represents 1 tCO2e.
- After the **validation and verification** of the project monitoring by an independent **VVB** *(validation & verification body ?�white-listed by the standard body)* the project is issued a **batch of carbon credits** by the **standard body** for this specific **monitoring period** — called a **vintage**. Thus, a **project** will have multiple **vintages** which represent different **monitoring periods**.
- The **issuance** of that **vintage's credits** to the project developer is recorded on the **public registry** maintained by the **standard body** with a unique [**serial number**](https://registry.verra.org/pdf/VCU%20Serial%20Number%20Help%20Format.pdf).
- These credits can now be **traded** between project developer and other **intermediate market actors** *(wholesalers, brokers, resellers, retailers)* without changing their **status**, i.e. still being `issued`
- When an **end-customer** purchases **credits** to **claim** the environmental benefit for them, the credits they bought change **status** to `retired` *(which is often done in their name by the party who sold the credits to them)*. `retired` credits can never be sold again.

***CARBON CREDIT PROPERTIES***

- A project can have multiple certifications, e.g. [Verra](https://verra.org/verra-standards-and-programs/) + [CCB](https://verra.org/project/ccb-program/) *(climate, community & biodiversity)*
- A project can have multiple vintages, e.g. 2019, 2020 ...
- A vintage can be split into multiple batches of credits, each held by different actors *(accounts in the given registry)*
- All credits within a vintage are identical, but each credit *(= each tCO2e)* has a unique serial number

***TOKEN PROPERTIES***

- A token should be tied as closely as possible to the underlying real-world asset, i.e. the carbon credit. This means that there has to be a direct linkage between the standard's public registry *(e.g. [Verra](https://registry.verra.org/app/search/VCS) or [Gold Standard](https://registry.goldstandard.org/))* and the issuance of tokens on-chain.
- Tokens representing credits from the same project and the same vintage should be fungible so that it's possible to retire only a fraction of a tonne of carbon.
- The token holder should be able to set a price per tonne of carbon at which the token can be sold and retired.
- Tokens should be composable as to create higher-order products, e.g. have a project-level token
