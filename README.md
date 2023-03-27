# KantoxEvaluation

The following test cases were created considering the following Assumptions:

- Dont know if the cashier system will be operate by the operator or by the user as a self service
- On the exercice its not specified if the rule will be automatically selected, or if the user can select which want to apply, maybe if you can have more than one rule applying in a single purshase process. (Im assuming that the rule of the client should be manually selected before the purchase process, because no logic was described to determine when the system will apply ReducedPriceRule or FractionPriceRule automatically).
- The TC's were focused on the business rules because in the long term will be easy to mantain due to should have less changes that product yml file.
- There are 2 sheets with test cases: the first based on the special rules and the 2nd based on the products file.
- Finally keep in mind that Tc's were created in a scalable in onder to apply same logic to each product.
