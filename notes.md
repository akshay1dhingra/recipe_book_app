Italian Recipe Book - Rails
Cocktail Recipe Book - Rails

Models:
User - Has many Recipes/ has many Ingredients through Recipes

Recipe - Belongs to User/ Has many Quantities/ Has many Ingredients through Quantities 

Ingredients -  Has many Users/ Has many Recipes through Quantities/ Has many Quantities 

Quantities (Join Table) - Belongs to Recipe/ Belongs to Ingredients

Many:Many between users and ingredients

Draw.io