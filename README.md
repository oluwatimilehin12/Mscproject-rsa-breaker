
## Running

This repository contains codes implementing [Wiener's attack](https://en.wikipedia.org/wiki/Wiener's_attack) in Python 3.

All dependencies are listed in [requirements.txt](./requirements.txt). To run this program, you need to clone this repo, install the dependencies with `pip`, and run the main file `Wiener.py`

# Install the dependencies
pip install -r requirements.txt

# Run it!
python3 Wiener.py
```


#### Exception
These codes are used to generate RSA keypairs vulnerable to Wiener's Attack (i.e. with small private exponent), when you do not supply the program with existing ones.

All unlicensed codes are under the [`libs`](/libs) directory, use them at your own risk.

## References & Further Reads

Boneh, Dan. "Twenty years of attacks on the RSA cryptosystem." *Notices of the AMS* 46.2 (1999): 203-213. https://www.ams.org/notices/199902/boneh.pdf

Calderbank, Alexander. “The RSA Cryptosystem: History, Algorithm, Primes”. Web. 2007. Accessed 27 April 2021. https://www.math.uchicago.edu/~may/VIGRE/VIGRE2007/REUPapers/FINALAPP/Calderbank.pdf

Celayes, Pablo. “rsa-wiener-attack”. Web. 2017. Accessed 24 April 2021. https://github.com/pablocelayes/rsa-wiener-attack

Schneier, Bruce. "Chapter 19.3: RSA". *Applied cryptography: protocols, algorithms, and source code in C.* john wiley & sons, 2007

Wiener, M.J. "Cryptanalysis of short RSA secret exponents," in *IEEE Transactions on Information Theory*, vol. 36, no. 3, pp. 553-558, May 1990, doi: [10.1109/18.54902](https://doi.org/10.1109/18.54902).

