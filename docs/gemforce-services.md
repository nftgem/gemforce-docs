# Gemforce Services

GemForce is expandable using services, which provide both a means to publicise an API internally and externally, and a way to extend the functionality of the application. Services are defined in the `services` directory, and are loaded by the `InitService` during application startup.

## Service Structure

Services are either accessed via static methods if no state is required, or via instance methods if state is required. 

## Service Methods

- `init` - initializes the service
- `start` - starts the service

## Services List

- `AbiService` - handles Ethereum ABI encoding and decoding
- `AttributeService` - handles attribute management for various entities
- `BackupService` - manages data backups and restoration
- `BlockchainService` - provides services related to various blockchains
- `CloudFunctionService` - manages cloud functions and their execution
- `ConfigSettingService` - manages configuration settings for various services
- `ConfigurationService` - deals with application configuration management
- `CrossmintService` - integrate with the Crossmint API
- `DashboardService` - manages application dashboard features and data
- `DataImportService` - imports data from various sources into the application
- `DeploymentArtifactService` - manages deployment artifacts for application deployment
- `DiamondService` - possibly manages diamond-related data and operations, specific to the application domain
- `DirectScaleService` - provides integration with the DirectScale platform
- `DynamicCardAssignmentService` - manages dynamic assignment of metadata to tokens
- `EthersService` - deals with Ethereum-based functionalities and operations
- `EventService` - manages event-related data and operations
- `FleekService` - integrates with the Fleek platform for storage and retrieval
- `ImageMakerService` - creates and processes images for the application
- `ImportExportService` - handles data import and export operations
- `InitService` - initializes and sets up services during application startup
- `LoggerService` - manages application logging and error reporting
- `MultiSaleService` - manages multisales (tokensales) and their related operations
- `ODataService` - provides OData protocol-related services and operations
- `OffchainMetadataService` - manages metadata for off-chain data
- `OffchainService` - handles off-chain data storage and retrieval
- `OrgSettingsService` - manages organization-wide settings in the application
- `ParseService` - provides methods to work with the parse server platform
- `PromptSaleService` - handles prompt sales and their related operations
- `ProjectService` - likely provides services that work on a project
- `RegistrationService` - manages user registration and related operations
- `ReplicateAIService` - interfaces with the Replicate.ai service
- `SchemasService` - deals with data schemas and structure
- `ServerConfigurationService` - manages server-related configurations and settings
- `SmartContractService` - deploys and interacts with smart contracts on a blockchain
- `SVGCompositingService` - deals with SVG image composition and manipulation
- `SyncDeploymentsService` - synchronizes deployment artifacts and changes
- `TaskService` - manages task-related data and operations
- `TokenSaleService` - handles token sales and related operations
- `TokenService` - handles token creation and management
- `TwitterService` - integrates with the Twitter API for various operations
- `UserService` - handles user data and related operations
