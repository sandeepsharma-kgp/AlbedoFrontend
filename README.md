"# AlbedoFrontend" 

How to create a new project in vue.js

        vue create <project_name>
        
// Select default settings

How to set up dependencies for Bootstrap-Vue

Reference : https://bootstrap-vue.js.org/docs
    
    npm i vue bootstrap-vue bootstrap

In main.js do the following additions :

import Vue from 'vue'

import BootstrapVue from 'bootstrap-vue'

import 'bootstrap/dist/css/bootstrap.css'

import 'bootstrap-vue/dist/bootstrap-vue.css'

Vue.use(BootstrapVue)


GitHub : 

git pull (Pull code)

git add . (Add everything that needs to be uploaded)

git commit -m "Lock everything to Load"

git push (Upload everything)

git status

git branch (List of branches)

git branch <name of branch>

git checkout <name of branch> (Switch to branch)

git push origin --delete <name of branch>