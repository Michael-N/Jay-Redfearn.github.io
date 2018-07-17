# Redfearn Phone repair
### Update Pricing 
- To update prices change the text withine the brackets in the file ``` listed_prices.json``` in the ```_data``` folder 
```

//Example

// Add a new Price:

[
  {"model":"iPhone 7 Plus","price":"$95.00"},
  {"model":"iPhone Infinity","price":"$100000000000.00"},
  {"model":"iPhone 8 Plus","price":"$my_new_price_here"}
]
```

### Update Charges & Info
- Here additional info relating too charges is stored. For each line in the list there is a bullet point on the page. Be carefull that the last item does not have a ``` , comma ``` after it!

```
//Example

[
    "I am the first bullet point",
    " Prices are effective as of month day, year",
    "I am the third bullet point"
]
```

### In General
- Most of the things that may need to be frequently changed can be done by editing files from the ```_data``` directory.
