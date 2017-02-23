# augeas
Project Augean Stables, in which the CM Database is cleaned.

1.) mongoimport the JSON ouput from Kuali.co
2.) get all keys
3.) read document one-by-one
    3.1) remove yucky tags
    3.2) identify utf chars
