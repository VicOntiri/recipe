<template>
    <div class="Breakfast">
    <div id="Breakfast">
        <h1>Tea Break Pancake </h1>
        <h2>Time</h2>
        <h3>(Time: 30 minutes)</h3>
        <img alt="pancakes" src="../assets/Pancakes.jpg">
<br>
        <h2>Ingredients</h2>
        2–4 servings
<li>One 2- to 3-pound farm-raised chicken</li>
<li> salt and freshly ground black pepper</li>
<li>2 tsp. minced thyme (optional)</li>
<li>Unsalted butter</li>
<li>Dijon mustard</li>



<h2>Instructions</h2>
<h3>Step 1</h3>
<p>Preheat the oven to 450°F. Rinse the chicken, then dry it very well with paper towels, inside and out. 
    <br> The less it steams, the drier the heat, the better.</p>
    <h3> Step 2</h3>
    <p>Salt and pepper the cavity, then truss the bird. Trussing is not difficult, and if you roast chicken often, 
        it’s a good technique to feel comfortable with. When you truss a bird, the wings and legs stay close to the body; 
        the ends of the drumsticks cover the top of the breast and keep it from drying out. 
        Trussing helps the chicken to cook evenly, and it also makes for a more beautiful roasted bird.</p>
        <h3>Step 3</h3>
        <p>Now, salt the chicken—I like to rain the salt over the bird so that it has a nice uniform coating that will result 
            in a crisp, salty, flavorful skin (about 1 Tbsp.).
             When it’s cooked, you should still be able to make out the salt baked onto the crisp skin. Season to taste with pepper.</p>
             <h3>Step 4</h3>
             <p>Place the chicken breast side up in a sauté pan or roasting pan and, when the oven is up to temperature, put the 
                chicken in the oven. I leave it alone—I don’t baste it, I don’t add butter; you can if you wish, but I feel this 
                creates steam, which I don’t want. Roast it until it’s done, 50 to 60 minutes. Remove it from the oven and add the
                 thyme, if using, to the pan. 
                Baste the chicken with the pan juices and thyme and let it rest for 15 minutes on a cutting board.</p>
                <h3>Step 5</h3>
                <p>Remove the twine. Separate the middle wing joint and eat that immediately. Remove the legs and thighs.
                     I like to take off the backbone and eat one of the oysters, the two succulent morsels of meat embedded here,
                      and give the other to the person I’m cooking with. But I take the chicken butt for myself. I could never
                       understand why my brothers always fought over that triangular tip—until one day I got the crispy, juicy
                        fat myself. These are the cook’s rewards. Cut the breast down the middle and serve it on the bone, with
                         one wing joint still attached to each. The preparation is not meant to be super elegant. Slather the 
                         meat with fresh butter. Serve with mustard on the side and, if you wish, a simple green salad. 
                    You’ll start using a knife and fork, but finish with your fingers, because it’s so good. </p>



  
    </div>
    <div>
        <footer>
        <ul>
        <li2><router-link to="/Breakfast">Chicken</router-link></li2>
        <li2><router-link to="/Breakfast">Fish</router-link></li2>
        </ul>
    </footer>
    </div>
   </div>
    </template>
    <script>
    export default {
    name: 'Breakfast-item',
    data() {
    }
    }
    </script>
    <style scoped="">
    #Breakfast {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
    Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 2rem;
    margin: 2rem;
    border: 1px solid #ddd;
    border-radius: 10px;
    }
    h {
    margin: 0 0 1.5rem 0;
    }
    h2 {
    margin: 0 0 1.5rem 0;
    }
    ul {
  list-style-type: none;
  padding: 0;
}
li2{
  display: inline-block;
  margin: 10px;
}
p{
  text-align: left;
}
    </style>