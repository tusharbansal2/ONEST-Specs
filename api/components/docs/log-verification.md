# [Draft] Test Scenarios WO - 2.0

> Logs to be submitted for the applicable flows below by creating a Pull Request (PR).

---

## Provider Setup

### Provider NP Setup
Configure two providers (each with 2 locations) and include:

- Supported fulfillment options: **[TBD]**
- Required credentials

### Category-Specific Catalog Setup
Same configuration as general setup, but with the following customizations:

- Job-related customizations:
  - Base applications
  - Variants
  - Application availability
  - Custom menu

- Example Scenarios:
  1. Lead Application (free or priced)
  2. Verified Leads
  3. Recruitment Fees

---

## Flow Details

---

### Flow 1: Catalog Discovery

1. `Search`  
2. `On_Search`  
3. `Search_Inc`  
4. `On_Search_Inc`  

---

### Flow 2: Application Lifecycle – Offer Accepted

1. `Search`  
2. `On_Search`  
3. `Select`  
4. `On_Select`  
5. `Init`  
6. `On_Init`  
7. `Confirm`  
8. `On_Confirm` – **Application Submitted**  
9. `On_Status` – **Application Accepted**  
10. `On_Status` – **Assessment In Progress**  
11. `On_Update` – **Offer Extended**  
12. `Update` – **Offer Accepted**  
13. `On_Update` – **Offer Accepted**  

---

### Flow 3: Application Lifecycle – Application Rejected

1. `Search`  
2. `On_Search`  
3. `Select`  
4. `On_Select`  
5. `Init`  
6. `On_Init`  
7. `Confirm`  
8. `On_Confirm` – **Application Submitted**  
9. `On_Status` – **Application Rejected**

---

## References

For detailed specifications and payload structures, refer to the  
[Official Documentation Sheet](https://docs.google.com/spreadsheets/d/118ShHWOE5Lx3Wh_35VLadqltMjp_AkCIZW0prP9xbNY/edit?gid=0#gid=0)
