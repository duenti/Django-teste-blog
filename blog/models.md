In out blog

Features
===============
Blog will have the following features

1. Post (Table in database)
2. Categories (Table in database)
3. Tag (Table in database)
4. Author (Table in database)

Let us make a relation between our tables
=========================================
1. Post can have many categories, and a category can have many posts (Relation between posts and category table) (MxM relation)

2. A tag can have many posts and a post can have many tag (MxM relation)

3. Author can have many posts, and a post can have a single author (1xM Relation) 

Attributes for tables
========================
Post
=====
1. title
2. created_date
3. body
4. tags
5. categories
6. author

Categories
===========
1. cat_name
2. cate_description

Author
=======
1. Author name
2. Author email
3. Author bio

Tag
===
1. Tag name