# Economy

## Resources
Resources are used for generating new planets, powering buildings etc.
Resources can be traded between entities.

Resource origins:

- [mines](#mines)
- [factories](#factories)

### Mines
Some parcels contain certain amount of resource of certain quality.
This resources can be *mined* by building an appropriate building (mine) on the
parcel. Final production of the resource depends on the mine's level.


### Factories
Factories has input and output resources. They transform one set of resources to
other set of resources.

For example:

Input:

- 10 Iron
- 15 Oxygen
- 2 Water

Output:

- 10 Plutonium
- 1 Water

## Initial emission of resources
Initial emission is done via [lottery](http://ethereum.stackexchange.com/a/207).

1. New lottery is created and required bet (Ether) is set.
2. "betting" countdown starts
3. Entities start submitting hashes of their numbers (from certain range) and
   sending their bets (Ether).
4. When "betting" countdown stops, "unhiding" countdown starts.
5. Entities must submit their numbers.
6. When "unhiding" countdown stops, random number is calculated from submitted
   numbers and winner of lottery is picked and recieves randomly generated
   bundle of resources.

## Parcels
Parcels can be traded between entities. On one parcel can be built up to one building.
Buildings built on parcels are connected to parcels, so parcel owner automatically
owns a building which is built on it.

Types of parcels:

- Deposit
- Plain

### Deposit
Deposit parcels contain limited sources of resources.

Attributes of deposit parcel:

- Resource type
- Amount
- Quality (production rate)

### Plain
Plain parcels contain no resources.

## Buildings
TODO

## Blueprints
TODO

## Companies
TODO

## Transactions
