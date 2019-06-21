"# AlbedoFrontend" 

!-----------------------------------------------------------------------------!

How to create a new project in vue.js ?

        vue create <project_name>
        
// Select default settings

How to set up dependencies for Bootstrap-Vue ?

Reference : https://bootstrap-vue.js.org/docs
    
    npm i vue bootstrap-vue bootstrap

!------------------------------------------------------------------------------!

In main.js do the following additions :

import Vue from 'vue'

import BootstrapVue from 'bootstrap-vue'

import 'bootstrap/dist/css/bootstrap.css'

import 'bootstrap-vue/dist/bootstrap-vue.css'

Vue.use(BootstrapVue)

Bootstrap vue doesn't allow local images . So use this instead by creating a static file

Referemce : https://bootstrap-vue.js.org/docs/reference/images/

<b-img :src="require('../static/book.jpg')"></b-img>

!-------------------------------------------------------------------------------!

GitHub : (The following code is to be referred and all steps aren't to be methodically followed)

git pull (Pull code)

git add . (Add everything that needs to be uploaded)

git commit -m "Lock everything to Load"

git push (Upload everything)

git status

git branch (List of branches)

git branch <name of branch>

git checkout <name of branch> (Switch to branch)

git push origin --delete <name of branch>