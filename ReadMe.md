# Task №1
| src/01. ArithmeticOperators.sol:Addition contract |                 |       |        |       |         |
|---------------------------------------------------|-----------------|-------|--------|-------|---------|
| Deployment Cost                                   | Deployment Size |       |        |       |         |
| 118979                                            | 235             |       |        |       |         |
| Function Name                                     | min             | avg   | median | max   | # calls |
| addition                                          | 26505           | 26505 | 26505  | 26505 | 1       |


| src/01. ArithmeticOperators.sol:AdditionOptimized contract |                 |       |        |       |         |
|------------------------------------------------------------|-----------------|-------|--------|-------|---------|
| Deployment Cost                                            | Deployment Size |       |        |       |         |
| 107327                                                     | 181             |       |        |       |         |
| Function Name                                              | min             | avg   | median | max   | # calls |
| addition                                                   | 26409           | 26409 | 26409  | 26409 | 1       |


| src/01. ArithmeticOperators.sol:Division contract |                 |     |        |     |         |
|---------------------------------------------------|-----------------|-----|--------|-----|---------|
| Deployment Cost                                   | Deployment Size |     |        |     |         |
| 105659                                            | 272             |     |        |     |         |
| Function Name                                     | min             | avg | median | max | # calls |
| divisionBy128                                     | 317             | 317 | 317    | 317 | 1       |
| divisionBy2                                       | 339             | 339 | 339    | 339 | 1       |


| src/01. ArithmeticOperators.sol:DivisionOptimized contract |                 |     |        |     |         |
|------------------------------------------------------------|-----------------|-----|--------|-----|---------|
| Deployment Cost                                            | Deployment Size |     |        |     |         |
| 93391                                                      | 214             |     |        |     |         |
| Function Name                                              | min             | avg | median | max | # calls |
| divisionBy128                                              | 241             | 241 | 241    | 241 | 1       |
| divisionBy2                                                | 263             | 263 | 263    | 263 | 1       |


| src/01. ArithmeticOperators.sol:Subtraction contract |                 |       |        |       |         |
|------------------------------------------------------|-----------------|-------|--------|-------|---------|
| Deployment Cost                                      | Deployment Size |       |        |       |         |
| 118979                                               | 235             |       |        |       |         |
| Function Name                                        | min             | avg   | median | max   | # calls |
| subtraction                                          | 26505           | 26505 | 26505  | 26505 | 1       |


| src/01. ArithmeticOperators.sol:SubtractionOptimized contract |                 |       |        |       |         |
|---------------------------------------------------------------|-----------------|-------|--------|-------|---------|
| Deployment Cost                                               | Deployment Size |       |        |       |         |
| 107543                                                        | 182             |       |        |       |         |
| Function Name                                                 | min             | avg   | median | max   | # calls |
| subtraction                                                   | 26412           | 26412 | 26412  | 26412 | 1       |

# Task №2
| src/02. ArrayLength.sol:ArrayLength contract |                 |      |        |      |         |
|----------------------------------------------|-----------------|------|--------|------|---------|
| Deployment Cost                              | Deployment Size |      |        |      |         |
| 362090                                       | 487             |      |        |      |         |
| Function Name                                | min             | avg  | median | max  | # calls |
| callFor                                      | 3694            | 3694 | 3694   | 3694 | 1       |


| src/02. ArrayLength.sol:ArrayLengthOptimized contract |                 |      |        |      |         |     
|-------------------------------------------------------|-----------------|------|--------|------|---------|     
| Deployment Cost                                       | Deployment Size |      |        |      |         |     
| 350023                                                | 430             |      |        |      |         |     
| Function Name                                         | min             | avg  | median | max  | # calls |     
| callFor                                               | 2477            | 2477 | 2477   | 2477 | 1       | 

# Task №3

| src/03. CalldataMemory.sol:CalldataMemory contract |                 |      |        |      |         |        
|----------------------------------------------------|-----------------|------|--------|------|---------|        
| Deployment Cost                                    | Deployment Size |      |        |      |         |        
| 160323                                             | 527             |      |        |      |         |        
| Function Name                                      | min             | avg  | median | max  | # calls |        
| add                                                | 3186            | 3186 | 3186   | 3186 | 1       |        

