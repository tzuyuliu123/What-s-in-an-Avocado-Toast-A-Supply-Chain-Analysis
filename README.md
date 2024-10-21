# **What-s-in-an-Avocado-Toast-A-Supply-Chain-Analysis**

Using dataset from Open Food Facts, analyse the supply chain of three key ingredients needed for making avocado toast in the United Kingdom: avocados, olive oil, and sourdough.

**The goal is to determine the most common country of origin for each of these ingredients, based on available food data.**

The relevant columns to keep are:
1. 'code': Unique identifier for each product.
2. 'lc': Language code for the data.
3. 'productnameen': The English product name.
4. 'quantity': Quantity of the product.
5. 'servingsize': The size of each serving.
6. 'packagingtags': Tags related to packaging types.
7. 'brands': The brands associated with the product.
8. 'brandstags': Tags related to the brands.
9. 'categoriestags': Tags related to product categories.
10. 'labelstags': Tags related to the product labels.
11. 'countries': Country where the product is sold.
12. 'countriestags': Tags related to countries.
13. 'origins': Country of origin.
14. 'origins_tags': Tags related to the country of origin.

## **Code Workflow**
1. **Filter and subset the dataset** for each of the three ingredients.
2. **Clean the data** by ensuring country names contains only letters and spaces.
3. **Find the most common country of origin** for each ingredient and store them in the respective variables. 
