# proto
Shared Service Proto Files


## Naming

### Messages
- ***Request
- ***Response

### Calls

#### Retrieve

	Retrieve{SubType} - Get a single item e.g. Retrieve / RetrieveBar
	
	Get{Type/SubType}s - Get a list of items e.g. GetFoos / GetBars

#### Mutate
	
	Create{SubType} - Create a new item, unlinked e.g. Create / CreateBar
	
	Add{SubType} - Link a new sub type to the parent type e.g. AddBar
	
	Set{SubType} - Link a new sub type to the parent type, where the sub types create will be unique e.g. SetBar
	
	Link{SubType} - Link an existing sub type to the parent e.g. LinkBar
	
	Unlink{SubType} - Remove the link between two items
	
	Remove{SubType} - Remove an item e.g. Remove / RemoveBar
	
#### Action

	Enable{SubType} - Enable an item e.g. Enable / EnableBar
	
	Disable{SubType} - Disable an Item e.g. Disable / DisableBar
	
	{Action}{SubType} - Perform an action e.g. Invite / SuspendBar
