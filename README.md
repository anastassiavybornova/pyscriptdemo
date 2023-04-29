# Demo: HTML + PYTHON
How to combine:
* User input in HTML form & 
* request handling in python?

See `demo.html`.

Comments:
* `<script defer src="https://pyscript.net/alpha/pyscript.js"></script>` instructs to use the [pyscript](https://docs.pyscript.net/latest/index.html) project scripts 
* thanks to pyscript we can run python code within the `<pyscript>` environment
* user requests (form, ok-button, what happens upon clicking etc.) is handled in HTML
* here, we generate the fake data (a json serializable dictionary of number-color pairs) within the python script --> can be replaced with sending an api request instead; for details see e.g. [here](https://docs.pyscript.net/latest/guides/http-requests.html)