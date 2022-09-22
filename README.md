# clean-coding



## Method naming practices  

1. Use find\<Noun\> when implementing method that does query for the user and returns results based upon some query.  
For example, when catalog page, when we are getting products based upon some filters, we could use findProducts as method name.  

2. Use fetch\<Noun\> when implementing method that fetches the related data based upon some specified identifiers in background.
For example, when fetching related information for products in order, if we are doing a separate API call for getting product information method can have name fetchProducts. Here method will be provided identifier based upon which it will fetch records.

3. Use get\<Noun\> when implementing method that fetches data for displaying purpose.  
For example, getCategories method could get all the categories that could be used for header of any ecommerce website
