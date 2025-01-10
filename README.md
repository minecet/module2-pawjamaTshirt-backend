# Description
The backend is a json-server, using the Ironback CLI. 
# API Routes
- GET / renders to the main custom design Tshirt template page
- GET, POST, DELETE /basket  renders to the shopping basket, in which the completed and added tshirt designs total and each price breakdown is shown to the user
- POST, PUT, DELETE /totalPrice/1 holds and updates the total basket amount
- POST and DELETE basket/:productid renders each custom designed tshirt product with the assigned unique id
- GET /Dogs renders the dog species, whose image icons are held in the frontend assets
- GET /Cats renders the cat species, whose image icons are held in the frontend assets
<br>
- Netlify
[Netlify](https://graceful-florentine-2d83e8.netlify.app/) 
<br>
- Render deployment
[Render]([https://module2-pawjamatshirt-backend.onrender.com]) 
