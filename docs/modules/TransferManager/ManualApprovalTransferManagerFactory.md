# ManualApprovalTransferManagerFactory
[see the source](git+https://github.com/PolymathNetwork/polymath-core/tree/master//Users/satyamagrawal/Repositories/polymath-core_v2/contracts/modules/TransferManager/ManualApprovalTransferManagerFactory.sol)


**Execution cost**: less than 102589 gas

**Deployment cost**: less than 1758400 gas

**Combined cost**: less than 1860989 gas

## Constructor



Params:

1. **_polyAddress** *of type `address`*
2. **_setupCost** *of type `uint256`*
3. **_usageCost** *of type `uint256`*
4. **_subscriptionCost** *of type `uint256`*

## Events
### LogChangeFactorySetupFee(uint256,uint256,address)


**Execution cost**: No bound available


Params:

1. **_oldSetupcost** *of type `uint256`*
2. **_newSetupCost** *of type `uint256`*
3. **_moduleFactory** *of type `address`*

--- 
### LogChangeFactorySubscriptionFee(uint256,uint256,address)


**Execution cost**: No bound available


Params:

1. **_oldSubscriptionCost** *of type `uint256`*
2. **_newMonthlySubscriptionCost** *of type `uint256`*
3. **_moduleFactory** *of type `address`*

--- 
### LogChangeFactoryUsageFee(uint256,uint256,address)


**Execution cost**: No bound available


Params:

1. **_oldUsageCost** *of type `uint256`*
2. **_newUsageCost** *of type `uint256`*
3. **_moduleFactory** *of type `address`*

--- 
### LogGenerateModuleFromFactory(address,bytes32,address,address,uint256)


**Execution cost**: No bound available


Params:

1. **_module** *of type `address`*
2. **_moduleName** *of type `bytes32`*
3. **_moduleFactory** *of type `address`*
4. **_creator** *of type `address`*
5. **_timestamp** *of type `uint256`*

--- 
### OwnershipTransferred(address,address)


**Execution cost**: No bound available


Params:

1. **previousOwner** *of type `address`*
2. **newOwner** *of type `address`*


## Methods
### setupCost()


**Execution cost**: less than 560 gas

**Attributes**: constant



Returns:


1. **output_0** *of type `uint256`*

--- 
### deploy(bytes)
>
> used to launch the Module with the help of factory


**Execution cost**: No bound available


Params:

1. **param_0** *of type `bytes`*

Returns:

> address Contract address of the Module

1. **output_0** *of type `address`*

--- 
### changeFactoryUsageFee(uint256)
>
> used to change the fee of the usage cost


**Execution cost**: less than 22509 gas


Params:

1. **_newUsageCost** *of type `uint256`*

    > new usage cost 



--- 
### changeFactorySetupFee(uint256)
>
> used to change the fee of the setup cost


**Execution cost**: less than 22399 gas


Params:

1. **_newSetupCost** *of type `uint256`*

    > new setup cost 



--- 
### changeFactorySubscriptionFee(uint256)
>
> used to change the fee of the subscription cost


**Execution cost**: less than 22377 gas


Params:

1. **_newSubscriptionCost** *of type `uint256`*

    > new subscription cost 



--- 
### getTags()
>
> Get the tags related to the module factory


**Execution cost**: No bound available

**Attributes**: constant



Returns:


1. **output_0** *of type `bytes32[]`*

--- 
### getDescription()
>
> Get the description of the Module


**Execution cost**: No bound available

**Attributes**: constant



Returns:


1. **output_0** *of type `string`*

--- 
### getInstructions()
>
> Get the Instructions that helped to used the module


**Execution cost**: No bound available

**Attributes**: constant



Returns:


1. **output_0** *of type `string`*

--- 
### getName()
>
> Get the name of the Module


**Execution cost**: less than 250 gas

**Attributes**: constant



Returns:


1. **output_0** *of type `bytes32`*

--- 
### getTitle()
>
> Get the title of the Module


**Execution cost**: No bound available

**Attributes**: constant



Returns:


1. **output_0** *of type `string`*

--- 
### getType()
>
> Type of the Module factory


**Execution cost**: less than 237 gas

**Attributes**: constant



Returns:


1. **output_0** *of type `uint8`*

--- 
### monthlySubscriptionCost()


**Execution cost**: less than 406 gas

**Attributes**: constant



Returns:


1. **output_0** *of type `uint256`*

--- 
### owner()


**Execution cost**: less than 735 gas

**Attributes**: constant



Returns:


1. **output_0** *of type `address`*

--- 
### polyToken()


**Execution cost**: less than 691 gas

**Attributes**: constant



Returns:


1. **output_0** *of type `address`*

--- 
### transferOwnership(address)
>
> Allows the current owner to transfer control of the contract to a newOwner.


**Execution cost**: less than 23039 gas


Params:

1. **newOwner** *of type `address`*

    > The address to transfer ownership to.



--- 
### usageCost()


**Execution cost**: less than 648 gas

**Attributes**: constant



Returns:


1. **output_0** *of type `uint256`*

[Back to the top ↑](#manualapprovaltransfermanagerfactory)