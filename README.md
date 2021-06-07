Front End for Google Search, Google Image Search, Google Advanced Search

& <form>
& <input>

Goal:
    & Forms that send data to an existing web server

Structure:
    & https://www.google.com/search
    & ?
    & query string
        & sequence of GET parameter
        & parameter = [name, value]
        & field = value1&field2=value2&field3=value3...
            "=" separates the name of the parameter from it's value
            "&" separates the parameter from one another
        & encodes the form data in the URL

q=SEARCHPARAMETER
    & q, query
https:/www.google.com/search/?q=SEARCHPARAMETER


