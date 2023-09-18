# KIVTECHS FLOW


```mermaid
graph LR
 subgraph 1A: Main Page
        1A["Main Page"]
    end
    subgraph Sign In
        2A[Sign In]
    end
    subgraph Register
        2B[Register]
    end
    subgraph OAuth
        2C[OAuth]
    end
  subgraph 3A: Catalogue
        3A["Catalogue"]
    end
   subgraph 4A: Product/Item Information
        4A["Product/Item Information"]
    end
    subgraph 4B: Pricing Slabs Based on Users
        4B["Pricing Slabs Based on Users"]
    end
    subgraph 4C: Pay Yearly, Monthly, Quarterly, Discount or Coupon Code
        4C["Pay Yearly, Monthly, Quarterly\nDiscount or Coupon Code"]
    end
    subgraph 4D: Payment Gateway (PG) Confirmation
        4D["Payment Gateway (PG) Confirmation"]
    end
    subgraph 5A: Acknowledgement
        5A["Acknowledgement"]
    end

    1A --> 2A
    1A --> 2B
    1A --> 2C
    2A --> 3A
    2B --> 3A
    2C --> 3A
  3A --> 4A
4A --> 4B
4B --> 4C
4C ---> 4D
4D ---> 5A
   

```
