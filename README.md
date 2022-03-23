# Shopping-Cart
 MIT Shopping Cart exercise utilizing Strapi DB. This project focused on manipulating state via React and leveraging data pulled from a strapi DB. I made a few improvements from the instructions provided in class, the one I am most pleased with is how if a user restocks the Products. The product list will increase the count of an existing product OR add a new product to the list if it does not already exist. 

# To try this project out for yourself: 
First download/fork/etc this repo to your own Github. Then run a local server (I used 8080) to host your index and cart.jsx files. Then run the strapi app using the command "npx strapi develop". 

# Future improvements
The UI could be improved, frankly I did not spend too much effort making this look nice and was more focused on manipulating state and pulling data from the strapi DB.
I would also like to not just pull data from the DB but also push the decrement of products to the DB as well when users "check out" 