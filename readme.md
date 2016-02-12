# Using Padrino

## Installing Padrino

To install Padrino you need to get the gem. Run:

```
gem install padrino
```

## Creating an app skeleton

You run padrino commands with g and use the project keyword to indicate you want to create a new project.

After that you feature the name and the following flags to highlight the parts you want:

-t testing stuff
-e views stuff
-c css preprocessor
-s 

```
padrino g project sample_blog -t shoulda -e erb -c sass -s jquery -d activerecord -b
```