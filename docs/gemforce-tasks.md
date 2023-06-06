# Gemforce Tasks

Gemforce tasks are implemented as Hardhat tasks. They are defined in the `tasks` directory, and are loaded by the `InitService` during application startup. Tasks are called from the command line using the `npx hardhat` command.

## Task Structure

Tasks are defined as follows:

```javascript
task("taskName", "Task description", async (args, hre) => {
  // Task code
});
```

## Tasks List

# Hardhat Tasks

This document provides a summary of various hardhat tasks available for execution and their descriptions.

## Task List

1. **import-schema** - Imports schema of a given Parse table.
2. **add-controller** - Adds a new controller address to the Diamond contract.
3. **export-all-collections** - Exports all Parse collections to JSON format.
4. **set-contract-metadata** - Sets token metadata, used for setting descriptions, names, and other related token information.
5. **get-tokensale-settings** - Retrieves settings for the token sale, such as start and end times, pricing, and limits.
6. **get-collection** - Retrieves a specific collection from the Parse database.
7. **get-token-attribute** - Retrieves an attribute of a token, such as its name or symbol.
8. **upload-file** - Uploads a file to a specified location.
9. **fleek:list-buckets** - Lists all available Fleek buckets.
10. **fleek:list-files** - Lists all files present in a specified Fleek bucket.
11. **fleek:get-file** - Retrieves a specific file from a Fleek bucket.
12. **fleek:upload-file** - Uploads a file to a specified Fleek bucket.
13. **fleek:upload-directory** - Uploads an entire directory to a specified Fleek bucket.
14. **export-collection** - Exports a specific Parse collection to JSON format.
15. **clear-database** - Removes all data from the database.
16. **sync-diamonds** - Synchronizes the diamond factory and the diamond contract, ensuring they are up to date.
17. **export-schema** - Exports the schema of a given Parse table.
18. **get-account-address** - Retrieves the Ethereum account address used for deploying contracts.
19. **set-contract-image** - Sets the image associated with a contract as part of its metadata.
20. **list-all-tasks** - Displays a list of all available hardhat tasks.
21. **list-bitgem-tasks** - Displays a list of all available hardhat tasks specific to Bitgem.
22. **get-elon-token** - Retrieves the contract address for a specified Elon token.
23. **list-elon-symbols** - Lists all symbols associated with Elon tokens.
24. **get-elon-image** - Retrieves the image associated with a specified Elon token.
25. **get-elon-settings** - Retrieves the settings for the Elon token, such as minting and pricing options.
26. **get-elon-supply** - Retrieves the current supply of Elon tokens, including the total number minted and available for sale.
27. **get-elon-metadata** - Retrieves the metadata associated with a specified Elon token, including attributes, image, and description.
28. **get-elon-attributes** - Retrieves the attribute replacements for a specified Elon token.
29. **get-elon-replacements** - Retrieves the attribute replacements for a specified Elon token.
30. **get-elon-price** - Retrieves the current price of an Elon token.
31. **mint-elons** - Mints a specified number of Elon tokens.
32. **mint-elon** - Mints a single Elon token to a specified recipient address.
33. **upload-elonpic** - Uploads an image associated with an Elon token.
34. **import-collection** - Imports a collection of Parse tables from a JSON file.
35. **get-diamond-address** - Retrieves the address of the deployed Diamond contract.
36. **get-token-image** - Retrieves the image associated with a specified token.
37. **export-all-schemas** - Exports the schema of all Parse tables present in the database.
38. **token-uri** - Retrieves the token URI for a specified symbol or all symbols.
39. **assign-token-image** - Associates an image with a specified token as part of its metadata.
40. **purchase** - Executes a purchase of a token from the multisale contract.
41. **multi-purchase** - Executes multiple individual token purchase transactions from the multisale contract (useful for testing mass transactions on the contract).
42. **create-tokensale** - Creates a new token sale using the settings specified in a provided JSON file.
43. **import-schemas** - Imports the schema of multiple Parse tables.
44. **import-schemas-from-file** - Imports the schema of multiple Parse tables from a JSON file.
45. **sync-deployments** - Synchronizes deployed contract ABIs with the Parse database.
46. **import-collections** - Imports collections of Parse tables to the database.
47. **import-collections-from-file** - Imports collections of Parse tables to the database from a JSON file.
48. **is-erc721** - Checks if a specified contract adheres to the ERC721 standard.
49. **send-721** - Transfers an ERC721 token to a specified recipient address.
50. **get-contract-metadata** - Retrieves the metadata associated with a specified contract.
51. **mint-token** - Mints a new token to a specified recipient address.
52. **sync-contract** - Synchronizes the metadata of the multisale contract with the database.
53. **deploy-diamond** - Deploys a new Nextgem Diamond contract.
54. **get-facets** - Retrieves the facets used by a Diamond contract.
55. **get-selector** - Retrieves a selector associated with a specific facet.
56. **add-facets** - Adds a facet and its associated selector(s) to the Diamond contract.
57. **replace-facet** - Replaces a facet and its associated selector(s) in a Diamond contract.
58. **remove-facet** - Removes a facet and its associated selector(s) from a Diamond contract.
59. **list-selectors** - Lists the selectors present in a specific facet.
60. **do-facets** - Executes a specific facet operation on the Diamond contract.
61. **upload-token-image** - Uploads an image to be associated with a token.
62. **set-token-svg** - Associates an SVG image with a token.
63. **get-collections** - Retrieves a list of collections stored in the Parse database.
64. **contract-uri** - Retrieves the contract URI for a specified symbol or all symbols.
65. **export-schemas** - Exports the schema of a specified Parse table.
