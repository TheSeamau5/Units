Units
=====

Units in Elm are made to make sure numbers in different units agree

Simple example

    x = seconds 1000
    -- Statement guarantees that x is 1000 seconds
    
Note, these units are not data types, they are merely functions that multiply a number by a constant and return the result


The following are all equivalent

    a = kilograms 10
    b = grams 10000
    c = tons 0.01
    
There is also basic support for imperial units

    d = pounds 30
