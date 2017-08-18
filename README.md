Recipe -
- recipe should be a valid object
- name should be present
- description should be present
- chef_id should be present **
- maximum lengthe for name & description, maybe a minimum for description


Chef - 
- chefname should be present
- email should be present
- size restriction on chefname and email
- email address should be in valid format
- email should be unique, case sensitive

17thAug17
Finished L82.
Proceed to L83



Prefix      Verb      URI Pattern         Controller#Action
recipes     GET       /recipes            recipes#index       #displays all the recipes
new_recipe  GET       /recipes/new        recipes#new         #displays a form
            POST      /recipes            recipes#create      #submits the info from the form
edit_recipe GET       /recipes/:id/edit   recipes#edit        #displays an edit form
            PATCH     /recipes/:id/       recipes#update      #submits the edited form info
recipe      GET       /recipes/:id        recipes#show        #displays a particular recipe
            DELETE    /recipes/:id        recipes#destroy     #deletes a particular recipe