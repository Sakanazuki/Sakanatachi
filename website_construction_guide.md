# description
This is a git repo I cloned from my github project, this project's purpose is to use the Pages function from github to automatically build a website.

# functions
- after having the basic codes, i do not need to code anymore.
- everytime I add folders and pictures, it would be automatically refreshed/listed on the webpage.
- it is mostly static, no backend logics.
- machine code and AI tools must carefully read this function requirements.

# website structure
this website should have a main page, it has the following tabs.
## TOP
contains website introdction
## 魚図鑑
contains pictures of differenet fish species. by clicking this tab, it would show a page with the following contents:
### a search box at the top. should be able to search any text related to species name.
### an index, Japanese takagana index, this index should be automatically updated according to each species' info. Species should be grouped into ア、イ, etc
### a summary/representative picture and name for each species. name should include three names, japanese katagana name, latin formal name, chinese name. each row should have 4 pictures/species. This thing should be summarized automatically according to species in gallery folder.


### species are contained in the gallery folder, each species in a single folder. the folder name has standard schema like アカイサキ_Caprodon schlegelii_許氏菱牙鮨, which matched the japanese, latin, and china names. the names are used to build the summary and index in 魚図鑑 tab.
within each species folder, a info.txt file is given. Besides, there are 1 to many pictures. 
this folder should contain no code, no html or js file.

In the 魚図鑑 tap, users could either click the names in the index, or click the summary picture, to enter into a new page with more detailed info. this page is simple, first contain text from info.txt. then with pictures in the folder, if multiple pictures are given, list the pictures according to the date they are added to the repo. the first picture should be used as the summary picture in the 魚図鑑 tab. For each picture, directly put the picture names under the picture as info. No need to parse it, since parsing may introduce errors.


## 釣り日記
this function should be developed later

# development and test
AI tools should enable a local test strategy. every time a tiny change is made, it should be immediately available on the new website, with potential refreshing (re-compiling the js/html ) required. limited backend function required.
