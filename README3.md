# Day 3 - API Integration Report: Shopping Clothing Website  

**Prepared by:** Laiba Adnan  
**Roll Number:** 00468361  

---

## 1. Introduction  
This report outlines the progress made on Day 3, focusing on API integration, schema updates, and data migration for the shopping clothing website. The aim was to connect the backend with the frontend, refine the database schema for better functionality, and successfully migrate data into Sanity CMS.  

---

## 2. API Integration Process  

### Steps Taken:  

1. **Connecting APIs**  
   - Built REST APIs to fetch product data, including names, prices, and images.  
   - Added endpoints to handle user actions, such as adding products to the cart.  

2. **Frontend Integration**  
   - Used `Axios` to fetch data from APIs and display it dynamically in the frontend.  
   - Integrated animations using the `Framer Motion` library to make product displays interactive.  

3. **Sanity CMS Updates**  
   - Successfully fetched product data from the API and stored it in **Sanity CMS**.  
   - Displayed data using GROQ queries, dynamically rendering a responsive product grid, including:  
     - Product name  
     - Price  
     - Product image  

---

## 3. Schema Adjustments  

The schema was updated to support enhanced search functionality for better user experience.  

### Changes Made:  
- **Search Field:** Added a string-based search mechanism to filter products dynamically by name or related terms.  
- **Streamlining:** Removed irrelevant fields to optimize the schema for the clothing platform's specific needs.  

---

### Screenshots  
**Frontend Display**  
![Product Grid](/public/Screenshot%20(55).png)  

**Search Functionality**  
![Search Feature](/public/Screenshot%20(56).png)  

**Sanity CMS Data**  
![sanity types](/public/Screenshot%20(57).png)  

**Migration Files**
![migration file](/public/Screenshot%20(58).png)
