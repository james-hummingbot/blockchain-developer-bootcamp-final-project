# blockchain-developer-bootcamp-final-project

Contract and web application for user authentication and read access.

The main idea is that a media provider (movie, book, comic, sports event) wants 
to provide user access in a publicly verifiable way. The users can purchase 
access via the blockchain, then users can get access with an off chain signature.

The frontend acts as a gateway between the provider and the user. The provider can
create an event and access to their product and the user can view it via the gateway.

The contract is a token or NFT contract that allows providers to mint and sell tokens
which give access to events. Ideally the contract provides customization to the media provider
like finite or inifite users allowed for the event, event time restrictions, transferability 
restrictions, secondary market, etc., but that would increase the scope of the project.

- Token or NFT contract that allows media providers to grant access to their media.
- Frontend for media providers (upload events and media) and users (purchase access and execute access rights).