| src/03. CalldataMemory.sol:CalldataMemoryOptimized contract |                 |      |        |      |         |
|-------------------------------------------------------------|-----------------|------|--------|------|---------|
| Deployment Cost                                             | Deployment Size |      |        |      |         |
| 151041                                                      | 484             |      |        |      |         |
| Function Name                                               | min             | avg  | median | max  | # calls |
| add                                                         | 2596            | 2596 | 2596   | 2596 | 1       |

# Task №4

| src/04. Loops.sol:Loops contract |                 |      |        |      |         |
|----------------------------------|-----------------|------|--------|------|---------|
| Deployment Cost                  | Deployment Size |      |        |      |         |
| 127197                           | 374             |      |        |      |         |
| Function Name                    | min             | avg  | median | max  | # calls |
| loopDoWhile                      | 1946            | 1946 | 1946   | 1946 | 1       |
| loopFor                          | 2641            | 2641 | 2641   | 2641 | 1       |
| loopWhile                        | 2069            | 2069 | 2069   | 2069 | 1       |


| src/04. Loops.sol:LoopsOptimized contract |                 |      |        |      |         |
|-------------------------------------------|-----------------|------|--------|------|---------|
| Deployment Cost                           | Deployment Size |      |        |      |         |
| 98989                                     | 240             |      |        |      |         |
| Function Name                             | min             | avg  | median | max  | # calls |
| loopDoWhile                               | 586             | 586  | 586    | 586  | 1       |
| loopFor                                   | 1281            | 1281 | 1281   | 1281 | 1       |
| loopWhile                                 | 709             | 709  | 709    | 709  | 1       |

# Task №5

| src/05. PackVariables.sol:PackVariables contract |                 |        |        |        |         |
|--------------------------------------------------|-----------------|--------|--------|--------|---------|
| Deployment Cost                                  | Deployment Size |        |        |        |         |
| 178533                                           | 611             |        |        |        |         |
| Function Name                                    | min             | avg    | median | max    | # calls |
| setValues                                        | 150861          | 150861 | 150861 | 150861 | 1       |


| src/05. PackVariables.sol:PackVariablesOptimized contract |                 |        |        |        |         |
|-----------------------------------------------------------|-----------------|--------|--------|--------|---------|
| Deployment Cost                                           | Deployment Size |        |        |        |         |
| 182613                                                    | 630             |        |        |        |         |
| Function Name                                             | min             | avg    | median | max    | # calls |
| setValues                                                 | 128733          | 128733 | 128733 | 128733 | 1       |

# Task №6

| src/06. Errors.sol:Errors contract |                 |      |        |      |         |
|------------------------------------|-----------------|------|--------|------|---------|
| Deployment Cost                    | Deployment Size |      |        |      |         |
| 119420                             | 249             |      |        |      |         |
| Function Name                      | min             | avg  | median | max  | # calls |
| call                               | 2357            | 2357 | 2357   | 2357 | 1       |


| src/06. Errors.sol:ErrorsOptimized contract |                 |      |        |      |         |
|---------------------------------------------|-----------------|------|--------|------|---------|
| Deployment Cost                             | Deployment Size |      |        |      |         |
| 108452                                      | 198             |      |        |      |         |
| Function Name                               | min             | avg  | median | max  | # calls |
| call                                        | 2303            | 2303 | 2303   | 2303 | 1       |

# Task №7

| src/07. Swap.sol:Swap contract |                 |     |        |     |         |
|--------------------------------|-----------------|-----|--------|-----|---------|
| Deployment Cost                | Deployment Size |     |        |     |         |
| 111969                         | 302             |     |        |     |         |
| Function Name                  | min             | avg | median | max | # calls |
| swap                           | 547             | 547 | 547    | 547 | 1       |


| src/07. Swap.sol:SwapOptimized contract |                 |     |        |     |         |
|-----------------------------------------|-----------------|-----|--------|-----|---------|
| Deployment Cost                         | Deployment Size |     |        |     |         |
| 90367                                   | 200             |     |        |     |         |
| Function Name                           | min             | avg | median | max | # calls |
| swap                                    | 282             | 282 | 282    | 282 | 1       |

