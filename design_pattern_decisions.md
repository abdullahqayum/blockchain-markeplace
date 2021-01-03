### Design patterns that are used this project are described below

#### Fail Early Fail Loud:
* We have used *require* instead of if in the following modifier
  1. onlyAdmin.
  2. onlySeller.
  3. onlyBuyer.
  4. listedSeller.
  5. inState to implement State machine Pattern.
  6. ensure no seller can create his own product order in *createOrder* method.
  7. Only buyer can pay for his order *payOrder* method.
  8. Only product owner or seller can withdraw his balance in *withdrawBalance* method.
  

#### State Machine Pattern:

#### Restrictring access:

#### Pull over push pattern:

#### Circuit Breaker Pattern:



