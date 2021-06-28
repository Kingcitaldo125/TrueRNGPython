# TrueRNGPython
Courtesy of [Random.org](https://www.random.org/), this is a true random number generator using [atmospheric noise](https://www.random.org/randomness/).
Random.org hosts an [API](https://www.random.org/integers/) that allows you to retrieve random numbers using either their site directly, or by way of a HTTP request.
Since we're using Python, we're using `urllib` to send a request to their server to retrieve randoms.

## Usage

Simply run the `example.py` file to generate a small array of randoms.

``` Python
import pGet

# Generate 5 randoms between 1 and 100 inclusive
lst = pGet.randRange(5,1,100)

for l in list:
  print("Item:",l)
```

## License

See the [LICENSE](https://github.com/Kingcitaldo125/TrueRNGPython/blob/master/LICENSE) file for details