# Task №8

| src/08. ArrayType.sol:ArrayType contract |                 |         |         |         |         |
|------------------------------------------|-----------------|---------|---------|---------|---------|
| Deployment Cost                          | Deployment Size |         |         |         |         |
| 91651                                    | 206             |         |         |         |         |
| Function Name                            | min             | avg     | median  | max     | # calls |
| initArray                                | 4499618         | 4499618 | 4499618 | 4499618 | 1       |


| src/08. ArrayType.sol:ArrayTypeOptimized contract |                 |         |         |         |         |
|---------------------------------------------------|-----------------|---------|---------|---------|---------|
| Deployment Cost                                   | Deployment Size |         |         |         |         |
| 89899                                             | 198             |         |         |         |         |
| Function Name                                     | min             | avg     | median  | max     | # calls |
| initArray                                         | 4436918         | 4436918 | 4436918 | 4436918 | 1       |

# Task №9

| src/09. NestedIf.sol:NestedIf contract |                 |     |        |     |         |
|----------------------------------------|-----------------|-----|--------|-----|---------|
| Deployment Cost                        | Deployment Size |     |        |     |         |
| 97897                                  | 235             |     |        |     |         |
| Function Name                          | min             | avg | median | max | # calls |
| call                                   | 346             | 353 | 356    | 357 | 4       |


| src/09. NestedIf.sol:NestedIfOptimized contract |                 |     |        |     |         |
|-------------------------------------------------|-----------------|-----|--------|-----|---------|
| Deployment Cost                                 | Deployment Size |     |        |     |         |
| 94891                                           | 221             |     |        |     |         |
| Function Name                                   | min             | avg | median | max | # calls |
| call                                            | 326             | 334 | 337    | 337 | 4       |


# Task №10

| src/10. MultiSigWallet.sol:MultiSigWallet contract |                 |       |        |        |         |
|----------------------------------------------------|-----------------|-------|--------|--------|---------|
| Deployment Cost                                    | Deployment Size |       |        |        |         |
| 886258                                             | 4222            |       |        |        |         |
| Function Name                                      | min             | avg   | median | max    | # calls |
| confirmTransaction                                 | 31243           | 86628 | 77008  | 124410 | 8       |
| executeTransaction                                 | 31287           | 31287 | 31287  | 31287  | 1       |
| getConfirmations                                   | 12041           | 12041 | 12041  | 12041  | 1       |
| getTransactionCount                                | 326             | 326   | 326    | 326    | 1       |
| owners                                             | 2604            | 3270  | 2604   | 4604   | 3       |
| receive                                            | 0               | 0     | 0      | 0      | 8       |
| required                                           | 2361            | 2361  | 2361   | 2361   | 1       |
| submitTransaction                                  | 31476           | 92750 | 102951 | 103023 | 7       |
| transactions                                       | 1299            | 1299  | 1299   | 1299   | 4       |


| src/10. MultiSigWallet.sol:MultiSigWalletOptimized contract |                 |       |        |        |         |
|-------------------------------------------------------------|-----------------|-------|--------|--------|---------|
| Deployment Cost                                             | Deployment Size |       |        |        |         |
| 944171                                                      | 4258            |       |        |        |         |
| Function Name                                               | min             | avg   | median | max    | # calls |
| confirmTransaction                                          | 23782           | 82404 | 74668  | 118754 | 8       |
| executeTransaction                                          | 23826           | 23826 | 23826  | 23826  | 1       |
| getConfirmations                                            | 15985           | 15985 | 15985  | 15985  | 1       |
| getTransactionCount                                         | 326             | 326   | 326    | 326    | 1       |
| owners                                                      | 2604            | 3270  | 2604   | 4604   | 3       |
| receive                                                     | 0               | 0     | 0      | 0      | 8       |
| required                                                    | 2361            | 2361  | 2361   | 2361   | 1       |
| submitTransaction                                           | 24015           | 89679 | 100611 | 100683 | 7       |
| transactions                                                | 1299            | 1299  | 1299   | 1299   | 4       |
