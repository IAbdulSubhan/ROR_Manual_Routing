# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# ROR_Manual_Routing
## Note: About deletion
Agar aap Ruby on Rails mein link_to/url ko use karte hue delete action perform karna chahte hain, toh aap method: :delete ka option pass karte hain. Yeh link ko DELETE request mein convert karta hai, lekin backend pe yeh request form ke zariye jaati hai, kyunki HTML forms mein sirf GET aur POST supported hote hain. Rails JavaScript helper isko handle karta hai aur DELETE request ko simulate karta hai.

Agar aap manually form ke zariye DELETE request bhejna chahte hain without link_to/url, toh aapko form_with helper ka use karna hoga aur method ko :delete set karna hoga.
