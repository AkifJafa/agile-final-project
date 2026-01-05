**As a** product manager
 **I need** the ability to create a product in the catalog  
 **So that** new products can be added to the system  

    ### Details and Assumptions
 * - A product has basic attributes such as name and description
 * - The catalog service is available
 
    ### Acceptance Criteria  
    ```gherkin
 Given the catalog service is running
 When I create a new product
 Then the product should be added to the catalog
 ```    
